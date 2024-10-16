---
type: docs
title: "rad group show CLI reference"
linkTitle: "rad group show"
slug: rad_group_show
url: /reference/cli/rad_group_show/
description: "Details on the rad group show Radius CLI command"
---
## rad group show

Show the details of a resource group

### Synopsis

Show the details of a resource group

Resource groups are used to organize and manage Radius resources. They often contain resources that share a common lifecycle or unit of deployment.

A Radius Application and its resources can span one or more resource groups, and do not have to be in the same resource group as the Radius Environment into which it's being deployed into.

Note that these resource groups are separate from the Azure cloud provider and Azure resource groups configured with the cloud provider.


```
rad group show resourcegroupname [flags]
```

### Examples

```
rad group show rgprod
```

### Options

```
  -g, --group string       The resource group name
  -h, --help               help for show
  -o, --output string      output format (supported formats are json, table) (default "table")
  -w, --workspace string   The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
```

### SEE ALSO

* [rad group]({{< ref rad_group.md >}})	 - Manage resource groups

