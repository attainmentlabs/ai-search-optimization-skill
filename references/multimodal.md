# Multimodal Search Optimization (MMS)

> Reference file for the attainment-ai-search-visibility skill.
> Covers Tier 3 Specialized discipline #15: Multimodal Search Optimization.
> Last updated: February 2026.

---

## Definition and Scope

Multimodal search refers to AI-powered search systems that process two or more input modalities simultaneously: image, text, audio, and video. Unlike traditional text-only search, multimodal systems understand the semantic relationship between a photo you take, the words you speak, and the answer they synthesize.

**Core modalities in modern search:**
- **Image-to-text**: Upload or photograph an object, receive text results (Google Lens, ChatGPT Vision)
- **Text-to-image search**: Describe what you want, see visual results (Bing Image Creator search, Ideogram)
- **Voice-to-answer**: Speak a query, receive a synthesized spoken answer (Google Assistant, Siri, Alexa)
- **Video understanding**: AI analyzes video frames and audio to extract meaning (Gemini, YouTube AI features)
- **Cross-modal retrieval**: Query with one modality, retrieve another (photograph a product, find where to buy it)

**Scale of multimodal search in 2026:**
- Google Lens: 10B+ visual searches per month (Google I/O 2023, trajectory continues upward)
- Pinterest: 600M+ visual searches per month within the app
- Amazon StyleSnap: Tens of millions of fashion lookups per month
- Google AI Overviews: Images now appear in over 40% of AI Overview responses (SEMrush, 2024)
- TikTok camera search: Launched 2024, now integrated into For You page discovery

**Why multimodal matters commercially:**
- Visual commerce market projected at $340B by 2028 (Grand View Research)
- 36% of consumers have used visual search to find products (Oberlo, 2024)
- "Near me" + image combination queries have grown 200%+ since 2022 (Google Trends)
- Conversion rate for visual search users is 48% higher than text search users (Salesforce)
- Mobile-first behavior: 85% of visual searches happen on smartphones

**The shift from text-only to cross-modal retrieval:**
Pre-2022, SEO was almost entirely about text signals: keywords, backlinks, content length. The release of GPT-4V (March 2023), Google's Gemini multimodal models (December 2023), and Google Lens reaching 10B monthly searches changed this. AI systems now build unified embeddings that span image and text space. A product optimized for text search can still be invisible to visual search, and vice versa. MMS closes that gap.

---

## Platform-Specific Multimodal Behavior

### Google Lens

Google Lens is the primary consumer multimodal surface with the largest reach.

**How Lens works technically:**
- Computer vision model analyzes photographed image
- Matches against Google's visual index (hundreds of billions of images)
- Cross-references with Knowledge Graph entities and product databases
- Returns: similar images, product shopping results, text extraction (OCR), landmark data, plant/animal ID, nutritional info (food photos), QR code scanning, translation

**Lens search surfaces:**
1. **Standalone Lens app**: Available Android and iOS, camera or gallery photo
2. **Google Search camera icon**: Tap the camera in the Google search bar (mobile)
3. **Chrome "Search this image"**: Right-click any web image on desktop, or long-press on mobile
4. **Google Images**: Search within image results using Lens overlay
5. **Google Shopping**: Lens integration for "shop the look" on any photo
6. **Google Maps**: Lens within Street View, local business photo search

**What makes a product appear in Lens results:**
- High-quality product image submitted to Google Merchant Center (GMC)
- Accurate GTIN/barcode data in product feed
- Consistent product images across GMC, website, and brand social
- ImageObject structured data with matching product schema
- Page with image has strong link authority and topical relevance
- Image file size under 2MB, served fast (under 500ms from Google CDN)

**Lens for local businesses:**
- Google Maps Photos: Lens scans interior/exterior business photos
- Google Business Profile photo optimization directly impacts Lens visibility
- User-generated photos (from customers) feed Lens results for location queries
- 360-degree virtual tours indexed by Lens and Maps together

**Lens OCR (Optical Character Recognition):**
- Lens extracts all text visible in a photo
- Menus, signs, business cards, whiteboards, packaging labels all get OCR-indexed
- Optimize physical signage and packaging with consistent brand terminology
- Restaurant menus: digitize and upload to GBP to align with what Lens reads from photos

### Google AI Overviews with Images

AI Overviews (formerly Search Generative Experience) now regularly include images directly in the AI-generated response card.

**When images appear in AI Overviews:**
- How-to queries with steps: AI pulls instructional images from authoritative pages
- Product comparisons: AI includes product imagery from merchant pages
- "What is X" queries: AI pulls defining images from Wikipedia, academic sources, brand pages
- Recipe queries: Dish photography from recipe sites (schema-required)
- Travel queries: Destination photos from travel publishers and Google Travel

**Signals that drive image inclusion in AI Overviews:**
1. Image is on a page that ranks in top 5 for the query (organic position is prerequisite)
2. ImageObject schema present with name, description, and url properties
3. Image has descriptive alt text matching query intent (not keyword stuffed)
4. Image dimensions meet Google's rich result requirements (minimum 696px wide for most types)
5. Page has HowTo, Recipe, Product, or FAQ schema that triggers enhanced AI Overview treatment
6. Image has been in Google's index for 90+ days (new images less likely to appear)
7. Surrounding text context confirms image relevance to the query topic

**Negative signals that exclude images:**
- Images blocked by robots.txt or X-Robots-Tag: noindex
- Images with generic alt text ("image1.jpg" or "photo")
- Images that fail Core Web Vitals causing poor page experience signal
- Images on pages with significant link spam or low trust signals
- Watermarked stock photography (AI deprioritizes in favor of original content)

### Bing Visual Search and Copilot

**Bing Visual Search:**
- Pinterest-style visual discovery integrated into Bing.com/images
- "Visual Search" button on any Bing image result
- Upload or URL-based image query
- Copilot (formerly Bing Chat) now accepts image uploads for multimodal Q&A

**Bing IndexNow protocol:**
- Bing pioneered IndexNow: ping Bing instantly when new images/pages are published
- Dramatically faster indexing than waiting for Bing crawler
- Submit via IndexNow API or plugins (Yoast SEO, Rank Math support it natively)
- Reduces time-to-index from weeks to hours for new visual content

**Copilot + image queries:**
- User uploads product photo, asks "where can I buy this" or "what is this"
- Copilot returns Bing Shopping results + visual search matches
- Optimize Bing Merchant Center product feeds (separate from Google Merchant Center)

### ChatGPT Vision (GPT-4V and o1 Models)

**What users do with ChatGPT Vision:**
- Upload photo of a product: "What is this, where can I buy it, how much does it cost?"
- Upload a document or screenshot: "Summarize this contract" or "Explain this chart"
- Upload a whiteboard photo: "Convert this diagram to text"
- Screenshot of a UI: "What UX problems do you see?" or "What app is this?"

**How ChatGPT retrieves information for visual queries:**
- For recognized products/brands: Draws from training data (knowledge cutoff: April 2024 for GPT-4o)
- For web search queries (with Browsing enabled): Searches Bing and returns cited results
- For entity recognition: Cross-references OpenAI's entity training data with visual analysis

**Brand visibility in ChatGPT Vision:**
- Ensure your brand/product is covered on: Wikipedia, major press, Reddit, top industry publications
- OpenAI's training data skews toward high-authority web text sources
- Product recognition: Submit products to major databases (Open Food Facts, UPCitemdb, Google Shopping)
- If user browses web with image: your page must be Bing-indexed with descriptive content near images

**o1 Model Multimodal Reasoning:**
- o1 ("strawberry") model released September 2024 applies chain-of-thought reasoning to visual inputs
- Handles complex visual reasoning: "What is wrong with this structural design?" or "Analyze this financial chart"
- For technical/professional services: create visual explainer content that o1 users would query about
- PDF analysis: o1 can parse multi-page PDFs with charts, tables, and text simultaneously

### Gemini Vision (Google's Multimodal AI)

**Gemini Vision capabilities:**
- Real-time video understanding: Gemini can watch a video and answer questions about it
- Document parsing: Upload a PDF or slide deck, Gemini extracts and analyzes all content
- Chart and graph analysis: Extracts data from visual charts without requiring underlying data
- Scientific image analysis: Diagrams, molecular structures, medical imagery
- Long-context multimodal: Gemini 1.5 Pro handles 1M token context including images and video

**How Gemini Vision impacts search:**
- Gemini powers Google AI Overviews since late 2024
- Gemini reads images on your page when deciding what to cite in AI Overviews
- Alt text + surrounding text + schema = what Gemini understands about your images
- Video content indexed via YouTube is processed by Gemini's video understanding model

**Gemini for Google Workspace:**
- Gemini in Gmail/Docs/Slides: Analyzes attached images and documents
- Enterprise Gemini: Answers employee queries from internal documents with images
- Implication: B2B brands creating whitepapers with charts should ensure charts are explained in adjacent text

### Pinterest Visual Search

**Pinterest scale and behavior:**
- 600M visual searches per month within Pinterest app
- 445M+ monthly active users (Pinterest Q3 2024 earnings)
- "Lens" feature: photograph anything, find similar Pinterest content and shoppable products
- "Shop the Look": Pin contains tagged products, visual search surfaces them

**Pinterest SEO for visual search:**
- Board titles and descriptions: Use exact category terms users search (not creative names)
- Pin descriptions: 100-500 characters, natural language describing the visual content
- Image quality: Vertical format (2:3 ratio, 1000x1500px ideal), high contrast, minimal text overlay
- Alt text on pins: Auto-generated from image title, manually editable in Business account
- Rich Pins: Enable Product Rich Pins (requires schema validation), auto-syncs price, availability
- Pinterest catalog: Upload product feed directly (similar to Google Merchant Center)

**Industries where Pinterest visual search drives significant traffic:**
- Home decor and interior design
- Fashion and apparel
- Food and recipe content
- Wedding and events
- Beauty and cosmetics
- DIY and crafts

### TikTok and Snapchat Camera Search

**TikTok visual search (launched 2024):**
- "Search" tab in TikTok now includes visual search: photograph an object, find related TikTok content and shoppable products
- TikTok Shop integration: Photograph product, see matching TikTok Shop listings
- Live Shopping: AI matches products shown in stream to searchable catalog

**TikTok SEO for visual discovery:**
- Product tags in videos: Tag products from TikTok catalog in video content
- Caption keyword optimization: First 150 characters are most weight-heavy for search
- In-video text overlays: TikTok OCR reads text shown in videos for search indexing
- Hashtags: Niche hashtags (under 500K uses) outperform over-saturated tags
- Audio: TikTok transcribes audio; speaking product names and category terms matters

**Snapchat Scan:**
- Scan (camera search) integrated into Snapchat: photograph products, scan QR codes, identify plants/animals
- Snapchat partnered with Amazon for in-app shopping from visual search results
- Lens Studio AR: Brands can create custom AR lenses that trigger product discovery (Lenses = visual ads)

### Amazon Rekognition and StyleSnap

**Amazon StyleSnap:**
- Photograph any fashion outfit or item, Amazon returns matching or similar products for purchase
- Powered by Amazon Rekognition (AWS computer vision service) + Amazon catalog
- High purchase intent: Users actively shopping when they use StyleSnap

**Amazon catalog optimization for visual search:**
- Main product image: Pure white background (#FFFFFF), product fills 85%+ of frame
- Multiple image types: Front, back, side, in-use lifestyle, scale reference
- Image requirements: Minimum 1000px on longest side (allows zoom), JPEG or PNG
- A+ Content: Enhanced brand content with comparison charts, lifestyle imagery
- Amazon Brand Registry: Required for full visual search feature access

**Amazon Rufus (AI Shopping Assistant, 2024):**
- Rufus accepts image queries: photograph item, ask "find me this on Amazon"
- Rufus also accepts conversational text queries about products
- Optimize for Rufus: Complete product descriptions, robust Q&A section, high review volume

---

## Image SEO for AI Systems

### File Naming

The filename is the first signal an AI system reads about an image before processing its visual content.

**Rules:**
- Use descriptive, hyphenated filenames: `blue-merino-wool-crew-neck-sweater-mens.jpg`
- Never use generic names: `IMG_1234.jpg`, `photo.png`, `untitled.jpeg`
- Include: primary category + key descriptor + variant (color, size if relevant)
- Maximum 5-7 words in filename (beyond this, diminishing signal value)
- Lowercase only, hyphens not underscores (underscores are not treated as word separators by Google)
- Include brand name for brand photography: `fitcommit-app-workout-tracking-screen.jpg`

**Filename templates:**
- Product: `{product-name}-{color}-{material}-{category}.jpg`
- Blog/editorial: `{topic}-{subtopic}-{year}.jpg`
- Team/headshot: `{firstname}-{lastname}-{title}-{company}.jpg`
- Infographic: `{topic}-infographic-{year}.jpg`

### Alt Text

Alt text is the primary text signal AI systems use to understand image content for indexing.

**Format: Descriptive, contextual, 120-150 characters**

Bad: `alt="sweater"`
Bad: `alt="blue sweater buy online cheap sweater wool sweater"`
Good: `alt="Men's blue merino wool crew-neck sweater with ribbed cuffs, shown folded on white surface"`

**Alt text formula:** [Subject] + [Visual description] + [Context/Purpose]

**Alt text for different image types:**
- Product images: Material, color, form factor, what it is, who it is for
- Infographics: "Infographic showing [title]: [list the 3 most important data points]"
- Charts/graphs: "Bar chart comparing [metric] across [categories], showing [key finding]"
- Team photos: "[Full name], [job title] at [company], [visual description e.g., smiling, seated at desk]"
- Screenshots: "Screenshot of [software/platform] showing [feature name] with [key element visible]"
- Before/after: "Before: [description]. After: [description] following [process/treatment]"
- Diagrams: "Diagram illustrating [process name] with [number] steps: [briefly list steps]"

**What alt text does NOT do:**
- Alt text is not for keyword stuffing (Google penalizes this)
- Alt text does not replace a caption (both serve different purposes)
- Alt text cannot convey everything in a complex chart (add a data table below)

### Title Attributes

- Image title: `title="Blue Merino Wool Sweater - FitCommit Apparel"`
- Lower weight than alt text for AI systems
- Primary use: Tooltip on hover (UX), secondary SEO signal
- Match page topic and schema name property

### Structured Data for Images

**ImageObject schema (standalone):**
```json
{
  "@context": "https://schema.org",
  "@type": "ImageObject",
  "name": "Blue Merino Wool Crew-Neck Sweater",
  "description": "Men's blue merino wool sweater with ribbed cuffs and hem, lightweight for layering",
  "url": "https://example.com/images/blue-merino-wool-sweater.jpg",
  "width": 1200,
  "height": 900,
  "encodingFormat": "image/jpeg",
  "contentUrl": "https://example.com/images/blue-merino-wool-sweater.jpg"
}
```

**ImageObject nested in Product schema:**
```json
{
  "@type": "Product",
  "name": "Blue Merino Wool Sweater",
  "image": [
    "https://example.com/images/sweater-front.jpg",
    "https://example.com/images/sweater-side.jpg",
    "https://example.com/images/sweater-worn-lifestyle.jpg"
  ]
}
```

**ImageObject nested in Article schema:**
```json
{
  "@type": "Article",
  "image": {
    "@type": "ImageObject",
    "url": "https://example.com/images/article-hero.jpg",
    "width": 1200,
    "height": 630
  }
}
```

### Surrounding Text Context

- The paragraph immediately before and after an image is used by AI to determine what the image is about
- Caption text (figure or figcaption element) is high-weight context signal
- Page title and H1 provide macro-context for every image on the page
- Avoid: using images as decoration with no surrounding descriptive text
- Best practice: Every image should have a meaningful caption (2-3 sentences that describe and add value)

**Caption structure:**
- Sentence 1: Describe what is literally in the image
- Sentence 2: Explain why it matters or what it shows
- Sentence 3 (optional): Credit or source if applicable

### Image Sitemaps

Image sitemaps tell Google's crawler about images that might be missed during regular crawling (especially images loaded via JavaScript or served from CDNs).

**Required image sitemap tags:**
```xml
<url>
  <loc>https://example.com/products/blue-sweater/</loc>
  <image:image>
    <image:loc>https://cdn.example.com/images/blue-sweater-front.jpg</image:loc>
    <image:title>Blue Merino Wool Sweater - Front View</image:title>
    <image:caption>Men's blue merino wool crew-neck sweater, lightweight and breathable</image:caption>
  </image:image>
</url>
```

**Image sitemap best practices:**
- Submit to Google Search Console under Sitemaps
- Update dynamically when new images are added (CMS plugins handle this)
- Maximum 50,000 images per sitemap (split into multiple if needed)
- Can nest image tags within existing URL sitemap (no need for separate file)

### Image Formats

- **JPEG**: Best for photographs and complex images, lossy compression, no transparency
- **WebP**: 25-35% smaller than JPEG at same quality, supported by all modern browsers, use for all new photography
- **AVIF**: 50% smaller than JPEG, newer format (2021+), growing browser support, best for future-proofing
- **PNG**: Lossless, larger file size, use only for images requiring transparency
- **SVG**: Vector format, infinitely scalable, ideal for logos and icons, indexed by Google

**Format conversion priority:**
1. Convert all JPEGs to WebP (immediate win)
2. Serve AVIF to supporting browsers via `<picture>` element with WebP fallback
3. Keep PNG only where transparency is essential
4. Never use BMP or TIFF on web

**Implementation with picture element:**
```html
<picture>
  <source srcset="image.avif" type="image/avif">
  <source srcset="image.webp" type="image/webp">
  <img src="image.jpg" alt="Descriptive alt text here" width="1200" height="900">
</picture>
```

### Image CDN

- **Cloudflare Images**: $5/month for 100K images, automatic WebP/AVIF conversion, global CDN, resizing on-the-fly
- **Imgix**: Enterprise image CDN, URL-based transformation parameters, used by Shopify and major e-commerce
- **Fastly Image Optimizer**: Edge-based image optimization, enterprise pricing
- **Bunny.net Optimizer**: Budget-friendly at $9.50/TB, WebP auto-conversion, suitable for SMBs

**CDN benefits for multimodal SEO:**
- Faster image delivery = better Core Web Vitals = better ranking signal
- Global edge nodes mean same image loads fast for Google's crawlers regardless of server location
- Automatic next-gen format serving reduces manual WebP/AVIF deployment effort

---

## Video Optimization for Multimodal

### YouTube (Primary Video Search Surface)

YouTube is the second largest search engine by query volume (3B searches/month). Google-owned, auto-transcripts feed into Google AI systems, and YouTube content appears in Google's main SERP via video carousels.

**YouTube search ranking factors:**
1. Watch time and audience retention percentage
2. Click-through rate from search results (thumbnail + title)
3. Likes, comments, shares (engagement signals)
4. Keywords in title, description (first 150 chars), tags
5. Transcript content (auto or manual, all indexed)
6. Chapter headings (each chapter = separate indexed text block)
7. Upload recency (freshness signal for timely topics)
8. Playlist organization (topical authority signal)

### Transcript Optimization

Transcripts are how AI systems understand video content. They are the text layer of video multimodal optimization.

**Manual VTT/SRT upload vs auto-generated:**
- Auto-generated transcripts: 85-95% accuracy on clear speech, errors common with technical terms, accents, industry jargon
- Manual upload: 99%+ accuracy, preferred by Google for rich results, required for some accessibility compliance
- Impact: Manual transcripts increase video view time by 12% on average (3Play Media research)

**How to upload manual transcript:**
1. Create SRT file: Each caption block = [number] / [timecode] / [text]
2. YouTube Studio > Your Video > Subtitles > Add Language > Upload file
3. Select ".srt" and upload

**Transcript content optimization:**
- State the video topic explicitly in first 30 seconds (high-weight indexing zone)
- Use natural language variations of target phrases throughout (not exact-match repetition)
- Include statistics, named entities, and specific terminology your audience searches
- Avoid verbal filler in the first 30 seconds: "Um, so, like" reduce keyword density in critical zone

### YouTube Chapters with Timestamps

Chapters turn one video into multiple indexed content nodes. Each chapter title is treated as a mini-headline by Google.

**How to add chapters:**
- In video description, list timestamps starting with 0:00:
```
0:00 Introduction
1:23 What is multimodal search
3:45 Google Lens optimization tactics
7:20 Video SEO checklist
```
- YouTube auto-detects and creates chapter markers

**Chapter naming best practices:**
- Use question format for some chapters: "How does Google Lens rank products?"
- Include primary keyword variations across chapter titles
- Keep chapter titles under 50 characters
- Minimum 3 chapters, Google recommends 5+ for chapter-rich results
- First chapter must start at 0:00

**Google Search benefit:**
- Videos with chapters appear with chapter previews in Google video results
- Each chapter can surface independently for chapter-specific queries
- YouTube "Key moments" in Google are drawn from chapters

### Video Schema Markup

```json
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Multimodal Search Optimization: Complete 2026 Guide",
  "description": "Step-by-step guide to optimizing for Google Lens, ChatGPT Vision, and Gemini for AI search visibility",
  "thumbnailUrl": "https://example.com/thumbnails/multimodal-guide.jpg",
  "uploadDate": "2026-02-15",
  "duration": "PT12M30S",
  "contentUrl": "https://www.youtube.com/watch?v=VIDEO_ID",
  "embedUrl": "https://www.youtube.com/embed/VIDEO_ID",
  "transcript": "Full transcript text here...",
  "hasPart": [
    {
      "@type": "Clip",
      "name": "What is multimodal search",
      "startOffset": 83,
      "endOffset": 225,
      "url": "https://www.youtube.com/watch?v=VIDEO_ID&t=83s"
    }
  ]
}
```

### Thumbnail Optimization

Thumbnails drive CTR which is a direct ranking signal for YouTube and indirect signal for Google video rich results.

**Thumbnail technical specs:**
- Dimensions: 1280x720px (16:9 aspect ratio)
- File size: Under 2MB
- Format: JPG, GIF, PNG, BMP
- Minimum width: 640px

**Thumbnail content best practices:**
- High contrast background (bright colors outperform neutral/dark)
- Human face with visible expression if applicable (drives 38% higher CTR per research)
- Readable text overlay: Maximum 6 words, minimum 60pt font equivalent at 1280px
- Consistent brand template across channel (color palette, font, logo placement)
- Show the "before" of a transformation or the most dramatic visual of the content
- Avoid: red circle/arrow clichés, cluttered compositions, dark or muddy images

### Video Sitemaps

```xml
<url>
  <loc>https://example.com/blog/multimodal-search-guide/</loc>
  <video:video>
    <video:thumbnail_loc>https://example.com/thumbnails/multimodal.jpg</video:thumbnail_loc>
    <video:title>Multimodal Search Optimization: Complete 2026 Guide</video:title>
    <video:description>Step-by-step guide to Google Lens, ChatGPT Vision, and Gemini optimization</video:description>
    <video:content_loc>https://example.com/videos/multimodal-guide.mp4</video:content_loc>
    <video:player_loc>https://www.youtube.com/embed/VIDEO_ID</video:player_loc>
    <video:duration>750</video:duration>
    <video:publication_date>2026-02-15T09:00:00+00:00</video:publication_date>
  </video:video>
</url>
```

### TikTok SEO (Video Platform as Search Engine)

TikTok is now the third most-used search engine among 18-34 year olds (Adobe 2023). Gen Z uses TikTok for restaurant discovery, product research, and how-to queries.

**TikTok indexing signals:**
1. Caption text (first 150 characters highest weight, 500 char total limit)
2. Spoken words in video (transcribed by TikTok's ASR system)
3. On-screen text overlays (OCR-indexed)
4. Hashtags (categorization signal, not as dominant as in 2021)
5. Sounds/audio track (trending sounds boost distribution, not search)
6. Engagement velocity in first 24 hours

**TikTok SEO tactics:**
- State the topic in the first 3 seconds of audio: "Here's how to optimize for Google Lens..."
- Add on-screen text overlay with the topic keyword within first 2 seconds
- Use caption to describe what viewer will learn: keyword-rich, natural language
- Create content that answers specific questions (TikTok search is query-driven)
- Reply to comments with video answers: Creates indexed video content tied to question text

### Instagram Reels Audio Indexing

Google began indexing Instagram Reel audio captions in 2024. This creates a new text layer for visual content on Instagram.

**What this means:**
- Spoken words in Reels are transcribed and Google can read them
- Instagram auto-generated captions appear in video and are indexed
- First 3 seconds of audio: Highest indexing weight (similar to YouTube intro)
- Caption text (Instagram caption below reel): Also Google-indexed for Reels

**Instagram Reels for multimodal SEO:**
- Speak target keywords naturally in first 3 seconds
- Enable auto-captions in Reels settings (Instagram transcribes automatically)
- Write descriptive captions using natural language (not hashtag spam)
- Include location tags (triggers local Google index entries)

---

## Voice Search Optimization

Voice search is a modality layer that overlaps with AEO (Answer Engine Optimization) but has distinct technical requirements.

### Smart Speaker Query Structure

**Google Home / Google Assistant query patterns:**
- "Hey Google, [question format]" -- Conversational, usually 5-10 words
- "OK Google, find [service] near me" -- Local intent dominant
- "Hey Google, how do I [task]" -- How-to intent

**Alexa query patterns:**
- "Alexa, order me [product]" -- Transactional, Amazon-native
- "Alexa, what is [definition]" -- Informational, sources from Bing/Wikipedia
- "Alexa, ask [skill name] about [topic]" -- Skill-based (relevant for brands with Alexa Skills)

**Siri query patterns:**
- "Hey Siri, [question]" -- Routes to Bing for most web queries (Safari + Bing partnership)
- "Hey Siri, find [business] near me" -- Routes to Apple Maps (optimize Apple Business Connect)
- "Hey Siri, call [business name]" -- Requires Apple Business Connect listing

### Featured Snippet = Voice Answer

For Google Assistant and Google Home: The answer read aloud is pulled from the featured snippet (Position 0).

**To win voice answers:**
- Structure content as a direct answer in the first 40-60 words after an H2 question heading
- Answer format: Complete sentence, answers the exact question, does not require visual context to make sense
- Common voice query templates:
  - "What is [X]?" -- Definition format
  - "How do I [X]?" -- Step format (numbered list)
  - "Where is [X]?" -- Location format (address, GBP data)
  - "How much does [X] cost?" -- Price format (specific number or range)

**Voice answer formatting checklist:**
- [ ] H2 or H3 phrased as a natural question
- [ ] Direct answer in first sentence after the heading (40-70 words)
- [ ] Answer can stand alone without visual context
- [ ] Page has FAQ schema wrapping the question-answer pair
- [ ] Page has high domain authority (featured snippets favor DR 50+ in competitive niches)

### Speakable Schema

Speakable schema tells Google which sections of a page are appropriate to be read aloud by voice assistants. Currently most relevant for news publishers.

```json
{
  "@context": "https://schema.org",
  "@type": "WebPage",
  "speakable": {
    "@type": "SpeakableSpecification",
    "xpath": [
      "/html/head/title",
      "/html/head/meta[@name='description']/@content",
      "//div[@id='summary-section']"
    ]
  }
}
```

**Who should implement speakable:**
- News publishers: Required to appear in Google News briefings for smart speakers
- FAQ pages: Mark up Q&A sections as speakable for voice answer eligibility
- Product pages: Mark up price and availability sections for voice commerce

### Local + Voice Search

"Near me" voice queries are the highest-converting voice queries. They trigger Google Business Profile data.

**Local voice query examples:**
- "Hey Google, where is the nearest [business type]?"
- "OK Google, what time does [business name] close?"
- "Hey Google, find a [service] open now"

**Google Business Profile signals for voice:**
- Business name (exact match to how customers say it)
- Primary category (used to match business type in queries)
- Hours (critical for "open now" voice queries)
- Phone number (read aloud for "call [business]" queries)
- Address (read aloud for navigation queries)
- Review count and average rating (mentioned in results: "4.8 stars with 312 reviews")

---

## Multimodal Content Strategy

### Product Image Requirements for Full Multimodal Coverage

**Minimum image set per product:**
1. Front view on white background (Google Merchant Center main image)
2. Back view on white background
3. Side view on white background
4. In-use lifestyle image (product in real-world context)
5. Detail/close-up (texture, craftsmanship, key feature)
6. Scale reference (product shown with hand, ruler, or familiar object for size)

**Recommended image set for maximum visibility:**
- Above 6 images + 360-degree spin images (12-36 frames) or video
- Before/after (where applicable: skincare, home improvement, fitness)
- Packaging image (for CPG products: Lens indexes packaging for brand recognition)
- Variant images for each color/style combination

### Infographic Optimization

Infographics are high-visual-engagement content but invisible to AI if not optimized for text extraction.

**Rules:**
- Alt text must describe ALL data points (not just "infographic about topic")
- Include a text summary below every infographic with all the same data
- Headline of infographic: Must appear in H2 or H3 on page (not just embedded in image)
- Provide downloadable version (increases backlinks, which increases image index priority)
- File size: Keep under 500KB (infographics often bloat to 2-5MB, killing LCP)

**Alt text for infographic example:**
Bad: `alt="Infographic about visual search growth"`
Good: `alt="Infographic: Visual search growth 2020-2026. Google Lens: 10B monthly searches (2023). Pinterest: 600M monthly. Amazon StyleSnap: 50M monthly. Visual commerce: $340B projected by 2028."`

### Charts and Graphs

AI systems cannot read data from image-format charts. They can only read the alt text and surrounding text.

**Best practice:**
1. Create chart in visualization tool (Datawrapper, Flourish, Google Charts)
2. Export as PNG or SVG
3. Write alt text that includes ALL key data points
4. Below the chart image: include a complete data table in HTML format
5. The HTML data table is what AI cites when it references your statistics

**This matters for GEO:** AI citations prefer pages where data is machine-readable. A chart on a page with a corresponding HTML data table gets cited more often than a chart-only page.

### User-Generated Content (UGC) and Visual Search

- Instagram tagged product photos: When users tag your product, Google Vision indexes these photos and can surface them in Google Images and Shopping
- Google Maps customer photos: Indexed by Lens, appear in local visual search results
- YouTube unboxing and review videos: AI systems recognize products in UGC video, associates with brand
- TikTok product mentions: User-generated TikTok content referencing brand appears in TikTok search

**To encourage UGC for visual search benefit:**
- Include product hashtag and encourage customer photos in post-purchase email
- Create an Instagram "tag us" prompt on packaging (printed directly on packaging)
- Respond to UGC posts (signals active brand engagement, increases post visibility)
- Repost UGC with permission (drives more UGC and signals authentic social proof)

### 360-Degree Product Views and AR

- **Google Shopping 360-degree**: Submit 360-spin images via Google Merchant Center (12-36 image sequence)
- **Snap Scan-to-Shop**: Snapchat camera identifies products, shows purchase link; requires product catalog integration
- **Apple Vision Pro Commerce**: Early-stage, brands building 3D USDZ product files for visionOS shopping
- **Google AR Beauty**: Foundation, lipstick, eyeshadow virtual try-on for beauty brands via Google Shopping

---

## Technical Multimodal SEO

### Core Web Vitals for Images

**LCP (Largest Contentful Paint) - Target: Under 2.5 seconds**

The LCP element is most often the hero image on the page. It is the single most impactful image optimization target.

**Diagnosing LCP:**
- PageSpeed Insights > "LCP element" shows which specific image is causing delay
- Chrome DevTools > Performance tab > Film strip view

**Fixing LCP image issues:**
1. Ensure LCP image is NOT lazy-loaded (common mistake: applying `loading="lazy"` to hero image)
2. Add `fetchpriority="high"` attribute to LCP image element
3. Add preload link in `<head>`: `<link rel="preload" as="image" href="hero.webp">`
4. Ensure LCP image is served from CDN (reduce TTFB)
5. Serve WebP or AVIF format (25-50% smaller than JPEG, faster download)
6. Size correctly: Serve image at actual display size (not 3000px image displayed at 600px)

**CLS (Cumulative Layout Shift) for images - Target: Under 0.1**
- Always include width and height attributes on img elements
- Reserve space for images during page load (prevents layout jump)
- Set aspect-ratio in CSS as fallback for dynamic images

### Lazy Loading Implementation

**Correct implementation:**
```html
<!-- Above-fold hero image: NO lazy loading -->
<img src="hero.webp" alt="Descriptive text" width="1200" height="630" fetchpriority="high">

<!-- Below-fold images: Lazy loading enabled -->
<img src="product.webp" alt="Descriptive text" width="600" height="600" loading="lazy">
```

**Common mistake:** Applying `loading="lazy"` to ALL images including the hero/LCP image. This delays the most critical render and tanks LCP score.

### Preload Hints for Critical Images

```html
<!-- In the <head> section -->
<link rel="preload" as="image" href="/images/hero.webp" type="image/webp">

<!-- For responsive images, include imagesrcset -->
<link rel="preload" as="image"
  imagesrcset="/images/hero-400.webp 400w, /images/hero-800.webp 800w, /images/hero-1200.webp 1200w"
  imagesizes="(max-width: 400px) 400px, (max-width: 800px) 800px, 1200px">
```

### Responsive Images (srcset and sizes)

```html
<img
  src="product-800.jpg"
  srcset="product-400.jpg 400w,
          product-800.jpg 800w,
          product-1200.jpg 1200w,
          product-2400.jpg 2400w"
  sizes="(max-width: 480px) 400px,
         (max-width: 768px) 800px,
         (max-width: 1200px) 1200px,
         2400px"
  alt="Men's blue merino wool crew-neck sweater"
  width="800"
  height="800"
  loading="lazy">
```

**Why srcset matters for multimodal SEO:**
- Google uses image quality as a signal for rich result eligibility
- Serving a 400px image to a desktop user = poor quality signal
- Responsive images ensure Google's crawler (which simulates various device types) sees appropriate resolution
- Correct srcset implementation reduces bandwidth by 40-70% (faster crawl, better Core Web Vitals)

### Structured Data Stacking

Combining multiple schema types on one page multiplies multimodal eligibility.

**E-commerce product page with multimodal optimization:**
```json
[
  { "@type": "Product", ... },
  { "@type": "ImageObject", ... },
  { "@type": "VideoObject", ... },
  { "@type": "FAQPage", ... },
  { "@type": "BreadcrumbList", ... }
]
```

**Publishing page with multimodal optimization:**
```json
[
  { "@type": "Article", ... },
  { "@type": "Person", "name": "Author Name", ... },
  { "@type": "ImageObject", ... },
  { "@type": "VideoObject", ... },
  { "@type": "FAQPage", ... }
]
```

### IndexNow for Media

IndexNow is a protocol allowing instant notification to search engines when content changes.

**Setup:**
1. Generate an IndexNow API key (any UUID: e.g., use uuidgenerator.net)
2. Place key file at `https://example.com/{your-key}.txt`
3. Submit pings when new images/pages go live:
```
GET https://api.indexnow.org/indexnow?url=https://example.com/new-page/&key={your-key}
```

**Bing accepts IndexNow, Google does not (yet).** Bing has stated IndexNow signals are used to prioritize crawl queue. Given Bing powers ChatGPT browsing, this matters for AI citation velocity.

**Plugins that handle IndexNow automatically:**
- Yoast SEO (WordPress): Built-in IndexNow support, submits on publish
- Rank Math (WordPress): IndexNow integrated in free version
- NuxtSEO (Nuxt.js): Module available
- Next-sitemap (Next.js): Manual implementation required

---

## Measurement and KPIs

### Google Search Console (Image-Specific)

**Navigating to image data:**
1. GSC > Performance > Search results
2. Click "Search type" dropdown, select "Image"
3. Filter by queries, pages, or countries specific to image search

**Key image search metrics:**
- Image search impressions: How often your images appear in Google Image results
- Image search clicks: Clicks from Google Images to your site
- Image search CTR: Typically 2-4% (lower than web search due to behavior difference)
- Image average position: Where your images rank in image search

**Image rich results:**
- GSC > Enhancements section shows: Product rich results, Recipe rich results, Video rich results
- Errors in rich results = images/structured data not qualifying for enhanced treatment
- Validate in Rich Results Test (search.google.com/test/rich-results)

### Video Performance in GSC

- GSC > Performance > Search type: Video
- Shows video impressions in Google Search video results
- Cross-reference with YouTube Studio analytics for comprehensive video search data
- GSC video tab shows which pages with embedded video are getting impressions

### YouTube Analytics for Multimodal KPIs

- **Search traffic source**: YouTube Analytics > Traffic source > YouTube search -- shows queries driving views
- **Impression CTR**: Average thumbnail + title CTR (benchmark: 4-10% is healthy)
- **Average view duration**: Percentage and absolute minutes (key retention metric for algorithmic ranking)
- **External traffic**: Views coming from Google Search video carousels (tracks Google multimodal surface)

### Visual Share of Voice Audit (Manual)

No automated tool fully measures visual share of voice. Manual process:

1. Identify 10-20 top commercial queries in your niche
2. Google each query with a mobile device
3. Screenshot: AI Overview images, Product carousel, Image pack at top of results
4. Count: How many visible images are yours vs competitor?
5. Google Lens: Photograph your own product, see what products rank above/alongside it
6. Repeat quarterly

**Visual share of voice benchmark targets:**
- Top 3 visual positions on your brand name queries: Required (brand protection)
- Top 5 visual positions on category queries: Strong position
- Appearing in AI Overview images for category queries: Advanced achievement

### Tools for Multimodal Audit

| Tool | Function | Pricing |
|------|----------|---------|
| Screaming Frog | Image audit: missing alt text, broken images, oversized files, non-WebP format | Free (500 URLs) / £259/yr |
| SEMrush Site Audit | Image optimization issues, alt text coverage report | Included in SEMrush plans |
| Ahrefs Site Audit | Image issues, Core Web Vitals data per page | Included in Ahrefs plans |
| PageSpeed Insights | LCP image diagnosis, CLS from images, WebP recommendations | Free (Google) |
| GTmetrix | Waterfall view for image load timing, format analysis | Free tier available |
| TinPNG / Squoosh | Manual image compression and WebP conversion | Free |
| Cloudflare Images | Automated WebP/AVIF serving, CDN delivery | $5/month per 100K images |
| Merkle Schema Generator | Build and validate ImageObject, VideoObject schema | Free |
| Google Rich Results Test | Validate structured data eligibility | Free (Google) |
| VidIQ | YouTube SEO analytics, keyword research for video | Free tier / $7.50/month |

---

## Quick Reference Checklist

### Image Optimization
- [ ] All product images have descriptive hyphenated filenames (not IMG_xxxx.jpg)
- [ ] All images have alt text: 120-150 characters, descriptive and contextual
- [ ] Hero/LCP image: NOT lazy-loaded, has fetchpriority="high" and preload link in head
- [ ] Below-fold images: loading="lazy" attribute present
- [ ] All images served in WebP format (AVIF as progressive enhancement)
- [ ] srcset and sizes attributes set for all images (responsive delivery)
- [ ] width and height attributes set on all img elements (prevents CLS)
- [ ] ImageObject schema deployed on pages with primary images
- [ ] Image sitemap created, submitted to GSC, auto-updating
- [ ] og:image set on all pages (1200x630px minimum, WebP accepted)
- [ ] Captions written for all significant images (figcaption element)
- [ ] Product images: Minimum 6 per product (front, back, side, in-use, detail, scale)

### Video Optimization
- [ ] YouTube channel has manual VTT transcripts uploaded for all major videos
- [ ] All videos have chapters starting at 0:00 (minimum 3, target 5+)
- [ ] VideoObject schema deployed on all pages with embedded video
- [ ] Video sitemap created and submitted to GSC
- [ ] Thumbnails: 1280x720px, high contrast, readable text, consistent brand template
- [ ] TikTok captions written with first 150 characters keyword-optimized
- [ ] Instagram Reels: auto-captions enabled, keyword spoken in first 3 seconds

### Google Lens and Visual Shopping
- [ ] Products listed in Google Merchant Center with accurate GTIN data
- [ ] Bing Merchant Center feed created (separate from Google)
- [ ] Google Merchant Center: 360-degree spin images submitted where applicable
- [ ] Google AR product integration submitted for eligible beauty/apparel products
- [ ] GBP photos updated monthly with correctly named, alt-text-optimized images

### Voice Search
- [ ] Every FAQ section: question as H2/H3, 40-70 word direct answer immediately after
- [ ] FAQ schema wrapping all Q&A pairs
- [ ] GBP: Hours, phone, address verified and accurate (powers voice local results)
- [ ] Apple Business Connect listing claimed and optimized (Siri local search)
- [ ] Speakable schema implemented for news publishers and key FAQ pages

### Core Web Vitals
- [ ] LCP: Under 2.5s on mobile (check PageSpeed Insights)
- [ ] CLS: Under 0.1 (images have fixed dimensions set)
- [ ] FID/INP: Under 200ms (not image-specific but part of overall page health)
- [ ] Image CDN deployed (Cloudflare Images or equivalent)

### Measurement
- [ ] GSC Search type: Image monitored monthly
- [ ] GSC Video tab reviewed monthly
- [ ] YouTube Studio search traffic reviewed monthly (top queries driving views)
- [ ] Manual visual share of voice audit: Quarterly
- [ ] Rich Results Test run after any schema changes
- [ ] Screaming Frog image audit run quarterly (catch regressions)

---

*End of multimodal.md reference file. Part of the attainment-ai-search-visibility skill suite.*
