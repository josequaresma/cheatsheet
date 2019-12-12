# Add tag to specific commit

From https://stackoverflow.com/questions/4404172/how-to-tag-an-older-commit-in-git

```
git tag -a v1.2 9fceb02 -m "Message here"
git push origin v1.2
```

Where 9fceb02 is the beginning part of the commit id.
