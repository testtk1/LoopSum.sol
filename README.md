# LoopSum.sol
Deploy a contract on Base LoopSum.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract LoopSum {
    function sum(uint n) public pure returns (uint) {
        uint total = 0;
        for (uint i = 0; i <= n; i++) {
            total += i;
        }
        return total;
    }
}
