# Token-Contracts
Create an BEP20 Token with liquidity and tax fee in BNB, USDT and USDC with our full audited smart contract solidity code, 100% token ownership.

Learn how to edit and deploy the contracts

https://www.youtube.com/watch?v=jocEqLQVIGI

All this contracts created by https://0xfactory.com

# How every contract works:
### 1- BEP20.sol : 
this contract collect fees when holders buy, sell or transfer and devided the tax %50 will send to the marketing wallet in BNB and %50 will added to the liquidity pool

### 2- bep20-USDT.sol : 
this contract collect fees when holders buy, sell or transfer and devided the tax %50 will send to the marketing wallet in USDT and %50 will added to the liquidity pool

### 3- bep20-USDC.sol : 
this contract collect fees when holders buy, sell or transfer and devided the tax %50 will send to the marketing wallet in USDC and %50 will added to the liquidity pool

### 4- BEP20-TaxOnly.sol : 
this contract collect fees when holders buy, sell or transfer and send all the tax to the marketing wallet in BNB


# Note:
the contract use 0xfactory router to make swap to collect and give the tax and increase the liquidity, it cost fee of 0.0005 BNB per swap.
