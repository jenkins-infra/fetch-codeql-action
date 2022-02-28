# Fetch CodeQL CLI Action

This action downloads a specific version of the CodeQL CLI.

The [official action](https://github.com/github/codeql/blob/a448db11b57e7bac553af29fd625c39dd86e45e6/.github/actions/fetch-codeql/action.yml) always downloads the latest version, which is unsuitable for the Jenkins Security Scan.
This action always downloads a specific version.
