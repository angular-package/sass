# angular-package

<a href='https://angular-package.dev' target='_blank'>
  <img align="right"  width="92" height="92" src="https://avatars.githubusercontent.com/u/31412194?s=400&u=c9929aa36826318ccac8f7b84516e1ce3af7e21c&v=4" />
</a>

The angular-package supports the development process of [angular](https://angular.io)-based applications in varied ways through the thoughtful, reusable, easy-to-use small pieces of code called packages.

<br>

<a href="https://angular-package.github.io/sass"><img src="https://sass-lang.com/assets/img/logos/logo.svg" width="92" height="92" /></a>

## Sass

Sass - extension for sass modules and new modules.

[![Gitter][gitter-badge]][gitter-chat]
[![Discord][discord-badge]][discord-channel]
[![Twitter][twitter-badge]][twitter-follow]

<!-- npm badge -->
[![npm version][sass-npm-badge-svg]][sass-npm-badge]

<!-- GitHub badges -->
[![GitHub issues][sass-badge-issues]][sass-issues]
[![GitHub forks][sass-badge-forks]][sass-forks]
[![GitHub stars][sass-badge-stars]][sass-stars]
[![GitHub license][sass-badge-license]][sass-license]

<!-- Sponsors -->
[![GitHub Sponsors][github-badge-sponsor]][github-sponsor-link]
[![Patreon Sponsors][patreon-badge]][patreon-link]

Extended sass modules:

* The [`sass:color`](https://sass-lang.com/documentation/modules/color/) is extended by [`@angular-package/sass/color`](https://docs.angular-package.dev/v/sass/color/overview) - module generates new colors based on existing ones, making it easy to build color themes.
* The [`sass:list`](https://sass-lang.com/documentation/modules/list/) is extended by [`@angular-package/sass/list`](https://docs.angular-package.dev/v/sass/list/overview) - module lets you access and modify values in lists.
* The [`sass:map`](https://sass-lang.com/documentation/modules/map/) is extended by [`@angular-package/sass/map`](https://docs.angular-package.dev/v/sass/map/overview) - module makes it possible to look up the value associated with a key in a map, and much more.
* The [`sass:math`](https://sass-lang.com/documentation/modules/math/) is extended by [`@angular-package/sass/math`](https://docs.angular-package.dev/v/sass/math/overview) - module provides functions that operate on numbers.
* The [`sass:meta`](https://sass-lang.com/documentation/modules/meta/) is extended by [`@angular-package/sass/meta`](https://docs.angular-package.dev/v/sass/meta/overview) - module exposes the details of Sass’s inner workings.
* The [`sass:selector`](https://sass-lang.com/documentation/modules/selector/) is extended by [`@angular-package/sass/selector`](https://docs.angular-package.dev/v/sass/selector/overview) - module provides access to Sass’s powerful selector engine.
* The [`sass:string`](https://sass-lang.com/documentation/modules/string/) is extended by [`@angular-package/sass/string`](https://docs.angular-package.dev/v/sass/string/overview) - module makes it easy to combine, search, or split apart strings.

<br>

New modules:

* The [`@angular-package/sass/class`](https://docs.angular-package.dev/v/sass/class/overview) module to handle [CSS class selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)(variants).
* The [`@angular-package/sass/comparison`](https://docs.angular-package.dev/v/sass/comparison/overview) module to compare single or multiple values.
* The [`@angular-package/sass/function`](https://docs.angular-package.dev/v/sass/function/overview) module function to handle calling [functions](https://github.com/angular-package/sass/tree/main/function), especially in a form of `string` in `list`.
* The [`@angular-package/sass/media`](https://docs.angular-package.dev/v/sass/media/overview) module to handle [@media](https://developer.mozilla.org/en-US/docs/Web/CSS/@media) [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) [at-rule](https://developer.mozilla.org/en-US/docs/Web/CSS/At-rule).
* The [`@angular-package/sass/object`](https://docs.angular-package.dev/v/sass/object/overview) module to handle [sass variable](https://sass-lang.com/documentation/variables/) of [`map`](https://sass-lang.com/documentation/modules/map/) type as named objects.
* The [`@angular-package/sass/property`](https://docs.angular-package.dev/v/sass/property/overview) module to set multiple [CSS properties](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) or variants with called [functions](https://github.com/angular-package/sass/tree/main/function) on values.
* The [`@angular-package/sass/query`](https://docs.angular-package.dev/v/sass/query/overview) module to execute query on [`list`](https://sass-lang.com/documentation/modules/list/) to retrieve data.
* The [`@angular-package/sass/translator`](https://docs.angular-package.dev/v/sass/translator/overview) module handles global dictionary to translate words.
* The [`@angular-package/sass/values`](https://docs.angular-package.dev/v/sass/values/overview) module to modify arbitrary values.
* The [`@angular-package/sass/var`](https://docs.angular-package.dev/v/sass/var/overview) module is designed to handle [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) with the use of words that can be translated by the dictionary.
* The [`@angular-package/sass/variant`](https://docs.angular-package.dev/v/sass/variant/overview) module to create variants usable in `class` and `property` modules.

<br>

Module moved:

* The `@angular-package/sass/number` moved to the [`@angular-package/sass/math`](https://docs.angular-package.dev/v/sass/math/overview) module.

<br>

Translator:

In the `beta` version, two translators are inside the [`translator`](https://github.com/angular-package/sass/tree/main/translator) folder. First(will be deprecated) [`v0.1.0`](https://github.com/angular-package/sass/tree/main/translator/v0.1.0), the default exported dictionary, was created to pass an external dictionary in some functions to merge with a global dictionary.
The second, newer, and simplified translator [`v1.0.0`](https://github.com/angular-package/sass/tree/main/translator/v1.0.0) is designed with only the global(internal) dictionary, and the external dictionary is passed only in `merge` and `translation`.

<br>

Sass extension is **free** to use. If you enjoy it, please consider donating via [fiat](https://docs.angular-package.dev/v/sass/donate/fiat), [Revolut platform](https://business.revolut.com/revolutme/angularpackage) or [cryptocurrency](https://spectrecss.angular-package.dev/donate/thb-cryptocurrency) the [@angular-package](https://github.com/sponsors/angular-package) for further development. ♥  

> Feel **free** to submit a pull request. Help is always appreciated.

<br>

## Table of contents

* [Skeleton](#skeleton)
* [Code scaffolding](#code-scaffolding)
* [Documentation](#documentation)
* [Changelog](#changelog)
* [Git](#git)
  * [Commit](#commit)
  * [Versioning](#versioning)
* [License](#license)

<br>

## Skeleton

This package was generated by the [skeleton workspace][skeleton] with [Angular CLI](https://github.com/angular/angular-cli) version `14.0.0`.

Copy this package to the `packages/sass` folder of the [skeleton workspace][skeleton] then run the commands below.

<br>

## Code scaffolding

Run `ng generate component component-name --project sass` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module --project sass`.
> Note: Don't forget to add `--project sass` or else it will be added to the default project in your `angular.json` file.

### Build

Run `ng build sass` to build the project. The build artifacts will be stored in the `dist/sass` directory.

### Publishing

After building your library with `ng build sass`, go to the dist folder `cd dist/sass` and run `npm publish`.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

<br>

## Documentation

The documentation is in construction and it's available at [https://docs.angular-package.dev/v/sass](https://docs.angular-package.dev/v/sass/)

<br>

## Changelog

To read it, click on the [CHANGELOG.md](https://github.com/angular-package/sass/blob/master/CHANGELOG.md) link.

<br>

## GIT

### Commit

* [AngularJS Git Commit Message Conventions][git-commit-angular]
* [Karma Git Commit Msg][git-commit-karma]
* [Conventional Commits][git-commit-conventional]

### Versioning

[Semantic Versioning 2.0.0][git-semver]

**Given a version number MAJOR.MINOR.PATCH, increment the:**

* MAJOR version when you make incompatible API changes,
* MINOR version when you add functionality in a backwards-compatible manner, and
* PATCH version when you make backwards-compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

**FAQ**
How should I deal with revisions in the 0.y.z initial development phase?

> The simplest thing to do is start your initial development release at 0.1.0 and then increment the minor version for each subsequent release.

How do I know when to release 1.0.0?

> If your software is being used in production, it should probably already be 1.0.0. If you have a stable API on which users have come to depend, you should be 1.0.0. If you’re worrying a lot about backwards compatibility, you should probably already be 1.0.0.

<br>

## License

MIT © angular-package ([license][sass-license])

<!-- Funding -->
[github-badge-sponsor]: https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&link=https://github.com/sponsors/angular-package
[github-sponsor-link]: https://github.com/sponsors/angular-package
[patreon-badge]: https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dangularpackage%26type%3Dpatrons&style=flat
[patreon-link]: https://www.patreon.com/join/angularpackage/checkout?fan_landing=true&rid=0

[angulario]: https://angular.io
[skeleton]: https://github.com/angular-package/skeleton

<!-- Update status -->
[experimental]: https://img.shields.io/badge/-Experimental-orange
[fix]: https://img.shields.io/badge/-Fix-red
[new]: https://img.shields.io/badge/-eNw-green
[update]: https://img.shields.io/badge/-Update-red
[documentation]: https://img.shields.io/badge/-Documentation-informational
[demonstration]: https://img.shields.io/badge/-Demonstration-green

<!-- Discord -->
[discord-badge]: https://img.shields.io/discord/925168966098386944?style=social&logo=discord&label=Discord
[discord-channel]: https://discord.com/invite/rUCR2CW75G

<!-- Gitter -->
[gitter-badge]: https://img.shields.io/gitter/room/angular-package/ap-sass?style=social&logo=gitter
[gitter-chat]: https://app.gitter.im/#/room/#ap-sass:gitter.im

<!-- Twitter -->
[twitter-badge]: https://img.shields.io/twitter/follow/angularpackage?label=%40angularpackage&style=social
[twitter-follow]: https://twitter.com/angularpackage

<!-- GIT -->
[git-semver]: http://semver.org/

<!-- GIT: commit -->
[git-commit-angular]: https://gist.github.com/stephenparish/9941e89d80e2bc58a153
[git-commit-karma]: http://karma-runner.github.io/0.10/dev/git-commit-msg.html
[git-commit-conventional]: https://www.conventionalcommits.org/en/v1.0.0/

<!-- This package: sass  -->
  <!-- GitHub: badges -->
  [sass-badge-issues]: https://img.shields.io/github/issues/angular-package/sass
  [sass-badge-forks]: https://img.shields.io/github/forks/angular-package/sass
  [sass-badge-stars]: https://img.shields.io/github/stars/angular-package/sass
  [sass-badge-license]: https://img.shields.io/github/license/angular-package/sass
  <!-- GitHub: badges links -->
  [sass-issues]: https://github.com/angular-package/sass/issues
  [sass-forks]: https://github.com/angular-package/sass/network
  [sass-license]: https://github.com/angular-package/sass/blob/master/LICENSE
  [sass-stars]: https://github.com/angular-package/sass/stargazers
<!-- This package -->
  [sass-github-changelog]: https://github.com/angular-package/sass/blob/main/CHANGELOG.md

<!-- Package: sass -->
  <!-- npm -->
  [sass-npm-badge-svg]: https://badge.fury.io/js/%40angular-package%2Fsass.svg
  [sass-npm-badge-png]: https://badge.fury.io/js/%40angular-package%2Fsass.png
  [sass-npm-badge]: https://badge.fury.io/js/%40angular-package%2Fsass
  [sass-npm-readme]: https://www.npmjs.com/package/@angular-package/sass#readme

  <!-- GitHub -->
  [sass-github-readme]: https://github.com/angular-package/sass#readme
