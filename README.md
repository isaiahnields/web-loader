# <img src="https://raw.githubusercontent.com/isaiahnields/web-loader/master/logo.png" width="48"> Web Loader

> A website downloader with a built-in JavaScript engine!

[![Phantomjs](https://img.shields.io/badge/phantomjs-2.1.1-800080.svg)](http://phantomjs.org/)
[![License](https://img.shields.io/github/license/isaiahnields/web-loader.svg)](https://github.com/isaiahnields/web-loader/blob/master/LICENSE)

## Table of Contents

[Purpose](#purpose)<br />
[Compatibility](#compatibility)<br />
[Set Up](#set-up)<br />
[Functionality](#functionality)<br />
[Use Cases](#use-cases)<br />
[Future Goals](#future-goals)<br />

## Purpose

The purpose of Web Loader is to give a user the ability to download portions of or entire websites.

## Compatibility

Web Loader is compatible with PhantomJS version 2.1.1 and above.

## Set Up

1. Install PhantomJS for your operating system: http://phantomjs.org/download.html.
2. Clone this repository.
3. You're done! You are now able to run loader.js from the command line.

## Functionality

There are two main ways to download a website with Web Loader:

#### 1. Host Download

A host website download involves downloading every page that is present on a given host.

To run a host website download, run a command of the following form:

```
phantomjs loader.js https://example.com
```

#### 2. Path Download

A path website download involves downloading pages that are in a specific path on the host.

To run a path website download, run a command of the following form:

```
phatomjs loader.js https://example.com /example/path
```

## Use Cases

There are a few uses cases for this software:

#### 1. Detect Website Changes

Running this program multiple times over a given time period could allow a user to detect changes that are made to a website. This might be useful in tracking when a business announces a new product or updates an application.

#### 2. Word Search

The resulting text files generated by this program can be rapidly searched, allowing a user to quickly check if website contains certain verbiage.

#### 3. Research

In general, this program may be useful in any sort of research that involves extracting verbiage from the internet.

## Future Goals

See [Projects](https://github.com/isaiahnields/CompetitorScraper/projects).
