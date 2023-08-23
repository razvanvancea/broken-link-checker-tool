# broken-link-checker-tool - tool to scan the website, pointing out broken links

### scan only the links in the current page
npx blc https://razvanvancea.ro -r --exclude-external  

### scan links recursively in the entire project (current page, other pages and subpages)
npx blc https://razvanvancea.ro -ro --exclude-external  


### exclude external domains
npx blc https://razvanvancea.ro -ro --exclude-external  


### exclude Twitter and LinkedIn urls
npx blc https://razvanvancea.ro -ro --exclude twitter --exclude linkedin  

### HELP
npx blc --help
