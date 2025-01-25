// SPDX-License-Identifier: MIT
pragma solidity ^0.8.7;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract AfghanCoin is ERC20, Ownable {
    constructor() ERC20("AfghanCoin", "AFG") Ownable(msg.sender) {
        // Initialize token supply: 100 billion tokens
        uint256 initialSupply = 100_000_000_000 * 10 ** decimals();
        _mint(msg.sender, initialSupply);
    }
}
