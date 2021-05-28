# qrafty-web
The public facing website for QraftyToken - https://snollygolly.github.io/qrafty-web/

# How to contribute
The website is QraftyToken is statically generated using [Hugo](https://gohugo.io/). To get started:

## Install Hugo
```
brew install hugo
```

See https://gohugo.io/getting-started/quick-start/ for additional context.


## Start the Hugo server and make your changes
```
hugo server
```
The site will be available at http://localhost:1313/. Feel free to edit or add new content and simply refresh in browser to see your changes.

## Deploying
Once you're happy your changes, commit and push them up. The site will be automatically rebuilt and deployed via the defined GitHub action found in `.github/workflows/gh-pages`.

