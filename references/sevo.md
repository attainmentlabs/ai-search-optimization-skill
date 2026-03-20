# SEvO: Search Everywhere Optimization

> Reference file for the attainment-ai-search-visibility skill.
> Covers the meta-framework that coordinates all 18 AI search disciplines.
> Last updated: February 2026.

---

## Definition and Philosophy

SEvO (Search Everywhere Optimization) is not a new discipline to add to a checklist. It is the meta-framework that coordinates all other AI search and discovery disciplines simultaneously. Where traditional SEO optimized for one algorithm (Google's web index), SEvO acknowledges that in 2026 a brand can be discovered, cited, ignored, or hallucinated across dozens of distinct AI-powered discovery surfaces simultaneously, each with its own ranking signals.

**The core problem SEvO solves:**

A brand could rank #1 on Google for its primary keyword while being completely absent from ChatGPT answers, hallucinated on Perplexity, invisible on Pinterest visual search, and unoptimized on TikTok search. Each of these surfaces has a different user intent, a different algorithm, and a different set of signals that determine visibility. SEvO is the framework for managing them all in a coordinated, prioritized way.

**The fundamental shift:**

Old world: "Rank #1 on Google for our keywords."
SEvO world: "Appear correctly whenever our ideal customer asks a question, regardless of where they ask it."

This is not an incremental evolution. It is a categorical shift in how search visibility is conceived. The unit of measurement is no longer a keyword ranking. It is citation and answer presence across the complete discovery landscape.

**Origin and attribution:**

The term SEvO was popularized in the AI search visibility community beginning in 2023. Crystal Carter (Head of SEO at Wix, formerly at Moz) used it in public talks to describe the expanding search surface map. Dharmesh Shah (HubSpot co-founder) articulated the underlying philosophy: "Optimize for every platform where your customers ask questions." The discipline formalized rapidly through 2024 as AI Overviews launched, ChatGPT hit 200M weekly users, and Perplexity reached 10M daily queries.

**Why "search everywhere" is no longer optional:**

- 27% of Google users click zero results (SparkToro 2024) -- they get their answer from AI Overview
- ChatGPT has 200M weekly active users as of February 2024 (OpenAI announcement)
- Perplexity AI: 10M+ daily queries by Q4 2024 (company disclosed)
- 40% of Gen Z uses TikTok as their primary search engine for lifestyle queries (Adobe 2023)
- Pinterest: 600M visual searches per month (Pinterest Q3 2024 earnings)
- Amazon Rufus: Tens of millions of AI-assisted shopping queries per week since launch
- If you optimize only for Google, you are invisible to a substantial and growing share of your market

---

## The SEvO Architecture: All 18 Disciplines Mapped

The 18 disciplines of AI search visibility map to four tiers based on priority and search surface type.

### Tier 1: Core AI Discovery (Highest Priority)

These disciplines underpin all other surfaces. If Tier 1 is broken, Tier 2 and 3 investments return less value.

**1. SEO Foundation**
- Discovery surfaces: Google organic (web), Bing organic, all AI systems (which crawl indexed pages)
- Core signals: Technical health (crawlability, indexation, Core Web Vitals), content quality, backlink authority, E-E-A-T
- Why it feeds everything: Every LLM citation, every AI Overview card, every Perplexity answer ultimately traces back to a crawled web page. SEO foundation is the prerequisite for all other disciplines.
- Key reference: `/reference/seo-foundation.md`

**2. AEO and Voice (Answer Engine Optimization)**
- Discovery surfaces: Google Featured Snippets, People Also Ask, Google Assistant, Siri, Alexa, smart speakers
- Core signals: Answer capsule structure (40-70 word direct answers), FAQ schema, question-format headings, featured snippet position
- Why it matters in SEvO: Voice search reads featured snippets aloud. AEO content feeds AI Overviews. Structured Q&A is the format all AI systems prefer.
- Key reference: `/reference/aeo-voice.md`

**3. GEO and LLMO (Generative Engine Optimization / LLM Optimization)**
- Discovery surfaces: ChatGPT (browsing + training), Perplexity AI, Claude, Gemini, Copilot, You.com, every LLM-powered answer surface
- Core signals: Citation hooks (statistics, named quotations, specific data), high-authority publisher mentions, Reddit presence, Wikipedia entry, training data coverage
- Why it matters: GEO is the discipline of appearing in the answer, not just in the search results. A page that ranks #1 but has no citable data gets mentioned less than a page at #5 with three specific statistics.
- Key reference: `/reference/geo-llmo.md`

**4. AIVO (AI Visibility Optimization / Brand Accuracy)**
- Discovery surfaces: All LLM-powered systems when asked about your brand or competitors
- Core signals: Brand entity establishment, hallucination monitoring, cross-platform information consistency, authoritative source coverage
- Why it matters: AI systems frequently hallucinate facts about brands: wrong pricing, discontinued products, incorrect founding dates, wrong team members. AIVO is active management of brand accuracy across AI systems.
- Key reference: Covered in brand monitoring section below

### Tier 2: High-Value AI Surfaces (Medium-High Priority)

These surfaces each reach significant audiences and require dedicated optimization. Which sub-set to prioritize depends on industry and ICP.

**5. AI Local SEO**
- Discovery surfaces: Google AI Overviews (local queries), Google Maps, Apple Maps, ChatGPT local recommendations, Bing local results
- Core signals: Google Business Profile completeness and activity, review velocity, cross-citation consistency (NAP: Name, Address, Phone identical everywhere), local schema markup
- Priority for: Any business with physical locations, service area businesses, restaurants, healthcare practices

**6. Social and Video Search**
- Discovery surfaces: YouTube (search + AI features), TikTok search, Instagram Reels (Google-indexed audio), LinkedIn search
- Core signals: YouTube: watch time, CTR, transcript content, chapters. TikTok: caption text, audio transcription, in-video text OCR.
- Priority for: Brands with younger demographics, consumer products, B2C, entertainment, education

**7. Visual Search Optimization**
- Discovery surfaces: Google Lens (10B+ monthly), Google Images, Pinterest (600M+ visual monthly), Amazon StyleSnap, TikTok camera search
- Core signals: Image filenames, alt text, surrounding text context, ImageObject schema, product feed data in Google Merchant Center, image quality and resolution
- Priority for: E-commerce, retail, fashion, home decor, food, beauty, any product-based business

**8. AI Overviews Optimization (AAIO)**
- Discovery surfaces: Google AI Overviews (launched May 2024, appears in 15-30% of queries by late 2024)
- Core signals: Strong organic position (top 5), page quality and E-E-A-T, FAQ schema, answer capsules, schema-eligible content types (How-to, Recipe, Product, FAQ)
- Priority for: All brands (Google AI Overviews is the single most disruptive change to Google search since Featured Snippets)
- Key reference: `/reference/aaio-overviews.md`

**9. Entity and Semantic SEO**
- Discovery surfaces: Google Knowledge Panel, Wikidata, Wikipedia, Linked Data web, Google's Knowledge Graph
- Core signals: Sameás relationships, Wikidata entity creation, Wikipedia coverage, structured data with sameAs properties, cross-platform entity consistency (same name, description, founding date everywhere)
- Priority for: All brands that want LLM citation authority and Knowledge Panel presence
- Key reference: `/reference/entity-semantic.md`

**10. Multimodal Search Optimization**
- Discovery surfaces: Cross-modal queries that combine image + text + voice (Google Lens + text, voice + location, video + text query)
- Core signals: All image SEO signals + voice search signals + video schema, unified across all content types
- Priority for: Brands creating any visual, video, or voice-accessible content (which is nearly everyone)
- Key reference: `/reference/multimodal.md` (this file)

### Tier 3: Specialized Surfaces (Prioritize by Industry)

**11. Conversational Search Optimization (CSO)**
- Multi-turn query sequences, Perplexity follow-up reasoning, Claude Projects, ChatGPT custom GPTs
- Priority: Professional services, complex B2B products, healthcare, legal, financial

**12. AI Shopping Optimization**
- Google Shopping AI, Merchant Center optimization, AI-generated product descriptions, Google's product carousels in AI Overviews
- Priority: E-commerce, retail, consumer products, DTC brands

**13. Marketplace Search Optimization**
- Amazon (A9/A10 algorithm + Rufus AI), Etsy, eBay, app stores (ASO: App Store + Google Play)
- Priority: Sellers on marketplace platforms, mobile app developers

**14. AI Local SEO (Advanced)**
- Neighborhood-level AI local targeting, review response optimization, Google Posts strategy, AI-powered Google Maps features
- Priority: Multi-location businesses, franchises, local service businesses

**15. Multimodal Search (Detailed)**
- Covered in `/reference/multimodal.md`
- Cross-modal retrieval, Lens-specific optimization, voice-visual combinations

**16. Competitive AI Monitoring**
- Monitoring how competitors appear vs your brand in AI answers, exploiting competitor hallucinations, share of AI voice tracking
- Priority: Competitive industries where AI is actively used in purchase decisions

**17. Agentic Search Optimization**
- Optimizing for AI agents that browse, shop, and make decisions on behalf of users (OpenAI Operator, Google Agentic AI, upcoming agent commerce layer)
- Status: Emerging, 2025-2026 priority. Focus now: structured data, machine-readable pricing, schema completeness

**18. AI Content Quality and Freshness**
- Ensuring LLM training data and AI answer data reflects current, accurate brand information
- Freshness signals for AI: Updated content, recent backlinks, active GBP, active social presence
- Priority: All brands, ongoing maintenance discipline

---

## The SEvO Audit Process

A complete SEvO audit takes 2-4 weeks depending on brand complexity. Here is the systematic process.

### Phase 1: Discovery Mapping (Week 1)

**Step 1: Define the customer discovery journey**

Map every touchpoint where an ideal customer might ask a brand-relevant question:
- Awareness stage: "What is [category]?" / "Best [category] for [need]" -- surfaces: Google, ChatGPT, TikTok search, YouTube
- Consideration stage: "Compare [Brand A] vs [Brand B]" / "[Brand] reviews" -- surfaces: Perplexity, Reddit, Google, YouTube reviews
- Decision stage: "Buy [product]" / "Where to get [service] near me" -- surfaces: Google Shopping, Amazon, Google Maps, voice search
- Post-purchase: "[Product] how to use" / "[Product] troubleshooting" -- surfaces: YouTube, ChatGPT, Google
- Loyalty/Advocacy: "[Brand] community" / "[Brand] updates" -- surfaces: Reddit, TikTok, Instagram

**Step 2: Run the Golden Prompts protocol**

Golden prompts are the 10-20 queries your ideal customers most commonly ask. Run each one across every major AI surface and document results.

Surfaces to test:
- ChatGPT (GPT-4o with browsing) -- use incognito, no custom GPTs
- Perplexity AI -- default mode and Pro mode
- Google Gemini -- Advanced (1.5 Pro)
- Claude (claude.ai) -- no Project context
- Microsoft Copilot (Bing-backed)
- Google search: standard, AI Overview present? What sources cited?
- YouTube search: What videos rank? Are yours present?
- TikTok search: What content surfaces? Brand tagged anywhere?
- Pinterest search (visual): Search category terms, who appears?

**Step 3: Document brand presence vs absence**

For each golden prompt on each surface, record:
- Does brand appear? (Yes / No / Partial)
- If yes: Is information accurate?
- If yes: What source is cited? (Where did the AI get this?)
- If no: Who does appear? (Competitive intelligence)
- Hallucinations detected? (Wrong price, discontinued product, wrong location, wrong CEO, etc.)

**Step 4: Existing asset inventory**

Audit what currently exists across these signals:
- [ ] Google Business Profile: claimed? Complete? Active posts?
- [ ] Wikipedia or Wikidata entry: exists? Accurate?
- [ ] Google Knowledge Panel: appears on brand name search?
- [ ] Dominant press mentions (TechCrunch, industry publications): current and accurate?
- [ ] Reddit threads mentioning brand: positive? Negative? Accurate?
- [ ] LinkedIn company page: complete? Active?
- [ ] GSC: indexation rate, Core Web Vitals status, sitemap submitted
- [ ] Product feed in Google Merchant Center: active? Complete GTIN data?

### Phase 2: Gap Analysis (Week 1-2)

**Discipline-by-discipline scoring (0-10 scale):**

| Score | Meaning |
|-------|---------|
| 0-2 | Not started or fundamentally broken |
| 3-4 | Partial implementation, major gaps |
| 5-6 | Basic implementation, refinement needed |
| 7-8 | Well-implemented, minor gaps |
| 9-10 | Fully optimized, monitoring in place |

**Quick-win identification criteria:**
- Implementation time: Under 1 week (not requiring new content or link building)
- Impact: High (affects a primary discovery surface)
- Complexity: Low (can be done by one person without external dependencies)

Examples of quick wins:
- Adding FAQ schema to existing FAQ page (1 hour, high impact on AEO + AIVO)
- Claiming and completing Google Business Profile (2 hours, high impact on local AI visibility)
- Fixing missing alt text across top 20 product images (1 day, impacts visual search and Google Images)
- Adding author schema to blog posts (half day, impacts E-E-A-T and GEO authority)
- Uploading manual transcript to top 5 YouTube videos (2 hours, impacts video search and GEO)

**Structural gap identification criteria:**
- Requires new content creation (weeks to months)
- Requires link building campaign
- Requires entity establishment on external platforms
- Requires technical site restructuring

### Phase 3: Implementation Roadmap

**Month 1: Foundation sprint**

Week 1-2: Technical SEO health
- Core Web Vitals: Fix LCP, CLS issues (priority: mobile)
- Indexation: Submit/update XML sitemap, fix crawl errors in GSC
- Structured data: Add Organization schema, add Person schema for all authors
- GBP: Claim if unclaimed, complete all fields, upload 10+ photos, set up weekly post cadence

Week 3-4: Content infrastructure
- Answer capsules: Add 40-70 word direct answers after every H2 on top 10 pages
- FAQ schema: Deploy on all pages that have Q&A content
- Meta descriptions: Rewrite to answer-format (first sentence is the direct answer)
- Internal linking: Map topical clusters, add hub-page internal links

**Month 2-3: AI discovery layer**

Content creation:
- GEO citation hooks: Add statistics, named quotations, and specific data points to top 10 pages
- Long-form definitional content: Create "What is [core concept]?" pages for primary topics
- Reddit strategy: Begin authentic participation in 3-5 relevant subreddits (answer questions, share expertise)
- FAQ expansion: 25+ Q&A pairs across site, all with schema

Technical:
- Image optimization: Alt text audit, filenames, WebP conversion, srcset implementation
- Video: Manual transcripts for top YouTube videos, chapters added, VideoObject schema deployed
- Author profiles: Dedicated author bio pages with Person schema, LinkedIn links, credentials
- Wikidata: Create or claim brand entity (if notable enough)

**Month 4-6: Surface expansion**

AI-specific:
- Entity establishment: Pursue Wikipedia coverage if eligible, or alternative authority sources (Crunchbase, industry directories)
- AIVO monitoring: Set up Profound.co or Otterly.ai for monthly golden prompt tracking
- Competitor gap analysis: Identify which competitor AI citations you should be targeting

Platform expansion:
- YouTube: Consistent publishing cadence, chapter optimization on all new videos
- Pinterest: Catalog upload if product-based, Rich Pins enabled, board SEO optimized
- Amazon (if applicable): A+ content, Q&A section populated, Rufus-optimized descriptions
- Local (if applicable): LocalViking GBP posting schedule, citation audit with Whitespark

**Ongoing: Continuous monitoring**

Monthly:
- Golden prompts run across all 5 major AI platforms
- GSC review: Image search, video search, AI Overview impressions
- AIVO check: Brand accuracy in AI responses, hallucinations corrected
- Review velocity: Track GBP, G2, TrustPilot, Clutch as relevant

Quarterly:
- Full SEvO score recalculation
- Competitor AI share of voice audit
- Visual search share of voice audit (manual Google Lens test)
- Content freshness review: Update top-performing pages with new data, dates

---

## SEvO Content Matrix

One piece of content can satisfy multiple disciplines simultaneously. This is how to achieve maximum ROI per content asset.

### Blog Post (Maximum Multimodal Treatment)

A single blog post can satisfy: SEO + AEO + GEO + Entity + AAIO + Multimodal

**Required elements:**
1. Title: Target keyword + informational intent
2. Meta description: 40-60 word direct answer to the implied question
3. Hero image: Descriptive filename + alt text + preloaded, WebP format
4. First paragraph: Answer capsule (120-150 char direct answer to implied query)
5. H2 structure: Question format ("How does X work?" not "How X Works")
6. Answer capsules: After each H2, a 40-70 word direct answer
7. Statistics: At least 3 citable statistics with source and date
8. Named quotation: One expert quote with name, title, company
9. FAQ section: 5+ Q&A pairs at bottom, with FAQ schema
10. Author bio: Links to Person schema author page
11. Internal links: 3-5 internal links to related pillar content
12. Schema stack: Article + ImageObject + FAQPage + Author (Person)
13. Image sitemap: Entry added/updated

**Result:** This one page qualifies for Featured Snippets (AEO), AI Overview inclusion (AAIO), LLM citation (GEO), author entity association (Entity), image rich results (Multimodal), and organic ranking (SEO).

### YouTube Video (Maximum Multimodal Treatment)

A single YouTube video can satisfy: Social/Video + Multimodal + GEO + SEO

**Required elements:**
1. Title: Primary keyword + intent signal (number, benefit, or question format)
2. Description: First 150 characters are highest weight, write as answer capsule + include keyword
3. Description continued: Full transcript summary, links to referenced resources, chapter timestamps
4. Tags: 5-10 tags (primary keyword, variations, category terms)
5. Chapters: Starting at 0:00, minimum 3 chapters, question-format chapter titles
6. Manual transcript: VTT/SRT file uploaded (not relying on auto-generated)
7. Thumbnail: 1280x720px, high contrast, readable text, consistent brand template
8. Cards and end screens: Link to related videos (increases session time, algorithmic signal)
9. Pinned comment: Summary of key points with timestamps (keyword-rich, indexed)
10. VideoObject schema: On the page where video is embedded (your website, not just YouTube)
11. Video sitemap: Updated with new video entry

**Result:** YouTube search ranking, Google video carousel inclusion, Gemini video understanding eligibility, GEO citation (YouTube videos are cited by LLMs), and traffic to your website page.

### Product Page (Maximum Multimodal + E-Commerce Treatment)

A single product page can satisfy: SEO + AAIO + AI Shopping + Visual + Multimodal

**Required elements:**
1. Title: [Brand] [Product Name] + key descriptor (material, use case, variant)
2. Meta description: Key benefit + feature + purchase signal
3. Product images: 6+ images with descriptive filenames and alt text, WebP, srcset
4. Product description: Direct opening line (AEO answer capsule format)
5. Bullets: Scannable features with specific measurements, materials, compatibilities
6. FAQ section: 5+ questions customers ask before buying, with FAQ schema
7. Reviews: Verified reviews with schema (ReviewCount, aggregateRating)
8. Schema stack: Product + Offer + AggregateRating + ImageObject (multiple) + FAQPage + BreadcrumbList
9. Internal links: Category page + related products + buying guide
10. Structured data testing: All schema validated in Rich Results Test before publishing
11. Google Merchant Center: Feed updated with accurate GTIN, price, availability

**Result:** Google Shopping AI carousel eligibility, Product rich results, AI Overview product inclusion, Google Lens shopping match, image search visibility, featured snippet eligibility for product-specific queries.

---

## SEvO Scoring System

The SEvO Score is a 0-100 benchmark for a brand's overall AI search visibility. Use it to baseline, prioritize, and report progress.

### Scoring Weights

**Foundation (25 points maximum)**

| Metric | Max Points | How to Score |
|--------|-----------|--------------|
| Core Web Vitals: All green on mobile | 5 | PageSpeed Insights: 5=all green, 3=some amber, 0=red |
| Indexation: 95%+ of target pages indexed | 5 | GSC Coverage report: 5=95%+, 3=85-94%, 0=below 85% |
| Schema: Organization + Person + BreadcrumbList | 5 | Rich Results Test: 5=all valid, 3=partial, 0=none |
| Content quality: E-E-A-T signals present | 5 | Author bios, expertise signals, citations: 5=strong, 3=partial, 0=absent |
| Backlink authority: DR 40+ (or industry equivalent) | 5 | Ahrefs/SEMrush DR: 5=40+, 3=25-39, 0=below 25 |

**Tier 1 AI Discovery (30 points maximum)**

| Metric | Max Points | How to Score |
|--------|-----------|--------------|
| AEO: Answer capsules on top 10 pages | 8 | 8=all pages, 5=50%+ pages, 2=few pages, 0=none |
| AEO: FAQ schema site-wide | 7 | 7=all FAQ content has schema, 4=partial, 0=none |
| GEO: Statistics + citations on top pages | 8 | 8=3+ per page on top 10, 4=some, 0=none |
| AIVO: Brand appears correctly in AI answers | 7 | 7=all major AI systems accurate, 4=some, 0=missing or hallucinating |

**Tier 2 High-Value Surfaces (25 points maximum)**

| Metric | Max Points | How to Score |
|--------|-----------|--------------|
| AI Local: GBP claimed, complete, active | 5 | 5=complete + weekly posts, 3=claimed but sparse, 0=unclaimed |
| Visual: Image alt text coverage 90%+ | 5 | 5=90%+, 3=60-89%, 0=below 60% |
| Video: YouTube transcripts + chapters | 5 | 5=all major videos optimized, 3=some, 0=none |
| Entity: Knowledge Panel or Wikidata entry | 5 | 5=KP present and accurate, 3=Wikidata only, 0=none |
| AAIO: Appears in AI Overviews for 3+ target queries | 5 | 5=3+ queries, 3=1-2 queries, 0=none |

**Tier 3 Specialized (20 points maximum)**

| Metric | Max Points | How to Score |
|--------|-----------|--------------|
| CSO: Conversational content and multi-turn optimization | 5 | 5=dedicated conversational content, 3=partial, 0=none |
| AI Shopping: Product schema complete + GMC feed | 5 | 5=both complete, 3=partial, 0=none |
| Marketplace: Amazon/Etsy/App Store optimization | 5 | 5=fully optimized, 3=partial, 0=none or N/A |
| Monitoring: Monthly AI tracking active | 5 | 5=automated + monthly manual, 3=manual only, 0=none |

### Score Interpretation

**80-100: Strong AI Search Visibility**
- Brand appears correctly across most major AI surfaces
- Monitoring and maintenance in place
- Action: Focus on Tier 3 refinements and competitive positioning

**60-79: Competitive Position with Surface Gaps**
- Foundation is solid, specific surfaces are underperforming
- Action: Identify which 2-3 disciplines have lowest scores, sprint to fix
- Typical gap areas at this score: AIVO monitoring absent, Tier 2 surface optimization incomplete

**40-59: Foundational Gaps Limiting AI Visibility**
- Technical or content infrastructure issues holding back all other disciplines
- Action: Foundation sprint first (Month 1 roadmap), then Tier 1 AI disciplines
- Common pattern: Good organic SEO but zero GEO/AEO optimization

**Under 40: Starting from Scratch**
- Significant gaps across all tiers
- Action: 6-month structured implementation roadmap, prioritize foundation and GBP first
- Do not attempt all 18 disciplines simultaneously -- use 80/20 framework first

---

## SEvO by Industry and Use Case

### Professional Services (Law, Accounting, Consulting, Coaching)

**Primary discovery surfaces:**
- ChatGPT/Perplexity: "Best [service type] for [situation]" -- high trust-transfer queries
- Google: Research-heavy, long-form queries, "how to choose [service provider]"
- LinkedIn: Professional credibility check, thought leadership discovery
- Reddit: Peer recommendations, "anyone used [firm/practitioner]?" queries

**Priority disciplines:**
1. GEO (highest priority): Clients use AI for research before hiring. Being cited = credibility.
2. AEO: "What does [service] cost?" / "How does [process] work?" -- high-value featured snippets
3. Entity: Knowledge panel, LinkedIn profile, Crunchbase, professional directory listings
4. AIVO: Hallucinations about credentials, expertise area, or pricing are brand-damaging

**What to skip (low ROI for professional services):**
- Visual search optimization (not product-focused)
- Marketplace optimization (not selling on Amazon)
- AI shopping (not applicable)

**Key content types:**
- Case studies with specific outcomes and data points (GEO citation magnets)
- "How [process] works" explainer pages (AEO answer capsules)
- FAQ pages per service line (FAQ schema)
- Author bio pages with credentials, publications, speaking engagements (Entity + E-E-A-T)

### E-Commerce and Retail

**Primary discovery surfaces:**
- Google Shopping AI and standard Shopping tab: Highest purchase intent
- Amazon Rufus: Second largest shopping search surface after Google
- Google Lens and Pinterest: Visual discovery of products
- TikTok Shop: Growing commerce layer on TikTok search
- YouTube: Product reviews and unboxing influencing purchase decisions

**Priority disciplines:**
1. AI Shopping Optimization: Product schema, GMC feed completeness, GTIN accuracy
2. Visual Search: Image alt text, filenames, ImageObject schema, Lens optimization
3. Marketplace: Amazon A+ content, Q&A, Rufus-optimized descriptions
4. SEO Foundation: Category pages, product pages with structured data stacking
5. Social/Video: TikTok Shop tags, YouTube product review content strategy

**Key tactics:**
- Product schema with every required field (including hasMerchantReturnPolicy and shippingDetails)
- Minimum 6 images per product: white background main + lifestyle shots
- 360-degree spin images submitted to Google Merchant Center
- GMC: Accurate GTIN on every SKU (enables Google Lens product match)
- Amazon: A+ content on all top-selling ASINs, Q&A section with 10+ answers

### Local Business (Healthcare, Dental, HVAC, Restaurants, Law Firms)

**Primary discovery surfaces:**
- Google Maps AI features: "Near me" queries with AI summaries (2024 feature)
- Google AI Overviews (local): AI answers "best [business type] near [city]"
- Voice search: "Hey Google, find a [business type] near me"
- ChatGPT local: "Best [restaurant type] in [neighborhood]" queries growing
- Siri + Apple Maps: Second-largest local search surface

**Priority disciplines:**
1. AI Local SEO: GBP optimization, NAP consistency, review velocity
2. AEO / Voice: Direct answers to local queries, FAQ schema for local questions
3. Entity: GBP listing is the local entity. Wikidata entry for larger businesses.
4. AIVO: Ensure AI systems have correct address, hours, services, pricing

**Key tactics:**
- GBP: Post weekly (Google Posts), answer every Q in Q&A section, respond to all reviews
- Review velocity: Aim for 2-5 new reviews per week from real customers
- NAP citations: Identical name, address, phone on all directories (Yelp, Bing Places, Apple Business Connect, Facebook, YellowPages, Foursquare)
- Apple Business Connect: Claim listing (powers Siri + Apple Maps results)
- Neighborhood-level content: Create pages or content specific to neighborhoods/suburbs served

### SaaS and B2B Technology

**Primary discovery surfaces:**
- ChatGPT and Perplexity: Buyers research software solutions using AI before touching sales
- Google: Long-tail decision-stage queries ("best [software type] for [use case] [team size]")
- G2, Capterra, TrustRadius: Review platform content is cited heavily by AI systems
- Reddit: r/[industry] subreddits are major training data sources and active research surfaces
- LinkedIn: Buyer research on company, leadership, thought leadership content

**Priority disciplines:**
1. GEO (highest priority): B2B buying cycles are research-heavy. AI citations at research stage = pipeline.
2. Entity: LinkedIn company page, Crunchbase, G2 profile, Product Hunt -- all feed LLM knowledge
3. AIVO: Brand hallucinations about features, pricing, or integrations can kill deals mid-cycle
4. CSO: Multi-turn queries ("OK so that solves X, but what about Y...") are common in B2B research

**Key content types:**
- Comparison pages: "[Your Product] vs [Competitor]" -- owned comparison content beats AI hallucination
- Use case pages: "[Product] for [team type / industry]" -- targets niche decision-stage queries
- Integration pages: "[Product] + [Partner Tool]" -- captures tool-stack queries
- ROI case studies with specific numbers: 3+ hard metrics per case study (GEO citation magnets)

### Healthcare and Regulated Industries

**Primary discovery surfaces:**
- Google: Health queries remain predominantly text-based, high-intent
- ChatGPT and Perplexity: Used for symptom research, treatment options, medication information
- Google AI Overviews: Health queries trigger AI Overviews with high frequency (and controversy)
- Reddit: r/health, r/medical subreddits are actively monitored by patients

**Priority disciplines:**
1. AEO: Health queries drive enormous featured snippet volumes
2. GEO: AI citation of health content requires extreme E-E-A-T (medical professional authorship, review dates, peer citations)
3. AAIO: AI Overviews in health are scrutinized -- optimize defensively to ensure accuracy
4. Entity: Author entity (physician credentials) is critical for health E-E-A-T

**Key requirements:**
- Author credentials: Every health article needs a named medical professional author with Person schema listing credentials, affiliation, and review date
- Medical review date: Visible on page and in schema. Stale medical content is cited less by AI.
- Peer citations: Link to and cite PubMed, clinical trial data, CDC, NIH -- LLMs weight these sources heavily
- HIPAA-safe tracking: Avoid Facebook Pixel and Google Ads broad-match on health pages (legal + crawl quality signal)

---

## SEvO Quick-Start Framework (80/20 Version)

If a client or brand has limited budget or time, these 5 actions cover approximately 80% of AI discovery value. Implement in order.

### Action 1: Technical SEO Foundation (Week 1)

**Why first:** All other actions return lower value if the technical foundation is broken. AI systems cannot cite pages they cannot crawl.

**Minimum viable checklist:**
- [ ] Submit XML sitemap to GSC and Bing Webmaster Tools
- [ ] Fix all GSC crawl errors (pages with 404, 5xx errors)
- [ ] Check robots.txt: Not blocking important pages or images
- [ ] Core Web Vitals mobile: LCP under 2.5s, CLS under 0.1 (fix LCP image preloading first)
- [ ] Ensure HTTPS throughout (mixed content kills trust signals)
- [ ] Mobile-friendly test: Pass (Google mobile-friendly test)

**Time to implement:** 1-3 days depending on site complexity

### Action 2: Answer Capsules on Every Major Page (Week 1-2)

**Why second:** Answer capsules are the single highest-leverage content change for AI visibility. They feed AEO, GEO, AAIO, and voice search simultaneously.

**What to do:**
- Identify top 10-15 pages by organic traffic or commercial importance
- Add a 120-150 character direct answer sentence immediately after the first H2 (or page intro)
- Reframe H2s as questions where possible
- Add FAQ schema to any page with Q&A content

**Template for every H2:**
```
## [Question Format Heading]

[Direct answer in 1-2 sentences, 40-70 words, can stand alone without reading the rest of the page. Include the target keyword naturally. Specific and factual.]

[Then the longer detailed section continues...]
```

**Time to implement:** 2-4 hours per page, 1-2 weeks for top 10 pages

### Action 3: GBP Optimization (Day 1 for local businesses)

**Why third:** GBP is the most underutilized high-impact signal. A complete, active GBP directly feeds Google AI Overviews local, Google Maps AI features, and voice search results.

**Minimum viable GBP checklist:**
- [ ] Claimed and verified
- [ ] Business name: Exact legal name (no keyword stuffing in business name -- violates policy)
- [ ] Categories: Primary + up to 9 secondary, choose most specific available
- [ ] Description: 750 characters, includes primary service keywords naturally
- [ ] Hours: Accurate, including special hours for holidays
- [ ] Phone: Primary local number (not tracking number as primary)
- [ ] Website: Canonical URL (not tracking URL)
- [ ] Photos: Minimum 10 (logo, cover, interior, exterior, team, products/services)
- [ ] Q&A: Pre-populate with 5-10 common questions and accurate answers
- [ ] Weekly posts: Set cadence (new offer, event, product, or update weekly)

**Time to implement:** 2-3 hours initial setup, 30 minutes per week ongoing

### Action 4: FAQ Schema + Author Schema (Week 2)

**Why fourth:** These two schema types unlock the most AI search features of any structured data types.

**FAQ schema unlocks:**
- Featured snippets (Google)
- People Also Ask boxes (Google)
- AI Overview FAQ treatment
- Voice search answers
- Perplexity and ChatGPT citation (well-structured Q&A is highly citable)

**Author schema (Person schema) unlocks:**
- E-E-A-T recognition by Google and AI systems
- Author entity association with topics (GEO authority)
- Knowledge Panel for notable individuals
- Citation credibility in GEO: "According to [Author Name], [Expert in X]..."

**Implementation priority:**
- FAQ schema: All pages with existing Q&A content (FAQ pages, support pages, product pages)
- Author schema: All blog posts, guides, and articles with named authors
- Organization schema: Homepage and About page

**Time to implement:** 1-2 days if using a schema plugin (Yoast SEO, Rank Math, or Schema Pro)

### Action 5: AIVO Monitoring (End of Month 1)

**Why fifth:** Without monitoring, you cannot know what AI systems are saying about your brand, whether they are hallucinating, or whether your optimization efforts are working.

**Minimum viable AIVO monitoring:**

**Monthly manual process (free):**
1. Run 10 golden prompts across ChatGPT, Perplexity, Gemini, Claude
2. Document: Is brand mentioned? Accurately? Source cited?
3. Any hallucinations: File a correction (ChatGPT: thumbs down + correct info; Perplexity: report inaccuracy)
4. Track month-over-month: Are you appearing more or less? More or less accurately?

**Automated monitoring tools:**
- Profound.co: Dedicated AI brand monitoring, tracks mentions across AI platforms, $299+/month
- Otterly.ai: AI search monitoring, prompt testing, competitor comparison, $49-$299/month
- AthenaHQ: AI visibility platform focused on GEO and AIVO, enterprise pricing
- BrandMentions: Broader web + social monitoring, catches AI-generated content that mentions brand

**Time to implement:** 2-3 hours setup, 1-2 hours per month ongoing

---

## SEvO Tools Ecosystem

A complete tools map organized by discipline.

### SEO Foundation

| Tool | Function | Price Range |
|------|----------|-------------|
| Google Search Console | Indexation, Core Web Vitals, rich results, clicks/impressions | Free |
| Bing Webmaster Tools | Bing indexation, IndexNow, Bing-specific errors | Free |
| Ahrefs | Backlink analysis, keyword research, site audit | $99-$449/month |
| SEMrush | Keyword research, site audit, position tracking, competitor analysis | $129-$449/month |
| Screaming Frog | Technical site crawl: broken links, missing alt text, duplicate content, schema | Free (500 URLs) / £259/yr |
| PageSpeed Insights | Core Web Vitals per URL, LCP diagnosis | Free |
| Chrome DevTools | Performance profiling, network waterfall, image load analysis | Free (built into Chrome) |
| Merkle Schema Generator | Build and validate structured data JSON-LD | Free |
| Google Rich Results Test | Validate schema eligibility for rich results | Free |

### GEO and AEO Tools

| Tool | Function | Price Range |
|------|----------|-------------|
| Profound.co | AI brand monitoring, citation tracking, competitive AI share of voice | $299+/month |
| Otterly.ai | AI search monitoring, prompt testing, brand vs competitor in AI answers | $49-$299/month |
| AthenaHQ | GEO and AIVO platform, enterprise AI visibility management | Enterprise |
| Search Response | AI answer tracking, where your content appears in AI responses | $99+/month |
| AlsoAsked.com | Question research for AEO: PAA cluster mapping | Free (limited) / $15/month |
| AnswerThePublic | Question research: what people ask about your topic | $99/month |

### Local SEO Tools

| Tool | Function | Price Range |
|------|----------|-------------|
| BrightLocal | Local rank tracking, citation audit, GBP management | $39-$49/month |
| Whitespark | Citation building, local rank tracker, GBP audit | $33-$200/month |
| LocalViking | GBP post scheduling, GeoGrid local rank tracking | $39+/month |
| Moz Local | Citation distribution and monitoring | $14-$33/month per location |
| Yext | Enterprise citation management, answers platform | $199+/month |

### Social and Video Tools

| Tool | Function | Price Range |
|------|----------|-------------|
| VidIQ | YouTube SEO: keyword research, competitor analysis, thumbnail scoring | Free / $7.50-$39/month |
| TubeBuddy | YouTube management: bulk processing, A/B thumbnail testing, tag research | Free / $4.50-$40/month |
| YouTube Studio | Native analytics: search queries, CTR, retention, external traffic | Free |
| Sprout Social | Social listening, scheduling, TikTok analytics | $249-$499/month |
| Metricool | Multi-platform scheduling + analytics including TikTok | $22-$99/month |

### Visual Search Tools

| Tool | Function | Price Range |
|------|----------|-------------|
| Cloudflare Images | CDN + automatic WebP/AVIF conversion + resizing | $5/month per 100K images |
| Imgix | Enterprise image CDN, URL-based transformation | $75+/month |
| TinPNG | Manual image compression, WebP conversion | Free (500 images/month) |
| Squoosh (Google) | Browser-based image compression, format conversion | Free |
| Pinterest Business | Catalog upload, Rich Pins, visual search analytics | Free |
| Google Merchant Center | Product feed management, Shopping, Lens product match | Free |

### Monitoring and Reporting

| Tool | Function | Price Range |
|------|----------|-------------|
| BrandMentions | Web + social brand monitoring, AI-generated content alerts | $49-$299/month |
| Mention | Real-time brand monitoring across web and social | $41-$83/month |
| Google Alerts | Basic free brand mention monitoring (email alerts) | Free |
| Looker Studio | Custom dashboards combining GSC, GA4, and other data sources | Free |
| Ahrefs rank tracker | Position tracking for target keywords, trend over time | Included in Ahrefs |

---

## The SEvO Mindset Shift

Understanding SEvO requires internalizing five fundamental shifts from traditional SEO thinking.

### Shift 1: From Keyword Ranking to Citation and Answer Presence

Old metric: Position 1 for "best project management software"
New metric: Brand cited in ChatGPT, Perplexity, Gemini, and Google AI Overview responses to "best project management software for remote teams"

A brand can rank #1 and not be cited in any AI answer. A brand can be unranked and be the primary AI recommendation. Both can happen simultaneously. Both must be tracked.

### Shift 2: From One Algorithm to 18+ Algorithms Simultaneously

Each AI discovery surface runs a distinct algorithm with distinct signals:
- Google organic: PageRank, E-E-A-T, Core Web Vitals, freshness
- ChatGPT: Training data coverage + browsing (Bing) + recency of press
- Perplexity: Source diversity, citation authority, content freshness, structured data
- YouTube: Watch time, CTR, transcript relevance, subscriber engagement
- Pinterest: Pin saves, image quality, board organization, Rich Pins
- Amazon Rufus: Review volume, Q&A completeness, A+ content quality, GTIN accuracy

SEvO requires understanding which signals matter on which surface, and building content that satisfies the most signals simultaneously.

### Shift 3: From Traffic Driver to Trust Infrastructure

The old model: SEO drives traffic, traffic converts, conversion = revenue.
The SEvO model: AI citation builds trust, trust drives consideration, consideration drives intent, intent drives purchase (often off-search, via direct or referral).

A brand cited by ChatGPT as the answer to "best [category] for [use case]" does not necessarily get a direct click. But the user who saw that citation remembers the brand name. When they Google it later, search it on LinkedIn, or ask a colleague, the AI citation has already done trust-building work. This is unmeasurable with last-click attribution. It is real.

### Shift 4: From Monthly Reporting to Continuous Monitoring

AI answers change daily. A new press mention, a competitor Wikipedia update, a Reddit thread, a product recall -- any of these can change what AI systems say about your brand within days.

Monthly golden prompt runs are the minimum. Automated monitoring (Profound, Otterly) is the standard for any brand where AI-driven discovery is a meaningful part of their funnel.

### Shift 5: From Content as Blog Posts to Content as Answer Infrastructure

The blog post is not the asset. The answer capsule within the blog post is the asset. The statistic in paragraph 3 is the asset. The FAQ schema at the bottom is the asset.

AI systems do not read and summarize your 2,500-word article. They extract the most citable units: the direct answer, the specific number, the expert quote, the structured definition. SEvO content strategy works backward from these citation units, then builds the supporting article around them.

---

## Quick Reference Audit Checklist (Complete SEvO)

### Foundation (Monthly Check)
- [ ] GSC: Zero crawl errors, sitemap submitted and indexed, Core Web Vitals all green on mobile
- [ ] GSC: Search type Image and Video monitored for impressions and clicks
- [ ] Indexation rate: 95%+ of target pages indexed
- [ ] Schema: Organization, BreadcrumbList, Author (Person) validated in Rich Results Test

### Tier 1 AI Discovery (Monthly Check)
- [ ] Golden prompts run: ChatGPT, Perplexity, Gemini, Claude, Copilot (10+ prompts each)
- [ ] Brand accuracy documented: Any hallucinations identified and flagged for correction
- [ ] Answer capsules: Present on all top 10 pages (40-70 word direct answers after each H2)
- [ ] FAQ schema: Deployed on all Q&A content across site
- [ ] GEO: At least 3 citable statistics with source and date on each top-10 page
- [ ] GEO: At least 1 named expert quotation per major content piece

### Tier 2 High-Value Surfaces (Monthly Check)
- [ ] GBP: Active (weekly posts published), Q&A section current, photos updated quarterly
- [ ] Reviews: Velocity on track (2-5 per week minimum for local businesses)
- [ ] Image alt text: 90%+ coverage across all pages (Screaming Frog audit quarterly)
- [ ] Images: WebP format deployed, srcset set, LCP image preloaded
- [ ] YouTube: New videos have manual transcripts + chapters within 48 hours of publish
- [ ] VideoObject schema: On all pages with embedded video
- [ ] Knowledge Panel or Wikidata: Accurate, monitored for unauthorized edits

### Tier 3 Specialized (Quarterly Check)
- [ ] AI Shopping: Product schema complete, GMC feed error-free, GTINs accurate
- [ ] Marketplace: Amazon A+ content live, Q&A populated, Rufus-optimized descriptions
- [ ] Pinterest: Catalog uploaded, Rich Pins enabled, board SEO reviewed
- [ ] App Store (if applicable): ASO reviewed, keywords updated, screenshots current
- [ ] Competitive AI audit: Top 3 competitors' AI visibility compared to brand

### Brand Accuracy Corrections (As Needed)
- [ ] ChatGPT hallucination: Report via thumbs down + "Provide feedback" with correct information
- [ ] Perplexity inaccuracy: Use "Sources" feedback button or flag via support
- [ ] Google Knowledge Panel: "Suggest a change" button, requires Google account
- [ ] Wikidata: Edit directly (requires Wikidata account, neutral point of view required)
- [ ] Press coverage: Pitch journalists with correct information to update old inaccurate articles

### Reporting (Monthly Deliverable)
- [ ] SEvO Score: Recalculated with current scores per discipline
- [ ] Golden prompt results: Screenshot + notes for each AI surface tested
- [ ] GSC highlights: Image search, video search, AI Overview impressions trends
- [ ] GBP insights: Views, searches, calls, direction requests (month-over-month)
- [ ] AIVO status: Any hallucinations found this month? Corrections submitted?
- [ ] Priority actions for next month: Top 3 gaps identified, with implementation plan

---

*End of sevo.md reference file. This is the meta-framework file for the attainment-ai-search-visibility skill suite. It should be read first when orienting to the skill, then use individual discipline reference files for tactical depth.*
