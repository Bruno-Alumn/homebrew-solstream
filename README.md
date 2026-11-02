# Homebrew tap for SolStream

[SolStream](https://github.com/Bruno-Alumn/SolStream) streams Windows apps from
your PC into their own native windows on your Mac. Install the Mac app with:

```sh
brew install --cask bruno-alumn/solstream/solstream
```

The PC needs SolStream too: run `SolStreamSetup` from the
[latest release](https://github.com/Bruno-Alumn/SolStream/releases/latest).

SolStream updates itself from new releases. The cask here comes from
`packaging/solstream.rb` in the main repository, and
`scripts/update-cask.sh --push` there brings it up to a new release.
