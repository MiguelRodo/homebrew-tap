# MiguelRodo's Homebrew Tap

This repository is published to Homebrew as the tap `MiguelRodo/tap`.

## Formulae

- `repos` - Cross-platform CLI for managing related Git repositories.
- `setupmjr` - Cross-platform setup utility. The formula depends on `repos` from this tap.

## Installation

Add the tap once:

```bash
brew tap MiguelRodo/tap
```

Install a formula with its fully qualified name:

```bash
brew install MiguelRodo/tap/repos
brew install MiguelRodo/tap/setupmjr
```

Installing `setupmjr` installs `MiguelRodo/tap/repos` automatically as a dependency.

The tap name follows Homebrew's standard mapping: `MiguelRodo/tap` resolves to the GitHub repository `MiguelRodo/homebrew-tap`.

## Updating

Use normal Homebrew updates:

```bash
brew update
brew upgrade MiguelRodo/tap/setupmjr
```

## Issues

For packaging or tap problems, open an issue in the repository that publishes the affected formula. For tool behaviour, use the corresponding source repository (`MiguelRodo/setupmjr` or `MiguelRodo/repos`).
