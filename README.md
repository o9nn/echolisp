# EchoLisp

This repository is intended to host EchoLisp, a JavaScript implementation of a Scheme-like Lisp language that runs in web browsers.

## About EchoLisp

EchoLisp is a feature-rich Lisp dialect with:
- Lexical scoping
- Tail call elimination
- Complex numbers and large integers
- JSON manipulation
- Graphical libraries
- Interactive worksheet interface

## Official Sources

- **Official Website**: http://www.echolalie.org/echolisp/
- **Documentation**: https://www.echolalie.org/echolisp/help.html
- **Download**: http://www.echolalie.org/echolisp/echolisp.zip

## Installation

To run EchoLisp locally:
1. Download the `echolisp.zip` file from the official website
2. Extract the contents
3. Open `index.html` in your web browser

## Automated Sync

This repository includes a GitHub Action workflow that automatically attempts to download and sync the EchoLisp content from the official source. The workflow:
- Runs weekly to check for updates
- Can be manually triggered from the Actions tab
- Downloads echolisp.zip from http://www.echolalie.org/echolisp/
- Automatically commits the content when successfully downloaded

To manually trigger the sync:
1. Go to the Actions tab in this repository
2. Select "Sync EchoLisp Content" workflow
3. Click "Run workflow"

## Status

**Note**: The repository content initialization is pending. A GitHub Actions workflow has been set up to automatically download the content when the echolalie.org domain becomes accessible.