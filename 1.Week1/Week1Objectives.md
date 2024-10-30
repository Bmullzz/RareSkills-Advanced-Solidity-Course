# RareSkills Week 1

## Topics

- Bonding curves
- safeERC20 transfer
- ERC777 re-entrancy
- Writing stylistically coorect Solidity code

//TODO

- 2 markdown files
    - MD 1 - Create a markdown file about what problems ERC777 and ERC1363 solves. Why was ERC1363 introduced, and what issues are there with ERC777?
    - Why does the SafeERC20 program exist and when should it be used?

- 4 Smart contracts
    - Contract 1 - Token with sanctions. Create a fungible token that allows an admin to ban specified addresses from sending and receiving tokens.
    - Contract 2 - Token with god mode. A special address is able to transfer tokens between addresses at will.
    - Contract 3 - Token sale and buyback with bonding curve. The more tokens a user buys, the more expensive the token becomes. To keep things simple, use a linear bonding curve. 
    - Contract 4 -  Untrusted escrow. Create a contract where a buyer can put an arbitrary ERC20 token into a contract and a seller can withdraw it 3 days later. Based on your readings above, what issues do you need to defend against? Create the safest version of this that you can while guarding against issues that you cannot control. Does your contract handle fee-on transfer tokens or non-standard ERC20 tokens.
