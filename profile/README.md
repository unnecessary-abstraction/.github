<!--
Copyright (C) 2023 Paul Barker
SPDX-License-Identifier: CC-BY-4.0
-->

# An Unnecessary Abstraction

Here you will find open source projects maintained by
[Paul Barker](https://pbarker.dev).

Feel free to contact me via [email :email:](mailto:paul@pbarker.dev) or
[Mastodon :elephant:](https://social.afront.org/@pbarker).

## Active Projects

* [mirrorshades](https://github.com/unnecessary-abstraction/mirrorshades)
  (Python application, Apache-2.0 licensed):
  A tool for automatically syncing data from git repository hosts (e.g.
  GitHub), cloud storage (e.g. NextCloud or Dropbox), mail servers and other
  remote sources. Easily extensible to support syncing over additional
  protocols. Using mirrorshades with a scheduling mechanism (such as
  [systemd timers](https://opensource.com/article/20/7/systemd-timers) or
  [yacron](https://pypi.org/project/yacron/)) allows you to maintain a local
  mirror as part of a caching or backup strategy.

* [meta-linux-mainline](https://github.com/unnecessary-abstraction/meta-linux-mainline)
  (OpenEmbedded/Yocto Project layer, MIT licensed):
  A collection of recipes for building the mainline and stable Linux kernel
  releases from kernel.org. This complements the kernel recipes in
  openembedded-core by offering older and (sometimes) newer kernels with no
  downstream patches applied (aka vanilla kernels). Currently updated around
  once every 2-3 months, though this can be improved with funding.

* [pbarker.dev](https://github.com/unnecessary-abstraction/pbarker.dev)
  ([Pelican](https://getpelican.com/) website, Apache-2.0 & CC-BY-NC-4.0 licensed):
  The source code for my personal website <https://pbarker.dev>.

* [scripts](https://github.com/unnecessary-abstraction/scripts)
  (Python, Apache-2.0 licensed):
  A collection of random scripts & tools which aren't big enough to justify
  having their own repositories.

## Inactive Projects

The following projects are no longer actively maintained.

* [containers](https://github.com/unnecessary-abstraction/containers)
  (Dockerfiles, Apache-2.0 licensed):
  Docker/Podman container images

* [betatest](https://github.com/unnecessary-abstraction/containers)
  (Python library, Apache-2.0 licensed):
  A couple of simple helpers for use with pytest.
