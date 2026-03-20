# CSO: Conversational Search Optimization - Multi-Turn AI Dialogue

## Reference Guide for the attainment-ai-search-visibility Skill

---

## 1. What CSO Is

Conversational Search Optimization (CSO) is the practice of structuring content and digital presence to perform well across multi-turn, dialogue-based AI interactions rather than single-query search events. It represents a fundamental shift in how people use AI systems to find information, evaluate vendors, and make decisions.

### How CSO Differs from Single-Query Search

Traditional search optimization (SEO) targets a single query. A user types "best project management software," Google returns a list of pages, the user clicks one. The interaction ends. The optimization goal is ranking for that one query.

Voice search optimization (VSO) extended this slightly into spoken single queries: "Hey Google, what's the best project management software?" Still a single query. Still a single response. The optimization goal is owning the featured snippet or voice answer for that one question.

CSO addresses an entirely different behavior. A user opens ChatGPT and starts a conversation:

- Turn 1: "I'm looking for a CRM for my dental practice. What should I consider?"
- Turn 2: "How does Salesforce compare to HubSpot for that use case?"
- Turn 3: "What would implementation look like for a 3-dentist practice?"
- Turn 4: "Are there any dental-specific CRM options I should know about?"
- Turn 5: "What do other dental practices say about Dentrix?"

This is a single buying intent expressed across five turns of dialogue. A business or brand that appears in Turn 1 but disappears from Turns 2-5 loses the conversion. A business that appears in Turn 3 but was absent in Turns 1-2 missed the framing of the entire conversation.

CSO asks: how do you build content and brand presence that persists across the entire conversation chain?

### How AI Maintains Session Context Across Turns

Modern AI systems maintain a context window that includes the entire conversation history within a session. When a user is on Turn 5 of a conversation, the AI "remembers" everything said in Turns 1-4. This means:

- The user's initial framing ("for my dental practice") persists as a lens for all subsequent answers
- Brands mentioned and evaluated in earlier turns can be referenced again
- The AI builds a contextual model of the user's needs that grows more specific with each turn
- Later answers are influenced by earlier answers in the same session

This context persistence is why early-turn appearance matters so much. Being cited in Turn 1 or Turn 2 means the brand is part of the established context for the rest of the conversation.

### The Shift from Search-as-Lookup to Search-as-Conversation

Traditional search is lookup behavior: the user knows roughly what they want and is looking for the location of the answer. Conversational search is exploration behavior: the user has a problem and is working through it with an AI interlocutor, often discovering what they want during the conversation itself.

This has major implications for content strategy. Lookup behavior is served by pages that directly answer specific queries. Exploratory conversation behavior is served by content that addresses an entire problem space, anticipates the natural progression of questions, and provides enough depth to be a useful source across multiple turns of a conversation.

### Why 44% of ChatGPT Citations Come from the First Third of Content

Research on ChatGPT citation behavior shows that 44% of citations reference content from the first third of an article or page. This finding reveals how AI systems process content for citation: they weight earlier content more heavily as representative of the document's core argument and authority.

This has a direct implication for CSO: the most citation-worthy content must appear early. Leading with secondary information, context-setting, or caveats before getting to substantive claims means the most valuable content is in the second or third third of the document, where it is significantly less likely to be cited.

The practical CSO rule: your most authoritative, specific, and citable claims go first.

---

## 2. Fanout Prompts

### What Fanout Prompts Are

Fanout prompts are the internal sub-queries that AI systems generate when decomposing a user's question. When a user asks a question, the AI does not process it as a single unit. It implicitly breaks the question into component questions that must be answered to compose a complete response.

This process is analogous to how a knowledgeable human expert would think through a complex question: they would mentally identify the sub-components of the question, retrieve information for each component, and then synthesize a complete answer.

Understanding fanout prompts is central to CSO because content must cover the entire fanout chain to be cited comprehensively rather than partially.

### Example Fanout Decomposition

**User query:** "What's the best CRM for a dental practice?"

**Internal fanout sub-queries the AI processes:**

- What features does a CRM for healthcare or dental specifically need?
- What CRM systems exist that serve dental practices or healthcare?
- How do those systems handle patient data and privacy (HIPAA considerations)?
- What do dental practice managers say about CRM tools they use?
- What does implementation look like for a small medical practice?
- What are the pricing tiers for CRM systems relevant to dental?
- What integrations do dental CRMs need (practice management software, billing)?
- Are there CRMs built specifically for dental versus general CRMs adapted for dental?

A piece of content that answers three of these eight sub-queries will be cited less completely than content that addresses six or seven of them. The AI synthesizes from whatever sources best cover the fanout chain.

### How to Identify Fanout Queries for Your Topic

For any topic, product, or service, map the fanout by thinking like an expert who has just been asked the most likely primary question about it.

**Step 1:** Write the primary user query (the question your ideal customer most likely asks AI when researching your category).

**Step 2:** Ask: to answer this question completely, what sub-questions must be addressed? Write them all out without filtering.

**Step 3:** Organize sub-questions into clusters: features/capabilities, comparisons, pricing, implementation, outcomes, risks, social proof, alternatives.

**Step 4:** Map your existing content against the sub-question clusters. Gaps in coverage are CSO optimization opportunities.

**Step 5:** Identify which sub-questions are most likely to appear in follow-up turns (these inform your Section 3 follow-up intent map).

### Creating Content That Covers the Entire Fanout Chain

Content that covers a full fanout chain is fundamentally different from content optimized for a single keyword. It is:

- Longer and more comprehensive by necessity (typically 1,500-4,000 words for complex topics)
- Organized in clearly navigable sections (each section addresses a fanout sub-query)
- Written to be extractable in fragments (each section can stand alone as an answer)
- Internally consistent (claims in one section do not contradict claims in another)

The goal is not to create the longest page on the internet. It is to create the most complete answer to the complete question. AI systems recognize completeness and reward it with more comprehensive citations.

---

## 3. Follow-Up Intent Mapping

### The 5 Common Follow-Up Patterns

Research on conversational AI search behavior reveals five recurring follow-up patterns that appear across nearly every topic domain. Mapping these for your product or service reveals the content gaps most likely to cause drop-off from your brand's presence in a conversation chain.

**Pattern 1: Deeper Exploration**
The user asks for more detail on something you mentioned. "Tell me more about [specific feature or claim]." "Can you elaborate on [concept]?"

This pattern requires that your content has depth beneath the top-line claims. If your content says "we offer advanced analytics" without explaining what that means in practice, the AI cannot elaborate on it in follow-up turns.

**Pattern 2: Comparison**
The user wants to evaluate your category or brand against alternatives. "How does [X] compare to [Y]?" "What's the difference between [approach A] and [approach B]?"

This pattern requires that your content addresses the competitive landscape honestly. Comparative content (when written fairly and factually) is among the most citation-worthy content AI systems use for comparison queries.

**Pattern 3: Cost and Pricing**
The user wants to understand financial commitment. "How much does [X] cost?" "What's the typical investment for [service]?"

If your content does not address pricing at all, the AI will source pricing information from elsewhere, potentially from outdated or inaccurate third-party sources. Publishing pricing context (ranges, factors that influence cost, what's included) is a CSO advantage.

**Pattern 4: Implementation**
The user wants to understand the path from decision to outcome. "How do I get started with [X]?" "What does implementation look like?" "How long does it take to see results?"

This pattern requires process content: step-by-step guides, timelines, what to expect, and what inputs are needed from the buyer. Implementation content is frequently cited in the consideration-to-decision phase of the buying journey.

**Pattern 5: Validation**
The user wants to stress-test the recommendation. "What are the downsides of [X]?" "Are there any complaints about [Y]?" "What do critics say?"

This is the most counterintuitive CSO requirement: content that honestly addresses limitations, trade-offs, and common criticisms is more likely to be cited in validation follow-up turns than content that only presents positive claims. AI systems synthesize balanced perspectives, and brands that proactively address downsides are seen as more trustworthy sources.

### How to Map Follow-Up Intents for Your Product or Service

For each of the five patterns, write 3-5 specific follow-up questions a user would ask after their initial query about your product or service.

Example for a B2B SaaS project management tool:

| Pattern | Example Follow-Up Questions |
|---|---|
| Deeper Exploration | "What does the reporting feature actually show?" "How does the automation work?" |
| Comparison | "How does it compare to Monday.com?" "What's the difference between this and Asana?" |
| Cost/Pricing | "How much does it cost per user?" "Is there a free tier?" "What do enterprise contracts look like?" |
| Implementation | "How long does onboarding take?" "Do we need an IT team to set this up?" "Can we migrate from Jira?" |
| Validation | "What are the most common complaints?" "What types of teams is this not a good fit for?" "Are there any hidden costs?" |

This map becomes the brief for content creation and gap analysis.

### Content Architecture That Satisfies All Follow-Up Patterns

A single comprehensive content piece should address all five patterns for its primary topic. The architecture:

- **Lead with the answer** (primary query response in first 200-300 words)
- **Features and capabilities section** (addresses Deeper Exploration follow-ups)
- **Comparison section** (addresses Comparison follow-ups, written fairly)
- **Pricing section** (addresses Cost follow-ups, even if only providing ranges)
- **Getting started section** (addresses Implementation follow-ups)
- **Honest limitations section** (addresses Validation follow-ups)
- **Social proof section** (addresses validation through third-party evidence)

---

## 4. Content Architecture for CSO

### Hub Pages vs. Topic Pages

**Hub pages** are high-level pages that cover a broad topic category. They serve as the entry point for AI systems synthesizing broad queries ("what is [topic]?" or "how does [category] work?"). Hub pages link to topic pages for depth.

**Topic pages** cover specific subtopics with enough depth to satisfy fanout sub-queries and follow-up intent patterns. They are the pages most likely to be cited in specific follow-up turns of a conversation.

For CSO, the relationship between hub and topic pages matters. AI systems navigating a website's content (when browsing is enabled) follow internal links. A well-linked content architecture guides AI from the broad topic through to the specific details, increasing the surface area available for citation at every turn of a user's conversation.

### Comprehensive Topic Coverage vs. Narrow Keyword Targeting

Traditional SEO often encourages narrow, keyword-specific pages: one page per keyword, optimized tightly for that query. CSO pushes against this model for topics where the user's need is complex.

A narrow keyword page can rank for one query but cannot sustain a multi-turn conversation. A comprehensive topic page covers the entire problem space and can be cited in Turn 1, Turn 2, and Turn 4 of the same conversation.

The practical balance: narrow keyword pages remain useful for high-volume, simple-intent queries where a direct answer is all that is needed. Comprehensive topic pages are the priority for complex buying decisions, comparative research, and evaluative queries where the user is working through a decision.

### Conversational Completeness

Conversational completeness is the degree to which a single piece of content can sustain a multi-turn conversation without the AI needing to source from elsewhere. A conversationally complete piece of content:

- Answers the primary question clearly at the start
- Addresses all major fanout sub-queries within the document
- Provides enough depth on each sub-topic that follow-up questions can be answered from the same source
- Includes honest comparative and validation content
- Ends with clear next steps or implementation guidance

Conversational completeness does not mean writing a 10,000-word document on every topic. It means writing enough to own the conversation for the specific buyer intent the content targets. A simple informational topic may achieve conversational completeness in 800 words. A complex B2B purchase decision may require 3,500 words.

### Internal Linking as Conversation Flow Guidance

When an AI system with browsing capabilities explores a website, internal links are the navigation pathways. Strategic internal linking creates a guided content journey that mirrors the natural progression of a buyer's conversation.

Example linking architecture for a CSO-optimized website:

- Hub page on "dental practice management" links to topic pages on each subtopic
- Topic page on "dental CRM" links to comparison page, pricing page, and implementation guide
- Comparison page links back to the hub and to specific feature detail pages
- Implementation guide links to customer success stories and onboarding resources

This architecture means that wherever an AI system enters the site's content, it can navigate to progressively more specific information, covering more fanout sub-queries and more follow-up intent patterns with each hop.

### FAQ Structures Optimized for Multi-Turn Context

FAQ sections are high-value CSO elements because they mirror the question-answer structure of conversational AI responses. AI systems extract FAQ content and use it to answer follow-up queries directly.

CSO-optimized FAQ design:

- Each question is written as the user would actually ask it in conversation (not as a corporate talking point)
- Answers are complete in themselves (can be extracted and cited without the surrounding context)
- Questions are ordered to mirror the natural progression of follow-up queries (not organized by category for human browsing convenience)
- Include questions that address the Validation pattern (common concerns, limitations, "is this right for me" questions)

---

## 5. Platform Differences for CSO

### ChatGPT: Web Browsing Per Turn with Context Management

When ChatGPT has web browsing enabled, it can search the live web for each turn of the conversation. However, it manages context across turns: information retrieved in Turn 1 can inform responses in Turn 3 without re-searching.

ChatGPT citation patterns for CSO:

- Citations in early turns tend to come from authoritative overview sources (comprehensive pages, industry reports, well-known publications)
- Citations in later turns tend to come from more specific sources (comparison pages, pricing pages, technical documentation)
- If a single website appears as a source in Turn 1, it is more likely to be referenced again in later turns because it is already in the conversation's context

For ChatGPT CSO optimization: ensure your most comprehensive hub page ranks for primary queries (Turn 1) and your specific topic pages are internally linked and discoverable from the hub (later turns).

### Claude: Training Data Primary with Context Accumulation

Claude (Anthropic's AI) in its default mode does not browse the web per turn. It draws primarily from training data. This means content that was indexed and widely linked before Claude's training cutoff has an advantage.

For Claude CSO optimization: long-form, authoritative content published on high-domain-authority sites and widely linked from other sources is the priority. Fresh content published after a training cutoff has zero Claude visibility until the next model update.

Context accumulation in Claude: as a conversation progresses, Claude builds an increasingly specific model of the user's needs from the conversation itself. It uses this model to select the most relevant information from its training data for each subsequent turn.

### Gemini: Google Integration with Real-Time Data Across Turns

Gemini has native Google Search integration and can pull real-time data into each turn of a conversation. It benefits from Google's full indexing capabilities and can surface very recent content.

Gemini CSO considerations:

- Traditional SEO factors (domain authority, page authority, backlinks) influence Gemini's content selection more than they influence ChatGPT or Claude
- Gemini's multi-turn context leverages Google's Knowledge Graph for entity consistency across turns
- GBP data can appear in Gemini's local-intent turns even within a broader B2B research conversation

For Gemini CSO optimization: strong traditional SEO foundation plus structured data (schema markup) is the highest leverage investment.

### Perplexity: Sources Refreshed Per Response with Threading Model

Perplexity searches the web freshly for each response in a conversation. This means citations can change between turns as different source pages rank better for each specific sub-query.

Perplexity CSO considerations:

- Perplexity shows its sources to users, making citation tracking straightforward
- A source that appears in Turn 1 is not automatically favored in Turn 2 (each turn is a fresh search)
- This means comprehensive, individually strong pages matter more than internal linking architecture for Perplexity
- Perplexity tends to favor Reddit, recent news, and high-authority industry publications

For Perplexity CSO optimization: each topic page must stand alone as a strong source, rather than relying on a hub-and-spoke architecture. Individual page authority and content completeness are the primary levers.

### Optimization Priorities by Platform

| Platform | Turn 1 Priority | Later Turns Priority | Key CSO Lever |
|---|---|---|---|
| ChatGPT | Hub page authority | Internal links to specific pages | Comprehensive hub + linked depth |
| Claude | Training data recency (within cutoff) | Context window management | Long-form authority content, wide backlinks |
| Gemini | Traditional SEO signals | Schema markup clarity | GBP + schema + SEO foundation |
| Perplexity | Individual page completeness | Individual page completeness | Standalone page authority per topic |

---

## 6. Dialogue-Flow Content Design

### Structuring Content as a Conversation

CSO-optimized content is structured to work as both a standalone article and a turn-by-turn dialogue response. The key is writing in a format where any section can be extracted and read independently, while the overall document flows from primary answer through progressive depth.

**The dialogue-flow structure:**

**Layer 1: Primary answer (first 200-300 words)**
Directly answers the most likely primary query. This is the Turn 1 citation zone. It should be complete enough to stand alone as an answer to the broad question.

**Layer 2: Core expansion (next 600-1,000 words)**
Expands the primary answer with the most important details: key features or capabilities, the most significant distinctions, and the primary value proposition. This is the Turn 2-3 citation zone for deeper exploration follow-ups.

**Layer 3: Comparative and contextual content (next 400-800 words)**
Addresses how this compares to alternatives, when this approach is and is not appropriate, and what the range of options looks like. This is the Turn 3-4 citation zone for comparison and validation follow-ups.

**Layer 4: Practical and procedural content (next 400-600 words)**
Covers implementation, getting started, pricing context, and timelines. This is the Turn 4-5 citation zone for implementation and cost follow-ups.

**Layer 5: Social proof and validation (final 200-400 words)**
Specific outcomes, use cases, and honest limitations. This closes the conversation with credibility.

### The Question Progression Structure

An alternative to the layered approach is the question-progression structure, where the entire piece is organized as an explicit Q&A that mirrors a natural conversation sequence.

Each H2 heading is written as the next natural question a user would ask. The content beneath each heading answers that question completely. This structure is highly AI-readable because it explicitly signals which content answers which question type.

Example question progression for a dental practice management software page:

- H2: What features should dental practice management software include?
- H2: How do the leading dental practice management systems compare?
- H2: What does implementation look like for a typical dental practice?
- H2: How much does dental practice management software cost?
- H2: What should you know before making a final decision?

Each section is complete enough to be extracted as a standalone response to its corresponding turn of a user's conversation.

### Anticipating the Conversation 3 Turns Ahead

The discipline of CSO content creation is thinking 3 turns ahead of the initial query. Before writing, ask:

- What will the user ask after reading my initial answer?
- What will they ask after that?
- And after that?

Map these turn sequences for your 3-5 most important topics. Then ensure your content answers every question in those sequences, either within a single page or through internal linking to pages that do.

Businesses that answer Turn 1 through Turn 5 within their owned content are far less likely to lose the conversation to a competitor who only answers Turn 1.

---

## 7. B2B Complex Purchase Decisions

### Why CSO Dominates Complex B2B Buying Journeys

Complex B2B purchases (software platforms, professional services, consulting engagements, enterprise solutions) involve extended evaluation periods, multiple stakeholders, and high switching costs. Buyers do not make these decisions after a single search query. They research over days or weeks, often returning to AI tools repeatedly across multiple sessions.

This makes CSO the most relevant optimization strategy for B2B companies with average contract values above approximately $10,000 annually. The buyer is not doing a single lookup. They are having an ongoing conversation with AI tools that continues across sessions.

### The Typical AI-Assisted Vendor Evaluation Conversation

B2B vendor evaluation through AI follows a recognizable arc:

**Session 1 (Awareness and Category Education):**
- "What should I look for in [category]?"
- "What are the main options in [category]?"
- "How does [category] work?"

**Session 2 (Shortlisting):**
- "Compare [Vendor A] vs [Vendor B] for [use case]"
- "What do users say about [Vendor A]?"
- "Is [Vendor A] worth the cost?"

**Session 3 (Evaluation):**
- "What does implementation look like with [Vendor A]?"
- "What are the most common complaints about [Vendor A]?"
- "How does [Vendor A] handle [specific concern like security/compliance]?"

**Session 4 (Validation and Decision):**
- "What questions should I ask [Vendor A] before signing?"
- "What should I negotiate in a [Vendor A] contract?"
- "What do [Vendor A] customers say after 12 months?"

A B2B company optimized for CSO has content that appears meaningfully in all four sessions across the entire evaluation arc.

### How Buyers Use ChatGPT Across Multiple Sessions

ChatGPT does not maintain memory between sessions by default (unless the Memory feature is enabled). This means each new session starts fresh, without the context of prior conversations.

The implication for CSO: your content must perform well in early-turn, category-level queries (Session 1 behavior) and in late-turn, brand-specific queries (Session 3-4 behavior). You cannot assume the buyer's AI has already established a favorable context about your brand from a prior session.

This is why breadth of content coverage matters for B2B CSO. A single comprehensive page is not enough. You need a content architecture that covers the full evaluation arc because each new session may enter at any point in that arc.

### Optimizing for the Entire Buyer's Journey as a Conversation

**Awareness content (Session 1 targets):**
- Category education guides: "what is [category], how does it work, who needs it"
- "How to evaluate [category]" guides: criteria, checklist, what matters most
- Industry-specific application guides: "how [category] works for [specific industry]"

**Consideration content (Session 2 targets):**
- Comparison pages: honest, factual comparisons with named competitors
- Use case pages: "[Product] for [specific use case or industry]"
- Review response content: appear in AI synthesis of review platforms

**Evaluation content (Session 3 targets):**
- Implementation and onboarding guides
- Security, compliance, and data handling documentation
- Technical specification and integration documentation
- Customer success stories with specific, measurable outcomes

**Decision content (Session 4 targets):**
- Pricing and packaging pages with honest context
- FAQ on contract terms, SLAs, and support
- Reference customer availability and case study access

---

## 8. The 44% First-Third Rule

### The Finding

Analysis of ChatGPT citation behavior shows that 44% of citations reference material from the first third of a content piece. This disproportionate weighting of early content has significant implications for how CSO-optimized content is structured.

The finding reflects a characteristic of how large language models process and weight content. Earlier content in a document is processed in a position where it can influence the model's interpretation of everything that follows. It establishes the document's framing, authority signals, and primary claims. Later content is processed as elaboration, qualification, or secondary material.

### Implications for Content Structure

The traditional journalistic and academic writing structures (inverted pyramid and linear argument respectively) both have strengths for different contexts. For CSO, the inverted pyramid approach (most important information first, supporting detail later) is strongly favored.

**What this means in practice:**

- Your strongest claim or most authoritative data point goes in the opening paragraph, not as the conclusion
- Specific numbers, statistics, and named outcomes appear in the first third of the content, not buried in the body
- The most distinctive and citable aspects of your product or service are stated explicitly in the first section
- Social proof references (notable customers, specific results) appear early, not as an afterthought

**What to move out of the first third:**

- Background and context that the reader likely already knows
- Broad category definitions before getting to your specific offering
- Caveats, limitations, and "but first, let's discuss..." setup content
- Long introductory narratives before the substantive content begins

### Leading with Citation-Worthy Content

A useful test for first-third content: would an AI system quote this sentence when recommending your product or service to a user? If the answer is no, it should not be in the first third of your content.

Citation-worthy content characteristics:

- Specific and concrete ("reduces time-to-hire by 40% on average" not "improves hiring efficiency")
- Attributable ("according to [source]" or "in our analysis of [X] customers")
- Directly relevant to the primary query the page targets
- Distinctive (says something that differentiates from generic category claims)

### The Inverted Pyramid for AI Visibility

The inverted pyramid structure places the most important information at the top and the least important at the bottom. For CSO, adapt this as:

- **Top of pyramid (first third):** Primary answer, key claims, specific outcomes, most distinctive differentiators
- **Middle (second third):** Supporting detail, comparisons, how it works, implementation context
- **Bottom (final third):** Additional context, edge cases, next steps, calls to action

This structure serves both AI citation behavior (front-loading the most citable content) and human reading behavior (most people do not read to the end of long content).

---

## 9. Schema for Conversational Content

### FAQPage Schema for Multi-Turn Optimization

FAQPage schema marks up question-and-answer content in a machine-readable format that AI systems and search engines can extract directly. It is the most important schema type for CSO because it explicitly signals the question-answer structure that maps to conversational turns.

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What features should I look for in a dental practice CRM?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A dental practice CRM should include patient communication tools (appointment reminders, recall messaging), integration with practice management software like Dentrix or Eaglesoft, HIPAA-compliant data handling, treatment plan tracking, and referral management. The most important feature for most practices is automated recall and reactivation messaging, which directly impacts schedule fill rates."
      }
    },
    {
      "@type": "Question",
      "name": "How much does a dental CRM cost?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Dental CRM pricing typically ranges from $200-600 per month for single-location practices. Enterprise solutions for DSOs (Dental Service Organizations) with multiple locations are typically priced by location or seat count, ranging from $100-300 per location per month. Most systems offer monthly and annual billing, with annual contracts typically offering 10-20% savings."
      }
    }
  ]
}
```

Write FAQ schema questions to mirror the natural language of follow-up queries, not the formal language of a product documentation page.

### HowTo Schema for Process-Oriented Conversations

When a user's conversation turns to implementation or process ("how do I get started?"), HowTo schema provides a directly extractable, structured answer.

HowTo schema includes: name (the overall process), description, totalTime, supply (inputs needed), and step array. Each step has a name and text. This structure maps directly to the question "how does this work step by step?" and can be extracted and presented cleanly in AI responses.

### DefinedTerm for Concept Definitions

When content defines category-specific or technical terms, DefinedTerm schema marks those definitions as extractable. This is valuable for Turn 1 queries that are educational in nature ("what is [term]?") and for conversations where the user is learning the category vocabulary.

### Speakable Schema Adapted for Text-Based AI

Speakable schema was originally designed for voice search, marking which sections of content are most appropriate for text-to-speech reading. For text-based AI conversations, the same schema can signal to AI systems which sections are the most condensed, citable summaries of the content's key points.

Applying Speakable markup to your page's primary answer paragraph and your key claim sections signals to AI systems: "this is the extract-ready summary of this content." While Speakable schema is not universally supported across all AI systems, it is a low-cost, potentially high-value signal for systems that honor it.

---

## 10. Measurement

### Auditing Brand Appearance Across Multi-Turn Conversations

The core measurement methodology for CSO is the conversation audit: a structured series of multi-turn prompts designed to test where and how a brand appears across a simulated buyer conversation.

Unlike traditional rank tracking (which produces a position number for a single query), conversation auditing produces a presence map: a record of which turns a brand appeared in, what language was used, and what competing brands or sources also appeared.

### Building a Conversation Audit Methodology

**Step 1: Define your primary query.**
This is the Turn 1 question your ideal buyer most likely asks when beginning research on your category. It should be phrased naturally, without your brand name.

**Step 2: Define 3-5 natural follow-up queries.**
Based on the 5 follow-up intent patterns (deeper exploration, comparison, pricing, implementation, validation), write the 3-5 most likely follow-up questions for your specific product or service. These become Turns 2 through 5-6 of your audit conversation.

**Step 3: Run the conversation.**
Open a fresh session (no prior context) in each AI platform. Ask Turn 1. Record the response: is your brand mentioned? At what point? What language is used? Then ask Turn 2 in the same session. Record. Continue through all turns.

**Step 4: Record findings in a tracking document.**

| Turn | Query | Platform | Brand Mentioned | Position | Language Used | Competing Brands Mentioned |
|---|---|---|---|---|---|---|
| 1 | Primary query | ChatGPT | Yes | 2nd | "known for ease of use" | Competitor A, Competitor B |
| 2 | Deeper exploration | ChatGPT | No | N/A | N/A | Competitor A, Competitor C |
| 3 | Comparison | ChatGPT | Yes | 1st | "strongest for small teams" | Competitor A |

**Step 5: Identify gaps.**
Turns where your brand is absent are content gaps. The follow-up intent pattern that turn represents is what the missing content needs to address.

### Monthly CSO Audit Cadence

Run a full conversation audit monthly for your top 3-5 buying journey entry points. Each entry point is a different Turn 1 primary query representing a different buyer type or use case.

Monthly cadence serves two purposes: tracking improvement from content investments (does a new comparison page lead to better Turn 3 presence next month?) and detecting new competitive incursions (has a competitor's new content started appearing in turns where you previously dominated?).

### Tools for CSO Tracking

No purpose-built CSO tracking tool currently exists that fully automates conversation auditing across platforms. The methodology above is a manual process. Tools that provide partial support:

- **Perplexity audit:** Perplexity shows its citations inline, making it the most transparent platform for tracking which specific pages are being cited in which turns
- **ChatGPT browsing mode:** When browsing is enabled, follow-up queries in the same session sometimes indicate which sources informed the response
- **Manual prompt testing:** The core methodology for all platforms
- **Brand mention monitoring (Brandwatch, Mention.com):** For tracking brand mentions on Reddit and other platforms that feed AI citations, though this is a proxy measure not a direct CSO measure

---

## 11. Implementation Sprint: 6-Week CSO Content Architecture Plan

### Week 1: Conversation Audit and Gap Mapping

Run a full conversation audit for your top 3 buyer entry points across ChatGPT, Perplexity, and Gemini. Document results in the tracking template from Section 10.

Map your existing content inventory against the fanout sub-queries identified in Section 2. For each fanout sub-query, record whether you have content that addresses it, whether that content is comprehensive or thin, and whether it appears in the first third of the relevant page.

Identify the top 5 content gaps: the turns and intent patterns where your brand is most consistently absent. These become your content creation priorities.

### Week 2: Content Architecture Design

Design your hub-and-spoke content architecture based on the gap mapping from Week 1. Define:

- Which page is the hub for each major buyer journey entry point
- Which topic pages need to be created or substantially expanded
- The internal linking structure that connects hub to topic pages and topic pages to each other
- The question-progression heading structure for each page to be created or revised

Write content briefs for the top 5 priority pieces identified in Week 1.

### Week 3-4: Content Creation

Write the priority content pieces from the Week 2 briefs. For each piece:

- Apply the inverted pyramid structure (most citable content in first third)
- Cover the full fanout chain for the piece's primary query
- Address all 5 follow-up intent patterns relevant to the topic
- Include honest comparison and validation content
- Write at conversational completeness depth for the target buyer complexity

Update internal linking from existing pages to newly created pages.

### Week 5: Schema Implementation

Add FAQPage schema to all pages with explicit Q&A sections. Add HowTo schema to any process or implementation pages. Add DefinedTerm schema to category education and glossary content. Review and update LocalBusiness or Organization schema on hub pages for entity clarity.

Verify schema implementation using Google's Rich Results Test for each updated page.

### Week 6: Re-Audit and Baseline Reset

Re-run the conversation audit from Week 1 using the same queries and platforms. Compare results against the Week 1 baseline. Document any changes in brand presence, turn position, and language used.

This re-audit establishes a new baseline that reflects the impact of the content and schema work. It also reveals whether the priority gaps from Week 1 have been addressed or require additional content work.

Set monthly re-audit schedule. Assign ownership of the monthly audit process. Create a running change log that tracks content investments and corresponding audit outcome changes month over month.

### Ongoing Optimization (Months 2-6)

- Monthly conversation audit across all platforms and entry points
- Quarterly content refresh: update statistics, examples, and comparative claims
- Monitor competitor appearance in your audit turns and respond with targeted content
- Track review platform sentiment (feeds AI synthesis quality) alongside CSO audit
- Add new buyer entry points to the audit scope as product or market scope expands

---

*Reference guide for the attainment-ai-search-visibility skill. Last updated: 2026.*
