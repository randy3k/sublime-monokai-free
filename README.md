# MonokaiFree

A beautiful, modern, high quality, Monokai theme for Sublime Text 3.

[![Build Status](https://img.shields.io/travis/gerardroche/sublime-monokai-free/master.svg?style=flat-square)](https://travis-ci.org/gerardroche/sublime-monokai-free) [![Build status](https://img.shields.io/appveyor/ci/gerardroche/sublime-monokai-free/master.svg?style=flat-square)](https://ci.appveyor.com/project/gerardroche/sublime-monokai-free/branch/master) [![Minimum Sublime Version](https://img.shields.io/badge/sublime-%3E%3D%203.0-brightgreen.svg?style=flat-square)](https://sublimetext.com) [![Latest Stable Version](https://img.shields.io/github/tag/gerardroche/sublime-monokai-free.svg?style=flat-square&label=stable)](https://github.com/gerardroche/sublime-monokai-free/tags) [![GitHub stars](https://img.shields.io/github/stars/gerardroche/sublime-monokai-free.svg?style=flat-square)](https://github.com/gerardroche/sublime-monokai-free/stargazers) [![Downloads](https://img.shields.io/packagecontrol/dt/MonokaiFree.svg?style=flat-square)](https://packagecontrol.io/packages/MonokaiFree) [![Author](https://img.shields.io/badge/twitter-gerardroche-blue.svg?style=flat-square)](https://twitter.com/gerardroche)

* Enhanced syntax highlighting for PHP, HTML, CSS, Markdown, JavaScript, Ruby, Python.
* Additional syntax highlighting for LESS, Sass, Laravel Blade, Visual Studio Code.
* Supported plugins: [GitGutter][], [SublimeLinter][], [NeoVintageous][].

![Monokai Free color palette](palette.png)

## INSTALLATION

### Package Control

The preferred method of installation is [Package Control](https://packagecontrol.io/browse/authors/gerardroche).

### Manual

Close Sublime Text then download or clone this repository to a directory named `MonokaiFree` in the Sublime Text Packages directory for your platform:

* Linux: `git clone https://github.com/gerardroche/sublime-monokai-free.git ~/.config/sublime-text-3/Packages/MonokaiFree`
* OSX: `git clone https://github.com/gerardroche/sublime-monokai-free.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/MonokaiFree`
* Windows: `git clone https://github.com/gerardroche/sublime-monokai-free.git %APPDATA%\Sublime/ Text/ 3/Packages/MonokaiFree`

## ACTIVATE

Go to `Menu > Preferences > Color Scheme...` and select MonokaiFree.

## Screenshots

### CSS

![CSS screenshot](screenshot-css.png)

### HTML

![HTML screenshot](screenshot-html.png)

### PHP

![PHP screenshot](screenshot-php.png)

![PHP screenshot](screenshot-php-extras.png)

### XML

![XML screenshot](screenshot-xml.png)

### [GitGutter][]

![Git Gutter screenshot](screenshot-git-gutter.png)

### [SublimeLinter][]

![Sublime Linter screenshot](screenshot-sublime-linter.png)

## CONTRIBUTING

### Tests

To run the tests install [ColorSchemeUnit][] (a framework for testing Sublime Text color schemes), and run the `ColorSchemeUnit: Test Suite` command via the Command Palette (`Ctrl+Shift+P`).

## LICENSE

Released under the [BSD 3-Clause License](LICENSE).

[GitGutter]: https://github.com/jisaacks/GitGutter
[NeoVintageous]: https://github.com/NeoVintageous/NeoVintageous
[SublimeLinter]: https://github.com/SublimeLinter/SublimeLinter3
[ColorSchemeUnit]: https://github.com/gerardroche/sublime-color-scheme-unit
