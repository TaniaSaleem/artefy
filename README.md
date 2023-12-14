## Description
Artefy deals with City or Horror images, Different collections of NFTs like Patron Badges, drops and Paintings etc. are included in it.

## Contract Details


1. NFT platform with dashboard, drop pages, marketplace, and auctions on Polygon blockchain network. 
2. Cross-chain bridge to transfer the NFT from the Polygon chain to Cronos chain.
3. ERC721 standard for Smart Contracts and Proxy pattern based approach for upgradeability.

## Components 

### Minting Portal
* Mint one NFT or batch of NFTs
     * IssueToken
     * IssueBatch

### Trading
* NFTs buying and Selling
    * Build the trading module for NFTs buying and Selling
    * Two options for payments
        * Matic
        * Fiat 
          * Paypal 
          *  Strape

### Marketplace
* Fixed point selling, English Auctions, available both in Fiat and Crypto
   * Build the Marketplace Smart Contracts using the Escrow approach
      * Listing of NFTs to Marketplace 
      * Unlisting of NFTs from Marketplace
      * Fixed point selling 

  * Build the English Auction with the following functionalities in Smart Contracts 
    * Create/Cancel/Update Auction
    * Bidding (Crypto/Fiat)
    * Refund Bid
    * Claim Auction Amount

### Bridging
* To bridge the NFTs on Cronos chain
  * Create and deploy NFT contracts on both chains.
  * Create and deploy bridge contracts on both chains.

### Deployed Contracts Addresses
* https://mumbai.polygonscan.com/address/0x5B12c1BD4fc7Fe1A7d829678E1b4cD69c541736b#code
* https://mumbai.polygonscan.com/address/0xF3914Bd4B0C29BA662f9e807Ee0c53082bba9c43#code
* https://mumbai.polygonscan.com/address/0xb7b909271a5653d5aca901b5b73a80bf9c620491#code
* https://mumbai.polygonscan.com/address/0x9df6c07c19e59c4545dc115605747d7a3f4aac09
