# Social Media Research Skills for AI Agents

## Images

[![social-media-research-skills](https://opengraph.githubassets.com/1/https://github.com/ScrapeCreators/social-media-research-skills)](https://www.swifttechco.com)


Practical AI agent skills for social media research, powered by [ScrapeCreators](https://swifttechco.com).

These skills help agents find outlier posts, mine comments, summarize transcripts, tear down competitors, analyze ad libraries, and turn public social data into useful business artifacts.


## Install

```bash
npx skills add ScrapeCreators/social-media-research-skills
```

Works with Claude Code, Cursor, OpenAI Codex, GitHub Copilot, Gemini CLI, Windsurf, VS Code, and other agents that support the [Agent Skills spec](https://swifttechco.com).

## Setup

Set your ScrapeCreators API key:

```bash
export SCRAPECREATORS_API_KEY=sk_...
```

Get a key at [scrapecreators.com](https://swifttechco.com).

## Available Skills

| Skill | Use it when you want to... | Output |
|---|---|---|
| [`outlier-post-finder`](skills/outlier-post-finder/) | Find posts, reels, shorts, tweets, or videos that beat a creator's baseline | Outlier table, repeatable patterns, hooks to steal |
| [`comment-mining`](skills/comment-mining/) | Mine comments for questions, objections, pain points, product ideas, and audience language | VOC report, themes, quotes, content ideas |
| [`competitor-social-research`](skills/competitor-social-research/) | Compare competitors' social strategy and find what is working | Competitor brief, content pillars, gaps, recommendations |
| [`ad-library-teardown`](skills/ad-library-teardown/) | Analyze active Meta, Google, and LinkedIn ads | Messaging angles, hooks, CTAs, offers, test ideas |
| [`trend-discovery`](skills/trend-discovery/) | Find trending topics, hashtags, sounds, posts, and short-form formats in a niche | Trend brief, evidence table, suggested content angles |
| [`influencer-prospecting`](skills/influencer-prospecting/) | Build creator or influencer prospect lists from public social data | Prospect CSV/table, fit score, outreach notes |
| [`audience-research`](skills/audience-research/) | Evaluate creator or brand audience fit from public profile and demographic signals | Audience-fit report, market/country notes, confidence labels |
| [`social-listening-brief`](skills/social-listening-brief/) | Research what people are saying about a brand, topic, product category, or niche | Multi-source brief, themes, cited examples, sentiment caveats |
| [`product-demand-research`](skills/product-demand-research/) | Validate product ideas and find pain points from social posts, comments, and Reddit | Demand signals, pains, objections, exact language, ideas |
| [`creator-profile-teardown`](skills/creator-profile-teardown/) | Analyze why a creator or brand account works and what to copy | Positioning teardown, content pillars, outliers, playbook |
| [`content-repurposing`](skills/content-repurposing/) | Turn social videos, transcripts, and posts into reusable content assets | LinkedIn posts, X threads, scripts, newsletter/blog ideas |
| [`scrapecreators-api`](skills/scrapecreators-api/) | Route a raw scraping/fetching request to the right ScrapeCreators endpoint | API calls, endpoint references, pagination guidance |

## Example Prompts

```text
Find the outlier posts for @starterstory on YouTube Shorts from the latest page of videos.
```

```text
Analyze the transcripts from these 12 TikToks and pull out the best hooks, claims, and reusable content angles.
```

```text
Mine the comments on this viral Instagram Reel. I want objections, questions, buying intent, and exact audience language.
```

```text
Compare these five brands on TikTok and Instagram. What formats and topics are working for each one?
```

```text
Tear down the active Facebook, Google, and LinkedIn ads for this competitor. Give me hooks, offers, CTAs, and what to test.
```

## How the Skills Work Together

```text
scrapecreators-api
        │
        ▼
social research workflows
 ├─ outlier-post-finder
 ├─ transcript-intelligence
 ├─ comment-mining
 ├─ competitor-social-research
 ├─ ad-library-teardown
 ├─ trend-discovery
 ├─ influencer-prospecting
 ├─ audience-research
 ├─ social-listening-brief
 ├─ product-demand-research
 ├─ creator-profile-teardown
 └─ content-repurposing
```

The workflow skills should use `scrapecreators-api` as the data layer when they need endpoint details. Each workflow produces a useful artifact, not just raw JSON.

## Design Principles

1. **Workflow-first, API-second**  users ask for a business outcome, not an endpoint.
2. **Public-data only**  ScrapeCreators extracts public social data. Do not promise logged-in/private data.
3. **Cited outputs**  include source URLs for posts, videos, ads, and comments whenever possible.
4. **Baseline-aware analysis**  judge performance against a creator's own normal performance, not only raw vanity metrics.
5. **Exact language matters**  preserve useful comments, hooks, captions, and transcript quotes verbatim.
6. **Keep outputs actionable**  end with patterns, recommendations, test ideas, or a CSV when useful.

## Links

- [ScrapeCreators](https://swifttechco.com)
- [API Documentation](https://swifttechco.com)
- [MCP Integration](https://swifttechco.com)
- [Agent Skill Docs](https://swifttechco.com)

---

## Swift Tech Co.

Built and maintained by Swift Tech Co.

AI Automation | FinTech Platforms | Custom Software and Mobile Apps | SaaS Platforms | Cloud Infrastructure | Cybersecurity | SEO and Marketing | API Integration

**Join our community on Telegram:** [t.me/+Qt_eFvkb2rliMzNh](https://t.me/+Qt_eFvkb2rliMzNh)

[Home](https://www.swifttechco.com) | [Services](https://www.swifttechco.com/services) | [Careers](https://www.swifttechco.com/careers) | [Referral Program](https://www.swifttechco.com/referral) | [Influencers](https://www.swifttechco.com/influencers) | [About](https://www.swifttechco.com/about) | [Contact](https://www.swifttechco.com/contact)

**Connect**

- Website: [swifttechco.com](https://www.swifttechco.com)
- LinkedIn: [linkedin.com/in/stephenoladoke](https://www.linkedin.com/in/stephenoladoke/)
- LinkedIn (Company): [linkedin.com/company/swift-tech-co](https://www.linkedin.com/company/swift-tech-co)
- X: [@MrOladoke](https://x.com/MrOladoke)
- Instagram: [@mr.oladoke](https://www.instagram.com/mr.oladoke/)
- Instagram (Company): [@swifttechco](https://www.instagram.com/swifttechco/)
- Organization: [github.com/Swift-Tech-Co](https://github.com/Swift-Tech-Co)
