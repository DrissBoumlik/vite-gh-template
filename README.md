This repository is useful if you need a quick html page to deploy to github pages 
the html file is splitted into imported ejs files (css too)


## Usage

Fork this repo, then do this

`git clone https://github.com/YOUR_USER_NAME/vite-gh-template`

`cd vite-gh-template`

`npm install`

in vite.config.js edit the base key (leave it as it is Or put your repo name in case you changed it while forking)

```js

export default defineConfig({

    /* ... */

    base: '/vite-gh-template/',

    /* ... */

});

```
 
run `npm run dev` to start editing

run `npm run preview` to have a local preview

Go to settings then click pages on left menu, check the "Build and deployment" section and in branch choose gh-pages

run `npm run build && npm run deploy` and visit https://YOUR_USER_NAME.github.io/vite-gh-template

