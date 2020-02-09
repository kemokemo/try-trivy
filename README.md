# try-trivy

This repo tries to execute [trivy](https://github.com/aquasecurity/trivy) on the `circle-ci`.

## check before commit

Before commit, you can check wheter the `.circleci/config.yml` is valid by the [circleci CLI](https://circleci.com/docs/ja/2.0/local-cli/).

```sh
circleci config validate
```
