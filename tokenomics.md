# Tokenomics

### Tokenomics

| Token Name |   Network  | Initial Supply | Debase Rate (per block) | Rewards (per block) |
| :--------: | :--------: | :------------: | :---------------------: | :-----------------: |
|    GARY    | PulseChain |   369,000,000  |          0.001%         |         1000        |

* 49% to Hex OA Address
  * We encourage the OA to donate this portion to the SENS Research Foundation.
* 6% for Hexican Legal Fees Fund
  * this fund supports Hexicans in their ongoing battle with the SEC (i.e. Hexologist)
* 9% to Dev aka The Commissioner
* 36% Initial LP (GARY / PLS)
  * LP token will be burned

### Rewards

If you stake your tokens in either Civil Action or Wells Notice Vaults, you will receive rewards for each block. The table above shows how many rewards in total will be distributed per block. All rewards you receive will not start to debase, until you claim them.

To see what % of rewards go to Civil Action and Wells Notice, please refer to the vaults table. Rewards can be changed by Degens Care and is subject to change.

Depositing or claiming will incur 24 hours lock on withdrawals. Depositing or claiming will not extend the timer but the timer will reset with another 24 hours. The debase is happening for the whole token supply including GARY in vaults and GARY in LP. Since GARY in LP also gets debased the amount of GARY will decrease but the amount of HEX will remain the same. That's the beauty of it since the price of GARY will continue to increase if no one is selling and GARY is stable.

### Contracts

The official contract addresses are:

* [GARY Contract](https://scan.v3.testnet.pulsechain.com/address/0x8aAC5570d54306Bb395bf2385ad327b7b706016b): 0x8aAC5570d54306Bb395bf2385ad327b7b706016b
* [GaryFactory Contract](https://scan.v3.testnet.pulsechain.com/address/0xA75E74a5109Ed8221070142D15cEBfFe9642F489): 0xA75E74a5109Ed8221070142D15cEBfFe9642F489
* [RichardHeartIsAlwaysRight Contract](https://scan.v3.testnet.pulsechain.com/address/0x64f5219563e28EeBAAd91Ca8D31fa3b36621FD4f): 0x64f5219563e28EeBAAd91Ca8D31fa3b36621FD4f

Degens Care has transferred ownership of all contracts to a Timelock contract, which will delay all changes 3 days before any contract admin state updates become live on the blockchain. And all minting and rebasing privileges are revoked for deployer:

* [Timelock Contract](https://scan.v3.testnet.pulsechain.com/address/0xd3b893cd083f07Fe371c1a87393576e7B01C52C6): 0xd3b893cd083f07Fe371c1a87393576e7B01C52C6
* [renounce MINTER\_ROLE](https://scan.v3.testnet.pulsechain.com/tx/0xcc971597d2ef396bb3064f2304799df9c6a6bf9edb46be14e53ffc57e6bbd153)
* [renounce REBASER\_ROLE](https://scan.v3.testnet.pulsechain.com/tx/0x3e29efae74bced0525b4e92c268564e5152de99c11e8ed8667e77c20e4a54863/)
