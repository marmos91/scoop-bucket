# marmos91/scoop-bucket

Scoop bucket for my projects.

## DittoFS has moved

`dfs` and `dfsctl` now live in [cubbit/scoop-bucket](https://github.com/cubbit/scoop-bucket):

```powershell
scoop uninstall dfs dfsctl
scoop bucket rm marmos91
scoop bucket add cubbit https://github.com/cubbit/scoop-bucket
scoop install cubbit/dfs
scoop install cubbit/dfsctl
```
