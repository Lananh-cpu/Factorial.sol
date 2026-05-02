# Factorial.sol
Factorial.sol
pragma solidity ^0.8.20;
contract Factorial {
    function fact(uint n) public pure returns(uint) {
        uint f = 1;
        for(uint i=1;i<=n;i++){
            f *= i;
        }
        return f;
    }
}
