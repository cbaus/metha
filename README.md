# Metha - The Meta-Ethereum Token
* __Token symbol__: METH
* __Deployed Contract Address__: [__Main Net__](https://etherscan.io/address/0x364aa6b380cb4f9cee6711326d6b33a81ce1998c) / [Testing on Rinkeby](https://rinkeby.etherscan.io/address/0x41bD17Ee4155Eb79ed77d7e197B006411074601B)
* __Contract JSON__: [metha.json](https://raw.githubusercontent.com/cbaus/metha/3c53ecb89eb03a5421a8992e42ba9791c5953a0c/metha.json)
* __Contract code__: [meth.sol](https://raw.githubusercontent.com/cbaus/metha/3c53ecb89eb03a5421a8992e42ba9791c5953a0c/meth.sol)
* __Traded on Exchanges__: [EtherDelta](https://etherdelta.com/#0x364aa6b380cb4f9cee6711326d6b33a81ce1998c-ETH)
* __Logo__:<br/>
![Metha logo](metha_logo_small.png)

## What is Metha?
It is an ERC20 token that represents 0.01 ETH. It can be converted to and from ETH but also traded and exchanged natively. At first sight, this seems to have no purpose but it actually can scientifically answer some questions about the Ethereum blockchain and smart contract security. Read on.

## Why recreate Ehtereum on the Ethereum blockchain?
This is not Ethereum, it is a tokenized ETH coin which bears distinct differences to the original coin.
Please bear with me to understand the full concept of this smart contract.<br/>
First the downside, METH does lose some functionality, for example it cannot be used natively as gas
or be traded as Ethereum on exchanges. It is, however, directly convertible and, thus, can indirectly fulfill
any function ETH fulfills. A small amount of fees have to be paid for each conversion. Due to the fact
that METH is not ETH, any rule or regulation that solely applies to ETH and is not enforced through the
Ethereum code does not apply to METH. Therefore tax regulations can be very different. Also legality of
ownership has be specifically applied to METH as well.<br/>
Furthermore, the token aims to be listed on cryptocurrency exchanges. When this happens, it should trade very
closely to the price of 0.01 ETH. Keep in mind, that a smart contract is never as secure as the main chain because
it dependes on an additional top layer. A small difference in the price of METH is expected and reflects
the general opinion of METH users on the smart contract trustability. This includes the security of the
virtual machine, the bytecode compilation through solidity 0.4.19, the ERC20 proposal and the implementation itself.


### Price of METH compared to ETH.
The following image shows factors that influence the METH price:<br/>
![Meth Price](./price.png)<br/>
The red arrow furthest to the right shows the contribution of the security decrease through the smart contract.
The difference due to the fee price is estimated further below in the text. The increase in the utility depends, however,
on multiple factors inclusing the domicile of the exchange, the regulations and others. No exact estimate can be given
at this time but it is expected to be lower than the influence due to the security in the beginning.

### Meta^n
Just think about the posibilities of Meta-Metha or even higher derivatives.

## Why not create another coin on Ethereum or Ethereum on another
blockchain?  This refers to a peg of an blockchain to a token on,
e.g., the Ethereum blockchain. Some projects like this exist out there
but they require offchain entities to function as a link between the
(side-)chains.  It is possible to natively on the Ethereum blockchain
to create any other token as a "meta"-token but ETH is the most
natural target for this project.

## Is a transaction more expensive for ETH or for METH?
A simple transaction on the main chain costs 21000 Gas.
On METH a transfer of token costs 36414 gas for transaction cost and 13542 gas for the execution cost (total 49956).
The payment is therefore about 2.5 times more expensice but as of 2018-07-10 about 0.0005 ETH which is about $0.24.
The fees are thus still acceptable low to send METH.

## Fees, security and owner rights
There are __no fees__ except for the blockchain
gas. The owner cannot take away any of your METH or stop you from
converting it into ETH. The contract guarantees that you will be able
to convert back. The owner can only help if poor souls send tokens
instead of ETH to the contract address.

