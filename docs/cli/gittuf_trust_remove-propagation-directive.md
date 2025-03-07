## gittuf trust remove-propagation-directive

Remove propagation directive from gittuf root of trust (developer mode only, set GITTUF_DEV=1)

```
gittuf trust remove-propagation-directive [flags]
```

### Options

```
  -h, --help          help for remove-propagation-directive
      --name string   name of propagation directive
```

### Options inherited from parent commands

```
      --create-rsl-entry             create RSL entry for policy change immediately (note: the RSL will not be synced with the remote)
      --no-color                     turn off colored output
      --profile                      enable CPU and memory profiling
      --profile-CPU-file string      file to store CPU profile (default "cpu.prof")
      --profile-memory-file string   file to store memory profile (default "memory.prof")
  -k, --signing-key string           signing key to use to sign root of trust
      --verbose                      enable verbose logging
```

### SEE ALSO

* [gittuf trust](gittuf_trust.md)	 - Tools for gittuf's root of trust

