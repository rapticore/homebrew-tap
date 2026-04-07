# Rapticore Tap

## Available Formulae

- `orewatch`

## Install

```bash
brew install rapticore/tap/orewatch
```

Or:

```bash
brew tap rapticore/tap
brew install orewatch
```

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "rapticore/tap"
brew "orewatch"
```

## Notes

- The formula installs the core `orewatch` CLI from the published PyPI source release.
- The optional macOS `mac-menubar` extra is not bundled into the tap formula.
- After install, initialize the monitor with `orewatch monitor quickstart /path/to/project --client <client>`.
