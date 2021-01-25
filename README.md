# littlecheck [![license_badge][]][license]

A simple action to run [littlecheck][].

## Usage

```yml
- uses: fish-actions/littlecheck@v1
  with:
    files: $GITHUB_WORKSPACE/tests/check/**
```

This snippet will run littlecheck on all files in the local repository's `/tests/check` directory.

[license_badge]: https://img.shields.io/github/license/fish-actions/install-fish
[license]: LICENSE.md
[littlecheck]: https://github.com/ridiculousfish/littlecheck
