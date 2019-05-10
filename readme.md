Runner management
=================

## Usage ##

Install global dependencies:

```bash
sudo npm install -g meta
```

Get meta repo:

```bash
git clone https://github.com/runner/meta.git runner
# or for Github users with granted access
git clone git@github.com:runner/meta.git runner
cd runner
```

All preparations:

```bash
npm install
meta git update
meta npm install
sudo meta npm link --all
```


## Packages ##

 Repo                                                                      | Build status                                                                                                                                          | NPM version                                                                                                                                                 | Dependencies status                                                                                                                                        | devDependencies status
---------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------
[generator-eslint](https://github.com/runner/generator-eslint.git)         | [![build status](https://img.shields.io/travis/runner/generator-eslint.svg?style=flat-square)](https://travis-ci.org/runner/generator-eslint)         | [![npm version](https://img.shields.io/npm/v/runner-generator-eslint.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-eslint)         | [![dependencies status](https://img.shields.io/david/runner/generator-eslint.svg?style=flat-square)](https://david-dm.org/runner/generator-eslint)         | [![dependencies status](https://img.shields.io/david/dev/runner/generator-eslint.svg?style=flat-square)](https://david-dm.org/runner/generator-eslint?type=dev)
[generator-gettext](https://github.com/runner/generator-gettext.git)       | [![build status](https://img.shields.io/travis/runner/generator-gettext.svg?style=flat-square)](https://travis-ci.org/runner/generator-gettext)       | [![npm version](https://img.shields.io/npm/v/runner-generator-gettext.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-gettext)       | [![dependencies status](https://img.shields.io/david/runner/generator-gettext.svg?style=flat-square)](https://david-dm.org/runner/generator-gettext)       | [![dependencies status](https://img.shields.io/david/dev/runner/generator-gettext.svg?style=flat-square)](https://david-dm.org/runner/generator-gettext?type=dev)
[generator-livereload](https://github.com/runner/generator-livereload.git) | [![build status](https://img.shields.io/travis/runner/generator-livereload.svg?style=flat-square)](https://travis-ci.org/runner/generator-livereload) | [![npm version](https://img.shields.io/npm/v/runner-generator-livereload.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-livereload) | [![dependencies status](https://img.shields.io/david/runner/generator-livereload.svg?style=flat-square)](https://david-dm.org/runner/generator-livereload) | [![dependencies status](https://img.shields.io/david/dev/runner/generator-livereload.svg?style=flat-square)](https://david-dm.org/runner/generator-livereload?type=dev)
[generator-notify](https://github.com/runner/generator-notify.git)         | [![build status](https://img.shields.io/travis/runner/generator-notify.svg?style=flat-square)](https://travis-ci.org/runner/generator-notify)         | [![npm version](https://img.shields.io/npm/v/runner-generator-notify.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-notify)         | [![dependencies status](https://img.shields.io/david/runner/generator-notify.svg?style=flat-square)](https://david-dm.org/runner/generator-notify)         | [![dependencies status](https://img.shields.io/david/dev/runner/generator-notify.svg?style=flat-square)](https://david-dm.org/runner/generator-notify?type=dev)
[generator-npm](https://github.com/runner/generator-npm.git)               | [![build status](https://img.shields.io/travis/runner/generator-npm.svg?style=flat-square)](https://travis-ci.org/runner/generator-npm)               | [![npm version](https://img.shields.io/npm/v/runner-generator-npm.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-npm)               | [![dependencies status](https://img.shields.io/david/runner/generator-npm.svg?style=flat-square)](https://david-dm.org/runner/generator-npm)               | [![dependencies status](https://img.shields.io/david/dev/runner/generator-npm.svg?style=flat-square)](https://david-dm.org/runner/generator-npm?type=dev)
[generator-pug](https://github.com/runner/generator-pug.git)               | [![build status](https://img.shields.io/travis/runner/generator-pug.svg?style=flat-square)](https://travis-ci.org/runner/generator-pug)               | [![npm version](https://img.shields.io/npm/v/runner-generator-pug.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-pug)               | [![dependencies status](https://img.shields.io/david/runner/generator-pug.svg?style=flat-square)](https://david-dm.org/runner/generator-pug)               | [![dependencies status](https://img.shields.io/david/dev/runner/generator-pug.svg?style=flat-square)](https://david-dm.org/runner/generator-pug?type=dev)
[generator-repl](https://github.com/runner/generator-repl.git)             | [![build status](https://img.shields.io/travis/runner/generator-repl.svg?style=flat-square)](https://travis-ci.org/runner/generator-repl)             | [![npm version](https://img.shields.io/npm/v/runner-generator-repl.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-repl)             | [![dependencies status](https://img.shields.io/david/runner/generator-repl.svg?style=flat-square)](https://david-dm.org/runner/generator-repl)             | [![dependencies status](https://img.shields.io/david/dev/runner/generator-repl.svg?style=flat-square)](https://david-dm.org/runner/generator-repl?type=dev)
[generator-sass](https://github.com/runner/generator-sass.git)             | [![build status](https://img.shields.io/travis/runner/generator-sass.svg?style=flat-square)](https://travis-ci.org/runner/generator-sass)             | [![npm version](https://img.shields.io/npm/v/runner-generator-sass.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-sass)             | [![dependencies status](https://img.shields.io/david/runner/generator-sass.svg?style=flat-square)](https://david-dm.org/runner/generator-sass)             | [![dependencies status](https://img.shields.io/david/dev/runner/generator-sass.svg?style=flat-square)](https://david-dm.org/runner/generator-sass?type=dev)
[generator-static](https://github.com/runner/generator-static.git)         | [![build status](https://img.shields.io/travis/runner/generator-static.svg?style=flat-square)](https://travis-ci.org/runner/generator-static)         | [![npm version](https://img.shields.io/npm/v/runner-generator-static.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-static)         | [![dependencies status](https://img.shields.io/david/runner/generator-static.svg?style=flat-square)](https://david-dm.org/runner/generator-static)         | [![dependencies status](https://img.shields.io/david/dev/runner/generator-static.svg?style=flat-square)](https://david-dm.org/runner/generator-static?type=dev)
[generator-webpack](https://github.com/runner/generator-webpack.git)       | [![build status](https://img.shields.io/travis/runner/generator-webpack.svg?style=flat-square)](https://travis-ci.org/runner/generator-webpack)       | [![npm version](https://img.shields.io/npm/v/runner-generator-webpack.svg?style=flat-square)](https://www.npmjs.com/package/runner-generator-webpack)       | [![dependencies status](https://img.shields.io/david/runner/generator-webpack.svg?style=flat-square)](https://david-dm.org/runner/generator-webpack)       | [![dependencies status](https://img.shields.io/david/dev/runner/generator-webpack.svg?style=flat-square)](https://david-dm.org/runner/generator-webpack?type=dev)
[logger](https://github.com/runner/logger.git)                             | [![build status](https://img.shields.io/travis/runner/logger.svg?style=flat-square)](https://travis-ci.org/runner/logger)                             | [![npm version](https://img.shields.io/npm/v/runner-logger.svg?style=flat-square)](https://www.npmjs.com/package/runner-logger)                             | [![dependencies status](https://img.shields.io/david/runner/logger.svg?style=flat-square)](https://david-dm.org/runner/logger)                             | [![dependencies status](https://img.shields.io/david/dev/runner/logger.svg?style=flat-square)](https://david-dm.org/runner/logger?type=dev)
[runner](https://github.com/runner/runner.git)                             | [![build status](https://img.shields.io/travis/runner/runner.svg?style=flat-square)](https://travis-ci.org/runner/runner)                             | [![npm version](https://img.shields.io/npm/v/runner.svg?style=flat-square)](https://www.npmjs.com/package/runner)                                           | [![dependencies status](https://img.shields.io/david/runner/runner.svg?style=flat-square)](https://david-dm.org/runner/runner)                             | [![dependencies status](https://img.shields.io/david/dev/runner/runner.svg?style=flat-square)](https://david-dm.org/runner/runner?type=dev)
[tools](https://github.com/runner/tools.git)                               | [![build status](https://img.shields.io/travis/runner/tools.svg?style=flat-square)](https://travis-ci.org/runner/tools)                               | [![npm version](https://img.shields.io/npm/v/runner-tools.svg?style=flat-square)](https://www.npmjs.com/package/runner-tools)                               | [![dependencies status](https://img.shields.io/david/runner/tools.svg?style=flat-square)](https://david-dm.org/runner/tools)                               | [![dependencies status](https://img.shields.io/david/dev/runner/tools.svg?style=flat-square)](https://david-dm.org/runner/tools?type=dev)


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/runner/meta/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`runner-meta` is released under the [GPL-3.0 License](http://opensource.org/licenses/GPL-3.0).
