# mohblack-updates

Public update feed for the MOH Black SUV tablet app (source code is in a private repo).

- `update.json`: latest app version; the tablet installs it when `versionCode` is higher than its own.
- `config.json`: remote settings; applied when `configVersion` increases. Do not put passwords here.
- Releases: signed APKs referenced by `update.json`.
