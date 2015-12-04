# update-go

These are the steps I go through to update Go on my machine when a new
version is released. Now they're all in a bash script, so I could have
just typed

```
$ update-go 1.5.2
```

this morning. Since I've already done that, it won't do it again

```
$ ./update-go 1.5.2
Updating Go to version 1.5.2
Current version is 1.5.2
Go is already up to date!
```

## TODO

- Maybe make it figure out the latest version, rather than take an argument.
- Maybe re-write it in Go.

