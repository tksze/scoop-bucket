## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add <bucketname> https://github.com/tksze/scoop-bucket
scoop install <bucketname>/<manifestname>
```

