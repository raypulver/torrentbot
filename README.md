# torrentbot
![build status](https://ci.appveyor.com/api/projects/status/github/raypulver/kat-cr)

torrentbot is a flexible torrent search module that currently searches

* [kat.cr](http://kat.cr)
* [demonoid.pw](http://demonoid.pw)
* [thepiratebay.org](https://thepiratebay.org)

The CLI application formats the top results into a list, and attempts to ensure that the same torrent does not appear twice in the list.


## Installation
To use the CLI application, use

```
npm install -g torrentbot
```

This will install an executable `torrentbot` to your `PATH`.

To use as a module, install to your project with

```
npm install --save torrentbot
```


## CLI Application Usage

A basic torrent search would look something like

```
torrentbot -c tv south park
```

## Under construction
