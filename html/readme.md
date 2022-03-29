## Create an HTML version
You can create an HTML version of the main documents. To do so, convert the MD file into HTTL using [pandoc](https://pandoc.org/), like so:

```console
pandoc --toc --metadata title="Plugin Script Docs" --standalone --from gfm --to html5 --css style.css ../readme.md -o index.html` 
```


