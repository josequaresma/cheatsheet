# Powershell

List folder contents

```
ls | % Name
```

Get size of folder contents (recursive)

```
ls -r | measure -s Length
```

Get number of files in folder

```
( Get-ChildItem . | Measure-Object ).Count
```

Get date

```
Get-Date -Format G
```
