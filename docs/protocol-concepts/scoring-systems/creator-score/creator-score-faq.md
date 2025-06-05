---
hidden: true
---

# Creator Score FAQ

### General Questions

<details>

<summary>What is Creator Score?</summary>

Creator Score is a numerical representation of a person's verified reputation as a content creator. It's designed to help identify authentic creators and provide a standardized measurement for creative impact and consistency, based on objective, verifiable data points related to content creation and creative contributions.

</details>

<details>

<summary>How is Creator Score different from Builder Score?</summary>

While Builder Score focuses on software development skills and contributions, Creator Score measures content creation activities and impact. Creator Score evaluates platforms like Zora, Mirror, Lens, and Farcaster, while Builder Score primarily evaluates GitHub and blockchain development activities.

</details>

#### Who is considered a "creator" for Creator Score?

A creator is someone who shares original content consistently. This includes visual artists, writers, audio creators, video creators, and community/meme creators. The key factor is creating content that provides value to others by informing, educating, entertaining, or inspiring.

#### What platforms are included in Creator Score?

Creator Score currently includes data from multiple platforms including Zora, Farcaster, Lens, Mirror/Paragraph, Hypersub, Base NFT ecosystem, X/Twitter, LinkedIn, and more. We continuously add new platforms as they become available through APIs or onchain data.

#### Do I need to have accounts on all supported platforms?

No. Creator Score aggregates data from whatever platforms you've verified, but you don't need to be active on all of them. However, having verified activity across multiple platforms will typically result in a higher score as it demonstrates broader impact.

### Score Calculation

#### How is Creator Score calculated?

Creator Score follows the same framework as Builder Score:

1. We collect verified data points from various platforms
2. We apply value conversions to normalize the data
3. Each data point is assigned a signal strength (weak, medium, strong)
4. Signal strength determines the maximum points possible for each data point
5. We apply multipliers to convert normalized values into points
6. All individual data point scores are summed for your total Creator Score

#### What are the different Creator Score levels?

Creator Score is organized into six levels:

* Level 1 (Novice): 0-39 points
* Level 2 (Apprentice): 40-79 points
* Level 3 (Practitioner): 80-119 points
* Level 4 (Advanced): 120-169 points
* Level 5 (Expert): 170-249 points
* Level 6 (Master): 250+ points

#### What types of metrics are included in Creator Score?

Creator Score considers three categories of metrics:

* **Creation Metrics**: Content published, frequency, streaks, longevity
* **Engagement Metrics**: Followers, engagement rates, audience metrics
* **Economic Metrics**: Earnings, collectors, NFT performance, subscriptions

#### Why isn't my follower count weighted more heavily?

While follower count is included in Creator Score, it's just one of many factors. Our research shows that follower counts can be artificially inflated and don't always correlate with actual creative impact. We prioritize metrics that demonstrate consistent creation, authentic engagement, and economic validation of your work.

#### How often is my Creator Score updated?

Creator Score is updated automatically when you connect new accounts or when our system refreshes data from your connected platforms. Most data points are refreshed daily, though some platforms may update less frequently depending on API limitations.

### Using Creator Score

#### How do I check my Creator Score?

You can check your Creator Score on the Talent Protocol app by logging in and viewing your profile. The Creator Score will appear alongside your Builder Score if you have verified creator accounts.

#### How can I improve my Creator Score?

To improve your Creator Score:

1. Connect more creator platforms (Zora, Mirror, Lens, etc.)
2. Create content consistently across your platforms
3. Build authentic audience engagement
4. Monetize your content through NFTs, subscriptions, etc.
5. Maintain consistent creative output over time

#### Can I game the system to artificially increase my Creator Score?

We've designed Creator Score to be resistant to manipulation by:

* Only including verified data points from trusted sources
* Applying normalization techniques that reduce the impact of outliers
* Using a combination of factors that would be difficult to artificially boost all at once
* Regularly monitoring for unusual patterns that may indicate gaming attempts

#### Does having a high Creator Score guarantee opportunities?

While a high Creator Score can increase your visibility and credibility, it doesn't guarantee specific opportunities. It's a tool that helps platforms, brands, and protocols discover authentic creators, but most opportunities will still involve additional considerations.

### Technical Questions

#### How do I integrate Creator Score into my platform?

You can integrate Creator Score through our API. Check our [Creator Score Implementation Guide](https://docs.talentprotocol.com/docs/implementation-guides/creator-score) for details on different integration options and code examples.

#### What API endpoints are available for Creator Score?

The main endpoints for Creator Score are:

* `/score?scorer=Creator+Score+Scorer` - Get a user's Creator Score
* `/search/advanced/profiles` - Search for profiles based on Creator Score
* `/creator_data_points` - Get detailed creator data points for a user

#### Can I create a custom scoring system based on Creator Score data points?

Yes, enterprise customers can create custom scoring systems using our data points. This allows you to create specialized scores that emphasize the metrics most relevant to your use case. Contact us at contact@talentprotocol.com to discuss custom scoring options.

#### Do you have webhooks for Creator Score updates?

Yes, we offer webhooks that can notify your application when a user's Creator Score changes significantly. This is particularly useful for applications that offer tiered benefits based on Creator Score levels.

### Partnership Questions

#### How can protocols or brands use Creator Score?

Protocols and brands can use Creator Score to:

* Identify authentic creators for partnerships or grants
* Create tiered reward programs based on verified reputation
* Implement creator discovery and curation systems
* Add reputation context to existing creator platforms
* Filter spam and low-quality content

#### Does Talent Protocol have a Creator Rewards program?

Talent Protocol works with partners like Base to create Creator Rewards programs. While we don't currently operate our own rewards program, we provide the infrastructure for protocols and platforms to run data-driven creator rewards programs.

#### How can my platform become a data source for Creator Score?

If you operate a platform that serves creators and would like to become a data source for Creator Score, please contact our partnerships team at contact@talentprotocol.com. We're always looking to expand our data sources with quality platforms that provide valuable creator metrics.

#### Can we white-label Creator Score for our platform?

Yes, we offer white-labeling options for platforms that want to incorporate Creator Score under their own branding. This includes custom UI elements, personalized scoring thresholds, and integration support. Contact our enterprise sales team for details.

### Future Development

#### Will more platforms be added to Creator Score?

Yes, we continuously add new platforms as they become available through APIs or onchain activity. Our roadmap includes adding more creator platforms, particularly those focused on specific creator types or emerging content formats.

#### Will there be a Creator Score NFT badge?

We're exploring the possibility of Creator Score achievement NFTs similar to our Builder Score levels. These would serve as verifiable proof of reaching certain Creator Score milestones and could unlock benefits across the ecosystem.

#### How does Creator Score relate to the $TALENT token?

Creator Score is part of our broader protocol economy powered by $TALENT. In the future, creators may be able to stake $TALENT to access premium features, and top creators may receive protocol rewards distributed in $TALENT tokens.

#### Is there a mobile app for tracking Creator Score?

We currently offer Creator Score through our web application. A dedicated mobile app for tracking reputation metrics, including Creator Score, is on our roadmap for future development.
