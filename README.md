
# Avalanche Ecosystem

Need Image from design team

Welcome to The Avalanche Ecosystem- This repository is the source data for The Avalanche Ecosystem, located here <https://ecosystem.avax.network/>.

If you are interested in adding your project to the Avalanche Ecosystem page, please follow the guidelines below. Please ensure complete accuracy with all form questions. Inaccurate or incomplete submissions will not be accepted.

# Submission Guidelines

To submit a project, create a pull request composed of two files:

  1. In the `projects` directory include the project info listed below. Name the file {{slug}}.json
  2. In the `img` directory include an image to represent your project.

If your project already exists in the `projects` direct, don't re-submit the project details. Instead edit the original file and/or the logos in a new pull request. 

## Project Info Submission

### **Required Fields**

- `name`: The name of the project.
- `slug`: A unique project identifier with no spaces.
- `date`: The date of project implementation. Format `yyyy-mm-dd`.
- `highlight`: A 1-2 sentence summary of the project and its offering in the Avalanche ecosystem.
- `logo`: A path for the logomark for the project.
- `tags`: From the list below, provide a comma separated list of categories that best describe the project. Minimum of 1 and maximum 4 tags.
- `status`: The development stage of the project- `live`,`coming soon`, or `terminated`.
- `website`: A URL for the project's website to direct users towards.
- `twitter`: The URL for the project's Twitter.
- `contact`: The project's best contact- public email, discord address, link, etc... 
- `summary`: A public summary of the project. Limited to 200 words. Provide an accurate description of the project to help users understand the offering.

### **Optional Fields**

- `telegram`: The URL for the project's Telegram channel.
- `discord`: The URL for the project's Discord channel.
- `docs`: The URL for the project's public documents.
- `github`: The URL for the project's github.
- `token`: The symbol of the project's specifically associated Avalanche token, only if applicable. If the token is wrapped for Avalanche, please indicate the wrapped token symbol.
- `cmc`: The URL for the project's token price tracker, only if applicable. e.g. coinmarketcap, coingecko, etc...

### Image Criteria
- All image files must be 80x80px / at an aspect ratio of ~1.
- Only .svg, and .png files are accepted.
- Please do not use SVGs with embedded PNG or JPG images.
- The image should be round for the best display result. A round mask will be applied when deployed, so non-round images will have edges cut off.


### Example File- Dev needs to decide on how to format this with info they have. Fill in example

```json
{
  "name": "Avalanche Bridge",
  "slug": "avalanche-bridge",
  "date": "2021-07-29",
  "highlight": "Avalanche's official low cost, fast, and simple bridge to move assets between chains.",
  "logo": "/img/avalanche-bridge.png",
  "tags": ["ava-labs","bridges","multi-chain"],
  "status": "Live",
  "website": "https://bridge.avax.network/",
  "twitter": "https://twitter.com/avalancheavax",
  "contact": "https://www.avax.network/contact",
  "summary": "The Avalanche Bridge (AB) is a low cost, low latency, and secure way to transfer assets from one blockchain to another. Leveraging Intel SGX and built on the back of Avalanche’s low energy and high TPS consensus algorithm, the AB provides users a smooth, quick, and inexpensive experience. Currently supporting the movement of ERC20’s from Ethereum onto the Avalanche C-Chain and back, Ava Labs has plans to advance the bridge further and increase the number of connected chains. Ava Labs designed the Avalanche Bridge on the principles that transactions across the bridge will be secure and finality will be swift. This makes Avalanche’s official bridge one of the best options to move assets onto the Avalanche C-Chain. Good Bridging.",
  
  "telegram": "https://t.me/avalancheavax",
  "discord": "https://t.me/avalancheavax",
  "docs":"https://docs.avax.network/learn/avalanche-bridge-faq",
  "github":"https://github.com/ava-labs",
  "token":"AVAX",
  "cmc":"https://coinmarketcap.com/currencies/avalanche/"
  
}
```

### Tags

Currently available categories to classify the project are listed below. Please only use one of the options and avoid typos.

```text
accelerator
amm
ava-labs
avalance-native
bridges
cex
community
dao
dapp
defi
dex
enterprise
exchange
explorer
fiat-ramps
funds
gaming
governance
government
info
infrastructure
launchpads
lending
marketplace
multi-chain
nft
nodes
oracle
portfolio
security
stablecoin
tools
wallet
yield-farming
```

## Questions

If there are any questions regarding submission... need to collect this info
