![](src/doc/banner.png)

# Modern.TiddlyDev

<center>

[![](https://img.shields.io/github/stars/tiddly-gittly/Modern.TiddlyDev?style=for-the-badge&color=red)](https://github.com/tiddly-gittly/Modern.TiddlyDev)&nbsp;&nbsp;[![](https://img.shields.io/github/forks/tiddly-gittly/Modern.TiddlyDev?style=for-the-badge)](https://github.com/tiddly-gittly/Modern.TiddlyDev)&nbsp;&nbsp;[![](https://img.shields.io/github/issues/tiddly-gittly/Modern.TiddlyDev?style=for-the-badge)](https://github.com/tiddly-gittly/Modern.TiddlyDev)&nbsp;&nbsp;[![](https://img.shields.io/github/watchers/tiddly-gittly/Modern.TiddlyDev?style=for-the-badge&color=blueviolet)](https://github.com/tiddly-gittly/Modern.TiddlyDev)&nbsp;&nbsp;[![](https://img.shields.io/github/license/tiddly-gittly/Modern.TiddlyDev?style=for-the-badge&label=Licence)](https://github.com/tiddly-gittly/Modern.TiddlyDev)&nbsp;&nbsp;[![](https://img.shields.io/github/followers/Gk0Wk?style=for-the-badge&label=Gk0Wk&color=critical)](https://github.com/Gk0Wk)

</center>

[View Tutorials](https://tiddly-gittly.github.io/Modern.TiddlyDev/)

Modern.TiddlyDev is a one-click development environment for various TiddlyWiki plug-in developers built on a modern front-end technology stack, with the following features and functions:

- Compile, test and publish plug-ins with one click:
  - Open the page server in development mode, which can be tested in the browser, automatically detect changes to the plug-in files and synchronize the plug-in content updates to the browser page, realizing the WYSIWYG of plug-in development;
  - One-click plugin building and support for generating plugin library for use by your subscribers.
  - Has a built-in GitHub Page publishing script that automatically publishes written plugin documentation pages and plugin library to the Internet;
  - Built-in GitHub Release script, which releases the plugin according to the version specified by the git tag;
- Tailored for TypeScript plugin development, so it is now easy to use TypeScript development in TiddlyWiki:
  - Multi-entry file compilation is supported, and various plugins can be easily written in TiddlyWiki;
  - Support for `.ts`, `.tsx`, `.jsx`, `.mjs`, `.cjs` files compiled with the [tw-react](https://github.com/tiddly-gittly/tw-react) plugin for React development in TiddlyWiki;
  - Use [tw5-typed](https://github.com/tiddly-gittly/TW5-Typed) to type annotate TiddlyWiki API to bring a native TypeScript experience to development;
  - Use the full amount of ESLint and Prettier rules provided by [Modern.JS](https://modernjs.dev/) to normalize the code;
  - Incremental project builds using the extremely fast [esbuild](https://esbuild.github.io/), which makes writing code a blast;
  - Support for setting browser compatibility ranges for plugins using [browserslist](https://browsersl.ist/);
  - Automatically generate sourcemap for source code (start by default when developing, specify to turn on when building), no need to worry about debugging!
  - The possibility of introducing CSS, JSON, etc. into the script;
  - Automatic volume compression of the plug-in (can be turned off);
  - Automatic generation of hash-check signatures for the generated plug-ins;

Don't worry, even if you are not good at programming, it doesn't matter, Modern.TiddlyDev can be your development tool as well. No code plugin development can be an enjoyable development experience as well!

There's a lot of work here, but it's just Out-of-the-Box for you. Use it and get started on your modern TiddlyWiki plugin development journey!

# Pending Updates
* While using Node.js v23.9.0 and NPM 11.3.0 under Arch Linux the install has many errors that need to be resolved

```
npm warn deprecated inflight@1.0.6: This module is not supported, and leaks memory. Do not use it. Check out lru-cache if you want a good and tested way to coalesce async requests by a key value, which is much more comprehensive and powerful.
npm warn deprecated @humanwhocodes/config-array@0.13.0: Use @eslint/config-array instead
npm warn deprecated rimraf@3.0.2: Rimraf versions prior to v4 are no longer supported
npm warn deprecated @humanwhocodes/object-schema@2.0.3: Use @eslint/object-schema instead
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated glob@7.2.3: Glob versions prior to v9 are no longer supported
npm warn deprecated eslint@8.57.1: This version is no longer supported. Please see https://eslint.org/version-support for other options.

```

* Current repo includes too much..will make simple and establish templates
* Chinese symbols are a distraction. Will remove all language support other than english.
* Will remove all files, etc that are not relevent to my environment
* Will add custom bash scripts for library generation, etc.

# Completed Tasks
* Configured gh pages
