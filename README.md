# Renovate base configuration for @javierbrea repositories

Shared [Renovate config presets](https://docs.renovatebot.com/config-presets/) used across
@javierbrea repositories.

## Presets

### `default`

Defined in [`./default.json`](./default.json).

* Sets `release` as the base branch.
* Groups all minor updates into a single PR and all patch updates into another; major updates are kept separate, one PR per major version bump.
* Pins `strip-ansi` to avoid its ESM-only release.
* Holds updates until 3 days after their release (no time-of-day schedule).
* No automerge - all PRs are left open for manual review.
* Opens up to 5 PRs per hour, keeps at most 2 PRs open and 4 branches active at once.
