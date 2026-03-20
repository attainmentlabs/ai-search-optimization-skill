# GEO and LLMO: Implementation Reference

> Skill reference file. Contains deep, actionable implementation knowledge for Generative Engine Optimization (GEO) and Large Language Model Optimization (LLMO). All statistics sourced from 2024/2025/2026 industry research.

---

## GEO (Generative Engine Optimization)

### Academic Foundation

GEO was formally defined by Princeton University researchers in November 2023 (arXiv preprint, later published at KDD 2024). The paper introduced GEO-bench, a 10,000-query benchmark dataset, and demonstrated that content optimized with GEO techniques achieved up to 40% higher visibility on Perplexity.ai compared to unoptimized content.

GEO is the strategic framework for getting content cited by AI systems. It covers content strategy, business positioning, author authority, and citation engineering. GEO surged 121% in practitioner searches during Q3/Q4 2025 (Search Engine Land), reflecting rapid mainstream adoption.

Key distinction: GEO is the "what" and "why." LLMO is the "how." They overlap approximately 80%, but GEO focuses on content strategy and business positioning, while LLMO focuses on the machine-readable infrastructure that makes GEO work.

---

### How AI Models Select Sources to Cite

Each AI platform has a different architecture, different data sources, and different citation behavior. Optimizing for one does not automatically cover the others. The table below maps platform behavior to strategy.

| Platform | Architecture | What It Cites | Key Strategy |
|----------|-------------|---------------|-------------|
| ChatGPT (no browsing) | Training data only | Wikipedia, authoritative sites in training corpus | Be well-documented before training cutoff |
| ChatGPT (with browsing) | RAG, real-time retrieval | Current web content, structured pages | Optimize for web search + structured data |
| Perplexity | Real-time web search, 21+ citations per answer | Reddit (#1 at 6.3%), news sites, authoritative domains | Reddit presence, original data, press coverage |
| Google AI Overviews | Search index + Gemini | Multiple web sources (avg 7.2 links) | Semantic completeness, schema, E-E-A-T |
| Gemini | Direct Knowledge Graph access + web | Knowledge Graph entities, authoritative web | Wikidata entry, Organization schema, web authority |
| Claude | Training data only (no browsing) | Quality and comprehensiveness over recency | Deep, accurate, well-structured content |

**Platform-specific implications:**
- ChatGPT browsing mode and Perplexity use real-time web retrieval. Fresh, well-structured content wins.
- ChatGPT without browsing and Claude rely on training data. Presence in authoritative sources that existed before the training cutoff is what matters.
- Perplexity cites 21+ sources per answer, creating more citation opportunities than any other platform. Each answer is a potential multi-slot visibility event.
- Gemini has direct access to Google's Knowledge Graph. Wikidata entries and Organization schema are the most powerful levers for Gemini visibility.
- Google AI Overviews synthesize from an average of 7.2 sources, compared to featured snippets which extract from one (Wellows, 2026).

---

### Reddit as the #1 AI Citation Source

Reddit accounts for 40.1% of all AI citations across major platforms (Profound, 2025). This makes Reddit the single most important third-party platform for AI visibility.

**Platform-specific Reddit citation rates:**
- Perplexity: 6.3% of all citations go to Reddit (highest single-source rate)
- Google AI Overviews: 2.3% of citations go to Reddit
- ChatGPT: 1.2% of citations go to Reddit

**Key stat:** Perplexity's Reddit citations jumped 40x between February and April 2025. This reflects Perplexity's data partnership with Reddit and its algorithmic preference for community-validated content.

**Reddit strategy for AI visibility:**

1. **Participate genuinely.** AI systems detect and downweight promotional content. Contribute expertise, answer questions, share data. Never self-promote.

2. **Target relevant subreddits.** Identify 5 to 10 subreddits where your ICP congregates. Build karma and reputation there before ever mentioning your brand.

3. **Write structured, data-rich answers.** Reddit posts that contain statistics, step-by-step breakdowns, and comparison tables are more likely to be cited by AI systems than one-liner replies.

4. **Consistency matters.** A profile with 50+ substantive posts across 6+ months carries more weight than a new account with 5 posts.

5. **Do not astroturf.** AI systems cross-reference Reddit usernames, post histories, and account ages. Fake or coordinated accounts get flagged and deindexed.

---

### Citation Hook Writing

A citation hook is a self-contained, quotable passage that AI can extract and cite verbatim. Citation hooks are the fundamental unit of GEO content. Every page optimized for AI citation should contain 3 to 5 hooks.

#### The 5 Types of Citation Hooks

**1. Statistic Hook**
Format: "[Specific number] [specific outcome] ([source], [year])"
Example: "97% cost reduction in accounts payable processing (BCG, 2025)"
When to use: Any time you have proprietary data, survey results, or third-party statistics. AI systems strongly prefer content with specific numbers over vague claims.

**2. Definition Hook**
Format: "[Term] is [clear, concise definition in one sentence]."
Example: "AEO is the practice of structuring content so AI systems can extract and present it as a direct answer."
When to use: For any industry-specific term, concept, or methodology your audience searches for. Definition hooks win "What is" queries across all AI platforms.

**3. Framework Hook**
Format: "[Process name] follows [number] steps: [list]."
Example: "The Clarity Cascade follows five stages: Market, Audience, Message, Narrative, Delivery."
When to use: When describing a methodology, process, or framework. AI systems love numbered sequences because they are unambiguous and extractable.

**4. Comparison Hook**
Format: "[X] [specific difference] compared to [Y] ([source])."
Example: "AI Overviews synthesize from an average of 7.2 sources, compared to featured snippets which extract from one (Wellows, 2026)."
When to use: For "vs" queries, product comparisons, or any content comparing two approaches. Comparison hooks are highly citation-worthy because they answer decision queries directly.

**5. Authority Hook**
Format: "According to [credible source], [specific finding]."
Example: "According to Gartner, 25% of organic search traffic will shift to AI chatbots by end of 2026."
When to use: When citing third-party research, industry reports, or expert statements. The "According to" prefix signals sourced information, which AI systems prioritize for factual queries.

#### Citation Hook Specifications

| Attribute | Specification |
|-----------|---------------|
| Length | 40 to 60 words per hook (optimal for AI extraction) |
| Self-containment | No "as mentioned above" or "see below." Each hook must work in isolation. |
| Source attribution | Include the source name and year within the hook itself |
| Specificity | Use specific numbers, not vague language ("97%" not "nearly all") |
| Idea density | One idea per hook. Never combine two claims in one hook. |
| Placement | Immediately after H2 headings for maximum extraction probability |
| Quantity | 3 to 5 hooks per page minimum. One per major section. |

#### Writing Hook Quality Checks

Before publishing, verify each citation hook against these criteria:
- Can a reader understand this sentence without reading anything else on the page?
- Does it contain at least one specific number or named entity?
- Does it include source attribution?
- Is it between 40 and 60 words?
- Would this sentence be a credible answer if read aloud by a voice assistant?

---

### Content Tone for AI Citation

The tone of your content directly affects citation probability. AI systems are sensitive to the difference between conversational, formal, and promotional writing.

**Key findings:**
- "Professional conversational" style wins the most citations across platforms: direct language combined with authoritative sourcing
- Conversational content outperforms formal content by 15 to 20% for educational topics on ChatGPT
- Formal tone maintains an 18 to 25% advantage for scientific, medical, legal, and technical content
- 82.5% of Google AI Overview citations link to "deep" content pages (2+ clicks from homepage)
- Only 0.5% of AI Overview citations go to homepages

**What "professional conversational" sounds like:**
- Direct subject-verb-object sentences
- Active voice, not passive
- Specific claims with sources, not vague hedging
- Short paragraphs (40 to 60 words)
- No jargon without explanation
- No hype words ("revolutionary," "game-changing," "cutting-edge")
- Data and examples instead of opinions and adjectives

**What gets ignored by AI:**
- Marketing copy with no data ("We are the leading provider of...")
- Thin content pages under 500 words
- Content that only links to other sources without adding analysis
- Pages with heavy ad interruptions that break passage extraction
- Content behind paywalls or login gates (most AI crawlers cannot access)

---

### GEO Content Structure

The optimal page architecture for AI citation follows a predictable pattern. AI systems extract content most effectively when pages use this structure.

**Optimal Page Architecture:**

```
H1: [Primary query as title]

[Answer capsule: 40-60 word direct answer to the primary query]

H2: [Question about Attribute 1]
[40-60 word citation hook answering the question]
[2-3 paragraphs expanding with data, examples, citations]

H2: [Question about Attribute 2]
[40-60 word citation hook]
[Expansion paragraphs]

[Comparison table if applicable]

H2: FAQ
[3-5 Q&A pairs with FAQPage schema]

H2: Key Takeaways
[Bulleted summary, 5-7 points]
```

**Structural specifications:**

| Element | Specification |
|---------|---------------|
| Paragraph length | 40 to 60 words per paragraph (optimal for AI citation extraction) |
| Passage length | 134 to 167 words per self-contained section (optimal for AI Overview extraction) |
| H2 headings | Phrased as questions matching real search queries |
| Answer capsule | First content element after H1, 40 to 60 words |
| Citation hooks | One per H2 section, placed immediately after the heading |
| FAQ section | 3 to 5 Q&A pairs, wrapped in FAQPage schema |
| Comparison tables | Semantic HTML `<table>` with `<thead>` and `<th>` elements |
| Internal links | 3 to 5 per page to related hub/spoke pages |
| Outbound citations | At least 2 to 3 links to authoritative Tier 1 sources per page |

**Self-contained passages (critical rule):**
Every passage under an H2 must stand alone. AI Overviews and other AI systems may extract only one passage from your page. If that passage contains "as mentioned above" or "see the section below," it becomes useless to the AI. Each passage should include the question, the answer, supporting detail, and a data point.

---

### GEO-Specific Schema

Schema markup increases AI citation probability by 73% (Wellows, 2026). The following schema types are most impactful for GEO.

#### Article Schema with Author Authority

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Title with Primary Keyword",
  "author": {
    "@type": "Person",
    "name": "Author Name",
    "jobTitle": "Title",
    "knowsAbout": ["Topic 1", "Topic 2"],
    "worksFor": {
      "@type": "Organization",
      "name": "Company Name"
    }
  },
  "datePublished": "2026-02-21T09:00:00-05:00",
  "dateModified": "2026-02-21T14:00:00-05:00",
  "about": {
    "@type": "Thing",
    "name": "Primary Topic"
  }
}
```

**Key fields for GEO:**
- `author.knowsAbout`: Tells AI systems what the author is an expert in. Use 3 to 5 specific topic areas.
- `author.worksFor`: Establishes institutional affiliation. AI systems weight affiliated authors higher than unaffiliated ones.
- `dateModified`: Must be updated when making real content changes. Stale `dateModified` values reduce citation probability.
- `about`: Helps AI systems categorize the page topically. Use the primary entity or concept the page covers.

#### Person Schema for Author Pages

```json
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Author Name",
  "jobTitle": "CEO",
  "worksFor": {
    "@type": "Organization",
    "name": "Company Name",
    "url": "https://company.com"
  },
  "knowsAbout": ["AI Search Optimization", "SaaS Growth Strategy", "Digital Marketing"],
  "sameAs": [
    "https://www.linkedin.com/in/authorname",
    "https://twitter.com/authorname",
    "https://www.wikidata.org/wiki/Q123456"
  ],
  "alumniOf": {
    "@type": "EducationalOrganization",
    "name": "University Name"
  },
  "award": ["Award Name (Year)"]
}
```

The `sameAs` array is critical for entity reconciliation. It tells AI systems that the author entity on this page is the same entity on LinkedIn, Twitter, Wikidata, etc. This strengthens the author's knowledge graph presence.

---

### Content Freshness for AI

Content freshness is a significant ranking factor across all AI platforms, though each platform weights it differently.

**Key statistics:**
- Content updated within 30 days receives 3.2x more AI citations than older content
- AI systems inject the current year into 28.1% of sub-queries automatically (e.g., "best CRM software" becomes "best CRM software 2026" internally)
- 23% of all featured content in AI Overviews is under 30 days old

**Platform-specific freshness behavior:**
- Perplexity: Heavily favors recent content. Real-time search means today's content can appear in today's results.
- Google AI Overviews: Moderately favors freshness. Content updated within 30 days gets a significant boost.
- ChatGPT (browsing): Favors recent content when browsing. Training data has a fixed cutoff.
- Claude: Values comprehensiveness over recency. Training data only. No real-time retrieval.

**Update strategy:**
- Make substantive content changes, not cosmetic date bumps. AI systems can detect when only the date was changed without meaningful content updates.
- Add a visible "Last Updated: [Month, Year]" to all content pages.
- Update `dateModified` in Article schema when making real revisions.
- Establish a quarterly content refresh cycle for your top 20 pages.
- Add new statistics, case studies, or examples during each refresh.
- Remove outdated information that could reduce content trust.

---

### GEO Measurement

Measuring AI visibility is still a nascent discipline. There is no industry-standard benchmark yet. The tools and methods below represent the current best practices.

#### Paid Tools

| Tool | Price | Capabilities |
|------|-------|-------------|
| Otterly.AI | $29 to $489/mo | Monitors ChatGPT, Perplexity, Google AI Overviews, Copilot, Gemini daily. Tracks brand mentions and citation frequency. |
| Profound | $99 to $399/mo | Enterprise AI brand visibility tracking. Tracks citation share across platforms. Source of the 40.1% Reddit stat. |
| SE Ranking | Varies | AEO-specific brand mention monitoring across AI platforms. |
| Semrush | $139+/mo | AI Overview keyword tracking within Position Tracking tool. |
| Ahrefs | $129+/mo | SERP features tracking includes AI Overviews. Content gap analysis. |

#### Manual Measurement Method

When tools are not in the budget, use this manual protocol:

1. Select 30 to 100 queries relevant to the business (mix of branded, unbranded, and competitor comparison queries)
2. Test each query across 4+ platforms: ChatGPT, Perplexity, Google AI Overviews, Gemini
3. For each query, record: Was your brand mentioned? Were you cited as a source? What was the citation position?
4. Calculate: (Your mentions) / (Total prompts tested) = AI visibility percentage
5. Repeat monthly. Track the trend.
6. Target: Improvement month over month. Even 5% monthly improvement compounds meaningfully over 12 months.

#### What to Track

| Metric | Source | Frequency |
|--------|--------|-----------|
| AI visibility percentage | Manual test protocol | Monthly |
| AI Overview citation count | Semrush, Ahrefs, or Otterly.AI | Weekly |
| Brand mention accuracy | Manual AI platform testing | Monthly |
| Citation hook extraction rate | Manual check of top 10 pages against AI responses | Monthly |
| Server log AI bot traffic | Server access logs (ChatGPT-User, PerplexityBot, OAI-SearchBot) | Weekly |
| Referral traffic from AI | Google Analytics (perplexity.ai, chat.openai.com referrals) | Weekly |

---

## LLMO (Large Language Model Optimization)

### How LLMO Differs from GEO

GEO is the strategic framework for getting cited by AI. It covers content strategy, business positioning, author authority, and citation engineering.

LLMO is the technical execution layer. It covers HTML structure, schema markup, entity relationships, crawl optimization, and the machine-readable infrastructure that makes GEO work.

The two overlap approximately 80%. LLMO focuses specifically on:
- Making content machine-readable (semantic HTML, clean structure)
- Making entities machine-identifiable (schema, sameAs, Knowledge Graph)
- Managing AI crawler access (robots.txt, llms.txt)
- Ensuring content is accessible to AI retrieval systems (server-rendering, page speed)
- Cross-platform entity consistency (same information everywhere)

**Origin:** LLMO emerged from practitioner communities around 2023. Search Engine Land, Neil Patel, and Surfer SEO have all published LLMO guides. The term has not been formally defined in academic research (unlike GEO).

---

### AI Bot User Agents (Complete Reference)

Understanding which bots to block and which to allow is foundational to LLMO. The distinction is between training crawlers (which harvest your content for model training) and inference/search crawlers (which fetch your content to serve it to users).

#### Training Crawlers (Block These)

These bots crawl your site to collect data for training AI models. They take your content but do not send users back to your site.

| Bot | Company | Purpose | Notes |
|-----|---------|---------|-------|
| GPTBot | OpenAI | Model training | 305% bandwidth increase May 2024 to 2025 |
| Google-Extended | Google | Gemini/Vertex AI training | Does NOT affect Google Search indexing |
| ClaudeBot | Anthropic | Claude model training | Does NOT affect Claude-Web inference |
| CCBot | Common Crawl | Open datasets for AI projects | Feeds many third-party AI models |
| Applebot-Extended | Apple | Apple Intelligence training | Separate from Applebot (Siri search) |
| Bytespider | ByteDance | TikTok search, CapCut AI | Very aggressive crawling behavior |
| cohere-ai | Cohere | Language model training | Enterprise LLM provider |

#### Search and Inference Crawlers (Allow These)

These bots fetch your content to display it to users in real time. They are the equivalent of Googlebot for the AI era. Blocking them makes you invisible in AI search results.

| Bot | Company | Purpose | Notes |
|-----|---------|---------|-------|
| ChatGPT-User | OpenAI | User-triggered page fetching | Fires when a user asks ChatGPT to browse a URL |
| OAI-SearchBot | OpenAI | SearchGPT indexing | Indexes content for OpenAI's search product |
| PerplexityBot | Perplexity | Perplexity search indexing | Respects robots.txt |
| Perplexity-User | Perplexity | User citation clicks | Bypasses robots.txt (user-initiated) |
| Claude-Web | Anthropic | Live citation fetching | Fires when Claude retrieves content for a response |
| Amazonbot | Amazon | Alexa queries, product recommendations | Also used for Amazon shopping results |
| MistralAI-User | Mistral | Le Chat citation fetching | Mistral's consumer AI product |
| DuckAssistBot | DuckDuckGo | DuckAssist AI answers | DuckDuckGo's AI answer feature |

#### Key Asymmetry

AI crawlers take far more than they send back. The crawl-to-referral ratio measures how many pages a bot crawls versus how many visitors it sends to your site.

- OpenAI crawl-to-referral ratio: 1,700:1 (crawls 1,700 pages for every 1 referral it sends)
- Anthropic crawl-to-referral ratio: 73,000:1

This imbalance is why the distinction between training crawlers and inference crawlers matters. Block training crawlers to reduce bandwidth consumption. Allow inference crawlers to appear in AI search results.

#### robots.txt Template

```
# Block training crawlers
User-agent: GPTBot
Disallow: /
User-agent: Google-Extended
Disallow: /
User-agent: ClaudeBot
Disallow: /
User-agent: CCBot
Disallow: /
User-agent: Applebot-Extended
Disallow: /
User-agent: Bytespider
Disallow: /
User-agent: cohere-ai
Disallow: /

# Allow search/inference crawlers
User-agent: ChatGPT-User
Allow: /
User-agent: OAI-SearchBot
Allow: /
User-agent: PerplexityBot
Allow: /
User-agent: Amazonbot
Allow: /
User-agent: Claude-Web
Allow: /
User-agent: MistralAI-User
Allow: /
User-agent: DuckAssistBot
Allow: /

# Allow traditional search engines
User-agent: Googlebot
Allow: /
User-agent: Bingbot
Allow: /
User-agent: AppleBot
Allow: /
```

**Important note:** 13.26% of AI bot requests ignored robots.txt in Q2 2025. Blocking training crawlers is a best practice signal, not a guarantee. But it does reduce overall crawl volume and establishes a clear compliance posture.

---

### Technical LLMO Checklist

Use this checklist when auditing any site for LLMO readiness:

**HTML and Structure:**
- [ ] Clean, semantic HTML (proper heading hierarchy, landmark regions)
- [ ] All content in initial HTML (not JavaScript-loaded)
- [ ] One `<h1>` per page, sequential heading hierarchy (h1, h2, h3), no skipped levels
- [ ] Landmark regions: `<nav>`, `<main>`, `<aside>`, `<footer>`, `<header>`
- [ ] Semantic tables with `<thead>`, `<th scope>` for tabular data
- [ ] Page speed under 3 seconds (ChatGPT-User has a short timeout)
- [ ] HTTPS sitewide
- [ ] No content behind "Show More" buttons requiring JavaScript interaction

**Schema Markup:**
- [ ] Organization schema with @id, sameAs, knowsAbout
- [ ] Person schema for all content authors (jobTitle, knowsAbout, sameAs)
- [ ] FAQPage schema on all Q&A content
- [ ] Article or BlogPosting schema on all content pages
- [ ] datePublished and dateModified in Article schema

**Entity and Authority:**
- [ ] Consistent entity information across all platforms (same name, same bio, same credentials)
- [ ] sameAs links to Wikidata, LinkedIn, Crunchbase, social profiles
- [ ] Cross-platform brand mentions (Reddit, Quora, industry publications)
- [ ] Author pages with full credentials and Person schema

**Crawler Management:**
- [ ] robots.txt: block training crawlers, allow inference crawlers
- [ ] llms.txt at domain root with 20 to 50 priority URLs
- [ ] Sitemap submitted to Google Search Console AND Bing Webmaster Tools

---

### Optimizing for Specific LLM Platforms

Each LLM platform has different citation preferences. The strategies below target the specific signals each platform prioritizes.

#### For ChatGPT Visibility

ChatGPT has two modes: training data only (default) and browsing mode (user-enabled). Strategy differs for each.

**Training data mode:**
- Wikipedia presence (if eligible) is the strongest signal
- Crunchbase profile (for business entities)
- Press coverage in major publications (Bloomberg, TechCrunch, Forbes, Reuters)
- Presence in authoritative reference sites (industry directories, G2, Capterra)
- Content must have existed before the training cutoff to be included

**Browsing mode:**
- Clear, structured FAQ content on your site
- Reddit activity in relevant subreddits (ChatGPT browses Reddit frequently)
- Recent content with clear dates (browsing mode values recency)
- Fast-loading pages (ChatGPT-User has a short timeout)
- Well-structured HTML that is easy to parse

**Combined strategy:**
1. Establish authoritative presence on Wikipedia, Crunchbase, and industry directories (training data)
2. Maintain fresh, well-structured content on your site (browsing mode)
3. Build genuine Reddit presence in relevant subreddits (both modes value Reddit)
4. Ensure press coverage mentions your brand alongside your key topics (training data + browsing)

#### For Perplexity Visibility

Perplexity uses real-time web search and cites 21+ sources per answer. It is the most citation-generous platform.

**Priority signals:**
- Reddit presence is critical. Reddit is the #1 cited source at 6.3% of all Perplexity citations.
- Fresh content. Perplexity's real-time search heavily favors recently published or updated content.
- Authoritative domain with clear E-E-A-T signals (author credentials, institutional affiliation, outbound citations to Tier 1 sources).
- Original data and statistics. Perplexity prioritizes pages with unique data points over pages that summarize others.
- 21+ citations per answer means more slots to win. Broad content coverage across a topic increases your chances of capturing one or more citation slots.

**Tactical actions:**
1. Publish original research quarterly (surveys, case studies, data analyses)
2. Update top 20 pages monthly with new data and examples
3. Participate in 5 to 10 relevant subreddits with substantive, expert-level comments
4. Include 2 to 3 specific, attributed statistics per page (these get cited directly)
5. Submit sitemap to Google and Bing (Perplexity indexes from both)

#### For Google Gemini and AI Overviews

Gemini has direct access to Google's Knowledge Graph. AI Overviews synthesize from Google's search index plus Gemini.

**Priority signals:**
- Wikidata entry. Gemini has direct Knowledge Graph access. A Wikidata entry establishes your entity in Google's ontology.
- Organization + Person schema with sameAs links. These help Gemini reconcile your entity across the web.
- Semantic completeness. AI Overviews prefer pages that cover the full attribute space of a topic. Use Surfer SEO or MarketMuse to score coverage. Target 8.5+ out of 10.
- Multi-modal content. Text + images + schema yields +317% higher citation rate in AI Overviews.
- Entity density. Target 15 to 20 named entities per 1,000 words. Pages with high entity density are 4.8x more likely to be cited in AI Overviews.

**Tactical actions:**
1. Create or claim a Wikidata entry for your organization (if eligible by notability standards)
2. Implement Organization and Person schema with comprehensive sameAs arrays
3. Audit top pages for semantic completeness using Clearscope, Surfer SEO, or MarketMuse
4. Add original images with descriptive alt text to every content page
5. Map and increase entity density to 15 to 20 named entities per 1,000 words

#### For Claude Visibility

Claude relies on training data only. It has no real-time web retrieval capability.

**Priority signals:**
- Quality and comprehensiveness over recency
- Well-documented entities in authoritative web sources
- Consistent, accurate information across multiple sources
- Deep, nuanced content that demonstrates genuine expertise

**Tactical actions:**
1. Ensure your brand, products, and key people are documented on authoritative reference sites (Wikipedia, Crunchbase, industry directories)
2. Build a network of authoritative backlinks and brand mentions that existed before Claude's training cutoff
3. Focus on content depth. Claude values comprehensive, accurate information over recency.
4. Maintain consistency. If your brand name, description, or product details differ across sources, Claude may present inaccurate information.

---

### Digital PR for LLMO

Digital PR is now a core visibility channel for AI search. It is no longer optional or "nice to have."

**Academic foundation:** MIT Sloan research found that LLMs prioritize three signals when selecting sources to cite: domain expertise, institutional credibility, and repeated validation across reputable publications. All three are driven by PR.

**How PR feeds AI visibility:**
- Earned media in authoritative publications directly feeds RAG (Retrieval Augmented Generation) systems used by Perplexity, Bing Copilot, and ChatGPT browsing mode.
- Brand mentions in press coverage become training data for future LLM versions.
- Guest articles on high-authority domains (DA 50+) establish entity co-citation: search engines and AI systems associate your brand with your topic based on where it appears alongside other known entities.
- Podcast appearances generate transcripts that are indexed and cited by AI systems.

**Execution targets:**
- 5 pitches per week to industry publications
- 10 podcast appearances per month (start with niche, build to mainstream)
- Guest articles on DA 50+ sites, published monthly
- Quarterly original research pieces (surveys, data analyses, case studies)
- Speaking engagements at industry conferences (generates mentions in event coverage)

**Measuring PR impact on AI visibility:**
- Track branded queries in AI platforms before and after PR placements
- Monitor AI citation sources to see if press articles are being cited
- Use Profound or Otterly.AI to measure AI brand visibility over time
- Track referral traffic from AI platforms (perplexity.ai, chat.openai.com in Google Analytics)

---

### llms.txt Implementation for LLMO

The `llms.txt` file is a plain-text Markdown file placed at the domain root that tells AI systems which pages contain authoritative content. It functions like a curated sitemap specifically for LLMs.

**File location:** `https://yoursite.com/llms.txt`

**Format:**

```markdown
# Business Name

> One-paragraph description of the business, its expertise, and its target audience.

## Core Pages
- [Page Title](https://yoursite.com/page-1): Brief description of what this page covers
- [Page Title](https://yoursite.com/page-2): Brief description of what this page covers

## Key Topics We Cover
- Topic 1
- Topic 2
- Topic 3

## Optional: Docs
- [API Reference](https://yoursite.com/docs/api): Full API documentation
```

**Best practices:**
- Include 20 to 50 links maximum. Only the highest-quality, regularly updated pages.
- Link to pages that demonstrate E-E-A-T (Experience, Expertise, Authoritativeness, Trustworthiness)
- Update the file when new cornerstone content is published
- Do not include thin content, duplicate pages, or paginated archives
- Keep total file size under 500 words

**Platform support:**
- Officially supported: Anthropic (Claude), Cursor, Mintlify
- Unofficially analyzed: OpenAI and Perplexity crawlers have been observed reading llms.txt (no public announcement)
- As of August 2025, only approximately 951 domains had published an llms.txt file. This represents a significant early-mover advantage.

**Companion file: llms-full.txt**
Some implementations include a longer version at `/llms-full.txt` with complete page content (not just links). This is useful for AI systems that prefer to ingest full text rather than crawl individual URLs.

---

### Entity Optimization for LLMO

Entity SEO is a prerequisite for LLMO. If AI systems cannot identify your brand as a distinct entity, they cannot cite it accurately.

**Entity reconciliation signals (in order of impact):**

1. **Wikidata entry:** Establishes your entity in the Knowledge Graph that Gemini accesses directly. Requires notability per Wikidata's guidelines.

2. **Organization schema with @id and sameAs:** The `@id` creates a unique URI for your entity. The `sameAs` array connects it to external profiles.

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "@id": "https://yoursite.com/#organization",
  "name": "Your Company",
  "url": "https://yoursite.com",
  "sameAs": [
    "https://www.wikidata.org/wiki/Q123456",
    "https://www.linkedin.com/company/yourcompany",
    "https://www.crunchbase.com/organization/yourcompany",
    "https://twitter.com/yourcompany",
    "https://www.youtube.com/@yourcompany",
    "https://github.com/yourcompany"
  ],
  "knowsAbout": [
    "Primary Topic 1",
    "Primary Topic 2",
    "Primary Topic 3"
  ],
  "founder": {
    "@type": "Person",
    "@id": "https://yoursite.com/#founder",
    "name": "Founder Name"
  }
}
```

3. **Consistent NAP across all platforms:** Name, Address, Phone must be character-level identical everywhere. "St." vs "Street" counts as a mismatch.

4. **Cross-platform brand mentions:** References to your brand on Reddit, Quora, Wikipedia, industry publications, news sites, and social media all strengthen entity recognition.

5. **Crunchbase profile:** For business entities, Crunchbase is heavily referenced by ChatGPT and other LLMs. Complete the profile with funding data, team members, products, and competitor relationships.

6. **Wikipedia page (if eligible):** The single strongest signal for training-data-based LLMs (ChatGPT, Claude). Requires meeting Wikipedia's notability guidelines. Do not create a Wikipedia page for your own company. It must be created by independent editors.

---

### Cross-Platform Entity Consistency

AI systems cross-reference your entity information across multiple sources. Inconsistencies reduce trust and can lead to inaccurate AI responses about your brand.

**What must be consistent everywhere:**
- Legal business name (exact spelling, capitalization, punctuation)
- Business description (core value proposition, not marketing fluff)
- Founding year
- Key personnel names and titles
- Physical address (if applicable)
- Industry categories
- Products and services descriptions

**Platforms to audit for consistency:**
- Your website (About page, footer, schema)
- Google Business Profile
- LinkedIn Company Page
- Crunchbase
- Wikidata (if entry exists)
- Industry directories (G2, Capterra, Clutch, etc.)
- Social media profiles (Twitter, Facebook, Instagram, YouTube)
- Press mentions (ensure journalists use your correct name and description)

**Audit frequency:** Quarterly. Create a spreadsheet listing each platform, the entity information displayed, and whether it matches the canonical version on your website.

---

### 12-Week GEO + LLMO Implementation Sprint

**Weeks 1-2: Foundation**

| Task | Details |
|------|---------|
| Audit top 20 pages | Identify which already have citation hooks, which need them |
| robots.txt | Block training crawlers, allow inference crawlers (use template above) |
| llms.txt | Create and deploy at domain root with 20 to 50 priority URLs |
| Organization schema | Implement with @id, sameAs, knowsAbout on all pages |
| Person schema | Add for all content authors with credentials |
| Entity consistency audit | Check NAP and description across 10+ platforms |

**Weeks 3-4: Content Optimization**

| Task | Details |
|------|---------|
| Citation hooks | Write 3 to 5 hooks per page for top 20 pages |
| Content structure | Restructure top 10 pages using GEO page architecture |
| Self-contained passages | Rewrite all passages to stand alone (remove "as mentioned above") |
| Semantic completeness | Audit top 10 pages with Surfer SEO or MarketMuse. Target 8.5+ score. |
| Content freshness | Add "Last Updated" dates. Update dateModified in schema. |

**Weeks 5-6: Entity and Authority**

| Task | Details |
|------|---------|
| Crunchbase profile | Create or complete with full company data |
| Wikidata entry | Create if eligible (notability required) |
| Reddit strategy | Identify 5 to 10 relevant subreddits. Begin genuine participation. |
| Author pages | Create dedicated author pages with Person schema and credentials |
| Cross-platform bios | Ensure identical core information on all platforms |

**Weeks 7-8: Digital PR Launch**

| Task | Details |
|------|---------|
| Media list | Build list of 50 industry publications accepting pitches or guest posts |
| First pitch round | Send 5 to 10 pitches to relevant publications |
| Original research | Begin one data-driven research piece (survey, case study, or analysis) |
| Podcast outreach | Contact 10 podcast hosts for guest appearances |
| LinkedIn thought leadership | Publish 2 to 3 articles establishing author expertise |

**Weeks 9-10: Multi-Modal Enhancement**

| Task | Details |
|------|---------|
| Original images | Add custom images with descriptive alt text to top 20 pages |
| Explainer videos | Produce 60 to 90 second videos for top 5 pages |
| VideoObject schema | Add to all pages with embedded video |
| Entity density | Map and increase to 15 to 20 named entities per 1,000 words |
| Comparison tables | Add semantic HTML tables to product/service comparison pages |

**Weeks 11-12: Measurement and Optimization**

| Task | Details |
|------|---------|
| AI visibility baseline | Test 30 to 100 queries across ChatGPT, Perplexity, Gemini, Google AI Overviews |
| Set up tracking | Configure Otterly.AI or manual tracking protocol |
| Server log analysis | Parse logs for ChatGPT-User, PerplexityBot, OAI-SearchBot traffic |
| Schema validation | Run all pages through Google Rich Results Test. Fix all errors. |
| Analytics setup | Configure Google Analytics to track AI referral traffic |
| Report and plan | Document baseline metrics. Plan next 12-week sprint based on gaps. |

---

## Quick Reference: GEO + LLMO Combined Checklist Per Page

Use this checklist when optimizing any page for AI citation:

**Content Structure:**
- [ ] Answer capsule (40 to 60 words) immediately after H1
- [ ] H2 headings phrased as search queries
- [ ] Citation hook (40 to 60 words) immediately after each H2
- [ ] Self-contained passages (134 to 167 words each)
- [ ] 40 to 60 word paragraphs throughout
- [ ] FAQ section (3 to 5 Q&A pairs) with FAQPage schema
- [ ] Comparison table (semantic HTML) if applicable
- [ ] Key takeaways section (5 to 7 bullets)

**Citation Readiness:**
- [ ] 3 to 5 citation hooks per page (one per section minimum)
- [ ] Statistics with attribution (source, year) in every hook
- [ ] Original data or proprietary insight included
- [ ] "According to [source]" framing for key claims
- [ ] Outbound links to 2 to 3 Tier 1 sources
- [ ] No "as mentioned above" cross-references

**Schema Markup:**
- [ ] Article or BlogPosting schema with datePublished and dateModified
- [ ] Person schema for author (jobTitle, knowsAbout, sameAs)
- [ ] Organization schema with @id and sameAs
- [ ] FAQPage schema wrapping Q&A content
- [ ] VideoObject schema (if video present)

**Entity Signals:**
- [ ] 15 to 20 named entities per 1,000 words
- [ ] Author name with credentials on the page
- [ ] Brand name mentioned consistently
- [ ] Internal links to entity-defining pages (About, author bio)
- [ ] External links to authoritative sources

**Technical LLMO:**
- [ ] Clean semantic HTML (heading hierarchy, landmark regions)
- [ ] Content in initial HTML (not JavaScript-loaded)
- [ ] Page speed under 3 seconds
- [ ] HTTPS enabled
- [ ] Visible "Last Updated: [date]" on page
- [ ] Mobile-responsive layout
- [ ] Schema validated with Google Rich Results Test

**Off-Page:**
- [ ] Brand mentioned on Reddit in relevant subreddits
- [ ] Crunchbase profile complete and accurate
- [ ] LinkedIn, Twitter, YouTube profiles with consistent entity information
- [ ] At least one recent press mention or guest article (within 90 days)
