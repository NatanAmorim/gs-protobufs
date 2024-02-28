# README

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Licensed under the Apache License, Version 2.0; you may not use this app except in compliance with the License. You may obtain a copy of the License at <https://opensource.org/licenses/Apache-2.0>.

- [About](#about)
- [Git Submodules](#git-submodules)
- [Proto3 Language Guide](#proto3-language-guide)
- [Contributing Guidelines](#contributing-guidelines)

## About

Protobufs used by the server and apps in the company "Gislaine Studio de Dança" in Andradina/Brazil.

## Git Submodules

This project is a submodule of the front-end and back-end.

- To add to your project use the following command (only add it if it's not already in the file `.gitmodules`).

```sh
git submodule add https://github.com/NatanAmorim/gs-protobufs
```

If this is your first time after adding it to the repository, you need to use `init` first:

```sh
git submodule init
```

To update on your local project, use one of the following commands.

```sh
git submodule update --init
```

```sh
git submodule update --recursive --remote
```

## Proto3 Language Guide

- [gRPC Guides](https://grpc.io/docs/guides/)
- [Language Guide (proto 3)](https://protobuf.dev/programming-guides/proto3) covers how to use the version 3 of Protocol Buffers in your project.
- gRPC uses a set of well defined [status response codes](https://grpc.github.io/grpc/core/md_doc_statuscodes.html) as part of the RPC API.
- [Google Common Types](https://github.com/googleapis/googleapis/tree/master/google/type) This package contains definitions of common types for Google APIs.
- Protobuf 3 support for Visual Studio Code with the extension [vscode-proto3](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3).

## Contributing Guidelines

We prefer all communications to be in English or Portuguese.

This project uses GitHub Issues to track bugs and feature requests. Please search the existing issues before filing new issues to avoid duplicates. For new issues, file your bug or feature request as a new Issue.

For help and questions about using this project, please uses the GitHub discussions.

### Security
<!--
Please do not report security vulnerabilities through public GitHub issues.\
Instead, please report them to {email-address}.\
You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message.
-->

If you believe you have found a security vulnerability in this software, we encourage you to inform us immediately. We will investigate all legitimate reports and do our best to quickly correct the issue.

Please include the requested information listed below (as much as you can provide) to help us better understand the nature and scope of the possible issue:

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

### Contributing Code

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your changes: `git checkout -b my-new-feature`
3. Make your changes and commit them: `git commit -am 'Add some feature'`
    - Include tests that cover your changes.
    - Update the documentation to reflect your changes, where appropriate.
    - Add an entry to the `CHANGELOG.md` file describing your changes if appropriate.
4. Push your changes to your fork: `git push origin my-new-feature`
5. Create a pull request from your fork to the main repository. `gh pr create` (with the GitHub CLI)

### Pull Request

- Clearly describe what you aim to add or fix.
- Try to minimize code changes and use existing style/functions.

### Reporting Issues and Bugs

If you find a bug, please report it by opening a new issue in the issue tracker. Please include as much detail as possible, including steps to reproduce the bug and any relevant error messages.

To better respond to issues please follow these general guidelines when explaining the problem.

1. Clearly describe what you aim to fix, if relevant attach output/logs/screenshots.
2. Describe how developers can reproduce the bug.
