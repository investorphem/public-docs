---
description: >-
  A scoring system that identifies talent in content creation and creative
  contribution.
---

# Creator Score

## What is the Creator Score?

Creator Score is a numerical value that represents a user's reputation as a content creator based on verified data across multiple platforms. Unlike traditional metrics that only consider follower count, Creator Score evaluates both quantity AND quality of creative output through verifiable signals.

The Creator Score is designed to:

* Help authentic creators gain recognition based on their actual contributions
* Provide protocols, brands, and platforms with reliable data to identify top creative talent
* Create a standardized measurement for creative impact and consistency
* Reward consistent, high-quality content creation over mere popularity

## Who is a Creator?

While Builder Score focuses on software development, Creator Score targets those who share original content consistently. A creator is someone that produces creative output (text, image, video, audio, interactive) that provides value to others by informing, educating, entertaining, or inspiring.

The Creator Score supports various creator types:

* **Visual Artists**: Illustrators, photographers, painters, graphic designers, animators
* **Writers**: Bloggers, journalists, essayists, poets, newsletter authors
* **Audio Creators**: Musicians, podcasters, sound designers, voice artists
* **Video Creators**: Filmmakers, vloggers, streamers, YouTube content producers
* **Community & Memes**: KOLs, meme artists, community builders

## Use Cases

Creator Score serves multiple purposes in the ecosystem:

* **For creators**: Objective verification of creative impact that can be shared across platforms
* **For protocols**: Reliable method to identify authentic creators for rewards, grants, and partnerships
* **For brands**: Data-driven discovery of talent for collaborations and sponsorships
* **For apps**: Enhanced context about users' creative contributions and reputation

## The "Creator Score" Scoring Framework

The Creator Score uses the same technical framework as the [Builder Score](../builder-score/) but with [data points](../../data-point.md) specifically relevant to creators. The final score is the sum of all data point scores with no maximum cap, and each data point is evaluated based on: signal strength, max score, multiplier (not publicly disclosed), value conversion (optional).

### **Signal Strength**

* The first step is defining how strongly a given data point signals someone is a real creator
* There's 3 possible levels:
  * **Strong**: Up to 40 points (e.g., zora rewards earned)
  * **Medium**: Up to 20 points (e.g., farcaster followers)
  * **Weak**: Up to 8 points (e.g., twitter account age)

### **Max Score**

* Maximum amount of points each data point can contribute to the Creator Score, based on the signal strength

### **Multiplier**

* Each data point has a multiplier to convert its readable value into points
* The multiplier is not publicly disclosed to prevent gaming (same approach as Builder Score)
* Example: for twitter followers, if the multiplier is 0.01 and I have 1,000 followers, I will receive 10 points

### **Value Conversion**

* Some data point original values are converted to normalized metrics.
* Example: We us a square root function for metrics like total followers or NFT earnings to prevent large creators from completely dominating



## Creator Score Levels

Similar to Builder Score, Creator Score is organized into levels to help users understand their standing:

<table><thead><tr><th width="68.375">Level</th><th width="101.484375">Score Range</th><th>Description</th></tr></thead><tbody><tr><td>1</td><td>0-39</td><td>Just getting started. Has created some content and taken first steps as a creator.</td></tr><tr><td>2</td><td>40-79</td><td>Creating content regularly with growing engagement. Beginning to build an audience.</td></tr><tr><td>3</td><td>80-119</td><td>Established creator with consistent output and meaningful engagement across platforms.</td></tr><tr><td>4</td><td>120-169</td><td>Accomplished creator with significant audience and proven monetization.</td></tr><tr><td>5</td><td>170-249</td><td>Top-tier creator with substantial influence and recognition in their domain.</td></tr><tr><td>6</td><td>250+</td><td>Elite creator with exceptional impact, audience, and earnings.</td></tr></tbody></table>



## Key Metrics

The Creator Score considers various metrics organized into three categories:

### 1. Creation Metrics

* Content Published - total number of content pieces published
* Content Frequency - number of unique pieces published per week/month
* Publishing Streak - consecutive weeks/months with published content
* Creative Longevity - time since first published content

### 2. Engagement Metrics

* Followers and subscriber counts across platforms
* Follower-to-following ratio
* Engagement rates and interactions with content

### 3. Economic Metrics

* Total earnings and rewards
* Unique holders/collectors/paid subscribers
* NFT mints, coin purchases or price
* Secondary market activity (NFT/coin trading)
* Collector loyalty/repeat engagement



