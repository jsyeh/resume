MY TODO
=======
- 2020 May: Kirby Wu 上課時, 有教使用 startbootstrap-resume, 我有做 3次修改
我在 Kirby Wu 課堂學習時, 有試著用 github 上面的 startbootstrap-resume, 再改它的 index.html

我改了3次

1. &lt;h1 class="mb-0"&gt; 改大名字
2. 再改一次
3. 貼上 og
            <meta property="og:url" content="kirby">
            <meta property="og:title" content="kirby kirby">
            <meta property="og:description" content="kirby kirby kirby">
            <meta property="og:locale"content="zh_TW">
            <meta property="og:image"content="">
            <meta property="og:image:type"content="image/jpeg">
            <meta property="og:image:width"content="1200">
            <meta property="og:image:height"content="630>
            <meta property="og:type" content="website">       
                                                      
- TODO: 我現在對 HTML/CSS/bootstrap/Web/github 都比較熟了, 再重來一次, 應該會順很多。
- 我有試著細看 https://github.com/StartBootstrap/startbootstrap-resume/ 對應的資料, 也查作者 Muller 的資訊, 也看到有人不小心把自己修改的 fork 送出 pull request
  - 關於如何 pull request, [github docs](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) 有介紹
- 有人在官網問怎麼變色彩, 有人問怎麼改左邊的 navpan, 有人問
- 有人在官網問 print 的問題, 也有人寫 CSS media print 的檔案, 去調整印出來的效果
- 可是風格不太合, 因為字會很大、留白會很多, 如果是很多內容的 resume 就很難在一頁裡印出來
  - https://stackoverflow.com/questions/56246371/print-friendly-web-resume
  - https://github.com/StartBootstrap/startbootstrap-resume/issues/66
- fork出來的專案, 不能變 private, 所以 github 建議可以用 mirror 的方式 copy 成新的 private repo
- 我有在 jsyeh.github.io/startbootstrap-resume 看過, 後來把 repo 改名成 resume, 所以是 jsyeh.github.io/resume
- 有發現 github pages 可以利用 Jekyll 機制, 來改變 theme [github docs](https://docs.github.com/en/github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-with-the-theme-chooser) 也就是 Jekyll 可以幫忙把 Markdown 的 README.md 改成
- 也有研究 Project social preview image (1280x640 or 640x320) 需要留下邊緣的出血空間

# [Start Bootstrap - Resume](https://startbootstrap.com/theme/resume/)

[Resume](https://startbootstrap.com/theme/resume/) is a resume and CV theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). This theme features a fixed sidebar with content sections to build a simple, yet elegant resume.

## Preview

[![Resume Preview](https://assets.startbootstrap.com/img/screenshots/themes/resume.png)](https://startbootstrap.github.io/startbootstrap-resume/)

**[View Live Preview](https://startbootstrap.github.io/startbootstrap-resume/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/StartBootstrap/startbootstrap-resume/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-resume.svg)](https://www.npmjs.com/package/startbootstrap-resume)
[![Build Status](https://travis-ci.org/StartBootstrap/startbootstrap-resume.svg?branch=master)](https://travis-ci.org/StartBootstrap/startbootstrap-resume)
[![dependencies Status](https://david-dm.org/StartBootstrap/startbootstrap-resume/status.svg)](https://david-dm.org/StartBootstrap/startbootstrap-resume)
[![devDependencies Status](https://david-dm.org/StartBootstrap/startbootstrap-resume/dev-status.svg)](https://david-dm.org/StartBootstrap/startbootstrap-resume?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:

- [Download the latest release on Start Bootstrap](https://startbootstrap.com/theme/resume/)
- Install using npm: `npm i startbootstrap-resume`
- Clone the repo: `git clone https://github.com/StartBootstrap/startbootstrap-resume.git`
- [Fork, Clone, or Download on GitHub](https://github.com/StartBootstrap/startbootstrap-resume)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with `dist` directory. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

Clone the source files of the theme and navigate into the theme's root directory. Run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

#### npm Scripts

- `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
- `npm run build:assets` copies the files in the `src/assets/` directory into `dist`
- `npm run build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
- `npm run build:scripts` brings the `src/js/scripts.js` file into `dist`
- `npm run build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
- `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
- `npm run start:debug` runs the project in debug mode
- `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`

You must have npm installed in order to use this build environment.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/StartBootstrap/startbootstrap-resume/issues) here on GitHub or leave a comment on the [theme overview page at Start Bootstrap](https://startbootstrap.com/theme/resume/).

## About

Start Bootstrap is an open source library of free Bootstrap themes and templates. All of the free themes and templates on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

- <https://startbootstrap.com>
- <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](https://davidmiller.io/)**.

- <https://davidmiller.io>
- <https://twitter.com/davidmillerhere>
- <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2020 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-resume/blob/gh-pages/LICENSE) license.
