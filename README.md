# @batch/semantic-release-gitlab-config

## Plugins

This shareable configuration use the following plugins:
- [`@semantic-release/commit-analyzer`](https://github.com/semantic-release/commit-analyzer)
- [`@semantic-release/release-notes-generator`](https://github.com/semantic-release/release-notes-generator)
- [`@semantic-release/changelog`](https://github.com/semantic-release/changelog)
- [`@semantic-release/git`](https://github.com/semantic-release/git)
- [`@semantic-release/gitlab`](https://github.com/semantic-release/gitlab)

## Install

```bash
$ npm install --save-dev semantic-release @batch/semantic-release-gitlab-config
```

## Usage

The shareable config can be configured in the [**semantic-release** configuration file](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration):

```json
{
  "extends": "@batch/semantic-release-gitlab-config"
}
```

## Configuration

See each [plugin](#plugins) documentation for required installation and configuration steps.
