# Learn Solidity, Blockchain, and Smart Contracts in a Free 16-Hour Course

### Step 1: [Head over to Free Code Camp](https://www.freecodecamp.org/news/learn-solidity-blockchain-and-smart-contracts-in-a-free/):


<iframe width="560" height="315" src="https://www.youtube.com/embed/M576WGiDBdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> 


This is a example [configuration](https://www.mkdocs.org/user-guide/configuration/):

Blockchain engineers are in extreme demand. Almost every day they are building billion dollar applications.

We just released a full course on the freeCodeCamp.org YouTube channel that will teach you all about Solidity, the blockchain, and smart contracts. Solidity is an object-oriented programming language for writing smart contracts.

This course will give you a full introduction into all of the core concepts in blockchain, smart contracts, solidity, NFTs/ERC721s, ERC20s, Coding Decentralized Finance (DeFi), python and solidity, Chainlink, Ethereum, upgradable smart contracts, and full stack blockchain development.

Here are all the sections covered in this comprehensive course:

Lesson 0: Welcome To Blockchain
1. What is a Blockchain?
2. Making Your First Transaction
3. How Do Blockchains Work?
4. Consensus
5. The Future
6. Miscellaneous
Lesson 1: Welcome to Remix! Simple Storage
Everything in this section can be read about in the Solidity Documentation
Remix
Basic Solidity
Deploying to a "Live" network
Lesson 2: Storage Factory
Inheritance, Factory Pattern, and Interacting with External Contracts
Lesson 3: Fund Me
Payable, msg.sender, msg.value, Units of Measure
Chainlink Oracles
Importing from NPM and Advanced Solidity
Lesson 4: Web3.py Simple Storage
Installing VSCode, Python, and Web3
Our First Python Script with Web3.py - Deploying a Contract
Interacting with Our Contract in Python & Web3.py
Lesson 5: Brownie Simple Storage
Brownie Introduction
Installing Brownie
Brownie Simple Storage Project
Testing Basics
Lesson 6: Brownie Fund Me
Introduction
Dependencies, Deploying, and Networks
Funding and Withdrawing Python Scripts
Testing across networks
Git
Lesson 7: SmartContract Lottery
Introduction
Lottery.sol
Testing Lottery.sol
Lottery.sol Testnet Deployment
Lesson 8: Chainlink Mix
Brownie Mixes
Lesson 9: ERC20s, EIPs, and Token Standards
Lesson 10: Defi & Aave
Defi Intro
Aave UI
Programmatic Interactions with Aave
Testing
Lesson 11: NFTs
Non-Technical Explainer
Simple NFT
SimpleCollectible Testing
Advanced NFT
Advanced deploy_and_create
Creating Metadata & IPFS
Lesson 12: Upgrades
Introduction to upgrading smart contracts
Upgrades-mix and code
Testing Upgrades
Upgrades on a testnet
Bonus Lesson 13: Full Stack Defi
Defi Stake Yield Brownie Scripts & Tests
Testing our Defi Stake Yield Brownie Dapp
Front End / Full Stack
Closing and Summary
Security
Where do I go now?
Learning More
Community
Hackathons

```yml
# Project information
site_name: Your Project
site_url: https://[YOUR_GITHUB_ID].github.io/[your-repository-name]
site_author: Thomas Südbröcker

# Repository
repo_name: [YOUR-REPOSITORY-NAME]
repo_url: https://github.com/[YOUR_GITHUB_ID]/[YOUR-REPOSITORY-NAME]
edit_uri: edit/master/[YOU-DOCUMENTATION_FOLDER]
docs_dir: [YOU-DOCUMENTATION_FOLDER]

# Navigation
nav:
  - Welcome:
    - Overview: README.md   
  
## DO NOT CHANGE BELOW THIS LINE

# Copyright
# TBD

# Theme
theme:
  name: material
  font:
    text: IBM Plex Sans
    code: IBM Plex Mono
  icon:
    logo: material/library
  features:
    # - navigation.tabs
    - navigation.instant
    - navigation.expand
  palette:
    scheme: default
    primary: blue
    accent: blue

# Plugins
plugins:
  - search

# Customization
# TBD

# Extensions
markdown_extensions:
  - abbr
  - admonition
  - attr_list
  - def_list
  - footnotes
  - meta
  - toc:
      permalink: true
  - pymdownx.arithmatex:
      generic: true
  - pymdownx.betterem:
      smart_enable: all
  - pymdownx.caret
  - pymdownx.critic
  - pymdownx.details
  - pymdownx.emoji:
      emoji_index: !!python/name:materialx.emoji.twemoji
      emoji_generator: !!python/name:materialx.emoji.to_svg
  - pymdownx.highlight
  - pymdownx.inlinehilite
  - pymdownx.keys
  - pymdownx.mark
  - pymdownx.smartsymbols
  - pymdownx.snippets:
      check_paths: true
  - pymdownx.superfences:
      custom_fences:
        - name: mermaid
          class: mermaid
          format: !!python/name:pymdownx.superfences.fence_code_format
  - pymdownx.tabbed
  - pymdownx.tasklist:
      custom_checkbox: true
  - pymdownx.tilde
```

### Step 2: Preview your documentation locally

```sh
python3 -m mkdocs serve  
```

* Example output:

```sh
INFO    -  Cleaning site directory 
INFO    -  Documentation built in 0.57 seconds 
[I 210125 09:15:48 server:335] Serving on http://127.0.0.1:8000
INFO    -  Serving on http://127.0.0.1:8000
[I 210125 09:15:48 handlers:62] Start watching changes
INFO    -  Start watching changes
[I 210125 09:15:48 handlers:64] Start detecting changes
INFO    -  Start detecting changes
```

### Step 3: Build the pages in the folder "/site", which will be added to your GitHub project

```sh
python3 -m mkdocs build
```