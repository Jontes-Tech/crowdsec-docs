---
id: cscli_collections_install
title: cscli collections install
---
## cscli collections install

Install given collection(s)

### Synopsis

Fetch and install given collection(s) from hub

```
cscli collections install collection [flags]
```

### Examples

```
cscli collections install crowdsec/xxx crowdsec/xyz
```

### Options

```
  -d, --download-only   Only download packages, don't enable
      --force           Force install : Overwrite tainted and outdated files
  -h, --help            help for install
      --ignore          Ignore errors when installing multiple collections
```

### Options inherited from parent commands

```
      --color string    Output color: yes, no, auto. (default "auto")
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --debug           Set logging to debug.
      --error           Set logging to error.
      --info            Set logging to info.
  -o, --output string   Output format: human, json, raw.
      --trace           Set logging to trace.
      --warning         Set logging to warning.
```

### SEE ALSO

* [cscli collections](/cscli/cscli_collections.md)	 - Manage collections from hub

