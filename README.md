# broken-link-checker-tool - 

This is a tool that scans a website, pointing out broken links

## Prerequisites

NodeJS

## SETUP

npm install


## RUN

-- scan only the links in the current page --

npx blc https://razvanvancea.ro -r --exclude-external  

-- scan links recursively in the entire project (current page, other pages and subpages) --

npx blc https://razvanvancea.ro -ro --exclude-external  


-- exclude external domains --
npx blc https://razvanvancea.ro -ro --exclude-external  


-- exclude specific domain URLs (e.g. Twitter and LinkedIn) -- 

npx blc https://razvanvancea.ro -ro --exclude twitter --exclude linkedin  

### HELP

npx blc --help

### Docs

https://www.npmjs.com/package/broken-link-checker

