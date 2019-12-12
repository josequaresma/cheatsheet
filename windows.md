# Powershell
Get size of folder contents (recursive)

```
ls -r | measure -s Length
```

Get number of files in folder

```
Write-Host ( Get-ChildItem . | Measure-Object ).Count
```
