---
title: SSHing to a Server
menu:
  main:
    parent: 'setup'
    weight: 7
aliases:
  - /docs/ssh
---

Once the [initial configuration]({{% relref "initial-configuration.md" %}}) is
complete, ScaleFT Users can SSH to all enrolled servers.

From an enrolled client, run `sft ssh <hostname>` where `<hostname>` is
the name of any enrolled host. You can see a list of available hosts by
browsing to your project in the ScaleFT Dashboard.

**Note:** the first time you run `sft ssh` you will be prompted to approve your
client's access to infrastructure credentials. This approval will last for up to
10 hours.
