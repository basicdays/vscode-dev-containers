# [codespaces-linux](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/codespaces-linux)
This document describes the base contents of the default GitHub Codespaces dev container image. Note that this image also includes detection logic to dynamically install additional language / runtime versions based on your repository's contents. Dynamically installed content can be found in sub-folders under `/opt`.

**Image version:** dev

**Source release/branch:** [main](https://github.com/microsoft/vscode-dev-containers/tree/main/containers/codespaces-linux)

**Digest:** sha256:136409193d2ef0cf5afe6e4f59ae2843154c34fdee758869db585f55d545c74d

**Tags:**
```
mcr.microsoft.com/vscode/devcontainers/universal:dev-focal
mcr.microsoft.com/vscode/devcontainers/universal:dev-linux
mcr.microsoft.com/vscode/devcontainers/universal:dev
```
> *To keep up to date, we recommend using partial version numbers. Use the major version number to get all non-breaking changes (e.g. `0-`) or major and minor to only get fixes (e.g. `0.200-`).*

**Linux distribution:** Ubuntu 20.04.3 LTS (debian-like distro)

**Architectures:** linux/amd64

**Available (non-root) user:** codespace

### Contents
**Languages and runtimes**

| Language / runtime | Version | Path |
|--------------------|---------|------|
| [Node.js](https://nodejs.org/en/) | 10.23.0<br />12.22.6<br />14.17.6 | /opt/nodejs/&lt;version&gt; |
| [Python](https://www.python.org/) | 3.6.15<br />3.7.12<br />3.8.12 | /opt/python/&lt;version&gt; |
| [Java](https://adoptopenjdk.net/) | 17.0.1 | /opt/java/&lt;version&gt; |
| [.NET](https://dotnet.microsoft.com/) | 3.1.415<br />5.0.403<br />6.0.100 | /home/codespaces/.dotnet<br />/opt/dotnet |
| [Ruby](https://www.ruby-lang.org/en/) | 2.7.2 | /opt/ruby/&lt;version&gt; |
| [PHP](https://xdebug.org/) | 7.2.34<br />7.3.27<br />7.4.26 | /opt/php/&lt;version&gt; |
| [PowerShell](https://docs.microsoft.com/en-us/powershell/) | 7.2.1 | /opt/microsoft/powershell |
| GCC | 9.3.0-17ubuntu1~20.04 | 
| Clang | 10.0.0-4ubuntu1 | 
| [Go](https://golang.org/dl) | 1.17.6 | /usr/local/go |
| [Rust](https://github.com/rust-lang/rust) | 1.58.1 | /usr/local/cargo<br />/usr/local/rustup |
| [Jekyll](https://jekyllrb.com/) | 4.2.1 | 

**Tools installed using git**

| Tool | Commit | Path |
|------|--------|------|
| [Oh My Zsh!](https://github.com/ohmyzsh/ohmyzsh) | d4f5fa37e8be25e1b4f281fcf5b90cf700dc3c95 | /home/codespace/.oh-my-zsh |
| [nvm](https://github.com/nvm-sh/nvm.git) | 3fea5493a431ac64470d4230d4b51438cf213bd1 | /home/codespace/.nvm |
| [nvs](https://github.com/jasongin/nvs) | 5c04eb39ade8148d1424cfd80fc4f035f9c3ac0f | /home/codespace/.nvs |
| [rbenv](https://github.com/rbenv/rbenv.git) | a76c4aaafa3dc710e16e1aefe2208bad0247b595 | /usr/local/share/rbenv |
| [ruby-build](https://github.com/rbenv/ruby-build.git) | 4f1e62f2f031c28a4bdbed8a28bf959b02b1b885 | /usr/local/share/ruby-build |

**Pip / pipx installed tools and packages**

| Tool / package | Version |
|----------------|---------|
| pylint | 2.12.2 |
| flake8 | 4.0.1 |
| autopep8 | 1.6.0 |
| black | 21.12b0 |
| yapf | 0.32.0 |
| mypy | 0.931 |
| pydocstyle | 6.1.1 |
| pycodestyle | 2.8.0 |
| bandit | 1.7.1 |
| virtualenv | 20.13.0 |
| pipx | 1.0.0 |

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

**Ruby gems and tools**

| Tool / gem | Version |
|------------|---------|
| rake | 13.0.6 |
| ruby-debug-ide | 0.7.3 |
| debase | 0.2.4.1 |
| jekyll | 4.2.1 |

**Cargo / rustup (Rust) crates and tools**

| Tool / crate | Version |
|--------------|---------|
| rls | 1.41.0 |
| rustfmt | 1.4.38 |
| rust-analysis | 1.58.1 |
| rust-src | 1.58.1 |
| clippy | 1.58.1 |

**Other tools and utilities**

| Tool | Version | Path |
|------|---------|------|
| [git](https://github.com/git/git) | 2.34.1 | /usr/local |
| [Xdebug](https://xdebug.org/) | 3.1.2 | /opt/php/lts |
| [Composer](https://getcomposer.org/) | 2.0.8 | /opt/php-composer |
| [kubectl](https://github.com/kubernetes/kubectl) | 1.23.2 | /usr/local/bin |
| [Helm](https://github.com/helm/helm) | 3.7.2 | /usr/local/bin |
| [Docker Compose](https://github.com/docker/compose) | 1.29.2 | /usr/local/bin |
| [SDKMAN!](https://github.com/sdkman/sdkman-cli) | 5.13.1 | /usr/local/sdkman |
| [rvm](https://github.com/rvm/rvm) | 1.29.12 | /usr/local/rvm |
| [GitHub CLI](https://github.com/cli/cli) | 2.4.0 | 
| [yarn](https://yarnpkg.com/) | 1.22.15 | /opt/yarn |
| [Maven](https://maven.apache.org/) | 3.6.3 | /opt/maven |
| [Gradle](https://gradle.org/) | 7.3.3 | 
| Docker (Moby) CLI &amp; Engine | 20.10.11+azure | 

**Additional linux tools and packages**

| Tool / library | Version |
|----------------|---------|
| apt-transport-https | 2.0.6 |
| apt-utils | 2.0.6 |
| azure-cli (Azure CLI) | 2.32.0-1~focal |
| build-essential | 12.8ubuntu1.1 |
| ca-certificates | 20210119~20.04.2 |
| clang | 1:10.0-50~exp1 |
| cmake | 3.16.3-1ubuntu1 |
| cppcheck | 1.90-4build1 |
| curl | 7.68.0-1ubuntu2.7 |
| dialog | 1.3-20190808-1 |
| g++ | 4:9.3.0-1ubuntu2 |
| gcc | 4:9.3.0-1ubuntu2 |
| gdb | 9.2-0ubuntu1~20.04.1 |
| git | 1:2.25.1-1ubuntu3.2 |
| git-lfs (Git Large File Support) | 3.0.2 |
| gnupg2 | 2.2.19-3ubuntu2.1 |
| htop | 2.2.0-2build1 |
| iproute2 | 5.5.0-1ubuntu1 |
| iptables | 1.8.4-3ubuntu2 |
| jq | 1.6-1ubuntu0.20.04.1 |
| less | 551-1ubuntu0.1 |
| libatk-bridge2.0-0 | 2.34.2-0ubuntu2~20.04.1 |
| libatk1.0-0 | 2.35.1-1ubuntu2 |
| libc6 | 2.31-0ubuntu9.2 |
| libc6-dev | 2.31-0ubuntu9.2 |
| libcups2 | 2.3.1-9ubuntu1.1 |
| libgbm1 | 21.0.3-0ubuntu0.3~20.04.5 |
| libgcc1 | 1:10.3.0-1ubuntu1~20.04 |
| libgssapi-krb5-2 | 1.17-6ubuntu4.1 |
| libgtk-3-0 | 3.24.20-0ubuntu1 |
| libicu66 | 66.1-2ubuntu2.1 |
| libkrb5-3 | 1.17-6ubuntu4.1 |
| liblttng-ust0 | 2.11.0-1 |
| libnspr4 | 2:4.25-1 |
| libnss3 | 2:3.49.1-1ubuntu1.6 |
| libpango-1.0-0 | 1.44.7-2ubuntu4 |
| libpangocairo-1.0-0 | 1.44.7-2ubuntu4 |
| libsecret-1-dev | 0.20.4-0ubuntu1 |
| libssl1.1 | 1.1.1f-1ubuntu2.10 |
| libstdc++6 | 10.3.0-1ubuntu1~20.04 |
| libx11-6 | 2:1.6.9-2ubuntu1.2 |
| libx11-xcb1 | 2:1.6.9-2ubuntu1.2 |
| libxcomposite1 | 1:0.4.5-1 |
| libxdamage1 | 1:1.1.5-2 |
| libxfixes3 | 1:5.0.3-2 |
| lldb | 1:10.0-50~exp1 |
| llvm | 1:10.0-50~exp1 |
| locales | 2.31-0ubuntu9.2 |
| lsb-release | 11.1.0ubuntu2 |
| lsof | 4.93.2+dfsg-1ubuntu0.20.04.1 |
| lxc | 1:4.0.6-0ubuntu1~20.04.1 |
| make | 4.2.1-1.2 |
| man-db | 2.9.1-1 |
| manpages | 5.05-1 |
| manpages-dev | 5.05-1 |
| manpages-posix | 2013a-2 |
| manpages-posix-dev | 2013a-2 |
| moby-cli (Docker CLI) | 20.10.11+azure-3 |
| moby-engine (Docker Engine) | 20.10.11+azure-3 |
| nano | 4.8-1ubuntu1 |
| ncdu | 1.14.1-1 |
| net-tools | 1.60+git20180626.aebd88e-1ubuntu1 |
| openssh-client | 1:8.2p1-4ubuntu0.4 |
| openssh-server | 1:8.2p1-4ubuntu0.4 |
| pigz | 2.4-1 |
| pkg-config | 0.29.1-0ubuntu4 |
| procps | 2:3.3.16-1ubuntu2.3 |
| psmisc | 23.3-1 |
| python3-dev | 3.8.2-0ubuntu2 |
| python3-minimal | 3.8.2-0ubuntu2 |
| rsync | 3.1.3-8ubuntu0.1 |
| sed | 4.7-1 |
| software-properties-common | 0.99.9.8 |
| strace | 5.5-3ubuntu1 |
| sudo | 1.8.31-1ubuntu1.2 |
| tar | 1.30+dfsg-7ubuntu0.20.04.1 |
| unzip | 6.0-25ubuntu1 |
| valgrind | 1:3.15.0-1ubuntu9.1 |
| vim | 2:8.1.2269-1ubuntu5.6 |
| vim-doc | 2:8.1.2269-1ubuntu5.6 |
| vim-tiny | 2:8.1.2269-1ubuntu5.6 |
| wget | 1.20.3-1ubuntu2 |
| xtail | 2.1-6 |
| zip | 3.0-11build1 |
| zlib1g | 1:1.2.11.dfsg-2ubuntu1.2 |
| zsh | 5.8-3ubuntu1 |

