# scoop-bucket

Scoop bucket for [what-to-run](https://github.com/zanza00/what-to-run) (`wtr`), a
task picker for `package.json`, `Makefile`, `Taskfile.yml`, `justfile` and the
other task files a repository can carry.

The manifest in `bucket/` is written by the release pipeline of what-to-run, so
it tracks every published version.

## Install

```powershell
scoop bucket add zanza00 https://github.com/zanza00/scoop-bucket
scoop install zanza00/what-to-run
```

Intel and ARM64 Windows are both supported.

## Update

```powershell
scoop update what-to-run
```

## Remove

```powershell
scoop uninstall what-to-run
scoop bucket rm zanza00
```

## License

The manifest and this README are MIT licensed, like what-to-run itself.
