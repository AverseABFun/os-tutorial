# 00: Environment Setup

In this tutorial, we will be using some tools, including [NASM](https://nasm.us/) and [QEMU](https://www.qemu.org/). To install them:

Windows:

First, install [Winget](https://github.com/microsoft/winget-cli) from [here](https://www.microsoft.com/p/app-installer/9nblggh4nns1). Then:

```sh
winget install nasm qemu
```

Debian/Ubuntu:

```sh
sudo apt install nasm qemu
```

MacOS:

First, install [Homebrew](https://brew.sh/). Then:

```sh
brew install nasm qemu
```

Other Linux distros:

I am unfamiliar with distos other then Debian/Ubuntu, and you should know your way around your package manager system or how to build from source.