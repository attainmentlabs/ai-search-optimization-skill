# AAIO and Google AI Overviews: Implementation Reference

> Skill reference file. Contains deep, actionable implementation knowledge for Agentic AI Optimization (AAIO) and Google AI Overviews Optimization. All statistics sourced from 2025/2026 industry research.

---

## AAIO (Agentic AI Optimization) Implementation

### What AAIO Means

AAIO optimizes websites for autonomous AI agents that browse, select, and transact without human intervention. The term and framework originate from the arXiv paper 2504.12482 by Floridi et al. (April 2025). The paper calls AAIO "fundamental digital infrastructure" for businesses.

Unlike traditional SEO (optimizing for human searchers) or AEO/GEO (optimizing for AI answer engines), AAIO targets a third audience: AI agents that act on behalf of users. These agents read structured data, fill out forms, compare prices, and complete purchases autonomously.

The core principle: your website must be machine-readable, machine-navigable, and machine-actionable. If an AI agent cannot understand your page, find your prices, or complete a booking without human help, you are invisible to agentic commerce.

---

### Live Agentic Commerce Platforms (2026)

| Platform | Capability | Status |
|----------|-----------|--------|
| ChatGPT Instant Checkout | Buy from Shopify/Etsy merchants | Live, US |
| Google Buy for Me | Purchase on behalf of users | Live, US |
| Perplexity Buy with Pro | Research and buy | Live, Pro subscribers |
| Amazon Rufus | In-app purchasing | Live |
| Google AI Mode | Restaurant reservations | Live, US |
| Google AI Mode | Hotel/flight bookings | In rollout |

Brands already processing agent orders: URBN, Etsy, Glossier, SKIMS, Spanx, Vuori, Walmart, Instacart.

Payment infrastructure is following quickly. Visa Trusted Agent Protocol and Mastercard Agent Pay are both launching in 2026, enabling AI agents to hold payment credentials and authorize transactions on behalf of users.

---

### Key Statistics

- ChatGPT agent-requested pages reached 33% of organic search traffic level by Aug 2025 (BrightEdge)
- Agentic traffic increased 1,300% from Jan to Aug 2025
- 58.5% of Google searches end without a click (zero-click searches)
- Shopify orders from AI searches grew 11x since Jan 2025
- 47% of US shoppers use AI for at least one shopping task
- Visa Trusted Agent Protocol and Mastercard Agent Pay launching 2026
- Gartner: 50% of enterprises will have autonomous agents in production by 2027
- Bain: $300-500B US agentic commerce by 2030

---

### AAIO vs Traditional SEO

| Dimension | Traditional SEO | AAIO |
|-----------|----------------|------|
| Audience | Human readers | AI agents |
| Success metric | Rankings, CTR | Task completion rate |
| Content goal | Persuade humans | Enable agents to understand and act |
| Schema purpose | Rich snippets | Machine-executable actions |
| Form design | Conversion-optimized UX | Autocomplete attributes, label associations |
| JavaScript | Can be lazy-loaded | Must be server-rendered |
| Speed | Google is patient | ChatGPT does not wait |
| Pricing display | May be hidden behind CTAs | Must be in text on page |
| Navigation | Visual menus work | Landmark regions and semantic HTML required |
| Trust signals | Social proof, testimonials | Structured credentials, verifiable data |

---

### Schema for AI Agents

Schema markup shifts from "nice for rich snippets" to "required for agent comprehension." AI agents rely on structured data to understand what a business offers, where it is located, how to book, and what it costs.

**LocalBusiness with ReserveAction:**

```json
{
  "@context": "https://schema.org",
  "@type": "Dentist",
  "@id": "https://yourdomain.com/#business",
  "name": "Business Name",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main St",
    "addressLocality": "Toronto",
    "addressRegion": "ON",
    "postalCode": "M5V 1A1",
    "addressCountry": "CA"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 43.6532,
    "longitude": -79.3832
  },
  "telephone": "+14165551234",
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"],
      "opens": "09:00",
      "closes": "17:00"
    }
  ],
  "potentialAction": {
    "@type": "ReserveAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "https://yourdomain.com/book",
      "actionPlatform": [
        "http://schema.org/DesktopWebPlatform",
        "http://schema.org/MobileWebPlatform"
      ]
    }
  }
}
```

Key fields for agents: `@id` (unique identifier for cross-referencing), `geo` (precise location), `openingHoursSpecification` (real-time availability), `potentialAction` (what an agent can do here).

**Service Schema with Pricing:**

```json
{
  "@type": "Service",
  "name": "Service Name",
  "description": "What this service includes",
  "provider": {"@id": "https://yourdomain.com/#business"},
  "areaServed": "Greater Toronto Area",
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "itemListElement": [
      {
        "@type": "Offer",
        "name": "Basic Service",
        "price": "149.00",
        "priceCurrency": "CAD",
        "availability": "https://schema.org/InStock"
      }
    ]
  }
}
```

Critical: Pricing must exist in both schema and visible page text. Agents cross-reference structured data against on-page content. Schema-only pricing without visible text is treated as less trustworthy.

**Product Schema for E-commerce:**

```json
{
  "@type": "Product",
  "name": "Product Name",
  "description": "Concise product description",
  "sku": "SKU-12345",
  "brand": {"@type": "Brand", "name": "Brand Name"},
  "offers": {
    "@type": "Offer",
    "price": "79.99",
    "priceCurrency": "USD",
    "availability": "https://schema.org/InStock",
    "seller": {"@id": "https://yourdomain.com/#business"},
    "shippingDetails": {
      "@type": "OfferShippingDetails",
      "shippingRate": {
        "@type": "MonetaryAmount",
        "value": "0",
        "currency": "USD"
      },
      "deliveryTime": {
        "@type": "ShippingDeliveryTime",
        "handlingTime": {"@type": "QuantitativeValue", "minValue": 0, "maxValue": 1, "unitCode": "DAY"},
        "transitTime": {"@type": "QuantitativeValue", "minValue": 3, "maxValue": 7, "unitCode": "DAY"}
      }
    },
    "hasMerchantReturnPolicy": {
      "@type": "MerchantReturnPolicy",
      "returnPolicyCategory": "https://schema.org/MerchantReturnFiniteReturnWindow",
      "merchantReturnDays": 30,
      "returnMethod": "https://schema.org/ReturnByMail"
    }
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.7",
    "reviewCount": "312"
  }
}
```

Shipping and return details are increasingly important for agent decision-making. Agents compare total cost (price + shipping) and return flexibility when selecting merchants.

---

### robots.txt for AI Agents

```
# Block training crawlers (data harvesting for model training)
User-agent: GPTBot
Disallow: /
User-agent: Google-Extended
Disallow: /
User-agent: ClaudeBot
Disallow: /
User-agent: CCBot
Disallow: /
User-agent: FacebookBot
Disallow: /
User-agent: Bytespider
Disallow: /
User-agent: Diffbot
Disallow: /

# Allow search/inference crawlers (these serve your content to users)
User-agent: ChatGPT-User
Allow: /
User-agent: OAI-SearchBot
Allow: /
User-agent: PerplexityBot
Allow: /
User-agent: Amazonbot
Allow: /
User-agent: Googlebot
Allow: /
User-agent: Bingbot
Allow: /
User-agent: AppleBot
Allow: /
```

**Critical distinctions:**
- `GPTBot` = OpenAI training crawler. Block it.
- `ChatGPT-User` = Live ChatGPT browsing on behalf of a user. Allow it.
- `OAI-SearchBot` = OpenAI search indexing. Allow it.
- `Google-Extended` = Gemini training crawler. Block it.
- `Googlebot` = Google Search indexing (including AI Overviews). Allow it.
- `ClaudeBot` = Anthropic training crawler. Block it.

Key fact: 13.26% of AI bot requests ignored robots.txt in Q2 2025. Blocking training crawlers does NOT prevent your content from appearing in AI search results. The training has already happened. But maintaining clear robots.txt signals is still best practice for ongoing compliance and new crawl prevention.

---

### llms.txt Implementation

The `/llms.txt` file is a plain-text summary of your site designed for LLM consumption. Place it at your domain root.

**Format:**

```
# Business Name

> One-sentence description of what you do and who you serve.

## Services
- Service 1: Description. Price: $X. [Book](https://yourdomain.com/book)
- Service 2: Description. Price: $X. [Book](https://yourdomain.com/book)

## Location
123 Main St, Toronto, ON M5V 1A1
Hours: Mon-Fri 9am-5pm

## Contact
Phone: +1-416-555-1234
Email: info@yourdomain.com
Book online: https://yourdomain.com/book

## Key Pages
- [About](https://yourdomain.com/about)
- [Services](https://yourdomain.com/services)
- [Pricing](https://yourdomain.com/pricing)
- [Blog](https://yourdomain.com/blog)
```

Keep it under 500 words. Use Markdown formatting. Include direct links to key pages. Update it when services or pricing change.

---

### HTML Requirements for Agents

AI agents interact with web pages more like screen readers than visual browsers. Every element must be programmatically identifiable.

**Forms:**
- All `<input>` fields must have associated `<label>` tags with `for` attributes matching the input `id`
- Add `autocomplete` attributes to all form fields (e.g., `autocomplete="given-name"`, `autocomplete="email"`, `autocomplete="tel"`)
- Group related fields with `<fieldset>` and `<legend>`
- Use proper `type` attributes on inputs (`type="email"`, `type="tel"`, `type="date"`)
- Submit buttons must use `<button type="submit">` with descriptive text, not `<div onclick>`

**Semantic HTML:**
- Use landmark regions: `<nav>`, `<main>`, `<aside>`, `<footer>`, `<header>`
- One `<h1>` per page. Sequential heading hierarchy (h1, h2, h3). Never skip levels.
- Replace `<div onclick>` with proper `<button>` or `<a>` elements
- Use `<table>` for tabular data with `<thead>`, `<th scope>` attributes
- Lists use `<ul>`, `<ol>`, `<li>`. Not styled divs.

**Accessibility (directly enables agents):**
- Add `aria-label` to icon buttons and elements without visible text labels
- Add `aria-describedby` for form validation messages
- All images must have descriptive `alt` text (not "image1.jpg" or empty alt)
- All links must have meaningful text (not "click here")
- Color contrast ratios must meet WCAG 2.1 AA (4.5:1 for text)

**Content rendering:**
- All pricing must be in text on the page, not only in PDFs or images
- Critical content must be in initial HTML, not loaded by JavaScript after page load
- Server-side render or pre-render all important content
- No content behind "Show More" buttons that require JavaScript interaction
- Phone numbers and addresses in text, not images

**Performance:**
- ChatGPT-User has a short timeout. Pages must load core content in under 3 seconds.
- Minimize render-blocking JavaScript
- Use `loading="lazy"` on below-fold images but keep above-fold images eager

---

### 12-Week AAIO Implementation for Local Service Businesses

**Weeks 1-2: Accessibility Audit**
- Test entire site with screen reader (macOS VoiceOver: Cmd+F5)
- Test site with CSS disabled (browser dev tools). Can you still understand and navigate it?
- Verify all critical content appears in initial HTML (View Source, not Inspect Element)
- Check every form: does each input have a label? Can you tab through the form logically?
- Document all issues in a spreadsheet: page, element, issue, priority

**Weeks 3-4: Schema Foundation**
- Add LocalBusiness schema with complete address, geo coordinates, phone, hours
- Add Service schema for each service with descriptions and prices
- Add ReserveAction or OrderAction for booking/purchasing
- Add AggregateRating if you have reviews (minimum 5 reviews)
- Validate everything with Google Rich Results Test (search.google.com/test/rich-results)
- Test schema with Schema.org Validator (validator.schema.org)

**Week 5: Crawler Configuration**
- Update robots.txt: block training crawlers, allow inference crawlers (see template above)
- Create and deploy `/llms.txt` at domain root
- Verify robots.txt is accessible at `yourdomain.com/robots.txt`
- Check server logs for existing AI bot traffic (search for ChatGPT-User, PerplexityBot, OAI-SearchBot)

**Weeks 6-8: Semantic HTML and Accessibility**
- Add `autocomplete` attributes to all form fields
- Add `aria-label` to all icon buttons, hamburger menus, close buttons
- Replace all `<div onclick>` handlers with `<button>` or `<a>` elements
- Add landmark regions: wrap navigation in `<nav>`, main content in `<main>`, sidebar in `<aside>`
- Fix heading hierarchy: one h1, sequential h2-h6, no skipped levels
- Add descriptive alt text to all images

**Weeks 9-10: Content and Pricing Clarity**
- Show all pricing in text on page (not hidden in modals, PDFs, or "contact for pricing")
- Ensure Offer schema on each service page matches the visible price
- Verify booking widget has proper form labels and autocomplete attributes
- Add clear service descriptions (what is included, what is excluded, duration)
- Ensure phone number, address, and hours are in plain text (not images)

**Weeks 11-12: Testing and Monitoring**
- Simulate agent navigation using Playwright or Puppeteer (automated browser scripts)
- Set up server log parsing to identify ChatGPT-User, OAI-SearchBot, PerplexityBot visits
- Track booking/contact form completion rate as baseline metric
- Test your key pages in ChatGPT: "Book an appointment at [your business]"
- Test in Perplexity: "Best [your service] in [your city]"
- Document baseline metrics for ongoing tracking

---

## Google AI Overviews Optimization

### How AI Overviews Work

Google AI Overviews (AIO) are AI-generated summaries that appear at the top of search results for many queries. They synthesize information from multiple sources and cite the pages they pull from. Being cited in an AI Overview is now a primary visibility goal.

AI Overviews do not simply extract from the highest-ranking page. They pull from multiple sources, often from pages that rank below position 5. This makes content quality and structure more important than traditional ranking position.

---

### How AI Overviews Select Sources

Ranking factors from Wellows 2026 study of 15,847 citations:

| Factor | Correlation | Selection Boost |
|--------|------------|-----------------|
| Multi-Modal Content (text + images + video) | r=0.92 | +156% to +317% |
| Verifiable Facts (cited claims, data points) | r=0.89 | +89% probability |
| Semantic Completeness (topic coverage) | r=0.87 | 4.2x higher |
| E-E-A-T Authority (expertise signals) | r=0.81 | 96% of citations |
| Entity Density (named entities per 1,000 words) | r=0.76 | 4.8x higher |
| Structured Data (schema markup) | n/a | +73% selection |
| Domain Authority (traditional DA/DR) | r=0.18 | Weak/negative correlation |

Key finding: 47% of citations came from pages below position 5 in traditional search results. The correlation between traditional ranking and AI Overview citation dropped to r=0.18. This means a page ranking at position 12 has nearly the same chance of being cited as a page ranking at position 2, provided the content quality factors above are strong.

---

### What Triggers AI Overviews

**Query characteristics:**
- 8+ word queries trigger AI Overviews 7x more often than shorter queries
- Question queries (how, what, why, best) trigger at 99.2% rate
- AI Overviews are expanding into commercial (18.57%) and transactional (13.94%) query types
- Highest category saturation: Science (25.96%), Computers/Electronics (17.92%)
- Local business queries: 35-46% now show AI summaries

**Implication for content strategy:** Target long-tail, question-based queries. These are the queries where AI Overviews appear most often and where citation opportunities are greatest.

---

### CTR Impact (Seer Interactive, Sep 2025)

**When AI Overviews appear but you are NOT cited:**
- Organic CTR drops from 1.76% to 0.61% (61% decline)
- Paid CTR drops from 19.7% to 6.34% (68% decline)

**When you ARE cited in the AI Overview:**
- 35% more organic clicks compared to standard organic results
- 91% more paid clicks when your ad appears alongside your AIO citation

**Strategic conclusion:** The goal is not to avoid AI Overviews. They are here permanently. The goal is to be the source cited in them. Being cited converts the AI Overview from a traffic killer into a traffic amplifier.

---

### 10 Tactics for AI Overview Citation

**1. Answer Block (First 10% of Page)**

Place a 40-70 word direct answer in the first 10% of your page content. Structure: [Direct Answer] [Who It Applies To] [Expected Outcome].

Example: "Dental implants cost between $3,000 and $6,000 per tooth in Canada, including the implant, abutment, and crown. This applies to patients with sufficient jawbone density who need to replace one or more missing teeth. Most patients can expect the implant to last 25+ years with proper care."

This block gives Google a clean, extractable answer for the AI Overview.

**2. Question-Based H2 Headings**

Write H2 headings that exactly match how people search. Use Google's "People Also Ask" and autocomplete suggestions as a source.

Examples:
- "How much do dental implants cost in Toronto?"
- "What is the recovery time for dental implants?"
- "Are dental implants covered by insurance in Ontario?"

Each H2 should be an exact or near-exact match to a real search query.

**3. Self-Contained Passages (134-167 Words)**

Each section under an H2 must stand alone as a complete, extractable unit. The AI Overview may pull only one section from your page. If that section references other parts of the page ("as mentioned above," "see the section below"), it becomes useless to the AI.

Target 134-167 words per passage. Include the question, the answer, supporting detail, and a data point or citation. Each passage is a miniature article.

**4. Semantic Completeness**

Cover the full topic, not just one angle. Use tools like Clearscope, Surfer SEO, or MarketMuse to score topic coverage. Target 8.5/10 or higher on semantic completeness.

AI Overviews prefer pages that comprehensively address a topic over pages that only cover one aspect. A page about "dental implant costs" should cover: procedure costs, insurance coverage, financing options, cost factors, comparison to alternatives, geographic price variation.

**5. Citation Hierarchy**

Not all citations are equal. The strength of your outbound citations affects whether Google trusts your content for AI Overviews.

- Tier 1 (+132% citation boost): Peer-reviewed studies, .gov sources, major institutions (WHO, CDC, Mayo Clinic)
- Tier 2 (+78% boost): Business publications (Bloomberg, Reuters, industry journals)
- Tier 3 (+52% boost): Expert quotes with credentials, named industry sources

Link to authoritative sources within your content. This signals that your claims are verifiable.

**6. Entity Density**

Target 15-20 named entities per 1,000 words. Named entities include: people, organizations, places, products, specific technologies, standards, regulations.

Use full names on first mention ("Dr. Sarah Chen, DDS, Toronto Dental Associates") before abbreviating. Link entities to their official websites or Wikipedia pages on first mention.

Pages with high entity density are 4.8x more likely to be cited in AI Overviews.

**7. Schema Markup**

Implement multiple complementary schema types on each page:

- `Article` schema with `author`, `datePublished`, `dateModified`
- `FAQPage` schema for question-answer pairs
- `Person` schema for authors with `jobTitle`, `knowsAbout`, `affiliation`
- `HowTo` schema for procedural content
- `LocalBusiness` schema on location pages

Combined schema markup increases AI Overview citation probability by 73%.

**8. Content Freshness**

Content updated within 30 days is 3.2x more likely to be cited. 23% of all featured content in AI Overviews is under 30 days old.

Add a visible "Last Updated: [Date]" on every page. Update the `dateModified` in Article schema when you make changes. Even minor updates (adding a new statistic, updating a price, adding a paragraph) count.

**9. Multi-Modal Content**

Pages with text, original images, and video see the highest citation rates.

- Original images with descriptive alt text: +156% citation boost
- 60-90 second video with VideoObject schema: +317% citation boost
- Infographics with structured alt text describing the data: strong boost
- Screenshots and diagrams count as original images

"Original" is key. Stock photos do not provide the same boost. Custom diagrams, charts, screenshots, and branded graphics perform significantly better.

**VideoObject schema example:**
```json
{
  "@type": "VideoObject",
  "name": "How Dental Implants Work",
  "description": "60-second explainer covering the dental implant procedure, recovery timeline, and costs in Toronto.",
  "thumbnailUrl": "https://yourdomain.com/images/implant-video-thumb.jpg",
  "uploadDate": "2026-01-15",
  "duration": "PT1M30S",
  "contentUrl": "https://yourdomain.com/videos/dental-implants.mp4"
}
```

**10. E-E-A-T Signals**

96% of AI Overview citations come from pages with strong Experience, Expertise, Authoritativeness, and Trustworthiness signals.

- Named authors with credentials on every article
- Author bio linking to LinkedIn, professional profiles, or institutional affiliations
- Person schema with `jobTitle`, `knowsAbout`, `worksFor`
- Cross-platform visibility (author is findable on multiple platforms)
- Institutional affiliation (university, hospital, recognized organization)
- Published date and update history visible on page

---

### Opt-Out Considerations

| Method | Effect | Recommendation |
|--------|--------|----------------|
| `<meta name="robots" content="nosnippet">` | Blocks AI Overviews AND featured snippets | Do not use. Loses 42.9% CTR from featured snippets. |
| `data-nosnippet` attribute on HTML elements | Blocks specific text sections from being used in snippets | Use selectively for proprietary content you do not want extracted. |
| `Google-Extended Disallow` in robots.txt | Blocks Gemini training only | Does NOT block AI Overviews. Use for training prevention. |
| Full opt-out from AI Overviews | Does not exist yet | UK CMA is pushing Google to build a clean opt-out mechanism. |

**Strategic recommendation:** Do NOT opt out. Being cited in AI Overviews earns 35% more organic clicks than standard results. The risk of losing citation opportunities outweighs the cost of content being summarized.

---

### AI Overview vs Featured Snippet

| Dimension | Featured Snippet | AI Overview |
|-----------|-----------------|-------------|
| Sources | Single page | Multiple sources |
| Ranking correlation | High (positions 1-5) | Low (r=0.18) |
| CTR when present | 42.9% | 0.61% organic (uncited) |
| CTR when cited | 42.9% | +35% above standard organic |
| Query types | Short, factual | Long-tail, complex |
| Content format | Single answer | Synthesized summary |
| Co-occurrence | Rarely shown together now | Replacing featured snippets |

AI Overviews are gradually replacing featured snippets for complex queries. Optimize for both, but prioritize AI Overview factors (multi-source authority, semantic completeness) over featured snippet factors (single concise answer).

---

### Measurement and Tracking

**Current limitations:**
- Google Search Console does NOT separate AI Overview impressions from standard organic impressions
- No native Google tool reports AI Overview citations
- Third-party tools are the only option for systematic tracking

**Tools for AI Overview tracking:**
- Semrush: AI Overview keyword tracking in Position Tracking tool
- Ahrefs: SERP features tracking includes AI Overviews
- SISTRIX: AI Overview visibility index
- BrightEdge: AI search share of voice reporting

**Manual tracking protocol (monthly):**
1. Select 30-100 target queries relevant to your business
2. Test each query across: Google (logged out, incognito), ChatGPT, Perplexity, Google AI Mode (if available), Gemini
3. Record for each query: Was your brand/site mentioned? Were you cited as a source? What position was the citation?
4. Calculate: (Your mentions) / (Total prompts tested) = AI visibility percentage
5. Track month-over-month to measure progress

**Key metrics to track:**
- AI visibility percentage (manual test)
- AI Overview citation count (Semrush/Ahrefs)
- Organic CTR changes on pages with AIO presence (GSC)
- AI bot traffic in server logs (ChatGPT-User, PerplexityBot, OAI-SearchBot)
- Booking/conversion rate from AI-referred traffic

---

### 90-Day AI Overview Optimization Sprint

**Days 1-30: Foundation**
- Audit top 20 pages for semantic completeness using Clearscope, Surfer SEO, or MarketMuse
- Add author Person schema to all content pages (jobTitle, knowsAbout, affiliation)
- Add one original image per article with descriptive alt text
- Build citation system: add outbound links to Tier 1 sources (peer-reviewed, .gov, institutions) in every article
- Implement Article + FAQPage schema on all content pages
- Add visible "Last Updated" dates to every page
- Rewrite introductions of top 10 pages with Answer Block structure (40-70 words)

**Days 31-60: Enhancement**
- Produce 60-90 second explainer videos for top 5 highest-traffic pages
- Add VideoObject schema to all video pages
- Map and increase entity density to 15-20 named entities per 1,000 words on all key pages
- Rewrite top 10 pages with self-contained 134-167 word passages under question-based H2s
- Add comparison tables to service and product pages
- Ensure every section can stand alone (remove all "as mentioned above" cross-references)

**Days 61-90: Authority and Measurement**
- Develop one original research piece (survey, case study, or data analysis) relevant to your industry
- Earn third-party mentions through PR, guest posts, or data citations
- Build cross-platform AI visibility: publish on LinkedIn, YouTube, podcast directories
- Set up monthly Semrush or Ahrefs AI Overview tracking for 50+ target keywords
- Establish manual testing protocol (30-100 queries across 4+ AI platforms)
- Run first manual AI visibility test and document baseline
- Set 90-day review meeting to analyze results and plan next sprint

---

## Combined AAIO + AI Overview Priority Matrix

For businesses implementing both simultaneously, prioritize by impact:

| Priority | Action | Benefits |
|----------|--------|----------|
| 1 | Schema markup (LocalBusiness, Service, Product, Article, FAQPage, Person) | Both AAIO (+agent comprehension) and AIO (+73% citation) |
| 2 | Semantic HTML, labels, autocomplete attributes | AAIO (agent navigation) and AIO (better crawling) |
| 3 | Answer Blocks and self-contained passages | AIO citation probability |
| 4 | robots.txt configuration | AAIO (training vs inference distinction) |
| 5 | Visible pricing in text and schema | AAIO (agent decision-making) and AIO (data extraction) |
| 6 | Multi-modal content (images, video, VideoObject schema) | AIO (+317% citation boost) |
| 7 | E-E-A-T signals and entity density | AIO (96% of citations) |
| 8 | llms.txt deployment | AAIO (LLM comprehension) |
| 9 | Content freshness and update cadence | AIO (3.2x citation rate) |
| 10 | Original research and third-party mentions | AIO (long-term authority) |

Schema and semantic HTML are the highest-leverage actions because they serve both optimization goals simultaneously.
