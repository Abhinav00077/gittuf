## gittuf policy remove-person

Remove a person from a policy file (requires developer mode and v0.2 policy metadata to be enabled, set GITTUF_DEV=1 and GITTUF_ALLOW_V02_POLICY=1)

### Synopsis

This command allows users to remove a person from the specified policy file. The person's ID is required. By default, the main policy file is selected.

```
gittuf policy remove-person [flags]
```

### Options

```
  -h, --help                 help for remove-person
      --person-ID string     person ID
      --policy-name string   name of policy file to remove person from (default "targets")
```

### Options inherited from parent commands

```
      --no-color                     turn off colored output
      --profile                      enable CPU and memory profiling
      --profile-CPU-file string      file to store CPU profile (default "cpu.prof")
      --profile-memory-file string   file to store memory profile (default "memory.prof")
  -k, --signing-key string           signing key to use to sign policy file
      --verbose                      enable verbose logging
```

### SEE ALSO

* [gittuf policy](gittuf_policy.md)	 - Tools to manage gittuf policies

