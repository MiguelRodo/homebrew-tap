# MiguelRodo's Homebrew Tap

This repository is published to Homebrew as the tap `MiguelRodo/tap`.

## Formulae

- `repos` - Cross-platform CLI for managing related Git repositories.
- `setupmjr` - Cross-platform setup utility. The formula depends on `repos` from this tap.

## Installation

Add and trust the tap once:

```bash
brew tap MiguelRodo/tap
brew trust MiguelRodo/tap
```

Homebrew 6 requires explicit trust for non-official taps. Whole-tap trust is appropriate here when you intend to use these related formulae together.

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
