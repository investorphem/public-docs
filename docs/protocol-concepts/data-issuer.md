---
description: >-
  A Data Issuer is the trusted entity associated with Data Point on Talent
  Protocol.
---

# Data Issuer

### Key Attributes:

* Represents the source of trust for the data (e.g., GitHub, Base, ENS).
* It can be distinct from the technical provider where Talent Protocol fetches the data from ([Accounts](account.md)).
* Some Data Issuers can also be [Accounts](account.md) (e.g., GitHub), while others are not (e.g., Base).
* Some [Accounts](account.md) can provide multiple data issuers (ex.: wallet address)
* A single Data Issuer can provide multiple [Data Points](data-point.md).

### Examples:

* GitHub is both an Account (where we get the data from technically) and the Data Issuer (entity that we trust to issue reputation data to a subject).
* Base is a Data Issuer, with multiple Data Points (number of transactions, smart contracts deployed, ...), but it's not an Account. The account in this case is the wallet address.\
