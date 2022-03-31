# TREE v1.1

### Summary
After TREE was deployed, we quickly found that the short interval between rebalances harmed TREE holders and distributed more profits to arb bots than to charity. We had to "trick" our reserve to send the $176k worth of DAI to an intermediary wallet, which was done through creating a new reserve and four manipulator contracts so that when rebasing was turned back on, the rebase would send the entire reserve to the new reserve.  From there we donated a portion of DAI to charity and returned the rest to investors.

### Resources
* [Announcement](https://medium.com/tree-finance/tree-2-0-62afc7225ffb)
* Contracts
    * [PausedReserve](https://etherscan.io/address/0x4Cd09fF2ceE7d82393B49e2dF0faC371Ab836Ac4)
    * [UniswapRouterManipulator](https://etherscan.io/address/0x9c551476d3852fEa0B37aEF5dF1bcAa80F06Ce94)
    * [OracleManipulator](https://etherscan.io/address/0x69a25Ac7e03F9c570C07aB36e13d582AD43259B8)
    * [UniswapPairManipulator](https://etherscan.io/address/0x0A5466b35CAfC4711C347fc2d34E10fC97E56774)
    * [OmniBridgeManipulator](https://etherscan.io/address/0x40F02925fA31e596623fB23F41275F58F47fA95c)
