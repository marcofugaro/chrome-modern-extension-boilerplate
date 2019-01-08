# DEPRECATED in favor of [browser-modern-extension-boilerplate](https://github.com/marcofugaro/browser-modern-extension-boilerplate). All browsers matter ❤️

# chrome-modern-extension-boilerplate

> Boilerplate for creating a chrome extension with up-to-date tools and autoreload of the extension

## Features

This project is born because of the lack of chrome extension starter kits which aren't from 2013 and don't use bower.

[Gulp 4](https://github.com/gulpjs/gulp/tree/4.0) is used to manage all the tasks and wire the tools together, it was chosen because it's easily hackable and configurable, you can make it fit and scale with your wildest chrome extension!

It uses [webpack](https://webpack.js.org/) to bundle javascript and [SCSS](http://sass-lang.com/) as a preprocessor. [Babel](http://babeljs.io/) transpiles all the future js stuff that hasn't landed in chrome yet, and there is a customizable [eslint](https://eslint.org/) config file.

The development mode has **autoreload** of the chrome extension, meaning that when you change a file, the extension is loaded again in chrome! 🔥

## Getting started

The easiest way is to use the [Yeoman generator](https://github.com/marcofugaro/generator-chrome-modern-extension), you get to configure more stuff that way.

Alternatively, run:

```
curl -fsSL https://github.com/marcofugaro/chrome-modern-extension-boilerplate/archive/master.tar.gz | tar -xz --strip-components=2 chrome-modern-extension-boilerplate-master/boilerplate
```

Otherwise you can `git clone` or [download](https://github.com/marcofugaro/chrome-modern-extension-boilerplate/archive/master.zip) this repo and get the contents of the `boilerplate` folder.

After you downloaded the files, create the .env file by running `cp .env.example .env`.

## What about other browsers?
If you wish to develop for other browers also, checkout the [`extension-boilerplate`](https://github.com/EmailThis/extension-boilerplate), it is nicely done.

## License

MIT © [Marco Fugaro](https://github.com/marcofugaro)
