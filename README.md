# QuantisNet (QUAN) Information
![QuantisNet](https://cdn.discordapp.com/attachments/436649409535541248/528345762795487240/321x81.png)

| [**Whitepaper**](https://github.com/QuantisDev/QuantisNet-PIVX-Fork-NEW-BLOCKCHAIN/blob/master/Whitepaper.pdf.pdf) | [**Website**](https://quantisnetwork.org/) | [**Discord**](https://discord.gg/cFYF57h) | [**Telegram**](https://t.me/quantis) |
## Core Specifications
- Consensus Algorithm: PoS + zPoS Hybrid

- Hashing Algorithm: XEVAN

- Block size: 2 MB

- Block Time: 110 Seconds (Re-targeting every block)

- Transactions per second: 173 TPS (current theoretical maximum)

- Mine-able: No

- Stake-able: Yes (Earn block reward from coin ownership)

- Masternode Support: Yes, 5,000 QUAN per masternode

- MINEABLE TOTAL MAX SUPPLY : 9,364,125 QUAN

- PRE-MINE SUPPLY Block 1 : 1,155,000 QUAN     

- QUAN MAX SUPPLY : 10,519,125 QUAN

- P2P Port: 7771

- RPC Port: 7772

- Current Wallet Version ( 2.0.1 ) Please see releases tabs for official wallet downloads 
* https://github.com/QuantisDev/QuantisNet-Fork-New-Chain/releases *

## Coin Emission Rate
Year 1: Block reward: Max. **5 QUAN** per block (split dynamically between stakers & masternodes)

Year 2: Block reward: Max. **6 QUAN** per block (split dynamically between stakers & masternodes)

Year 3: Block reward: Max. **0.03** QUAN per block (split dynamically between stakers & masternodes)

Year 4: Block reward: Max. **0.015** QUAN per block (split dynamically between stakers & masternodes)

## Coin Supply Control
**Dynamic Coin Supply**: ALL transaction fees & zPIV minting fees are burnt.

## Block Reward Breakdown

0 - 2,500 TEST NET phase 0.001 QUAN / BLOCK ( 50% MN - 50% POS )

BLOCK 2,501 - 12,501 - 28.5 QUAN / MN 1.5 POS = 300,000 QUAN ( 95% - 5% ) 300,000.01 

BLOCK 12,502 - 512,502 - 4 QUAN/BLOCK 1.0  POS = 500,000 QUAN ( 80% - 20% ) 2,500,000

BLOCK 512,503 - 1,012,503 - 4.5 QUAN/BLOCK 1.5 POS = 3,000,000 QUAN ( 75% - 25% ) 3,000,000

BLOCK 1,012,504 - 1,512,504  - 0.02 QUAN/BLOCK - 0.01 POS = 0 QUAN ( 100% - 66.6% ) 15,000

BLOCK 1,512,505 - 1,762,505 - 0.01 QUAN/BLOCK - .005 POS = 0 QUAN ( 100% - 66.6% ) 3,750

BLOCK 1,762,505 - 2,012,505 - 0.001 QUAN/BLOCK - 0.0005 POS = 0 QUAN ( 100% - 66.6% ) 375

BLOCK 2,012,506 - INFINITY - 0.000001 QUAN/BLOCK - .000001 POS ( 100% - 50% )

### Blocks Forecast


| Expected Date        | Blocks Passed           |
| ------------- |:-------------:|
| January 2020      | **512,502** |
| January 2021      | **1,025,006**      |
| January 2022 | **1,525,008**      |
| July 2022 | **1,762,505**      |
| January 2023 | **2,012,505**      |

## Budget Eligibility / Governance 
20% of Block Rewards used to fund budget when activated
Each Masternode is allowed 1 vote per proposal 

## PoS Stake Eligibility (QUAN)
Maturity Confirms: 101 confirms

Wallet Status: Requires core wallet to remain online and unlocked for staking.

## zPoS Stake Eligibility (QUAN) ( Will be disabled until future wallet release )
Maturity Confirms: 200 confirms

Wallet Status: Requires core wallet to remain online and unlocked for staking.

## Transaction Send Eligibility
Minimum Confirm (QUAN) : 6 confirms

Minimum Confirm (zQUAN): 20 confirms + 1 new mint of the same denomination in the network

## SwiftX Eligibility
Confirmations: 1 for locking and 6 to spend.
Collateral held time: 15 minutes.

## Masternode Network Expiry
Node expiration: 120 minutes
Node removal: 130 minutes


# Quantis Privacy Features
- Privacy Technology: Custom Zerocoin Protocol based on Libzerocoin (we call this zQUAN)

- Key Features: Custom accumulator check-pointing system

- Accumulator Modulus: RSA-2048

- zPIV Denominators: 1, 5, 10, 50, 100, 500, 1000, 5000

- Mint time: >= 0.5 seconds

- Spend time: >= 2.5 seconds

- Maximum single Spend limit: 35,000 QUAN

- Maximum single Spend denomination count limit: 7

- Fees (mint): 0.01 PIV per minted zQUAN denomination.

- Fees (spend): No fee

- Minimum QUAN confirmation count required to mint zQUAN: 6 confirmations

- Minimum zQUAN confirmation count required before spend: 20 confirmations

- Maturity requirement before zQUAN can be spent: 1 new identical denomination mint added to accumulator


### Proof of Work (PoW) Phase Period
April 25th 2018 to January 4th 2019 (FINISHED)
### Proof of Stake (PoS) Phase Period
April 25th 2018 from block 1 onward (CURRENT)
