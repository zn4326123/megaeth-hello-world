# MegaETH Hello World

**My first smart contract deployed on MegaETH testnet**

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloMegaETH {
string public message = "Hello from MegaETH!";

function update(string memory newMsg) public {
message = newMsg;
}
}
--- ## Deployment Info -
**Network**: MegaETH Testnet - **Contract Address**: `0x...` (update after deploy)
- **Block Number**: #123456
<p align="center">
 <img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="150"/
>
</p>

