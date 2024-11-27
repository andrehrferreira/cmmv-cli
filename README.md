<p align="center">
  <a href="https://cmmv.io/" target="blank"><img src="https://raw.githubusercontent.com/andrehrferreira/docs.cmmv.io/main/public/assets/logo_CMMV2_icon.png" width="300" alt="CMMV Logo" /></a>
</p>
<p align="center">Contract-Model-Model-View (CMMV) <br/> Building scalable and modular applications using contracts.</p>
<p align="center">
    <a href="https://www.npmjs.com/package/@cmmv/core"><img src="https://img.shields.io/npm/v/@cmmv/core.svg" alt="NPM Version" /></a>
    <a href="https://github.com/andrehrferreira/cmmv-server/blob/main/LICENSE"><img src="https://img.shields.io/npm/l/@cmmv/core.svg" alt="Package License" /></a>
    <a href="https://dl.circleci.com/status-badge/redirect/circleci/QyJWAYrZ9JTfN1eubSDo5u/JEtDUbr1cNkGRxfKFJo7oR/tree/main" target="_blank"><img src="https://dl.circleci.com/status-badge/img/circleci/QyJWAYrZ9JTfN1eubSDo5u/JEtDUbr1cNkGRxfKFJo7oR/tree/main.svg?style=svg" alt="CircleCI" /></a>
</p>

<p align="center">
  <a href="https://cmmv.io">Documentation</a> &bull;
  <a href="https://github.com/andrehrferreira/cmmv-cli/issues">Report Issue</a>
</p>

## Description

The CMMV CLI is a versatile command-line tool designed to streamline the creation, development, and management of CMMV applications. It simplifies various tasks, such as generating the project structure, running the application in development mode, and preparing it for production with efficient building and bundling processes. This CLI promotes clean and modular architectural practices, encouraging well-organized and scalable applications.

For further details, explore the [documentation](https://cmmv.io/docs).

## Installation

The ``@cmmv/cli`` package provides a simple command-line interface for quickly scaffolding CMMV projects. You can use it with pnpm global installation or directly with npx for one-time use.

```bash
pnpm add -g @cmmv/cli
```

Once installed globally, you can run the cmmv command anywhere:

```bash
cmmv init <project-name>
```

## Use with npx

For a one-time use without global installation, you can use ``npx``:

```bash
pnpm dlx @cmmv/cli@latest init <project-name>
```