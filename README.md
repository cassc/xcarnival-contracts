All XCarnival contracts deployed by 0xc087629431256745e6e3d87b3ec14e8b42d47e48 as of 06/28/2022


[Source](https://xcarnival-lab.medium.com/xcarnival-has-got-1-467-eth-back-the-security-agencies-have-tentatively-determined-the-hackers-3ea05ad134ae)

> The overall logic is that the hacker first generates multiple contract addresses, then goes to call the `XNFT` contract, pledges the NFT, then generates an orderld, then withdraws the NFT, multiple times this operation, then calls the `XToken` contract’s `borrow()` through the previous contract address as well as the orderld In the call to `borrow()`, there is no judgment that the NFT has been withdrawn, so the hacker borrowed and then did not pay it back, then keeps repeating this operation.


