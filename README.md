# basecontract
#### HOW TO CREATE SIMPLE CONTRACT ON BASE MAINNET WITH LESS GAS FEE ####

1. go to remix.ethereum.org
2. Create new file
3. create name .sol example base.sol
4. Paste this script

```// SPDX-License-Identifier: GPL-3.0

pragma solidity >=0.8.2 <0.9.0;


contract testBase { 

    uint256 number;


    function store(uint256 num) public {
        number = num;
    }


    function retrieve() public view returns (uint256){
        return number;
    }
}
```
5.Click Solidity Compiler 
- Compile file tadi
- Click Logo ETH ( Deploy )
- Click Environment
- Select " Injected Provider - Metamask "
- Deploy & Accept Contract Via Metamask
