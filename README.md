# empty_project_03
New empty project just waiting for you to fork it, edit it and push it back through a pull request to ds4es.

Fork and Pull Request Workflow
==============================

<!-- :: \iffalse -->
[![Download PDF][SHIELD_PDF]][DOWNLOAD_PDF]
[![Download TXT][SHIELD_TXT]][DOWNLOAD_TXT]
[![CC BY 4.0 License][SHIELD_CCBY]][CCBY]
<!-- :: -->
[SHIELD_PDF]: https://img.shields.io/badge/download-PDF-brightgreen.svg
[SHIELD_TXT]: https://img.shields.io/badge/download-TXT-brightgreen.svg
[SHIELD_CCBY]: https://img.shields.io/badge/license-CC%20BY%204.0-blue.svg
[DOWNLOAD_PDF]: https://github.com/susam/gitpr/releases/download/0.6.0/gitpr.pdf
[DOWNLOAD_TXT]: https://github.com/susam/gitpr/releases/download/0.6.0/gitpr.txt
<!-- :: \fi -->
<!-- Version 0.6.0 (2018-11-19) -->
<!-- :: \maketitle -->

This document describes how developers may contribute pull requests to
an upstream repository and how upstream owners may merge pull requests
from contributors according to the very popular fork and pull request
workflow followed in many projects on GitHub.

The download buttons above download version 0.6.0 <!-- x -->
(the latest stable release) of this document. <!-- x -->
<!-- x -->
The most recent version of this document is available at
[git.io/gitpr](https://git.io/gitpr).

<!-- :: \iffalse -->

Every project has a main development branch where the developers push
commits on a day-to-day basis. Usually, the main development branch is
`master` but some projects choose to have `develop` or `trunk` or
another branch for day-to-day development activities. We refer to this
main development branch as the *main development branch* throughout this
document to keep the text general. However in the command examples and
ASCII-diagrams, we use `master` as an example of the main development
branch.

We use the following placeholders in the command examples and
ASCII-diagrams in this document:

  - `GITHUB`: [`github.com`](https://github.com/) or domain
    name/hostname of your private GitHub Enterprise system.
  - `USER` or `CONTRIBUTOR`: The user that forks an upstream repository,
    creates pull requests, and sends them to the upstream repository.
  - `UPSTREAM-OWNER`: Owner of the upstream repository. This is the name
    of the user or organization that merges pull requests into the
    upstream repository.
  - `REPO`: Repository name.
  - `FILES`: One or more filenames to be staged for a commit.
  - `TOPIC-BRANCH`: Feature-specific or bug-specific branch where a
    contributor develops her or his contribution. This is referred to as
    the *topic branch* in the text.
