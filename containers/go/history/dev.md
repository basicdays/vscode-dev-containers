# [go](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/go)

**Image version:** dev

**Source release/branch:** [main](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/go)

**Definition variations:**
- [1.17-bullseye](#variant-117-bullseye)
- [1.16-bullseye](#variant-116-bullseye)
- [1.17-buster](#variant-117-buster)
- [1.16-buster](#variant-116-buster)

## Variant: 1.17-bullseye

**Digest:** sha256:c1c85e1dd301d780294f1591695557c21bee02527126e0a34e487427fcac435f

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/go:dev-1.17-bullseye
mcr.microsoft.com/vscode/devcontainers/go:dev-1.17
mcr.microsoft.com/vscode/devcontainers/go:dev-1
mcr.microsoft.com/vscode/devcontainers/go:dev-1-bullseye
mcr.microsoft.com/vscode/devcontainers/go:dev-bullseye
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.17.6 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | 3f5402e2687475d83ec98613dc93373620e5ce57 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.7.5 |
| honnef.co/go/tools | 0.2.1 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.1.3 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.8.0 |
| github.com/golangci/golangci-lint | 1.43.0 |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u1 |
| dialog | 1.3-20201126-1 |
| g++ | 4:10.2.1-1 |
| gcc | 4:10.2.1-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u2 |
| libc6-dev | 2.31-13+deb11u2 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u1 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u1 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1k-1+deb11u1 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u2 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| make | 4.3-4.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5 |
| pkg-config | 0.29.2-1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.17-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2 |
| zsh | 5.8-6+b2 |

## Variant: 1.16-bullseye

**Digest:** sha256:570173c4e51b5332364b03c8da3836dff849306d8e98600a2c65faccd46c31a2

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/go:dev-1.16-bullseye
mcr.microsoft.com/vscode/devcontainers/go:dev-1.16
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 11 (bullseye)

**Architectures:** linux/amd64, linux/arm64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.16.13 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.7.5 |
| honnef.co/go/tools | 0.2.1 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.1.3 |
| github.com/uudashr/gopkgs | 1.3.2 |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.8.0 |
| github.com/golangci/golangci-lint | 1.43.0 |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.2.4 |
| apt-utils | 2.2.4 |
| ca-certificates | 20210119 |
| curl | 7.74.0-1.3+deb11u1 |
| dialog | 1.3-20201126-1 |
| g++ | 4:10.2.1-1 |
| gcc | 4:10.2.1-1 |
| git | 1:2.30.2-1 |
| gnupg2 | 2.2.27-2 |
| htop | 3.0.5-7 |
| iproute2 | 5.10.0-4 |
| jq | 1.6-2.1 |
| less | 551-2 |
| libc6 | 2.31-13+deb11u2 |
| libc6-dev | 2.31-13+deb11u2 |
| libgssapi-krb5-2 | 1.18.3-6+deb11u1 |
| libicu67 | 67.1-7 |
| libkrb5-3 | 1.18.3-6+deb11u1 |
| liblttng-ust0 | 2.12.1-1 |
| libssl1.1 | 1.1.1k-1+deb11u1 |
| libstdc++6 | 10.2.1-6 |
| locales | 2.31-13+deb11u2 |
| lsb-release | 11.1.0 |
| lsof | 4.93.2+dfsg-1.1 |
| make | 4.3-4.1 |
| man-db | 2.9.4-2 |
| manpages | 5.10-1 |
| manpages-dev | 5.10-1 |
| manpages-posix | 2017a-2 |
| manpages-posix-dev | 2017a-2 |
| nano | 5.4-2 |
| ncdu | 1.15.1-1 |
| net-tools | 1.60+git20181103.0eebece-1 |
| openssh-client | 1:8.4p1-5 |
| pkg-config | 0.29.2-1 |
| procps | 2:3.3.17-5 |
| psmisc | 23.4-2 |
| rsync | 3.2.3-4+deb11u1 |
| strace | 5.10-1 |
| sudo | 1.9.5p2-3 |
| unzip | 6.0-26 |
| vim-tiny | 2:8.2.2434-3+deb11u1 |
| wget | 1.21-1+deb11u1 |
| yarn | 1.22.17-1 |
| zip | 3.0-12 |
| zlib1g | 1:1.2.11.dfsg-2 |
| zsh | 5.8-6+b2 |

## Variant: 1.17-buster

**Digest:** sha256:00ad4c4e38ecb33b61878ea43ef27ae983ea3c1b0da49491e6a60991c83eadad

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/go:dev-1.17-buster
mcr.microsoft.com/vscode/devcontainers/go:dev-1-buster
mcr.microsoft.com/vscode/devcontainers/go:dev-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.17.6 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.7.5 |
| honnef.co/go/tools | 0.2.1 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.1.3 |
| github.com/uudashr/gopkgs | 2.0.1+incompatible |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.8.0 |
| github.com/golangci/golangci-lint | 1.43.0 |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u2 |
| dialog | 1.3-20190211-1 |
| g++ | 4:8.3.0-1 |
| gcc | 4:8.3.0-1 |
| git | 1:2.20.1-2+deb10u3 |
| gnupg2 | 2.2.12-1+deb10u1 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10 |
| libc6-dev | 2.28-10 |
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
| make | 4.2.1-1.2 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| pkg-config | 0.29-6 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1+deb10u1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u3 |
| unzip | 6.0-23+deb10u2 |
| vim-tiny | 2:8.1.0875-5 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.17-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1 |
| zsh | 5.7.1-1 |

## Variant: 1.16-buster

**Digest:** sha256:804aa3e6ac9cce9e0412c3541dc6d358d934634975b3410da363a8fbbde18789

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/go:dev-1.16-buster
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Debian GNU/Linux 10 (buster)

**Architectures:** linux/amd64

**Available (non-root) user:** vscode

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Go](https://golang.org/dl) | 1.16.13 | /usr/local/go |

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/vscode/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /usr/local/share/nvm |

**Go tools and modules**

| Tool / module | Version |
|---------------|---------|
| golang.org/x/tools/gopls | 0.7.5 |
| honnef.co/go/tools | 0.2.1 |
| golang.org/x/lint | 0.0.0-20210508222113-6edffad5e616 |
| github.com/mgechev/revive | 1.1.3 |
| github.com/uudashr/gopkgs | 1.3.2 |
| github.com/ramya-rao-a/go-outline | 0.0.0-20210608161538-9736a4bde949 |
| github.com/go-delve/delve | 1.8.0 |
| github.com/golangci/golangci-lint | 1.43.0 |

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 1.8.2.3 |
| apt-utils | 1.8.2.3 |
| ca-certificates | 20200601~deb10u2 |
| curl | 7.64.0-4+deb10u2 |
| dialog | 1.3-20190211-1 |
| g++ | 4:8.3.0-1 |
| gcc | 4:8.3.0-1 |
| git | 1:2.20.1-2+deb10u3 |
| gnupg2 | 2.2.12-1+deb10u1 |
| htop | 2.2.0-1+b1 |
| iproute2 | 4.20.0-2+deb10u1 |
| jq | 1.5+dfsg-2+b1 |
| less | 487-0.1+b1 |
| libc6 | 2.28-10 |
| libc6-dev | 2.28-10 |
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
| make | 4.2.1-1.2 |
| man-db | 2.8.5-2 |
| manpages | 4.16-2 |
| manpages-dev | 4.16-2 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| nano | 3.2-3 |
| ncdu | 1.13-1+b1 |
| net-tools | 1.60+git20180626.aebd88e-1 |
| openssh-client | 1:7.9p1-10+deb10u2 |
| pkg-config | 0.29-6 |
| procps | 2:3.3.15-2 |
| psmisc | 23.2-1+deb10u1 |
| rsync | 3.1.3-6 |
| strace | 4.26-0.2 |
| sudo | 1.8.27-1+deb10u3 |
| unzip | 6.0-23+deb10u2 |
| vim-tiny | 2:8.1.0875-5 |
| wget | 1.20.1-1.1 |
| yarn | 1.22.17-1 |
| zip | 3.0-11+b1 |
| zlib1g | 1:1.2.11.dfsg-1 |
| zsh | 5.7.1-1 |

