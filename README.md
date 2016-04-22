# ember-cli-deploy-scout-pack

> An ember-cli-deploy plugin pack for Scout

**BREAKING CHANGE:** This deployment pack now relies on Azure Table Storage rather than Redis.

This plugin pack is different from the core [ember-cli-deploy-lightning-pack](https://github.com/ember-cli-deploy/ember-cli-deploy-lightning-pack) in that it relies on Azure Blob/Table Storage rather than Amazon S3/Redis.

## Installation

```
ember install ember-cli-deploy
ember install ember-cli-deploy-scout-pack
```

The necessary set of plugins will be available to ember-cli-deploy and an example `deploy/config.js` file will be generated for you to customize with information for your deployment environments.

## What plugins are made available?

* [ember-cli-deploy-azure-tables](https://github.com/duizendnegen/ember-cli-deploy-azure-tables)
* [ember-cli-deploy-azure-blob](https://github.com/duizendnegen/ember-cli-deploy-azure-blob)
* [ember-cli-deploy-build](https://github.com/ember-cli-deploy/ember-cli-deploy-build)
* [ember-cli-deploy-display-revisions](https://github.com/ember-cli-deploy/ember-cli-deploy-display-revisions)
* [ember-cli-deploy-manifest](https://github.com/ember-cli-deploy/ember-cli-deploy-manifest)
* [ember-cli-deploy-revision-data](https://github.com/ember-cli-deploy/ember-cli-deploy-revision-data)
* [ember-cli-deploy-gzip](https://github.com/ember-cli-deploy/ember-cli-deploy-gzip)
