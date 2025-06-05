---
description: How to get started using Talent Protocol's API
---

# Get Started

### Reputation Infrastructure for Builders and Creators

Talent Protocol helps builders and creators get rewarded by making their reputation more visible.

We track builder activity across blockchains, GitHub, Twitter and other platforms, to calculate a [Builder Score](protocol-concepts/scoring-systems/builder-score/) that helps ecosystems reward real contributors.

With Talent Protocol:

* **Builders** get rewarded for shipping real apps
* **Creators** get rewarded for sharing engaging content
* **Ecosystems** can reach and reward top builders and creators
* and **Apps** can integrate verified reputation data with a single API call

With over 11M+ accounts indexed and dozens of apps integrating our API, Talent Protocol is building the reputation layer for the new internet.



### What Can You Build?

* **Identity & Auth**: Add reputation-based context and authentication to your app.&#x20;
  * Examples: [Basenames](https://x.com/TalentProtocol/status/1825995151275434439) and [Etherscan](https://x.com/TalentProtocol/status/1830974248363622607)
* **Search & Discovery**: Find top builders based on verified reputation data
  * Examples: [Veew.ai](https://veew.ai/) and [Talent App](https://app.talentprotocol.com/search)
* **Reputation Systems**: Create custom scoring systems using our data primitives.&#x20;
  * Example: [Moxie](https://build.moxie.xyz/the-moxie-protocol/based-rewards#breakdown-of-the-formula)

### Quick Start

1. Get your testing API key on our [app](https://app.talentprotocol.com/developers), or [contact us](https://tally.so/r/mYYjPJ) for a full access one.
2. Explore our [API Reference](developers/talent-api/api-reference-v1/)&#x20;
3. &#x20;Jump into specific guides:
   * [Authentication](developers/talent-api/authentication.md)
   * [Builder Score](developers/talent-api/api-reference-v2/score.md)
   * [Credentials](developers/talent-api/api-reference-v2/credentials.md)

### Core Concepts

Talent Protocol is built around the following core concepts to create a comprehensive reputation system:

* **Profile**: The unified representation of a builder's identity and reputation data. A Profile can represent either a verified User or an independent Account.
  * Users can have multiple connected Accounts feeding data into their Profile
  * Independent Accounts have their own Profile until claimed by a User
* [**User**](protocol-concepts/user.md): An individual who has signed up on one of our apps and verified their identity. Users can connect multiple Accounts.
* [**Account**](protocol-concepts/account.md): A connection to a third-party data source (wallet, GitHub, X, etc.) that provides reputation data.
* [**Data Point**](protocol-concepts/data-point.md): A specific verified fact about a builder (GitHub stars, wallet transactions, etc.).
* [**Events**](protocol-concepts/event.md): Historical records of reputation changes
* [**Score**](protocol-concepts/scoring-systems/): A numerical measure of reputation calculated from Data Points using a specific Scoring System.



### Support

* Join our [Discord](https://discord.gg/talentprotocol) and [Farcaster](https://warpcast.com/~/channel/talent) for technical support
* Follow [@TalentProtocol](https://twitter.com/TalentProtocol) for updates

Ready to start building? \
Let's make great builders stand out together. 🫡
