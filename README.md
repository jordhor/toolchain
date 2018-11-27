
# Toolchain guide

[npm](#npm) | [Babel](#babel) | [Webpack](#webpack)

This is a guide


## npm

### How to update npm to latest version in Windows

First run **PowerShell** as Administrator.

Grant execution privileges
```
Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
```

Install package for upgrade on Windows
```
npm install --global --production npm-windows-upgrade
```

Update `npm` to latest version
```
npm-windows-upgrade --npm-version latest
```

