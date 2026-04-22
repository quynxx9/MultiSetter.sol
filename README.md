# MultiSetter.sol
MultiSetter.sol
pragma solidity ^0.8.20;
contract MultiSetter {
    uint public a;
    uint public b;

    function set(uint _a, uint _b) public {
        a = _a;
        b = _b;
    }
}
