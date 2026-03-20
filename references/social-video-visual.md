# Social Search, Video SEO, and Visual Search: Implementation Reference

> Actionable implementation knowledge for Social Search Optimization, Video SEO, and Visual Search Optimization. Every section includes specifications, code, data, and measurement guidance.

---

## Social Search Optimization

Social platforms are now search engines. 51% of Gen Z prefer TikTok over Google for search (Google's own internal data, 2024). 40% of Gen Z prefer Instagram or TikTok over Google for product discovery. Social search is not a supplement to Google. It is a parallel discovery surface that often acts as the first touchpoint.

---

### TikTok Search

#### Algorithm Ranking Factors (In Order of Weight)

1. **User interactions:** Completions, replays, shares, comments, likes. Completion rate is the single most important signal. A 15-second video watched to the end outranks a 60-second video abandoned at 50%.
2. **Video information:** Captions, hashtags, sounds, effects. TikTok indexes the audio track. Speaking keywords out loud matters.
3. **Account authority:** Consistent posting cadence, niche focus, engagement history across recent videos.
4. **Device and account settings:** Language preference, country setting, device type. These filter distribution, not rank within it.

#### Optimization Tactics

**Audio optimization (unique to TikTok):**
- Say the target keyword within the first 3 seconds of audio. TikTok transcribes and indexes audio content.
- Repeat the keyword naturally 2 to 3 times throughout the video.
- Trending sounds and audio clips get 2 to 3x more initial distribution from the algorithm.
- Original audio with keyword density also indexes well for search.

**Caption optimization:**
- Use the primary keyword in caption text. This is the single strongest text-based discovery signal.
- Front-load the keyword in the first line of the caption.
- Write 100 to 300 character captions. Shorter captions get better completion rates; longer captions provide more keyword surface.
- Include a CTA question to drive comments (comments boost ranking).

**Hashtag strategy:**
- 3 to 5 keyword-relevant hashtags per video.
- Use search-intent hashtags, NOT trending entertainment hashtags.
- WRONG: #fyp #viral #foryoupage (these are noise, not search signals)
- RIGHT: #homegymsetup #proteinpowderreview #mealprep2026
- Mix one broad category tag, two mid-volume niche tags, and one to two specific long-tail tags.

**Completion rate optimization:**
- Completion rate is the #1 ranking signal. Keep videos tight.
- Hook in first 1 to 2 seconds (pattern interrupt, question, or bold claim).
- Optimal lengths for search: 30 to 60 seconds for tutorials, 15 to 30 seconds for quick answers.
- Loop structure: end feeds naturally into beginning, encouraging rewatches.
- Add text overlays that require rewatching to fully read.

**Cross-platform discovery:**
- TikTok search results now appear directly in Google Search.
- A TikTok video ranking for "best protein powder 2026" can surface in Google SERP.
- This means TikTok SEO delivers Google visibility as a secondary benefit.

---

### Instagram Search

#### How Instagram Search Works

Instagram search returns four content types: Accounts, Hashtags, Places, and Reels. The algorithm weighs these signals for ranking:

1. **Text match:** Query matching against username, name, bio, caption text, hashtags, and location.
2. **User activity:** Content the searcher has interacted with previously.
3. **Popularity signals:** Engagement velocity (likes, comments, shares, saves within first 30 minutes), follower count, post frequency.
4. **Content relevance:** How well the content matches the inferred search intent.

#### Optimization Tactics

**Caption keyword strategy:**
- Caption keywords are now the primary discovery mechanism. Hashtag-only strategies are outdated.
- Place the primary keyword in the first line of the caption (Instagram truncates after 125 characters in feed).
- Write captions that mirror the exact phrases people search: "how to build a home gym on a budget" not "gym vibes."
- 150 to 300 word captions perform best for Explore and search distribution.

**Alt text optimization:**
- Instagram indexes alt text for Explore, search, and Reels ranking.
- Add custom alt text via Advanced Settings on every post.
- Format: [Primary subject] [action or description] [context] [keyword].
- Example: "Woman performing barbell hip thrust in home gym with resistance bands."
- Do NOT leave alt text empty. Instagram auto-generates alt text, but it is generic and misses keywords.

**Reels search optimization:**
- Instagram Reels appear directly in Google Search results (video carousel).
- Reels captions should mirror Google search queries verbatim: "how to meal prep for weight loss" not "meal prep tips."
- First 3 seconds: state the topic clearly (Instagram indexes audio).
- Use keyword-rich on-screen text overlays (Instagram OCR reads them).
- 30 to 90 second Reels get the best search distribution.

**Account-level signals:**
- Account must be set to Public. Private accounts are excluded from search indexing.
- Consistent niche focus builds account authority (posting about fitness daily > random topics).
- Bio should include primary keywords naturally: "Home gym equipment reviews and workout guides."
- Username and display name are indexed. Include a keyword if natural: "gymguide.marcus" > "marcus2847."

**Location tags:**
- Tag location on every relevant post for local discoverability.
- Location pages are browsable and searchable.
- For local businesses: use your exact business location, not the city.

**Hashtags (still useful, declining weight):**
- 5 to 10 hashtags per post (down from the old 30-hashtag strategy).
- Place in caption body or first comment.
- Use a mix: 2 to 3 broad (500K+ posts), 3 to 4 mid (50K to 500K), 2 to 3 niche (under 50K).
- Research hashtag post counts before using. Oversaturated tags bury your content.

---

### Pinterest Search

Pinterest is a visual search engine with a shopping-intent user base. 90% of Pinterest users are in a shopping or planning mindset. 83% of weekly Pinners have made a purchase based on content they saw on Pinterest.

#### Ranking Factors

1. **Pin quality:** Save rate, click-through rate, close-up views. Saves are the #1 engagement signal.
2. **Domain quality:** Overall engagement history from pins linked to your domain. Sites with consistently high-performing pins rank higher.
3. **Keyword relevance:** Pin description, pin title, board name, board description all contribute to keyword matching.
4. **Image quality and format:** 2:3 vertical ratio, minimum 1000x1500px, high resolution, clear subject.
5. **Freshness:** New pins are distributed more aggressively than repins of existing content.

#### Optimization Tactics

**Image specifications:**
- 2:3 vertical aspect ratio (1000x1500px minimum). This is non-negotiable. Landscape or square images are penalized in feed distribution.
- High resolution, bright lighting, clear subject.
- Light text overlays help Pinterest OCR understand pin semantics and improve search matching.
- Use branded templates for recognition and consistency.

**Pin title optimization:**
- Maximum 100 characters. Keyword-first structure.
- WRONG: "My Favorite Things for the Kitchen"
- RIGHT: "Kitchen Organization Ideas: 10 Budget-Friendly Storage Solutions"

**Pin description optimization:**
- 200 to 300 characters with natural keyword use.
- Include secondary keywords and related terms.
- Write for humans first, search engine second. Descriptions that read like keyword lists get flagged.

**Board optimization:**
- Board names should be searchable keywords, NOT creative names.
- WRONG: "My Happy Place" or "Inspo Board"
- RIGHT: "Home Gym Setup Ideas" or "Healthy Meal Prep Recipes"
- Board descriptions: 200 to 500 characters with keyword variations.
- Organize pins into 10 to 15 focused boards per account.

**Rich Pins:**
- Enable Rich Pins via Open Graph tags or Schema.org markup on your website.
- Three types: Product (price, availability, purchase link), Article (headline, author, description), Recipe (ingredients, cook time, servings).
- Product Rich Pins auto-update pricing and availability from your site.
- Rich Pins get higher distribution and trust signals.

**Posting cadence:**
- 5 to 15 fresh pins per day (new images, not repins).
- Pin consistently rather than in bursts.
- Schedule pins for peak times: 8 to 11 PM and 2 to 4 PM (user's local timezone).

---

### Reddit as a Search Surface

Reddit has become the most influential platform for AI-generated answers and is reshaping how people validate purchase and service decisions.

#### Key Statistics

- Reddit is the #1 most cited source by AI models: 40.1% of all AI citations (Profound, 2025).
- 80 million people use Reddit search weekly.
- Reddit content appears in Google AI Overviews (2.3% of citations) and Perplexity (6.3%).
- Perplexity's Reddit citations jumped 40x between February and April 2025.
- Google ranks Reddit threads prominently for "best [product]" and "[product] reddit" queries.
- Reddit has exclusive data licensing deals with Google and OpenAI for AI training data.

#### Strategy: Genuine Participation, Not Marketing

Reddit is hostile to self-promotion. Accounts that only post about their own products get banned and downvoted into invisibility.

**What works:**
- Genuine participation in relevant subreddits over months before any mention of your product.
- Answering questions thoroughly with first-hand experience.
- Including your product as ONE option among several, with honest pros and cons.
- Building comment karma and post history before any brand-related activity.
- Contributing original research, data, or guides that the community values.

**What gets you banned or shadowbanned:**
- Creating accounts solely to promote your brand.
- Posting links to your site without context or value.
- Using multiple accounts to upvote your own content.
- Astroturfing (fake grassroots enthusiasm).
- Ignoring subreddit-specific rules.

**Subreddit selection:**
- Find subreddits where your ICP already asks questions.
- Check subreddit rules before participating (many ban promotional content outright).
- Prioritize subreddits with 50K to 500K members. Mega-subreddits bury content; tiny subreddits have no reach.
- Monitor with Reddit search or third-party tools for brand mentions and relevant questions.

**Long-term play:**
- A single highly-upvoted Reddit comment mentioning your product can be cited by ChatGPT, Perplexity, and Google AI Overviews for months.
- Reddit threads age well. A 2-year-old thread about "best CRM for startups" still surfaces in AI answers.
- The ROI is asymmetric: one authentic, helpful comment can generate more AI citations than a $10K content marketing campaign.

---

## Video SEO Implementation

### YouTube Ranking Factors (2026, Ordered by Impact)

1. **Click-through rate (CTR) from impressions.** YouTube measures how often viewers click your thumbnail when it appears. Higher CTR = more distribution.
2. **Watch time and audience retention.** Total minutes watched and the retention curve shape. Videos where viewers watch 70%+ get significantly more distribution.
3. **Engagement signals.** Likes, comments, shares, subscribe actions, playlist additions. Comments with keywords may reinforce topical relevance.
4. **Upload frequency and consistency.** Channels that publish on a predictable schedule receive algorithmic preference. Weekly minimum recommended.
5. **Session starts.** Videos that begin a viewing session (user opens YouTube and clicks your video first) are heavily rewarded.
6. **Video information.** Title, description, tags, transcript, chapters. These are the text signals YouTube uses for search matching.
7. **Channel authority.** Subscriber count, total channel views, niche consistency, channel age.

---

### Title Optimization

| Attribute | Specification |
|-----------|---------------|
| Primary keyword placement | First 5 words |
| Optimal length | 50 to 60 characters (fully visible in search results) |
| Search query match | Include the exact search query as naturally as possible |
| Number usage | Numbers increase CTR: "7 Ways...", "2026 Guide", "Top 5..." |
| Parenthetical modifiers | Boost CTR: "(Step-by-Step)", "(2026)", "(Free Template)", "(Full Guide)" |

**Title formulas that perform:**
- "How to [Action] in [Timeframe] ([Modifier])"
- "[Number] [Topic] Tips That Actually Work ([Year])"
- "[Topic] for Beginners: [Specific Outcome] (Step-by-Step)"
- "I Tried [Product/Method] for [Duration]. Here's What Happened."

**Anti-patterns:**
- All-caps titles (reads as clickbait, reduces trust)
- Misleading titles (high CTR but low retention = algorithmic penalty)
- Titles without the target keyword (invisible to search)
- Titles over 70 characters (truncated in search, key info cut off)

---

### Description Optimization

**Structure:**

```
[First 100 words: Primary keyword + direct answer to the search query. This section
appears in search previews and is the most heavily weighted text for ranking. Write it
as a standalone summary.]

[Middle section: 200 to 400 additional words covering secondary keywords, context,
and supporting information. YouTube indexes the full description.]

[Timestamps / Chapters section: See Chapter Timestamps below]

[Links section: Website, social profiles, related videos, resources mentioned]

[Hashtags: 3 to 5 keyword-relevant hashtags at the bottom]
```

**Key rules:**
- First 100 words must include the primary keyword and directly answer the search query.
- Total description: minimum 200 to 500 words.
- Include secondary and related keywords naturally throughout.
- YouTube indexes the full description text for search matching.
- Link to your website and related resources (drives referral traffic).
- Never leave the description empty or use only a single sentence.

---

### VideoObject Schema

Embed this structured data on any page that hosts or embeds a YouTube video. This enables Google rich results (video carousel, key moments).

```json
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Video Title with Primary Keywords",
  "description": "Description with primary keyword in first sentence. 100 to 300 characters.",
  "thumbnailUrl": "https://yourdomain.com/thumbnail.jpg",
  "uploadDate": "2026-02-21T09:00:00-05:00",
  "duration": "PT15M33S",
  "contentUrl": "https://www.youtube.com/watch?v=VIDEO_ID",
  "embedUrl": "https://www.youtube.com/embed/VIDEO_ID",
  "interactionStatistic": {
    "@type": "InteractionCounter",
    "interactionType": {"@type": "WatchAction"},
    "userInteractionCount": 12500
  },
  "hasPart": [
    {
      "@type": "Clip",
      "name": "Introduction to Topic",
      "startOffset": 0,
      "endOffset": 45,
      "url": "https://www.youtube.com/watch?v=VIDEO_ID&t=0"
    },
    {
      "@type": "Clip",
      "name": "Key Concept Explained",
      "startOffset": 46,
      "endOffset": 180,
      "url": "https://www.youtube.com/watch?v=VIDEO_ID&t=46"
    },
    {
      "@type": "Clip",
      "name": "Step-by-Step Implementation",
      "startOffset": 181,
      "endOffset": 420,
      "url": "https://www.youtube.com/watch?v=VIDEO_ID&t=181"
    }
  ]
}
```

The `hasPart` / `Clip` property generates Key Moments in Google Search results. Each clip requires `name`, `startOffset`, and `endOffset` in seconds.

**Implementation notes:**
- Place in a `<script type="application/ld+json">` block on the page.
- `duration` uses ISO 8601 format: PT[hours]H[minutes]M[seconds]S.
- `thumbnailUrl` must be a crawlable URL (not base64 or data URI).
- Validate with Google Rich Results Test before deploying.

---

### Chapter Timestamps (Key Moments)

Add timestamps in the YouTube description to generate Key Moments in Google Search and chapters in the YouTube player.

**Format:**
```
0:00 Introduction
0:45 What is [Topic]
2:30 Why [Topic] Matters in 2026
4:15 Step 1: [Action]
6:00 Step 2: [Action]
8:30 Common Mistakes to Avoid
10:15 Results and Before/After
12:00 Final Thoughts
```

**Requirements (all must be met):**
- First timestamp MUST be 0:00.
- Minimum 3 timestamps.
- Each chapter must be at least 10 seconds long.
- Timestamps must be in ascending order.
- Use descriptive chapter titles with keywords (not "Part 1", "Part 2").

**SEO benefit:** Key Moments appear as clickable timestamps in Google search results, increasing CTR and providing additional real estate in SERP.

---

### Thumbnail Optimization

| Attribute | Specification |
|-----------|---------------|
| Dimensions | 1280x720px (16:9 ratio) |
| Format | JPG or PNG |
| File size | Under 2MB |
| Face usage | Expressive human faces increase CTR 20 to 30% |
| Text overlay | 3 to 5 words maximum (CTR drops at 6+ words) |
| Background | High-contrast color (not white, not grey) |
| Branding | Consistent color palette and font for channel recognition |

**Thumbnail testing:**
- YouTube's native Test & Compare feature: upload 2 to 3 thumbnail variants per video.
- YouTube auto-serves the winning variant after 7 to 14 days of data collection.
- Early CTR (first 24 to 48 hours) has disproportionate impact on initial distribution.
- If CTR drops below 4%, the thumbnail is underperforming and should be replaced.
- Average CTR benchmark: 4 to 6% is good, 8 to 10%+ is excellent.

**Design principles:**
- Contrast: thumbnail must be distinguishable at 116x65px (mobile search size).
- Emotion: surprised, curious, or determined facial expressions outperform neutral.
- Complementary, not duplicate: the thumbnail should add context the title does not.
- No clickbait: thumbnails that promise what the video does not deliver cause retention drops and algorithmic penalties.

---

### Transcript Optimization

**Why custom transcripts matter:**
- Auto-generated captions are 85 to 95% accurate. That 5 to 15% error rate can mangle keywords.
- Upload a custom .SRT or .VTT file to ensure exact target keywords appear correctly in the indexed transcript.
- YouTube indexes the full transcript text for search matching.
- Google can extract specific transcript passages for AI Overviews.

**File formats:**
- `.srt` (SubRip): Most widely supported. Includes sequence number, timecodes, and text.
- `.vtt` (WebVTT): W3C standard. Supports styling. Used by HTML5 video players.

**Transcript on your website:**
- Post the full transcript on the page where the video is embedded.
- A 15-minute video produces approximately 2,000 to 2,500 words of transcribable content.
- This text is indexed by Google and strengthens the page's topical relevance.
- Format with H2/H3 headings corresponding to video chapters for maximum SEO value.

**Transcription tools:**
- Rev.com: $1.50/minute, human transcription (highest accuracy).
- Otter.ai: AI-powered, real-time. Good for drafts, needs keyword review.
- Descript: AI transcription with editor. Can correct and export .SRT directly.
- YouTube Studio: Auto-generate, then download and manually correct keywords.

---

### Video in AI Overviews

Google AI Overviews increasingly cite video content, especially from YouTube.

**Key statistics:**
- Nearly 30% of Google AI Overviews cite at least one YouTube video.
- Video + text + schema on the same page yields 156 to 317% higher citation rate than text alone.
- Short, focused explainer videos (60 to 90 seconds) on a single concept are the most cited format.

**Optimization for AI Overview citation:**
- Script for clarity: deliver the direct answer within the first 15 seconds.
- One video per concept. Do not combine multiple topics in a single video.
- Pair video with 300 to 500 words of supporting text on the same page.
- Add VideoObject schema with Clip/hasPart markup.
- Build topical depth: many videos covering different aspects of the same subject cluster.

**Page structure for maximum citation:**
```html
<h1>How to [Topic]: Complete Guide (2026)</h1>
<p>[Answer capsule: 40 to 60 words directly answering the search query]</p>

<h2>Video Guide</h2>
<iframe src="https://youtube.com/embed/VIDEO_ID" ...></iframe>
<script type="application/ld+json">[VideoObject schema]</script>

<h2>Full Transcript</h2>
<p>[Complete video transcript with H3 subheadings matching chapters]</p>

<h2>Key Takeaways</h2>
<ul>
  <li>[Takeaway 1]</li>
  <li>[Takeaway 2]</li>
</ul>
```

---

### YouTube Shorts Search Optimization

YouTube Shorts compete in both YouTube search and Google Discover/Search video carousels.

**Optimization tactics:**
- Titles DO index in YouTube search. Maximum 60 characters. Keyword-first.
- 3 to 5 keyword hashtags in the description.
- Completion rate is heavily weighted. Loops count as rewatches and boost completion metrics.
- Optimal length: 30 to 45 seconds for educational, 15 to 20 seconds for quick tips.
- Vertical format (9:16), 1080x1920px.
- Shorts appear in Google Discover feeds and Google Search video carousels.
- Hook in first 1 second. Shorts viewers decide to stay or scroll within 1 to 2 seconds.

**Shorts as a discovery funnel:**
- Use Shorts to drive viewers to longer-form content.
- End card / pinned comment linking to the full video.
- Shorts build channel authority and subscriber count, which benefits long-form video ranking.

---

## Visual Search Optimization

### Google Lens (12 Billion Searches Per Month)

Google Lens processes 12 billion visual searches monthly (Google, 2025). It is the fastest-growing search surface and is integrated into the Google app, Chrome, Google Photos, and Android camera.

#### How Lens Identifies Content

1. **Object detection and segmentation:** Lens isolates distinct objects within an image.
2. **Visual feature extraction:** Color, shape, texture, pattern, and spatial relationships are analyzed.
3. **Cross-reference with metadata:** Alt text, filename, surrounding text on the page, and structured data are matched against visual features.
4. **Confidence scoring:** Visual match + metadata confirmation determines ranking. Strong metadata alignment with visual content produces the highest confidence scores.

#### Making Images Lens-Friendly

**Product photography:**
- Clean, uncluttered backgrounds. White or light solid backgrounds work best for product images.
- Single dominant subject per image. Lens performs poorly on busy, cluttered scenes.
- Multiple angles: front, side, back, close-up detail. Each angle is a separate discovery opportunity.
- High resolution: minimum 1000px on the shortest side.
- Original images. Google deprioritizes stock photography and duplicate images that appear across many domains.

**Contextual images (lifestyle, in-use shots):**
- Product clearly visible and identifiable within the scene.
- Natural lighting preferred over heavily filtered or stylized images.
- Include recognizable context clues (kitchen for cookware, gym for equipment).

**Demographics and usage:**
- The 18 to 24 age demographic is the heaviest Google Lens user segment.
- 1 in 3 Google Lens results come from images hosted on pages that already rank in the top Google search results.
- Implication: strong SEO + strong image optimization = compounding visibility.

---

### Image SEO Best Practices

#### File Naming

File names are indexed by search engines and should describe the image content with keywords.

| Quality | Example | Why |
|---------|---------|-----|
| BAD | IMG_3847.jpg | No keywords, no description |
| BAD | product-1.jpg | Generic, no specificity |
| BAD | best-running-shoes-2026-nike-adidas-brooks-asics-review.jpg | Keyword stuffing |
| GOOD | black-leather-chelsea-boot-mens.jpg | Descriptive, keyword-rich, concise |
| GOOD | home-gym-barbell-rack-setup.webp | Clear subject, natural keywords |

**Rules:**
- Maximum 5 to 6 words, hyphen-separated.
- Lowercase only.
- No underscores (Google treats hyphens as word separators but underscores as joiners).
- No special characters, spaces, or accented characters.
- Describe what is IN the image, not the page topic.

#### Alt Text

Alt text serves three purposes: accessibility (screen readers), SEO (search engines index it), and AI extraction (AI systems use it to understand images).

**Format:** [Primary subject] [action or description] [context] [keyword]

**Length:** 60 to 125 characters.

**Examples:**
- GOOD: "Stainless steel kettlebell set on rubber gym floor mat with weight rack in background"
- GOOD: "Woman performing deadlift with proper form in home gym"
- BAD: "Image of a kettlebell" (too vague)
- BAD: "Photo of our amazing premium kettlebell set best kettlebell 2026 buy now" (keyword stuffing)
- BAD: "" (empty alt text on meaningful images)

**Rules:**
- Do NOT start with "Image of" or "Photo of" (screen readers already announce "image").
- Do NOT keyword stuff.
- Do NOT leave empty on any meaningful image.
- Decorative images (borders, spacers) should use `alt=""` (empty alt, not missing alt).
- Every product image, infographic, chart, and hero image needs descriptive alt text.

#### Image Format Selection

| Use Case | Format | Why |
|----------|--------|-----|
| Photographs | WebP | 25 to 34% smaller than JPEG at equivalent quality |
| Transparency needed | WebP | Supports alpha channel, smaller than PNG |
| Icons and logos | SVG | Infinitely scalable, tiny file size |
| Maximum compression | AVIF | Best compression ratio available (if browser support acceptable) |
| Fallback | JPEG | Universal support, acceptable quality |
| Animated images | WebP or AVIF | Smaller than GIF by 50 to 80% |

**Implementation:**
```html
<picture>
  <source srcset="image.avif" type="image/avif">
  <source srcset="image.webp" type="image/webp">
  <img src="image.jpg" alt="Descriptive alt text with keywords"
       width="1200" height="800" loading="lazy">
</picture>
```

Always include `width` and `height` attributes to prevent Cumulative Layout Shift (CLS). Use `loading="lazy"` for below-the-fold images.

#### Image Sitemaps

Image sitemaps tell Google about images that may not be discovered through normal crawling (JavaScript-loaded images, CDN-hosted images, images behind lazy-load).

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"
        xmlns:image="http://www.google.com/schemas/sitemap-image/1.1">
  <url>
    <loc>https://yourdomain.com/page/</loc>
    <image:image>
      <image:loc>https://yourdomain.com/images/product-name.webp</image:loc>
      <image:title>Product Name with Keywords</image:title>
      <image:caption>Descriptive caption explaining the image content and context</image:caption>
    </image:image>
    <image:image>
      <image:loc>https://yourdomain.com/images/product-name-side-view.webp</image:loc>
      <image:title>Product Name Side View</image:title>
      <image:caption>Side angle showing product dimensions and build quality</image:caption>
    </image:image>
  </url>
</urlset>
```

**Rules:**
- Maximum 1,000 images per page entry.
- Submit to Google Search Console under Sitemaps.
- Update when new product images are added.
- Include all product images, infographics, and original photography.
- Do NOT include decorative images, icons, or UI elements.

---

### ImageObject Schema

Use ImageObject structured data for key images (product photos, infographics, hero images) to provide Google with rich metadata.

```json
{
  "@context": "https://schema.org",
  "@type": "ImageObject",
  "name": "Descriptive Name with Keywords",
  "description": "150 to 300 character description of the image content and context",
  "contentUrl": "https://yourdomain.com/images/product-name.webp",
  "width": 1200,
  "height": 800,
  "encodingFormat": "image/webp",
  "author": {
    "@type": "Person",
    "name": "Author Name"
  },
  "datePublished": "2026-02-21",
  "copyrightHolder": {
    "@type": "Organization",
    "name": "Your Company"
  }
}
```

**For articles and blog posts:** Use a minimum 1200x630px hero image for Google rich results and social sharing cards.

**For product pages:** Use multiple ImageObject entries within a Product schema:

```json
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "Product Name",
  "image": [
    "https://yourdomain.com/images/product-front.webp",
    "https://yourdomain.com/images/product-side.webp",
    "https://yourdomain.com/images/product-detail.webp"
  ],
  "description": "Product description with keywords",
  "brand": {"@type": "Brand", "name": "Brand Name"},
  "offers": {
    "@type": "Offer",
    "price": "49.99",
    "priceCurrency": "USD",
    "availability": "https://schema.org/InStock"
  }
}
```

---

### Pinterest Lens Optimization

Pinterest Lens visual search can identify 2.5+ billion object types and is strongest in home decor, fashion, food, and DIY categories.

**How Pinterest Lens differs from Google Lens:**
- Pinterest Lens surfaces shoppable results with pricing and direct purchase links.
- It favors lifestyle images (product in context/use) over white-background product isolates.
- Pinterest Lens results link directly to pins and merchant product pages.

**Optimization tactics:**
- 2:3 vertical ratio (1000x1500px minimum). Consistent with pin format requirements.
- Lifestyle images showing the product in use surface more frequently than isolated product shots.
- Light text overlays help Pinterest OCR understand pin semantics and improve search matching.
- Enable Product Rich Pins via Open Graph tags or Product schema on your website.
- Use original photography. Duplicate images from manufacturer catalogs are deprioritized.
- Include multiple product angles pinned to the same board.

---

### Google Images Ranking Factors (Ordered by Impact)

1. **Page title relevance.** The H1 and title tag of the hosting page must be topically relevant to the image.
2. **Alt text match to search query.** Direct keyword match between alt text and the user's image search query.
3. **Filename keywords.** Descriptive, hyphenated filenames with target keywords.
4. **Surrounding text context.** The paragraph immediately before and after the image provides contextual relevance signals.
5. **Caption text.** Use the `<figcaption>` HTML element for image captions. Google indexes this specifically.
6. **Page authority.** Domain rating, backlink profile, and overall site trust.
7. **Structured data.** Product, Recipe, Video, and ImageObject schema markup.
8. **Image uniqueness.** Original images rank higher than stock photos or duplicated images across many sites.
9. **Image quality.** High resolution balanced against file size. WebP conversion helps both quality and Core Web Vitals.

**Caption implementation:**
```html
<figure>
  <img src="home-gym-setup.webp"
       alt="Complete home gym setup with power rack, barbell set, and rubber floor mats"
       width="1200" height="800" loading="lazy">
  <figcaption>A complete home gym setup featuring a power rack, Olympic barbell set,
  and interlocking rubber floor mats in a 200 square foot garage space.</figcaption>
</figure>
```

Google specifically indexes `<figcaption>` text and uses it as a ranking signal for image search.

---

### Visual Search Commerce Data

| Metric | Value | Source |
|--------|-------|--------|
| Visual search market size (2024) | $40 billion | Grand View Research |
| Projected market size (2032) | $150+ billion | Grand View Research |
| Pinterest conversion rate increase via visual search | 73.9% | Pinterest Business |
| Pinterest CPC decrease via visual search | 8.92% | Pinterest Business |
| Online shoppers influenced by images | 50% | Salsify, 2024 |
| Google Lens monthly searches | 12 billion | Google, 2025 |
| Pinterest Lens object recognition | 2.5+ billion types | Pinterest |

**Gen Z visual search behavior ("see-photograph-buy" flow):**
1. See a product on social media (TikTok, Instagram, Pinterest).
2. Screenshot or photograph it.
3. Use Google Lens or Pinterest Lens to identify the product.
4. Compare prices and reviews across merchants.
5. Purchase (often within 24 hours).

This flow bypasses traditional search entirely. Brands not optimized for visual search are invisible in this purchase journey.

---

### E-Commerce Image Optimization Priority Checklist

Implementation order for maximum impact:

1. **Product schema with multiple ImageObject entries.** Enables rich results with product images, pricing, and availability in Google Search.

2. **Original product photography.** Removes the duplicate image penalty. Manufacturer stock photos that appear on 50+ retailer sites provide no differentiation.

3. **WebP conversion for all images.** 25 to 34% file size reduction improves Core Web Vitals (LCP), which is a ranking factor for both web and image search.

4. **Alt text audit and rewrite.** Review every product image. Rewrite generic or missing alt text using the [subject] [description] [context] [keyword] format.

5. **Descriptive filenames for all new images.** Rename on upload. Retroactively rename and 301-redirect if feasible.

6. **Rich Pins enabled on Pinterest.** Requires Open Graph tags or Product schema on your site. Auto-syncs pricing and availability.

7. **Image sitemap submitted to Google Search Console.** Ensures all product images are discovered and indexed, especially those loaded via JavaScript or CDN.

8. **Rich Results Test validation for every product template.** Test one URL per template type. Fix all errors and warnings before scaling.

---

## Measurement and Tracking

### Social Search Metrics

| Platform | Key Metrics | How to Track |
|----------|------------|--------------|
| TikTok | Search impressions, profile views from search, keyword ranking | TikTok Analytics (Creator Tools), TikTok Keyword Insights Tool |
| Instagram | Accounts reached via search, Explore impressions, hashtag reach | Instagram Insights (Professional Account required) |
| Pinterest | Search impressions, saves, outbound clicks, pin close-ups | Pinterest Analytics (Business Account), Pinterest Trends |
| Reddit | Thread views, upvotes, comment engagement, referral traffic | Reddit post analytics, Google Analytics referral data |

### Video SEO Metrics

| Metric | Benchmark | Tool |
|--------|-----------|------|
| YouTube CTR | 4 to 6% good, 8 to 10%+ excellent | YouTube Studio Analytics |
| Audience retention (%) | 50%+ is good, 70%+ is excellent | YouTube Studio |
| Search impressions | Track month-over-month growth | YouTube Studio > Traffic Sources > YouTube Search |
| Google video carousel appearances | Track via search impression data | Google Search Console > Search Appearance > Video |
| AI Overview video citations | Manual tracking monthly | Search top 20 queries, document citations |

### Visual Search Metrics

| Metric | Tool |
|--------|------|
| Google Images traffic | Google Search Console > Search Type > Image |
| Image rich results | Google Search Console > Search Appearance |
| Pinterest visual search traffic | Pinterest Analytics > Impressions |
| Schema validation | Google Rich Results Test |
| Core Web Vitals (image-related) | Google PageSpeed Insights, Chrome DevTools |
| Image indexing coverage | Google Search Console > Pages report (filter by image URLs) |

---

## Quick Reference: Cross-Channel Optimization Checklist

Use this checklist when optimizing content for social, video, and visual search simultaneously:

### Social Search
- [ ] TikTok: Target keyword spoken in first 3 seconds of audio
- [ ] TikTok: Keyword in caption text
- [ ] TikTok: 3 to 5 keyword hashtags (not entertainment hashtags)
- [ ] Instagram: Primary keyword in first line of caption
- [ ] Instagram: Custom alt text on every image
- [ ] Instagram: Reels caption mirrors Google search query
- [ ] Pinterest: 2:3 vertical images (1000x1500px minimum)
- [ ] Pinterest: Keyword-first pin titles (max 100 chars)
- [ ] Pinterest: Rich Pins enabled via schema or OG tags
- [ ] Reddit: Genuine participation, not self-promotion

### Video SEO
- [ ] YouTube title: primary keyword in first 5 words, 50 to 60 chars
- [ ] YouTube description: primary keyword + answer in first 100 words
- [ ] YouTube description: total 200 to 500 words minimum
- [ ] Chapter timestamps added (first at 0:00, minimum 3 chapters)
- [ ] Thumbnail: 1280x720px, face + 3 to 5 words text, high contrast
- [ ] Custom transcript (.SRT/.VTT) uploaded
- [ ] VideoObject schema on website embed page
- [ ] Clip/hasPart markup for Key Moments
- [ ] Full transcript posted on website page

### Visual Search
- [ ] File names: descriptive, hyphenated, 5 to 6 words max
- [ ] Alt text: 60 to 125 chars, [subject] [description] [context] [keyword]
- [ ] Image format: WebP primary, AVIF where supported, JPEG fallback
- [ ] Width and height attributes on all img tags (prevents CLS)
- [ ] `<figcaption>` on key images
- [ ] ImageObject or Product schema on product/hero images
- [ ] Image sitemap submitted to Google Search Console
- [ ] Original photography (not duplicated stock images)
- [ ] Minimum 1000px shortest side for all important images
- [ ] Rich Results Test: all product templates validated
