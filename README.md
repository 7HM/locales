Learning Locker Language Files
==============================

To create a new language pack:

* Fork this repo
* Create a sub folder within lang/ for the specific language named with the language code e.g. en / fr / de
* Copy the en folder (which we keep up to date)
* Translate
* Issue a pull request for us to merge it back in

If you prefer, we also use Transifex to help aid translation - see below.

Usage
=====

To use with your install of Learning Locker, grab the language files you want and place it in the app/lang folder.

Transifex
=========

Here is the [Learning Locker project on Transifex](https://www.transifex.com/organization/learning-locker/dashboard) - it provides a handy interface to help track how many strings are needing translated for any language being worked on.

_When using Transifex, make sure you download the file locally before translating - their online editor misses out most of the strings for some reason._

The files on Transifex are automatically updated when we make changes to the core english files in Learning Locker. As they are translated, we merge
them here.