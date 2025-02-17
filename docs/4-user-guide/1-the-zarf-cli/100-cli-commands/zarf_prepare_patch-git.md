## zarf prepare patch-git

Converts all .git URLs to the specified Zarf HOST and with the Zarf URL pattern in a given FILE.  NOTE: 
This should only be used for manifests that are not mutated by the Zarf Agent Mutating Webhook.

```
zarf prepare patch-git [HOST] [FILE] [flags]
```

### Options

```
  -h, --help   help for patch-git
```

### Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc.
```

### SEE ALSO

* [zarf prepare](zarf_prepare.md)	 - Tools to help prepare assets for packaging

