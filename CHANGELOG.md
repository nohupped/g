Changelog
=========

## Unreleased

## 0.3.0 - 2018-07-28

- Fix visual glitch while getting remote versions list
- Fix activation error on MacOS because of `cp` and `ln` long params
- Fix unbound var error on install script on MacOS
- Exclude beta version from version list
  * Beta versions can still be installed if you provide the version, e.g. `1.11beta2`

## 0.2.0 - 2018-04-22

- Improve documentation
- Add install script
- BREAKING: short option for `--non-interactive` went from `-i` to `-y`
- Improve logic to check for valid download URLs
- Improve code style and good practices
- Clear Go dist files before activating new version
- Place versions dir inside `$GOROOT` instead of `$GOPATH`
- Use symbolic links for go binaries, instead of hard links
- Fix typo in usage docs by Angel Perez <iAngel.p93@gmail.com>

## 0.1.0 - 2018-04-08

### Added
- Initial release
