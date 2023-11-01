# Renovate base configuration for @javierbrea repositories

This repository contains the [config presets for renovate bot](https://docs.renovatebot.com/config-presets/) in all @javierbrea repositories.

## Presets description

* Set `release` as base branch.
* Merge minor and patch updates automatically.
* Avoid upgrading ESM packages.
* Run every weekday after 9pm and before 5pm.
* Merge up to 5 PRs per hour and 2 concurrently.

## Config file

Config presets default file is at: [./default.json](./default.json)
