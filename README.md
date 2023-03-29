# Website for Simon Aubury

Source files for [simonaubury.com](https://simonaubury.com) website

The website is built with [Hugo](https://gohugo.io/) a popular open-source static site generator

## Build
To locally run this website, run the following and visit http://localhost:1313

```bash
hugo server --buildDrafts
```

## Theme
The [aether](https://themes.gohugo.io/themes/aether/) blog theme is used
## Deploy


A [GitHub action](https://docs.github.com/en/actions) is used to build the Hugo site, and then publish back to [GitHub Pages](https://pages.github.com/).

- The [GitHub action for this site](.github/workflows/deploy_me.yml) 
- Documentation for the helper [hugo-deploy-gh-pages GitHub](https://github.com/benmatselby/hugo-deploy-gh-pages) action
- GitHub Pages repo is at https://github.com/saubury/saubury.github.io



## Notes for running locally on Windows

To run on a Windows machine and visit http://localhost:1313

```
cd /d D:\git\saubury-hugo
c:\scripts\hugo.exe server --buildDrafts
```

