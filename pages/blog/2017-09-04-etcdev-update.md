---
title: "ETCDEV Update"
date: 2017-09-0
author: Isaac Ardis (@whilei/@ia)
---


### The team

__Stewart (@sjm)__ has left us to join the hoards of ICO overachievers, tempting fate
with a brilliant scheme to unify and simplify Dapp programming with a Nix-based
package manager and graph-based language based on the _Fractalide_ system.

While we were sorry to see Stewart leave, we are very glad to welcome Javascript
developer __Yury (@gagarin55)__. Yury has a broad and diverse background in blockchain
technology and applications, and has been a longtime steady and vital force in the ETC community. He's wasted no time in providing a myriad of firm, yet gentle,
refactorings, fixes, and new features for Emerald Wallet.


### The projects

#### Geth

- Implemented [ECIP-1017](https://github.com/ethereumproject/ECIPs/blob/master/ECIPs/ECIP-1017.md) monetary policy protocol changes in the __4.0.0 release__, as well as a few other features and improvements. If you use geth, please upgrade! The latest stable releases can always be found on the [Github Release page](https://github.com/ethereumproject/go-ethereum/releases), and change details can be found in [the changelog](https://github.com/ethereumproject/go-ethereum/blob/master/CHANGELOG.md).

#### SputnikVM

- Created [SputnikVM-Dev](https://github.com/ethereumproject/sputnikvm-dev/releases), an interactive environment using [SputnikVM](https://github.com/ethereumproject/sputnikvm) and [etcommon](https://github.com/ethereumproject/etcommon-rs) to enable __development and testing on SputnikVM via RPC__. Just look at all those [supported methods](https://github.com/ethereumproject/sputnikvm-dev)!
- For bonus points, @sorpaas also built a minimalist (but fully functioning!) client with Sputnik and etcommon called [etclient](https://github.com/sorpaas/etclient).


#### Emerald Wallet

- A __second beta release__ [v0.5.0-beta2](https://github.com/ethereumproject/emerald-wallet/releases) of Emerald Wallet will be available this week, including features, improvements, and fixes relating to key import/export, hardware support, and UI improvements.


#### Emerald Vault + CLI

- Refactored Emerald Vault into two packages: [Emerald Vault](https://github.com/ethereumproject/emerald-rs) contains the Emerald business and security logic, and [Emerald CLI](https://github.com/ethereumproject/emerald-cli) now contains the user-facing implementation connected with Vault. This separation of concerns should pave the way for smoother future-feature implementations and core and Dapp developer experiences.

### ECIPs

Several new proposals have been added, including

- a recursive length prefix __(RLP) media type__ for streamlining HTTP responses
- changes relating to the __GHOST protocol__ for using uncles in total difficulty calculation
- options for increasing address and transaction __readability__
- an outline for beginning discussions around __sidechains__

As usual, all proposals associated discussions can be found in the [ECIPs Github repository](https://github.com/ethereumproject/ECIPs/pulls).
