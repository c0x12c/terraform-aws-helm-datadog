# Changelog

All notable changes to this project will be documented in this file.

## [0.8.0]() (2025-08-11)

### BREAKING CHANGES

* Change tag key from `map_env` to `env` by removing space
* Remove blank lines when rendering http_check.yaml file
* Lock helm version < 3 to prevent error

## [0.7.0]() (2025-06-14)

### BREAKING CHANGES

* Change module named to `helm-datadog`, and be flattened and moved to root `aws`, which could be recognized by tools to export and deploy to Terraform Registry.

### Fix bugs

* Fix the typo in assigning node_selector and tolerations for agents, which should be `agents.node_selector` and `agents.tolerations` instead of missing `s`.

## [0.1.59]() (2025-01-22)

### Features

* Updated README files to include usage details for installing and configuring EKS Helm modules
* Custom the Datadog helm chart by using the variables to enable/disable features

## [0.1.22]() (2024-12-25)

### Features

* Initial commit with all the code
