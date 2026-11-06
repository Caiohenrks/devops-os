# Changelog

## [Unreleased]

### Changed

- `/bin/sh` agora aponta para o bash. O link era para o dash, e o Linux From Scratch exige que `sh` seja o bash. Como `/bin` aponta para `usr/bin`, o ajuste é `ln -sfn bash /usr/bin/sh`.
