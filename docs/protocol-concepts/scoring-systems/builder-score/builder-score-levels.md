---
description: >-
  Breakdown of the 6 Builder Score Levels and implementation guidelines for
  developers.
---

# Builder Score Levels

Builder Score Levels provide a structured way to understand and interpret Builder Score values in the Talent Protocol ecosystem. These levels help both developers integrating our API and individual builders track progress and set goals.

### Understanding Builder Score Levels

Builder Score is an uncapped scoring system that measures a builder's verified reputation data across multiple categories. To make these scores more intuitive and actionable, we've established six distinct levels that represent increasing degrees of building activity and impact.

Each level corresponds to a specific Builder Score range:

<table><thead><tr><th width="88.421875">Level</th><th width="141.96875">Name</th><th width="129.71484375">Score Range</th><th>Description</th></tr></thead><tbody><tr><td>1</td><td>Novice</td><td>0-39</td><td>Just getting started with the basics. They've connected some accounts and taken their first steps as a builder.</td></tr><tr><td>2</td><td>Apprentice</td><td>40-79</td><td>They're building sporadically and starting to make their mark. Their contributions are starting to get noticed.</td></tr><tr><td>3</td><td>Practitioner</td><td>80-119</td><td>They've established themselves as serious builders with real impact. Their work speaks for itself across multiple platforms.</td></tr><tr><td>4</td><td>Advanced</td><td>120-169</td><td>They've built some impressive things and contributed to notable projects. Their reputation is solid and growing.</td></tr><tr><td>5</td><td>Expert</td><td>170-249</td><td>They're among the top builders with an exceptional track record. People look to their work as an example.</td></tr><tr><td>6</td><td>Master</td><td>250+</td><td>They're one of the most accomplished builders in the ecosystem with contributions that have made a real difference.</td></tr></tbody></table>

### Use Cases

* **Base**: Offers discounted Basename registrations for builders at Level 3 (Practitioner) or higher
* **Hackathons:** Prioritizes hackathon applications from builders at Level 4 (Advanced) or higher
* **Communities**: Automatically approves membership for builders at Level 2 (Apprentice) or higher

### Implementation Guide

When integrating Builder Score into your app or protocol, you can use these levels to:

* **Access Control**: Gate specific features or capabilities based on Builder Score Levels
* **User Segmentation**: Create targeted experiences for different builder segments
* **Reward Distribution**: Allocate rewards or incentives proportionally to builder levels
* **Interface Design**: Visually represent levels with badges or other UI elements
* **Governance Rights**: Allocate voting weight or proposal rights

**Recommended Level Requirements:**

* General access and basic features: Level 1 (Novice)
* Premium features and moderate incentives: Level 3 (Practitioner)
* Exclusive access and significant incentives: Level 5 (Expert)

### Onchain Level Badges

Builders will be able to mint achievement badges for each Builder Score Level they reach. These badges:

* Serve as permanent proof of achievement
* Can be displayed on profiles across the web3 ecosystem
* May unlock special perks from ecosystem partners
* Create a collection that visually represents a builder's journey

### Important Notes

* **Absolute Values**: Builder Score Levels are based on absolute score values, not percentile ranks.
* **Forward Evolution**: As our protocol adds more data points and users, the distribution of levels will naturally evolve.
* **Periodic Review**: We review and may adjust level ranges periodically to maintain meaningful separation between tiers.
* **Non-Decay**: Once you've minted a level badge, it remains in your collection even if your Builder Score temporarily decreases.
