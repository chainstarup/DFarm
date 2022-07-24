# Unicofarm
Farm ERC-1155 NFT by staking ERC-20 LP Tokens

## User Flow:
 * NFT's are deposited into this contract, having some Price as `points` associated to them.
 * In order to claim an NFT, the user must have sufficient `points` to reach Price threshold.
 * To increase `points` balance, user must deposit lp tokens to this contract.
 * `points` balance increases dynamically with each passing second allowing user to Farm NFTs!

 ## Features:
* Supports ERC-1155 NFT
* Stake LP tokens.
* Rate of NFT accumulation proportional to amount of LP tokens user is providing.
* Farm for all NFTs at once. Choose particular NFTs on claim.
* Resume farming from where left, if LP tokens withdrawn in between.
* Claim all eligible random NFTs with farmed points balance.
* Withdraw LP tokens, and claim NFTs in single transaction.
