### Setup Gitbook Tutorials
https://toolchain.gitbook.com/setup.html

### Plugin I use

```json
{
    "root": "./",
    "title": "Startup Journey with Bob",
    "author": "Bob Lee",
    "description": "Resources for iOS 10 and Swift 3 tutorials",
    "isbn": "",

    "plugins": [
       "image-captions",
       "youtube",
       "mermaid-gb3"
     ],

     "pluginsConfig": {
       "image-captions": {
             "caption": " _CAPTION_"
         }
     },
     "styles": {
       "website": "website.css"
     }
    }
```

website.css

```css

figure {
    margin: 1.5em 0px;
    padding:10px 0;
    text-align: center;
}

figcaption {
    clear: left;
    margin: 0.75em 0px;
    text-align: center;
    font-style: normal;
    line-height: 1.0em;
    font-size: 6px;
    color: #808080;
}


img {
  algin: cetner
}
```
