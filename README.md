# Comprehensive Lightning Network Node Operator Resources

A curated collection of essential tools, guides, and communities for Bitcoin Lightning Network node operators.

## Introduction

This guide provides a comprehensive list of resources for Lightning Network node operators, including installation guides, management tools, security best practices, and community resources. Whether you're a beginner or an experienced operator, you'll find valuable information to help you run and optimize your Lightning Network node.

## Table of Contents

1. [Essential Reading](#essential-reading)
2. [Node Installation](#node-installation)
3. [Backups and Recovery](#backups-and-recovery)
4. [Self-Hosting Solutions](#self-hosting-solutions)
5. [Managed Cloud Hosting](#managed-cloud-hosting)
6. [Lightning Network Implementations](#lightning-network-implementations)
7. [Node Management Web Interfaces](#node-management-web-interfaces)
8. [Security Tools](#security-tools)
9. [Node Management Tools](#node-management-tools)
10. [Node Services](#node-services)
11. [Channel Management](#channel-management)
12. [Tutorials and Guides](#tutorials-and-guides)
13. [Liquidity Management](#liquidity-management)
14. [Network Explorers](#network-explorers)
15. [Communities](#communities)
16. [Watchtowers](#watchtowers)
17. [Mempool Resources](#mempool-resources)
18. [Educational Resources](#educational-resources)
19. [Network Statistics](#network-statistics)
20. [Further Reading](#further-reading)

## Essential Reading

- [Understanding Lightning Network: Comprehensive Guide by Diamond Hands](https://docsend.com/view/x2yscafayexddzps)
- [Jameson Lopp's Lightning Network Liquidity Management Guide](https://blog.lopp.net/lightning-network-liquidity-management-guide/)
- [Alex Bosworth's In-Depth Liquidity Management Strategies](https://github.com/alexbosworth/run-lnd/blob/master/LIQUIDITY.md)
- [Lightning Network Node Profitability: PLEBNET Insights](https://www.youtube.com/watch?v=LRZy-VtCPe4)
- [Running a Lightning Network Node: A Beginner's Journey](https://medium.com/coinmonks/adventures-in-running-a-bitcoin-lightning-node-part-1-the-awakening-61345585acc3)
- [Mastering Inbound Liquidity: Step-by-Step Guide](https://www.youtube.com/watch?v=WWs1D9LLcpc)

## Node Installation

### LND (Lightning Network Daemon)

- [Alex Bosworth's Comprehensive LND Installation Guide](https://github.com/alexbosworth/run-lnd)
- [Official LND Installation Documentation](https://github.com/lightningnetwork/lnd/blob/master/docs/INSTALL.md)
- [Bitcoin Kit Makefile: Streamlined Installation](https://github.com/Perlover/bitcoin-kit-makefile)
- [LND with PostgreSQL Integration](https://github.com/blckbx/lnd_postgres)
- [Secure LND Setup via VPN](https://github.com/Wired4ncer/lnd_via_vpn)


### CLN (Core Lightning)

- [Video Tutorial: Step-by-Step CLN Installation](https://www.youtube.com/watch?v=_Hrnls92TxQ)
- [RaspiBolt CLN Installation and Configuration](https://raspibolt.org/guide/bonus/lightning/cln.html)
- [Core Lightning Plugins Repository](https://github.com/lightningd/plugins)

## Backups and Recovery

- [LND Backup and Recovery Strategies](https://github.com/lightningnetwork/lnd/blob/master/docs/recovery.md)
- [Core Lightning Backup Best Practices](https://lightning.readthedocs.io/BACKUP.html)

## Self-Hosting Solutions

- [RaspiBlitz: DIY Bitcoin & Lightning Node](https://github.com/rootzoll/raspiblitz)
- [Umbrel: User-Friendly Bitcoin Node](https://getumbrel.com/)
- [MyNode: Full Bitcoin Node & Lightning Network Box](https://mynodebtc.com/)
- [NixBitcoin: Nix-based Bitcoin Node](https://nixbitcoin.org/)
- [Blockstream's Guide: Building a High-Quality Lightning Network Node](https://medium.com/blockstream/build-a-pretty-good-lightning-network-node-468778a078b7)
- [Minibolt: Step-by-Step Guide to Building a Bitcoin & Lightning Node](https://github.com/minibolt-guide/minibolt)
- [Awning: Portable Docker-Only Bitcoin + Lightning Node](https://github.com/giovantenne/awning)
- [TunnelSats: Pre-Configured VPN for Lightning Nodes](https://github.com/Tunnelsats/tunnelsats)

## Managed Cloud Hosting

- [Nodl: Professional Bitcoin & Lightning Node Solutions](https://www.nodl.eu/)
- [Voltage: Cloud-Native Bitcoin Infrastructure](https://voltage.cloud/)
- [Rizful: Instant Lightning Node](https://rizful.com/)

## Lightning Network Implementations

- [LND (Lightning Network Daemon)](https://github.com/lightningnetwork/lnd)
- [Core Lightning (formerly c-lightning)](https://github.com/ElementsProject/lightning)
- [Eclair: Scala-based Lightning Implementation](https://github.com/ACINQ/eclair)
- [LDK-node](https://github.com/lightningdevkit/ldk-node)
- [LDK Server: Fully-Functional Lightning Node Daemon](https://github.com/lightningdevkit/ldk-server)

## Node Management Web Interfaces

- [Ride The Lightning (RTL): Feature-Rich Web Interface](https://github.com/Ride-The-Lightning/RTL)
- [Thunderhub: Powerful Lightning Node Management Dashboard](https://github.com/apotdevin/thunderhub)
- [LNCLi Web: User-Friendly LND Web Client](https://github.com/mably/lncli-web)
- [Lightning Terminal: All-in-One Node Management Tool](https://github.com/lightninglabs/lightning-terminal)
- [LNDG: LND Dashboard and Graph](https://github.com/cryptosharks131/lndg)
- [Torq: Advanced Lightning Network Management Platform](https://github.com/lncapital/torq)
- [Bitcoin Connect: Enable WebLN in All Browsers with a Single Button](https://github.com/getAlby/bitcoin-connect)

## Security Tools

- [Validated Lightning Signer: Enhanced Security for Lightning Nodes](https://vls.tech/)
- [Sphinx Key: Hardware Security Module for Lightning](https://github.com/stakwork/sphinx-key)
- [Lightning Vault: Secure Key Management Solution](https://github.com/bolt-observer/lightning-vault/)
- [Validating Lightning Signer (VLS): Library for Securing Lightning Nodes](https://github.com/lightning-signer/validating-lightning-signer)
- [ngx_l402: Nginx Module for L402 Lightning Network Authentication](https://github.com/DhananjayPurohit/ngx_l402)

## Node Management Tools

### CLN Tools 
- [CLN Cheatsheet: Quick Reference for Core Lightning Commands](https://github.com/grubles/cln-cheatsheet)
- [lnurl-commando](https://github.com/jb55/lnurl-commando) - An lnurl/lnaddress server that fetches invoices over commando
- [CLBOSS: Automated Core Lightning Node Manager](https://github.com/ZmnSCPxj/clboss)
- [Rune Workshop](https://jb55.com/runes) - A web UI for constructing commando auth runes
- [c-lightning-REST](https://github.com/Ride-The-Lightning/c-lightning-REST) - REST APIs for c-lightning written with node.js
- [circular](https://github.com/giovannizotta/circular) - Core Lightning plugin that helps routing nodes rebalance their channels 
- [consolidator](https://github.com/daywalker90/consolidator/) - Core lightning (CLN) plugin to help consolidate your UTXO's
- [sling](https://github.com/daywalker90/sling) - Core Lightning plugin to automatically rebalance multiple channels
- [nostrify](https://github.com/joelklabo/nostrify) - Core Lightning plugin that sends events to Nostr

### LND Tools
- [Balance of Satoshis: Advanced Node Management Toolkit](https://github.com/alexbosworth/balanceofsatoshis)
- [BOS Commands Document: Comprehensive Guide to Balance of Satoshis](https://github.com/niteshbalusu11/BOS-Commands-Document)
- [Charge-LND: Automated Fee Management for LND](https://github.com/accumulator/charge-lnd)
- [Rebalance-LND: Channel Rebalancing Tool](https://github.com/C-Otto/rebalance-lnd)
- [CircuitBreaker: Automated Channel Management](https://github.com/lightningequipment/circuitbreaker)
- [LNDPyTools: Python-based LND Management Utilities](https://github.com/Gridflare/lndpytools)
- [Lightning Jet: Advanced Node Optimization Tool](https://github.com/itsneski/lightning-jet)
- [LNDManage: Python-based LND Management Suite](https://github.com/bitromortac/lndmanage)
- [LNTop: Top-like Monitoring Tool for LND](https://github.com/edouardparis/lntop)
- [Suez: Channel Rebalancing Script](https://github.com/prusnak/suez)
- [LND-ManageJ: Java-based LND Management Tool](https://github.com/C-Otto/lnd-manageJ)
- [LNDmon: Drop-in LND Monitoring with Prometheus+Grafana](https://github.com/lightninglabs/lndmon)
- [LNC Web: Lightning Node Connect for Web Applications](https://github.com/lightninglabs/lnc-web)
- [LNDinit: Cloud Infrastructure Tooling for LND Provisioning](https://github.com/lightninglabs/lndinit)
- [LndHub.go: Accounting Wrapper for Lightning Network (LndHub Compatible)](https://github.com/getAlby/lndhub.go)


## Node Services

- [LNRouter: Comprehensive Lightning Network Analysis](https://lnrouter.app/)
- [LN Node Insight: Advanced Node Metrics and Analysis](https://lnnodeinsight.com/)
- [Lightning Watch: Real-Time Lightning Network Monitoring](https://lightning.watch/)
- [Alby Hub: Your Own Bitcoin Lightning Node](https://github.com/getAlby/hub)
- [Lightning.Pub: Nostr Native Lightning Node](https://github.com/shocknet/Lightning.Pub)

## Channel Management

### Channel Opening Suggestions


- [Lightning Terminal: Channel Management Platform](https://terminal.lightning.engineering/#/)
- [Lightning Network Autopilot: Automated Channel Management](https://github.com/renepickhardt/lightning-network-autopilot)
- [Faraday: Lightning Channel Management & Optimization Tool](https://github.com/lightninglabs/faraday)
- [PeerSwap Web: Lightweight Web UI for PeerSwap](https://github.com/Impa10r/peerswap-web)

## Tutorials and Guides

- [Lightning Node Management by Openoms: Comprehensive Guide](https://github.com/openoms/lightning-node-management)
- [Bitcoin Tutorials by Openoms: In-Depth Learning Resources](https://github.com/openoms/bitcoin-tutorials)
- [Lightning node tutorials by DarthCoin](https://darth-coin.github.io/nodes/nodes-en.html)
- [Recovering Funds from Stuck Closing Transactions: Troubleshooting Guide](https://community.umbrel.com/t/the-guide-where-your-lightning-close-transaction-cant-get-the-channel-closed/15096)
- [Autoswap to Automate Your Lightning Liquidity Management with Boltz Client](https://blog.boltz.exchange/p/guide-how-to-use-boltz-clients-autoswap)
- [Chantools command generator - helps you do recover funds from broken nodes](https://guggero.github.io/chantools/doc/command-generator.html) -

## Liquidity Management

### Inbound Liquidity

- [Comprehensive Inbound Liquidity Guide](https://github.com/openoms/lightning-node-management/blob/master/docs/createinboundliquidity.md)

### Swaps and Exchanges

- [Coinos: Instant Bitcoin-to-Lightning Swaps](https://coinos.io/login)
- [FixedFloat: Cryptocurrency Exchange with Lightning Support](https://fixedfloat.com/)
- [SideShift: Automated Crypto Trading Platform](https://sideshift.ai/btc/ln)
- [Boltz Exchange: Non-Custodial Bitcoin Exchange](https://boltz.exchange/) - swaps LN, BTC, L-BTC
- [Lightning Loop: Submarine Swaps for Liquidity Management](https://github.com/lightninglabs/loop)
- [Boltz Client: Non-Custodial Swap Client for CLN & LND](https://github.com/BoltzExchange/boltz-client)
- [ZigZag: Fast Crypto Exchange with Lightning Support](https://zigzag.io/)

### Liquidity Marketplaces

- [Lightning Pool: Marketplace for Lightning Liquidity](https://lightning.engineering/pool/)
- [Lightning Pool: Non-Custodial Batched Channel Lease Auction](https://github.com/lightninglabs/pool)
- [Voltage Flow: Liquidity Management Platform](https://voltage.cloud/flow)
- [Amboss Magma: Advanced Liquidity Marketplace](https://amboss.space/magma)

### Channel Leasing and LSPs

- [LNBIG: Large-Scale Lightning Network Service Provider](https://lnbig.com/)
- [Lightning Network Plus (LN+): Collaborative Channel Opening](https://lightningnetwork.plus/)

- [LightningTo.Me: Free Inbound Liquidity Service](https://lightningto.me/)
- [Bitrefill Thor Channels: On-Demand Lightning Channels](https://www.bitrefill.com/buy/lightning-channel/)
- [Voltage Flow: Automated Liquidity Management](https://voltage.cloud/flow/)
- [Blocktank: Professional Lightning Service Provider](https://blocktank.to/)

## Network Explorers

- [1ML: Comprehensive Lightning Network Explorer](https://1ml.com/)
- [Amboss Space: Advanced Lightning Network Analytics](https://amboss.space/)

- [LN Lighthouse: Visual Lightning Network Explorer](https://lnlighthouse.online/)
- [Mempool Lightning Explorer: Bitcoin and Lightning Integration](https://mempool.space/lightning)

## Communities

- [Lightning Liquidity & Pool Telegram Group](https://t.me/LNBalancedChannels)
- [Plebnet Telegram Community](https://t.me/plebnet)
- [Lightning Network Matrix Chat](https://matrix.to/#/#btcln:matrix.org)
- [r/lightningnetwork Subreddit](https://www.reddit.com/r/lightningnetwork/)
- [r/TheLightningNetwork Subreddit](https://www.reddit.com/r/TheLightningNetwork/)
- [Rings of Fire Telegram Group](https://t.me/theRingsOfFire)
- [Rings of Fire GitHub Wiki](https://github.com/Rings-of-Fire/ring-of-fire/wiki)
- [Reddit Liquidity Swaps Thread](https://www.reddit.com/r/TheLightningNetwork/search?sort=new&restrict_sr=on&q=flair%3ALiquidity%2BSwaps)

## Watchtowers

- [The Eye of Satoshi: Rust-based Watchtower Implementation](https://github.com/talaia-labs/rust-teos)
- [LND Watchtower: Built-in Watchtower Functionality](https://docs.lightning.engineering/lightning-network-tools/lnd/watchtower)

## Mempool Resources

- [Mempool.space: Real-Time Bitcoin Mempool Visualizer](https://mempool.space/)

- [Johoe's Bitcoin Mempool Statistics: Historical Mempool Data](https://jochen-hoenicke.de/queue/#BTC,24h,weight)
- [TX Street: Visual Bitcoin and Ethereum Transaction Monitor](https://txstreet.com/v/btc)

## Educational Resources

- [Lightning Curriculum by Chaincode Labs: Comprehensive Learning Path](https://github.com/chaincodelabs/lightning-curriculum)
- [Mastering the Lightning Network: Open-Source Book](https://github.com/lnbook/lnbook)
- [Professional Lightning Network Node Rebalancing Tutorial](https://www.youtube.com/watch?v=0r3Th42zfDk)
- [Comprehensive Bitcoin Lightning Network Node Setup Tutorial](https://www.youtube.com/watch?v=KItleddMYFU)
- [T-bast's Lightning Network Documentation](https://github.com/t-bast/lightning-docs)
- [Interactive Lightning Network Workshop](https://github.com/roeierez/lightning-workshop)
- [Cyberhub's Lightning Network Resources](https://cyberhubnode.notion.site/cyberhubnode/Cyberhub-Home-34858179510a44)

## Network Statistics

- [1ML.com Lightning Network Statistics](https://1ml.com/statistics)
- [Bitcoin Visuals - Lightning Network Metrics](https://bitcoinvisuals.com/lightning)

## Further Reading

- [Diamond Hands Lightning Network Routing Report](https://medium.com/@coin_and_peace/diamond-hands-lightning-routing-report-jan-2022-85733104fa8d)
- [Jameson Lopp's Comprehensive Lightning Network Resource Collection](https://www.lopp.net/lightning-information.html)
- [LND Security Case Study: Recovering Funds from a Hacked Node](https://medium.com/@goryachev/bitcoin-node-security-case-study-e1ca00a378b5)

## Related Resources

To explore other aspects of the Bitcoin and freedom tech ecosystem, check out these additional resource directories:
- [nostr.net](https://www.nostr.net) - A complete guide to Nostr - projects, implementations, developer tools and all other resources
- [liquidnetwork.wiki](https://liquidnetwork.wiki) - A curated list of Liquid Network resources, libraries, tools and applications
- [pubky.tech](https://pubky.tech) - Pubky, an open protocol for censorship resistant web applications
- [dlc.wiki](https://www.dlc.wiki) - Everything you need to know about Discreet Log Contracts
- [ungovernable.tech](https://ungovernable.tech) - A collection of resources on encryption, privacy tools, and decentralized technologies
- [lightning-network.tech](https://www.lightning-network.tech/)  - Essential tools, guides, and communities for Bitcoin Lightning Network node operators.
- [ark-protocol.com](https://ark-protocol.com) - A directory of Ark protocol resources, libraries, tools and applications

## Contributing

If you'd like to add something to this list, please submit a [Pull Request on GitHub](https://github.com/aljazceru/lightning-network.tech).

This directory is maintained by [aljaz](https://disobey.dev/contact/). Your contributions help keep this information up-to-date and valuable for the Lightning Network community.
- [lightning-onion](https://github.com/lightningnetwork/lightning-onion) - Onion Routed Micropayments for the Lightning Network ⭐ 416
- [docs.lightning.engineering](https://github.com/lightninglabs/docs.lightning.engineering) - Building lapps, running lnd, and more ⭐ 73
- [lightning-node-connect](https://github.com/lightninglabs/lightning-node-connect) - No description ⭐ 82
- [docker-bitcoin-core](https://github.com/lightninglabs/docker-bitcoin-core) - A bitcoin-core docker image ⭐ 14
- [lightning-api-ng](https://github.com/lightninglabs/lightning-api-ng) - Automated API-documentation generation source code for Lightning Lab's FOSS software suite ⭐ 5
- [lnc-rn](https://github.com/lightninglabs/lnc-rn) - Lightning Node Connect npm module for React Native ⭐ 7
- [lnc-core](https://github.com/lightninglabs/lnc-core) - Type definitions and utilities for Lightning Node Connect, leveraged by lnc-web and lnc-rn ⭐ 7
- [lnd-fuzz](https://github.com/lightninglabs/lnd-fuzz) - No description ⭐ 5
- [migrate](https://github.com/lightninglabs/migrate) - Database migrations. CLI and Golang library. ⭐ 0
- [charts](https://github.com/lightninglabs/charts) - No description ⭐ 9
- [lnget](https://github.com/lightninglabs/lnget) - wget for the pay-per-request web (powered by Lightning Lab's L402 protocol) ⭐ 10
- [lightning-agent-tools](https://github.com/lightninglabs/lightning-agent-tools) - AI agent toolkit (skills+MCP server) for Lightning Network payments. Run nodes, pay for APIs (L402), host paid endpoints, and manage credentials.  ⭐ 43
- [ai-docs-sync](https://github.com/lightninglabs/ai-docs-sync) - CLI tool to sync AI guidance from .ai-docs/ to harness-specific outputs (Claude, Cursor, Copilot, Codex, Gemini) ⭐ 0
- [L402sdk](https://github.com/lightninglabs/L402sdk) - L402 client SDK for AI agent frameworks — pay for APIs with Lightning ⭐ 15
- [elements](https://github.com/ElementsProject/elements) - Open Source implementation of advanced blockchain features extending the Bitcoin protocol ⭐ 1151
- [libwally-core](https://github.com/ElementsProject/libwally-core) - Useful primitives for wallets ⭐ 302
- [filebazaar](https://github.com/ElementsProject/filebazaar) - Sell digital files with Bitcoin & Lightning :zap: ⭐ 124
- [nanopos](https://github.com/ElementsProject/nanopos) - A simple Lightning :zap: point-of-sale system, powered by Lightning Charge ⭐ 115
- [rust-elements](https://github.com/ElementsProject/rust-elements) - Rust support for Elements transaction/block deserialization ⭐ 57
- [peerswap](https://github.com/ElementsProject/peerswap) - No description ⭐ 124
- [glightning](https://github.com/ElementsProject/glightning) - No description ⭐ 11
- [ELIPs](https://github.com/ElementsProject/ELIPs) - Elements Improvement proposals ⭐ 15
- [qa-assets](https://github.com/ElementsProject/qa-assets) - Elements-related blobs used for quality assurance. ⭐ 2
- [cln-application](https://github.com/ElementsProject/cln-application) - Official core lightning application by Blockstream ⭐ 47
- [garecovery](https://github.com/Blockstream/garecovery) - GreenAddress recovery tool for 2of2 and 2of3 wallets ⭐ 132
- [esplora](https://github.com/Blockstream/esplora) - Explorer for Bitcoin and Liquid ⭐ 1226
- [electrs](https://github.com/Blockstream/electrs) - An efficient re-implementation of Electrum Server in Rust ⭐ 377
- [gdk](https://github.com/Blockstream/gdk) - Blockstream Green Development Kit ⭐ 195
- [green_android](https://github.com/Blockstream/green_android) - Blockstream Green Wallet for Android ⭐ 258
- [green_ios](https://github.com/Blockstream/green_ios) - Blockstream Green Wallet for iOS ⭐ 159
- [satellite-api](https://github.com/Blockstream/satellite-api) - Blockstream Satellite API ⭐ 37
- [bitcoin-images](https://github.com/Blockstream/bitcoin-images) - This repository contains some useful Docker images.  ⭐ 22
- [asset_registry_db](https://github.com/Blockstream/asset_registry_db) - Assets db ⭐ 16
- [green_cli](https://github.com/Blockstream/green_cli) - Command line wallet for Blockstream Green ⭐ 33
- [liquid_multisig_issuance](https://github.com/Blockstream/liquid_multisig_issuance) - Issuance of liquid assets with multisig and registry support ⭐ 7
- [green_qt](https://github.com/Blockstream/green_qt) - Blockstream Green App ⭐ 251
- [Jade](https://github.com/Blockstream/Jade) - Jade hardware wallet ⭐ 454
- [blind_pin_server](https://github.com/Blockstream/blind_pin_server) - No description ⭐ 16
- [greenlight](https://github.com/Blockstream/greenlight) - Build apps using self-custodial lightning nodes in the cloud ⭐ 139
- [asset_registry_testnet_db](https://github.com/Blockstream/asset_registry_testnet_db) - No description ⭐ 3
- [app-bitcoin-new](https://github.com/Blockstream/app-bitcoin-new) - Liquid Network application for Ledger hardware wallets ⭐ 1
- [jadediyflasher](https://github.com/Blockstream/jadediyflasher) - A webpage to flash DIY devices into Jade ⭐ 15
- [lwk](https://github.com/Blockstream/lwk) - Liquid Wallet Kit ⭐ 105
- [tinycbor](https://github.com/Blockstream/tinycbor) - Concise Binary Object Representation (CBOR) Library ⭐ 0
- [lwk-swift](https://github.com/Blockstream/lwk-swift) - No description ⭐ 1
- [qtkeychain](https://github.com/Blockstream/qtkeychain) - Platform-independent Qt API for storing passwords securely. ⭐ 0
- [zxing-cpp](https://github.com/Blockstream/zxing-cpp) - C++ port of ZXing ⭐ 0
- [simplicity-dex](https://github.com/Blockstream/simplicity-dex) - A Distributed Exchange for Simplicity. ⭐ 3
- [gl-sdk-swift](https://github.com/Blockstream/gl-sdk-swift) - Glue code for swift clients wanting to use the gl-sdk code ⭐ 0
- [waterfalls](https://github.com/Blockstream/waterfalls) - No description ⭐ 0
- [simplicity-playground](https://github.com/Blockstream/simplicity-playground) - No description ⭐ 0
- [simplicity-codespace](https://github.com/Blockstream/simplicity-codespace) - No description ⭐ 0
- [electrum](https://github.com/spesmilo/electrum) - Electrum Bitcoin Wallet ⭐ 8455
- [btcpayserver](https://github.com/btcpayserver/btcpayserver) - Accept Bitcoin payments. Free, open-source & self-hosted, Bitcoin payment processor.  ⭐ 7531
- [damus](https://github.com/damus-io/damus) - iOS nostr client ⭐ 2120
- [Lightning-map](https://github.com/KlosStepan/Lightning-map) - Lightning Everywhere ⚡ A platform for collecting merchants and e-shops that accept the Lightning Network (Bitcoin L2) as a payment method. ⭐ 6
- [action-ln](https://github.com/nobe4/action-ln) - Link files between repositories, from GitHub Actions. ⭐ 5
- [constants-float64-ln-two-pi](https://github.com/stdlib-js/constants-float64-ln-two-pi) - Natural logarithm of 2π. ⭐ 3
- [stats-base-dists-cosine-logcdf](https://github.com/stdlib-js/stats-base-dists-cosine-logcdf) - Natural logarithm of cumulative distribution function (CDF) for a raised cosine distribution. ⭐ 2
- [stats-base-dists-lognormal-cdf](https://github.com/stdlib-js/stats-base-dists-lognormal-cdf) - Lognormal distribution cumulative distribution function (CDF). ⭐ 2
- [stats-base-dists-weibull-logcdf](https://github.com/stdlib-js/stats-base-dists-weibull-logcdf) - Weibull distribution logarithm of cumulative distribution function (CDF). ⭐ 2
- [stats-base-dists-lognormal-logpdf](https://github.com/stdlib-js/stats-base-dists-lognormal-logpdf) - Natural logarithm of the probability density function (PDF) for a lognormal distribution. ⭐ 2
- [stats-base-dists-erlang-logpdf](https://github.com/stdlib-js/stats-base-dists-erlang-logpdf) - Natural logarithm of the probability density function (PDF) for an Erlang distribution. ⭐ 2
- [ln-service](https://github.com/alexbosworth/ln-service) - Node.js interface to LND ⭐ 321
- [tiny-cuda-nn](https://github.com/NVlabs/tiny-cuda-nn) - Lightning fast C++/CUDA neural network framework ⭐ 4471
- [LightningFlowComponents](https://github.com/UnofficialSF/LightningFlowComponents) - A collection of unofficial Flow extensions that can be used to enhance Salesforce Flow and Orchestrator. ⭐ 647
- [pennylane-lightning](https://github.com/PennyLaneAI/pennylane-lightning) - The Lightning plugin ecosystem provides fast quantum state-vector and tensor network simulators written in C++ for use with PennyLane. ⭐ 135