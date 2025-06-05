---
description: A User represents an individual that signed up on talentprotocol.com
---

# User

A **User** represents an individual that signed up on talentprotocol.com to verify their reputation data and increase their [Builder Score](scoring-systems/builder-score/), by connecting multiple [**accounts**](account.md)**.**

An [**Account**](account.md) represents a connection with a third-party entity (e.g., Wallet Address, GitHub, X, LinkedIn) that feeds reputation data into Talent Protocol. Accounts can exist independently or be linked to a user.&#x20;

### Key Attributes:

* Each user has a unique identifier (UUID) in the Talent database, ensuring every user is distinct.
* Users have a single profile URL aggregating data from all associated accounts.
  * `talentprotocol.com/UUID`
* A user can connect multiple [accounts](account.md), but an account can only be linked to one user at a time.
* A user aggregates reputation data from all its connected [accounts](account.md) into a unified [Builder Score](scoring-systems/builder-score/).
* A user is be able to sign-in to the Talent Protocol App with any account that they connected.
* For now, only the Talent Protocol app can create, update or delete users from the database. Ecosystem apps can only read data.&#x20;

### Types of Users:

* **User**: when we mention the term "user", we're referring to all individuals who signed up at talentprotocol.com, even if they haven’t connected a wallet or other accounts yet.
* **Onchain User**: Users with a verified EVM address added to the onchain Talent Registry.
* **Verified User**: Users who have earned a [Human Checkmark](human-checkmark.md).
* **Paying User**: Users who have spent funds on Talent Protocol, via the app or smart contracts.
* **Private User**: Users hidden from the app and API outputs, but still present in the database.
