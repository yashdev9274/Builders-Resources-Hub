---
title: Basics
description: This page contains Solidity resource
slug: /solidity
sidebar_position: 1
---

# Intro to solidity

## Default-Values

This code is the simple representaion of what are the defalut values of these following data types.

```jsx title="Solidity code"

contract DefaultValuse{

    bool public b; // false
    uint public u; // 0
    int public i; // 0
    address public a; // 0x0000000000000000000000000000000000000000
    bytes32 public b32; // 0x0000000000000000000000000000000000000000000000000000000000000000

}
```

## Constants

These are the state variables that never changes, these types of variables are used to safe gas.

```jsx title="Solidity code"

// Here two contracts are created
// to create constant variable we use "constant" and write the variable in capital letters.

// here the cost of gas used in deploying this "Consants" contract is

contract Constants{

    address public constant MY_ADDRESS = 0x0000000000000000000000000000000000000000; // random address
    uint public constant MY_UINT = 123;
}

contract Var{
        address public MY_ADDRESS = 0x0000000000000000000000000000000000000000; // random address

}
```
