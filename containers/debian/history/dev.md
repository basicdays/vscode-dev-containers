# [debian](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/debian)

**Image version:** dev

**Source release/branch:** [main](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/debian)

**Definition variations:**
- [buster](#variant-buster)
- [bullseye](#variant-bullseye)
- [stretch](#variant-stretch)

## Variant: buster

**Digest:** sha256:c3a972e04db4501857fbc95703de109734723d53f6e2f10dfd8c2cb54895c23a

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/base:dev-buster
mcr.microsoft.com/vscode/devcontainers/base:dev-debian-10
mcr.microsoft.com/vscode/devcontainers/base:dev-debian10
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 3f5402e2687475d83ec98613dc93373620e5ce57 | /home/vscode/.oh-my-zsh |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u2 |
| dialog | 1.3-20190211-1 |
| git | 1:2.20.1-2+deb10u3 |
| gnupg2 | 2.2.12-1+deb10u1 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10 |
| libgcc1 | 1:8.3.0-6 |
| libgssapi-krb5-2 | 1.17-3+deb10u3 |
| libicu63 | 63.1-6+deb10u2 |
| libkrb5-3 | 1.17-3+deb10u3 |
| liblttng-ust0 | 2.10.3-1 |
| libssl1.1 | 1.1.1d-0+deb10u7 |
| libstdc++6 | 8.3.0-6 |
| locales | 2.28-10 |
| lsb-release | 10.2019051400 |
| lsof | 4.91+dfsg-1 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1+deb10u1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u3 |
| unzip | 6.0-23+deb10u2 |
| vim-tiny | 2:8.1.0875-5 |
| wget | 1.20.1-1.1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1 |
| zsh | 5.7.1-1 |

## Variant: bullseye

**Digest:** sha256:658cc0ae30e0185c6449ce5802d08805f64b00a991c019501d8f4b240688122f

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/base:dev-bullseye
mcr.microsoft.com/vscode/devcontainers/base:dev-debian-11
mcr.microsoft.com/vscode/devcontainers/base:dev-debian11
mcr.microsoft.com/vscode/devcontainers/base:dev-debian
mcr.microsoft.com/vscode/devcontainers/base:dev
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/vscode/.oh-my-zsh |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u1 |
| dialog | 1.3-20201126-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u2 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u1 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u1 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1k-1+deb11u1 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u2 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2 |
| zsh | 5.8-6+b2 |

## Variant: stretch

**Digest:** sha256:56fbef5cf8db9602139b7199db9733021f41ace8c2e319b41f7ba655b95269e6

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/base:dev-stretch
mcr.microsoft.com/vscode/devcontainers/base:dev-debian-9
mcr.microsoft.com/vscode/devcontainers/base:dev-debian9
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 9 (stretch)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/vscode/.oh-my-zsh |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.4.11 |
| apt-utils | 1.4.11 |
| ca-certificates | 20200601~deb9u2 |
| curl | 7.52.1-5+deb9u16 |
| dialog | 1.3-20160828-2 |
| git | 1:2.11.0-3+deb9u7 |
| gnupg2 | 2.1.18-8~deb9u4 |
| htop | 2.0.2-1 |
| iproute2 | 4.9.0-1+deb9u1 |
| jq | 1.5+dfsg-1.3 |
| less | 481-2.1 |
| libc6 | 2.24-11+deb9u4 |
| libgcc1 | 1:6.3.0-18+deb9u1 |
| libgssapi-krb5-2 | 1.15-1+deb9u3 |
| libicu57 | 57.1-6+deb9u5 |
| libkrb5-3 | 1.15-1+deb9u3 |
| liblttng-ust0 | 2.9.0-2+deb9u1 |
| libssl1.0.2 | 1.0.2u-1~deb9u6 |
| libssl1.1 | 1.1.0l-1~deb9u4 |
| libstdc++6 | 6.3.0-18+deb9u1 |
| locales | 2.24-11+deb9u4 |
| lsb-release | 9.20161125 |
| lsof | 4.89+dfsg-0.1 |
| man-db | 2.7.6.1-2 |
| manpages | 4.10-2 |
| manpages-dev | 4.10-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 2.7.4-1 |
| ncdu | 1.12-1+b1 |
| net-tools | 1.60+git20161116.90da8a0-1 |
| openssh-client | 1:7.4p1-10+deb9u7 |
| procps | 2:3.3.12-3+deb9u1 |
| psmisc | 22.21-2.1+b2 |
| rsync | 3.1.2-1+deb9u3 |
| strace | 4.15-2 |
| sudo | 1.8.19p1-2.1+deb9u3 |
| unzip | 6.0-21+deb9u2 |
| vim-tiny | 2:8.0.0197-4+deb9u4 |
| wget | 1.18-5+deb9u3 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.8.dfsg-5 |
| zsh | 5.3.1-4+deb9u4 |

