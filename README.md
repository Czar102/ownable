<h1 align=center><code>
Ownable Contract using Two-Step Transfer Pattern
</code></h1>


## Introduction

Contract module which provides a basic access controler mechanism,
where there is an account (an owner) that can be granted exclusive
access to specific functions.

The contract owner is changeable through a two-step transfer pattern,
in which a pending owner is assigned by the owner. Afterwards the
pending owner can accept the contract's ownership.

Note that the contract's owner can not be set to the zero address,
i.e. the contract can not be without ownership.

The contract's initial owner is the contract deployer.

This module is used through inheritance. It will make available the
modifier `onlyOwner`, which can be applied to your functions to
restrict their use to the owner.

This contract is heavily inspired by OpenZeppelin's `Ownable` contract.
For more info see https://github.com/OpenZeppelin/openzeppelin-contracts.


## Safety

This is experimental software and is provided on an "as is" and
"as available" basis.

We do not give any warranties and will not be liable for any loss incurred
through any use of this codebase.


## Installation

To install with [**DappTools**](https://github.com/dapphub/dapptools):

```sh
dapp install byterocket/ownable
```

To install with [**Foundry**](https://github.com/gakonst/foundry):

```sh
forge install bytetocker/ownable
```
