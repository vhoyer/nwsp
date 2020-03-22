Newbie Webdev Starter Pack
==========================

Welcome to Newbie Webdev Starter Pack, NWSP for short.

This project comes with:

- A bundler ([`parcel-bundler`](https://parceljs.org/)) to read all your code and prepare a package of files browsers can execute;
- A development server ([`parcel-bundler`](https://parceljs.org/)) to prepare a local host server with hot-reloading so you don't have to keep reloading the page manually;
- `npm` already configured with a deploy command: `npm run deploy` (powered by [`gh-pages`](https://www.npmjs.com/package/gh-pages));

Dependencies
------------

This template project expects you already have installed on your system the following programs:

- [git](https://git-scm.com)
- [node and npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)

Getting started
---------------

To start, clone the project, enter the folder, run npm install and start the dev server and start coding at `src`!

```bash
git clone https://github.com/vhoyer/newbie-webdev-starter-pack
cd newbie-webdev-starter-pack
npm install
npm run dev
```

Also, I recommend you delete the `.git` folder that came with this template for you to start fresh your project. To do so, just run the following:

```bash
# this commands expect a linux environment
rm -rf .git
git init
git add -A
git commit -m ":tada: Initial commit"
```

```dos
REM this commands expect a windows environment
RMDIR /s /q .git
git init
git add -A
git commit -m ":tada: Initial commit"
```

All set to right modern JavaScript projects! Just start coding!
