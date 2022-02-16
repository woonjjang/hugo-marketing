# hugo tailwind base theme

Based on [bep/hugo-starter-tailwind-basic](https://github.com/bep/hugo-starter-tailwind-basic)


## development

```
hugo mod init github.com/team-durumi/hugo-theme-tw
hugo new site exampleSite

npm -g i google-font-downloader
cd exampleSite/static/
google-font-downloader https://fonts.googleapis.com/css2?family=Gothic+A1:wght@300&display=swap
google-font-downloader https://fonts.googleapis.com/css2?family=Gothic+A1:wght@500&display=swap

- flesler.url-encode
- Tyriar.lorem-ipsum
- yzhang.markdown-all-in-one
- bradlc.vscode-tailwindcss
- csstools.postcss

# Run server.

$ git clone https://github.com/team-durumi/hugo-theme-tw.git
$ cd hugo-theme-tw/exampleSite
$ npm i && hugo serve
# open http://localhost:1313
```
