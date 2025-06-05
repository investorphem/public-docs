---
description: >-
  Technical specifications and usage examples for all endpoints in the Talent
  Protocol V2 API.
---

# API Reference - V2

The Talent Protocol API V2 provides comprehensive access to verified builder reputation data through a redesigned architecture that's more powerful and flexible than V1.

### Key Improvements in V2

* **Advanced Search**: Filter profiles by multiple criteria including tags, scores, and human verification status
* **Profile-Centric Design**: Streamlined endpoints organized around Profiles as the central entity
* **Multiple Scoring Systems**: Support for Builder Score and other upcoming scores
* **Consistent Responses**: Standardized response formats across all endpoints
* **Improved Pagination**: Options for both page-based and cursor-based pagination

### Getting Started

All V2 API endpoints require authentication using your API key in the `X-API-KEY` header.

Base URL: `https://api.talentprotocol.com/`

#### Core Endpoints

* [**Profile Search**](search.md): `/search/advanced/profiles` - Find profiles matching specific criteria
* [**Profile Data**](search.md): `/profile` - Get profile information by ID or account identifier
* [**Score Data**](score.md): `/score` - Get Builder Score and other scoring information
* [**Farcaster Scores**](farcaster-scores.md): `/farcaster/scores` - Get the Builder Score of Farcaster users
* [**Credentials Data**](score.md#credentials): `/credentials` - Get the points each data point contributed to the Builder Score
* [**Data Points**](broken-reference): `/data_points` - Get the data points providing a list of slugs and for a Talent profile
* [**Account Data**](accounts.md): `/accounts` - Get connected accounts information
* [**Social Data**](socials.md): `/socials` - Get connected social media information

See the individual endpoint documentation for detailed request and response formats.
