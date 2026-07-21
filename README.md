# Renovate base configuration for @javierbrea repositories

Shared [Renovate config presets](https://docs.renovatebot.com/config-presets/) used across
@javierbrea repositories.

## Presets

### `default`

Defined in [`./default.json`](./default.json).

* Sets `release` as the base branch.
* Automerges minor and patch updates; major updates are left for manual review.
* Pins `strip-ansi` to avoid its ESM-only release.
* Runs on weekday nights (after 9pm and before 5pm).
* Merges up to 5 PRs per hour and 2 concurrently.
