# Python Dice Game
> A simple Python dice game which uses player authentication.

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

This script is a simple dice game which allows 2 players to randomly roll dice together. The script uses a basic level of authentication, refusing any users who do not input the correct credidentails listed in the text file. This is a very insecure method of authentication, however it was a basic project.

This project was originally a task for the OCR GCSE Computer Science Programming Project, however the task is no longer worth any marks. 
This was a simple project to advance my skills in authentication, of which I didn't spend a lot of time on. 

The code is messy, I know that, but I am constantly making changes and if you see something in my code which doesn't work or could be done less intensively, please let me know.

![](header.png)

## Installation

Simply clone the repository to your computer using the `git` command:

`git clone https://github.com/hg1233/Dice-Game.git`

## Usage example

The script runs out of the box, simply clone the repository then run the code. You may modify the `accountsfile.txt` to either view or create your own credidentials for the script.
The format for creating credidentials is as follows:

`<username> <password> <name>`

If you have done it correctly, it should match the same formatting as the example registered users.

_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

The code runs off of many global variables. This, as well as some other things, makes the code very messy.
If you wish to adapt this code, feel free to request any changes that could improve the code.

## Release History

* 0.2.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.2.0
    * CHANGE: Remove `setDefaultXYZ()`
    * ADD: Add `init()`
* 0.1.1
    * FIX: Crash when calling `baz()` (Thanks @GenerousContributorName!)
* 0.1.0
    * The first proper release
    * CHANGE: Rename `foo()` to `bar()`
* 0.0.1
    * Work in progress

## Meta

BlueTechFox – [@BlueTechFox](https://twitter.com/BlueTechFox) 
[https://github.com/hg1233/projects](https://github.com/hg1233/)

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
