# Install Git on QNAP

This code is copy from Michael Huang blog post <https://sdhuang32.github.io/install-git-on-qts/>

using docker image `sdhuang32/c7-systemd` to build git into /share/Public/toolchain/

then add path to `/etc/profile`

## Installation

```sh
curl -LJO https://github.com/ntsd/install-git-on-qnap/archive/refs/tags/0.0.1.tar.gz

tar -xvzf install-git-on-qnap-0.0.1.tar.gz

cd install-git-on-qnap-0.0.1

./install-git-on-qts.sh
```
