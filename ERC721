// SPDX-License-Identifier: MIT
pragma solidity >=0.6.2 <0.9.0;

import "https://github.com/openZeppelin/openzeppelin-contracts/blob/release-v3.1.0/contracts/token/ERC721/ERC721.sol";
contract NFT is ERC721{
constructor (string memory name, string memory symbol) public ERC721(name,symbol){

    }
    function mint (uint256 _id) public{
        _mint(msg.sender,_id);
    }
}
