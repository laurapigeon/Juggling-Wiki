<%*
const key = "siteswap";
const value = tp.frontmatter[key];
let currentFile = app.workspace.getActiveFile();

const filteredFiles = app.vault.getMarkdownFiles().filter(file => {

  const foundValue = app.metadataCache.getFileCache(file)?.frontmatter?.[key];

  if (!foundValue || file == currentFile) {
    return false;
  }

  return foundValue === value;
});

if (filteredFiles.length != 0) {
	const filteredLinks = [];
	
	for (const filteredFile of filteredFiles) {
		filteredLinks.push("[[" + filteredFile.basename + "]]");
	}
	
	app.fileManager.processFrontMatter(currentFile, (frontmatter) => {
	    frontmatter["siteswap pair"] = filteredLinks;
	});
}
-%>