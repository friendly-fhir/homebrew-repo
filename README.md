# Homebrew Tap

This is the 🍺 [Homebrew] tap for the [Friendly FHIR] Organization

[Homebrew]: https://brew.sh/
[Friendly FHIR]: https://friendly-fhir.org

## Installations

Installing formulae from this tap is simple. You can either `install` using the
full name of the formula like:

```bash
brew install "friendly-fhir/homebrew-tap/<formula>"
```

Or you can `tap` the repository and then install the formula without qualification

```bash
brew tap friendly-fhir/homebrew-tap
brew install "<formula>"
```

Tapping a formula only needs to be done once, but you will need to `update` the
tap to get the latest versions of the formulae:

```bash
brew update
```

## Formulae

### `fhenix`

The formula for the [`fhenix`] CLI tool is available in this tap.

```bash
brew install friendly-fhir/homebrew-tap/fhenix
# or, if tapped:
brew install fhenix
```

[`fhenix`]: https://github.com/friendly-fhir/fhenix

## Documentation

More information on Homebrew can be found by running `brew help`, `man brew` or
reading [Homebrew's official documentation](https://docs.brew.sh).
