# Windows certificate download
https://raw.githubusercontent.com/GeekDuanLian/windows-cert-sync/main/root.sst
https://raw.githubusercontent.com/GeekDuanLian/windows-cert-sync/main/disallowedcert.sst
https://raw.githubusercontent.com/GeekDuanLian/windows-cert-sync/main/pinrules.sst

## Import certificate
You need run as Administrator.
```
certutil -addstore root root.sst
certutil -addstore disallowed disallowedcert.sst
```
`pinrules.sst` don't know what's the use at the moment, ignore it.
