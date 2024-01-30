[![Teurelis](./assets/banner.png)](https://teurelis.com/)

## What is Teurelis?

Teurelis is a web app for managing interconnected reading notes. It is designed and built for learners, researchers, and thinkers, but can also be used to manage complex projects.

<br />
<a href="https://teurelis.com/">
  <img alt="Teurelis" src="./assets/mockup.png" width="50%">
</a>
<br />

### Development Status

The app has been developed since 2021. The current version is fully functional. All major features are implemented and more are in development.

## Features

### Bibliographic and Content Notes

The *bibliographic note* body consists of a bibliographic entry formatted according to [Chicago Manual of Style 17 (Notes and Bibliography)](https://www.chicagomanualofstyle.org/book/ed17/part3/ch14/toc.html).

Availbable bibliographic note types:
- Book
- Book Volume
- Book Part
- Book Volume Part
- Journal
- Article
- Online Resource
- Online Resource Part
- Miscellaneous Resource
- Miscellaneous Resource Part

The *content note* body consists of a title and body text with support for [Remarkable Markdown](https://github.com/jonschlinkert/remarkable) syntax.

Both *bibliographic note* and *content note* can contain the following types of metadata:
- related bibliographic resource
- subject paths
- multi-directional link groups to other notes

<br />
<figure>
  <img alt="Bibliographic and Content Notes" src="./assets/feat_notes.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Bulk Editing

Available bulk edit actions:
- Adding/removing subject paths in the selected notes
- Connecting selected notes with a multidirectional link group

<br />
<figure>
  <img alt="Bulk Editing" src="./assets/feat_bulk-edit.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Different Layout Options

#### Choose between visually grouping notes in a subject tree or viewing them all in a single grid:

<br />
<figure>
  <img alt="Note grouping options" src="./assets/feat_grouping.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

#### Choose between a single-column or multi-column note desk layout:

<br />
<figure>
  <img alt="Column layout options" src="./assets/feat_columns.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Option Panels

Option panels provide quick access to:
- Exploring bibliographic references and subject path trees
- Detailed search options
- Account management (database export/import, password update, logout)

<br />
<figure>
  <img alt="Option Panels" src="./assets/feat_panels.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Browsing Options and Settings

#### Navigating forward and backward through the browsing history:

<br />
<figure>
  <img alt="Browsing history" src="./assets/feat_history.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

#### Filtering notes based on detailed criteria, multiple sorting options, and desk/note display settings:

<br />
<figure>
  <img alt="Options and Settings" src="./assets/feat_settings.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Responsive Design

All functionality is fully available on both mobile and desktop.

<br />
<figure>
  <img alt="Responsive Design" src="./assets/feat_rwd.gif" width="75%">
  <figcaption>Click on the image to enlarge.</figcaption>
</figure>
<br />

### Browser Support

The latest versions of all major browsers are supported:

![](https://img.shields.io/badge/Chrome-Latest-informational?style=flat&logo=googlechrome&color=green)
![](https://img.shields.io/badge/Edge-Latest-informational?style=flat&logo=microsoftedge&color=green)
![](https://img.shields.io/badge/Opera-Latest-informational?style=flat&logo=opera&color=green)
![](https://img.shields.io/badge/Firefox-Latest-informational?style=flat&logo=firefox&color=green)
![](https://img.shields.io/badge/Safari-Latest-informational?style=flat&logo=safari&color=green)

## Demo Access

For guest user login please go to [app.teurelis.com](https://app.teurelis.com/) and use the following credentials:

```
User/email: demo
Password: teurelis
```

The app landing page is available at [teurelis.com](https://teurelis.com/).

## Tech Stack

### Primary Technologies

- JavaScript
- [Svelte](https://svelte.dev/)
- [Userbase](https://userbase.com/) (user accounts, database)
- CSS
- HTML

### Deployment

- [Netlify](https://netlify.com/) (hosting, serverless functions)

### Tools

- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- [npm](https://www.npmjs.com/)
- [webpack](https://webpack.js.org/)

### Regular dependencies

- [lz-string](https://github.com/pieroxy/lz-string) (string compression)
- [object-sizeof](https://github.com/miktam/sizeof) (estimating the size of JavaScript objects in memory)
- [remarkable](https://github.com/jonschlinkert/remarkable) (Markdown parsing)
- [dompurify](https://github.com/cure53/DOMPurify) (HTML sanitization)
- [@fortawesome/fontawesome-free](https://github.com/FortAwesome/Font-Awesome) (icon library)

### Development dependencies:

- [webpack-cli](https://github.com/webpack/webpack-cli) (running webpack with CLI commands)
- [webpack-dev-server](https://github.com/webpack/webpack-dev-server) (live build reload)
- [webpack-merge](https://github.com/survivejs/webpack-merge) (separate configurations for development and production environments without duplicating code)
- [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) (automatic HTML generation)
- [css-loader](https://github.com/webpack-contrib/css-loader) (importing CSS into JavaScript)
- [svelte-loader](https://github.com/sveltejs/svelte-loader) (importing Svelte into JavaScript)
- [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) (extracting CSS into separate files)
- [svelte-preprocess](https://github.com/sveltejs/svelte-preprocess) (pre-processing of Svelte components--using PostCSS in this case)
- [autoprefixer](https://github.com/postcss/autoprefixer) (automatic CSS vendor prefixes)
- [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin) (CSS minification)
- [terser-webpack-plugin](https://github.com/webpack-contrib/terser-webpack-plugin) (JavaScript minification)
- [svelte-i18n](https://github.com/kaisermann/svelte-i18n) (managing multiple languages in Svelte)
- [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) (managing environment variables)
