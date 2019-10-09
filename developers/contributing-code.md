---
description: >-
  Mattermost is an open-source platform and welcomes contributions from our
  community!
---

# Contributing Code

## [Contribution guidelines](https://www.mattermost.org/contribute-to-mattermost/)

## [How to Develop Plugins with Mattermost](https://developers.mattermost.com/extend/plugins/)

## [Setting up a Mattermost Development Environment](https://developers.mattermost.com/contribute/server/developer-setup/)

## Plugin Development

This plugin contains both a server and web app portion.

Use `make dist` to build distributions of the plugin that you can upload to a Mattermost server for testing.

Use `make check-style` to check the style for the whole plugin.

### Server

Inside the `/server` directory, you will find the Go files that make up the server-side of the plugin. Within there, build the plugin like you would any other Go application.

### Web App

Inside the `/webapp` directory, you will find the JS and React files that make up the client-side of the plugin. Within there, modify files and components as necessary. Test your syntax by running `npm run build`.

