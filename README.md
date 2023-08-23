# broken-link-checker-tool

This is a tool that scans a website, pointing out broken links

## Prerequisites

NodeJS [SETUP Tutorial](https://youtu.be/j8HZpFjPPVU)

## INSTALLATION

```sh
npm install
```


## RUN

-- scan only the links in the current page --


```sh
npx blc https://razvanvancea.ro
```

-- scan links recursively in the entire project (current page, other pages and subpages) --

```sh
npx blc https://razvanvancea.ro -ro
```


-- exclude external domains --

```sh
npx blc https://razvanvancea.ro -ro --exclude-external  
```


-- exclude specific domain URLs (e.g. Twitter and LinkedIn) -- 

```sh
npx blc https://razvanvancea.ro -ro --exclude twitter --exclude linkedin  
```

### HELP

```sh
npx blc --help
```


[NPM Docs](https://www.npmjs.com/package/broken-link-checker)



