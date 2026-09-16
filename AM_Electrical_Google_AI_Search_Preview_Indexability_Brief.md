# AM Electrical — Google Search Preview, Indexability & AI Discoverability Brief

## PURPOSE

This is a SECONDARY implementation brief to be used **in addition to the main AM Electrical SEO brief**.

Website:

**https://www.am-electrical.net/**

The specific problem to solve is visible in the attached Google Search screenshot.

The current Google result for AM Electrical is not presenting the business as strongly as it could.

The screenshot shows:

- The AM Electrical website result appears with a title similar to:
  **“AM Electrical: Electrician Lake Forest | Commercial …”**
- The snippet contains useful information, but Google is not presenting a particularly strong first-party business summary.
- Google's AI Overview is pulling business information from multiple external sources.
- Yelp and MapQuest are prominently surfaced as supporting sources/cards.
- The user's own website should become a much clearer, more authoritative first-party source for what AM Electrical is, where it operates, what it does, and how customers can contact it.

The goal is NOT to manipulate Google or artificially suppress Yelp/MapQuest.

The goal is to make the **official AM Electrical website so clear, crawlable, structured, and authoritative that Google has a strong first-party source to understand and reference.**

---

# VERY IMPORTANT: GOOGLE'S ACTUAL AI SEARCH GUIDANCE

Do not implement fake “AI SEO hacks.”

Google's current documentation says the same foundational SEO practices apply to AI Overviews and AI Mode. Pages need to be crawlable, indexable, eligible for normal Search snippets, and contain useful, people-first information.

Google specifically says there are **no additional technical requirements or special schema required for AI Overviews/AI Mode**.

Google also explicitly says that files such as `llms.txt` are not required for Google Search and do not improve Google Search visibility.

Therefore:

## DO NOT:

- Add `llms.txt because someone claims Google AI needs it
- Create fake AI-only pages
- Hide AI content from humans
- Stuff pages with long-tail queries
- Create hundreds of tiny “AI answer” pages
- Add fake structured data
- Add fake reviews
- Add fake business information
- Attempt to manipulate AI citations

## DO:

- Make the website crawlable
- Make important content indexable
- Make the business identity unambiguous
- Make the homepage semantically clear
- Use strong first-party textual content
- Use accurate structured data
- Make NAP/business information consistent
- Build useful service pages
- Build legitimate internal links
- Maintain an accurate Google Business Profile
- Use real first-hand business information
- Make the site fast and accessible
- Monitor Google Search Console

Google's current AI guidance:

https://developers.google.com/search/docs/appearance/ai-features

https://developers.google.com/search/docs/fundamentals/ai-optimization-guide

Google states that generative AI features use information from Google's Search index and that foundational SEO remains important.

---

# THE SPECIFIC PROBLEM SHOWN IN THE SCREENSHOT

Treat the screenshot as a search-result UX problem.

Google is currently able to identify:

> AM Electrical

and

> electrician / electrical contractor / Lake Forest

but the search result and AI-generated business presentation can be strengthened.

The result should make it extremely obvious to both humans and search systems:

> **AM Electrical is a licensed electrician/electrical contractor serving Lake Forest, California.**

The official website should clearly communicate:

- Business name
- Primary business category
- Location
- Address, where appropriate
- Phone
- Services
- Residential/commercial/industrial scope
- Emergency availability
- Experience
- Licensing information, if verified
- Service area
- Contact method
- Real-world business identity

---

# FIRST-PRIORITY GOAL

When someone searches for:

- AM Electrical Lake Forest
- AM Electrical Service Lake Forest
- electrician Lake Forest CA
- electrician in Lake Forest CA
- Lake Forest electrical contractor
- emergency electrician Lake Forest
- commercial electrician Lake Forest

the official AM Electrical website should present a strong, clear first-party result.

This does NOT mean guaranteeing position #1.

Google controls ranking and can rewrite titles/snippets.

The goal is to give Google the strongest accurate information possible so it can understand and represent the site correctly.

---

# GOOGLE SEARCH RESULT COMPONENTS TO OPTIMIZE

The official website result has several components:

1. Site name
2. Favicon
3. URL/domain
4. Title link
5. Snippet
6. Potential sitelinks
7. Structured information where eligible

Google generates these automatically, but site owners can influence them through site content and technical implementation.

Google documentation:

https://developers.google.com/search/docs/appearance/site-names

https://developers.google.com/search/docs/appearance/title-link

https://developers.google.com/search/docs/appearance/snippet

---

# 1. SITE NAME

Google should clearly understand the official site name as:

**AM Electrical**

Not:

- AM Electrical Service
- AM Electrical Contractor
- AM Electrical Lake Forest
- AM-Electrical.net
- some generic generated name

unless Google determines otherwise from external evidence.

Implement/verify `WebSite` structured data on the homepage.

Example concept:

```json
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "AM Electrical",
  "alternateName": "AM Electrical Service",
  "url": "https://www.am-electrical.net/"
}
```

Do not blindly use the alternate name.

Only use it if it is genuinely used by the business and supported by the existing business identity.

The visible homepage branding should consistently say:

**AM Electrical**

Google says `WebSite` structured data is the most important way to indicate a preferred site name.

---

# 2. HOMEPAGE TITLE LINK

Audit the current `<title>`.

The screenshot appears to show a title along the lines of:

> AM Electrical: Electrician Lake Forest | Commercial ...

This is directionally good but may be too broad/long and may not present the cleanest brand + location + service relationship.

Test a title such as:

> AM Electrical | Lake Forest, CA Electrician | 24-Hour Service

OR:

> AM Electrical | Lake Forest Electrician | 24-Hour Electrical Service

Choose the final version based on the actual homepage content and Google title guidelines.

The title should communicate:

**brand + primary service + location + legitimate differentiator**

Do not cram every service into the homepage title.

Do not use:

> Best #1 Top-Rated Cheapest Electrician Lake Forest CA Commercial Residential Industrial Emergency Electrician

---

# 3. HOMEPAGE H1

The visible H1 should reinforce the same entity relationship.

Recommended conceptual direction:

> **Lake Forest Electrician for Residential & Commercial Electrical Service**

If industrial work is a genuine core offering, include it naturally in supporting copy rather than making the H1 excessively long.

The first screen of the site should clearly communicate:

**AM Electrical = electrician = Lake Forest**

---

# 4. HOMEPAGE INTRODUCTION

The first substantial text on the homepage should give Google and users an unambiguous business summary.

Use real facts.

Conceptual structure:

> **AM Electrical is a licensed electrical contractor serving Lake Forest, California, with 37 years of electrical experience. The business provides residential, commercial and industrial electrical service, including electrical repair, troubleshooting, upgrades and 24-hour emergency response.**

Do not copy this blindly.

Verify every claim against the existing site/business information.

The important principle is:

**Say exactly what the business is, where it is, what it does, and why it is established.**

---

# 5. META DESCRIPTION

Create a strong homepage meta description.

Possible direction:

> AM Electrical provides licensed residential, commercial and industrial electrical service in Lake Forest, CA, with 37 years of experience and 24-hour emergency response.

Verify all facts.

Do not assume Google will always use the meta description.

Google primarily generates snippets from page content and may use the meta description when it provides a better description.

Therefore:

**The visible homepage content must also contain the same core facts.**

Do not hide important business information exclusively inside metadata.

---

# 6. SEARCH SNIPPET OPTIMIZATION

The screenshot indicates that the Google preview should do a better job of communicating the business.

Build a highly understandable opening section.

The page should naturally contain phrases and concepts such as:

- AM Electrical
- Lake Forest, California
- electrician
- electrical contractor
- residential electrical service
- commercial electrical service
- industrial electrical service
- electrical repair
- emergency electrical service
- 24-hour response
- 37 years of experience

Only include services actually offered.

Do not repeat these terms unnaturally.

Google can generate different snippets depending on the search query.

The goal is to give Google multiple strong passages from which to construct relevant snippets.

---

# 7. BUSINESS ENTITY CLARITY

This is one of the highest priorities.

The site should consistently describe the same real-world entity.

Create a coherent relationship:

```text
AM Electrical
      │
      ├── Electrician / Electrical Contractor
      │
      ├── Lake Forest, California
      │
      ├── 37 Years Experience
      │
      ├── Residential
      │
      ├── Commercial
      │
      ├── Industrial
      │
      ├── Electrical Repair
      │
      └── 24-Hour Emergency Response
```

The same entity should be recognizable across:

- Homepage
- About page
- Contact page
- Service pages
- Footer
- Structured data
- Google Business Profile
- legitimate directory listings

---

# 8. LOCAL BUSINESS STRUCTURED DATA

Audit the existing JSON-LD.

Implement accurate LocalBusiness/electrical-business structured data where appropriate.

Potential properties:

- `@type`
- `@id`
- `name`
- `url`
- `telephone`
- `address`
- `areaServed`
- `sameAs`
- `logo`
- `image`
- `description`
- `openingHoursSpecification`
- `contactPoint`

Only include properties that can be verified.

Use a stable entity ID such as:

```text
https://www.am-electrical.net/#business
```

Conceptual structure:

```json
{
  "@context": "https://schema.org",
  "@type": "Electrician",
  "@id": "https://www.am-electrical.net/#business",
  "name": "AM Electrical",
  "url": "https://www.am-electrical.net/",
  "telephone": "VERIFIED_PHONE",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "VERIFIED_ADDRESS",
    "addressLocality": "Lake Forest",
    "addressRegion": "CA",
    "postalCode": "VERIFIED_ZIP",
    "addressCountry": "US"
  }
}
```

Do not copy placeholder values into production.

Validate the final structured data.

Google's structured-data guidance:

https://developers.google.com/search/docs/appearance/structured-data/intro

---

# 9. ENTITY RELATIONSHIPS

Where appropriate, connect structured data entities using:

- `@id`
- `url`
- `mainEntity`
- `mainEntityOfPage`
- `about`
- `provider`
- `areaServed`
- `sameAs`

Do not over-engineer the graph.

The goal is a clean, truthful entity graph.

Conceptually:

```text
WebSite
   │
   └── publisher / about
             ↓
        AM Electrical
             │
             ├── provides → Electrical Services
             ├── areaServed → Lake Forest
             └── sameAs → verified external business profiles
```

---

# 10. SAMEAS / EXTERNAL SOURCES

This is particularly important because the screenshot shows Google using external sources such as Yelp and MapQuest.

Do NOT attempt to eliminate these sources.

Instead, make the official website and legitimate business profiles agree.

Audit:

- Google Business Profile
- Yelp
- MapQuest
- Facebook
- any legitimate business directories
- licensing/business references where publicly available

Check:

- Business name
- Phone
- Address
- Website
- Category
- Description
- Service area

Correct inconsistencies where the business owner controls the listing.

Do not create fake listings.

Do not create dozens of low-quality directory profiles just for SEO.

---

# 11. GOOGLE BUSINESS PROFILE

The Google Business Profile is extremely important for a local business.

Audit the relationship between the website and GBP.

The website should not contradict GBP.

Verify:

- business name
- primary category
- address
- phone
- website
- hours
- emergency availability
- services
- service areas
- business description

If GBP information is missing or inaccurate, create an OWNER TASK rather than inventing information.

Google's generative AI guidance specifically points to keeping Business Profile information up to date for local business visibility.

---

# 12. YELP / MAPQUEST PROBLEM

Do NOT frame this as:

> “How do we make Yelp disappear?”

That is the wrong goal.

The correct goal is:

> “How do we make AM Electrical's own website a stronger and clearer first-party source than the information Google currently has to assemble from third-party listings?”

The screenshot shows that Google is using Yelp and MapQuest as sources for business information.

That suggests a useful audit:

### Check whether these external listings agree with the official site.

If they disagree:

- identify the discrepancy
- correct owner-controlled listings where possible
- make the website consistent
- make GBP consistent
- use verified `sameAs` relationships where appropriate

If they agree:

- leave them alone
- focus on improving the first-party website's authority, content, crawlability, and entity clarity

---

# 13. FIRST-PARTY CONTENT SHOULD ANSWER BASIC ENTITY QUESTIONS

The homepage should answer these questions directly.

### Who are you?

> AM Electrical

### What are you?

> Licensed electrician / electrical contractor

### Where are you?

> Lake Forest, California

### What do you do?

> Residential, commercial and industrial electrical service

### What problems do you handle?

> Electrical repair, troubleshooting, upgrades, etc.

### Are you available for emergencies?

> 24-hour response, if verified

### How much experience?

> 37 years, if verified

### How do I contact you?

> Phone/contact form

These facts should exist in visible HTML, not only JavaScript, images, or metadata.

---

# 14. CRAWLABILITY

Audit the actual HTML Google receives.

Important content should be present in crawlable HTML.

Check:

- HTTP status
- robots.txt
- robots meta tags
- canonical
- JavaScript rendering
- hydration
- dynamically injected text
- hidden content
- lazy-loaded critical content
- navigation links
- sitemap
- internal links

Do not assume that because content appears visually in a browser it is necessarily ideal for crawling.

Google can process JavaScript, but clear server-rendered/indexable content is preferable when practical.

---

# 15. INDEXABILITY

For every important URL:

Check:

- returns HTTP 200
- indexable
- no accidental `noindex`
- not blocked by robots.txt
- canonical points to itself
- linked internally
- included in sitemap where appropriate
- useful unique content

Create an indexability table:

| URL | HTTP | Indexable | Canonical | Sitemap | Internal Links | Notes |
|---|---:|---:|---:|---:|---:|---|

---

# 16. INTERNAL LINKING FOR AI + SEARCH

Google's AI systems can use query fan-out and retrieve multiple related pages.

Make it easy for the site to establish relationships between services and location.

Example:

```text
Homepage
   ↓
Lake Forest Electrician
   ↓
Electrical Repair
   ↓
Emergency Electrical Service
   ↓
Commercial Electrical
   ↓
Contact
```

Use descriptive anchor text.

Avoid:

- click here
- learn more
- read more

when a more descriptive anchor is natural.

Example:

> View our electrical repair services in Lake Forest

is more useful than:

> Click here

---

# 17. SERVICE PAGES AS AI-RETRIEVABLE SOURCES

Each important service should have a dedicated, useful page where justified.

Example:

```text
/electrical-repair-lake-forest-ca
/emergency-electrician-lake-forest-ca
/commercial-electrician-lake-forest-ca
/residential-electrician-lake-forest-ca
```

Only create pages for real services.

Each page should clearly state:

- service
- location
- who the service is for
- common problems
- what AM Electrical does
- when customers should call
- emergency information if relevant
- contact CTA

This gives Google individual authoritative pages it can retrieve when users ask specific questions.

---

# 18. AI-STYLE QUESTION COVERAGE

Do not create hundreds of FAQ pages.

Instead, make existing service pages genuinely answer common customer questions.

Examples:

### Electrical Repair

> What are common signs that a home needs electrical repair?

### Emergency Service

> When should I call an emergency electrician?

### Electrical Panels

> When should an electrical panel be inspected or upgraded?

### Commercial

> What types of commercial electrical work does AM Electrical provide?

Answer based on actual company services and expertise.

Use concise direct answers followed by useful detail.

This makes the content useful to humans and easier for search systems to understand.

---

# 19. FIRST-PARTY EXPERTISE

This is especially important for Google's current generative-AI guidance.

Google says unique, non-commodity content can be valuable.

Do not fill the site with generic AI-written electrical advice.

Instead, incorporate authentic business knowledge such as:

- 37 years of experience
- actual types of jobs handled
- actual commercial/industrial experience
- common electrical issues encountered
- real project photos
- real service process
- real safety considerations
- actual service limitations
- genuine local knowledge

The website should contain information that is difficult for a generic AI content farm to reproduce accurately.

---

# 20. REAL PHOTOS

Use authentic AM Electrical photos wherever possible.

Useful examples:

- actual electrician
- actual service vehicle
- actual electrical panels
- actual commercial work
- actual industrial work
- actual completed projects
- legitimate Lake Forest/local business imagery

Add:

- descriptive filenames
- useful alt text
- image dimensions
- optimized formats
- relevant captions where useful

Do not pretend stock photos are actual AM Electrical work.

---

# 21. FAVICON / BRAND RECOGNITION

Audit the favicon.

The Google result should have a recognizable AM Electrical icon.

Ensure:

- favicon exists
- correct dimensions
- crawlable
- appropriate `<link rel="icon">`
- consistent branding

Google recommends providing a favicon of at least 48×48 pixels.

---

# 22. OPEN GRAPH

Audit:

```text
og:title
og:description
og:image
og:url
og:type
og:site_name
```

Homepage example direction:

```text
og:title = AM Electrical | Lake Forest, CA Electrician
og:description = Licensed electrical service for Lake Forest homes, businesses and properties, with 37 years of experience and 24-hour response.
og:site_name = AM Electrical
og:url = https://www.am-electrical.net/
```

Verify every claim.

Use a high-quality representative image.

---

# 23. SOCIAL / EXTERNAL BRAND CONSISTENCY

Search the web for the business name.

Document:

- Google
- Yelp
- MapQuest
- Facebook
- other legitimate profiles

Create:

| Source | Business Name | Phone | Address | Website | Category | Status |
|---|---|---|---|---|---|---|

Identify inconsistencies.

Do not create fake profiles.

---

# 24. SEARCH CONSOLE

This is mandatory if access is available.

Inspect:

- URL Inspection
- Page indexing
- Sitemaps
- Performance
- queries
- pages
- countries
- devices
- Search appearance
- generative AI performance report

Google launched dedicated Search Console reporting for generative AI visibility in 2026.

Use it.

Google documentation/report announcement:

https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports

The report can show:

- impressions
- pages
- countries
- devices
- dates

Use this to establish a baseline before making changes.

---

# 25. REQUEST RECRAWL AFTER CHANGES

After implementation:

1. Deploy
2. Verify production HTML
3. Validate structured data
4. Verify robots.txt
5. Verify sitemap
6. Use Search Console URL Inspection
7. Request indexing/recrawl where appropriate
8. Submit/update sitemap

Do not expect Google to change the search preview instantly.

Google states that recrawling/reprocessing can take days to weeks or longer depending on the situation.

---

# 26. GOOGLE SEARCH TEST QUERIES

After implementation, monitor these exact searches:

```text
AM Electrical
AM Electrical Lake Forest
AM Electrical Service Lake Forest
electrician Lake Forest CA
electrician in Lake Forest CA
Lake Forest electrical contractor
emergency electrician Lake Forest
commercial electrician Lake Forest
residential electrician Lake Forest
electrical repair Lake Forest CA
```

Record:

- whether official website appears
- title shown
- snippet shown
- site name shown
- favicon
- sitelinks
- AI Overview mentions
- sources used by AI Overview
- GBP information
- third-party listing discrepancies

Do not claim success until Google has recrawled/reprocessed the changes.

---

# 27. SEARCH RESULT TARGET

The desired conceptual result is something like:

**AM Electrical**

**AM Electrical | Lake Forest, CA Electrician | 24-Hour Service**

> Licensed electrical contractor serving Lake Forest, CA with 37 years of experience. Residential, commercial and industrial electrical service, including repair, troubleshooting and 24-hour emergency response.

This is an example target, not a guarantee of the exact text Google will display.

Google may rewrite both title and snippet.

---

# 28. AI OVERVIEW TARGET

The goal is for Google to have enough trustworthy first-party information to confidently understand:

> AM Electrical is a Lake Forest, California electrical contractor/electrician offering residential, commercial and industrial electrical services, with 37 years of experience and 24-hour emergency response.

The goal is NOT to force Google to say this exact sentence.

The website should simply make this fact pattern extremely clear.

---

# 29. DO NOT OVERFOCUS ON “AI SEO”

The highest priority remains:

```text
CRAWLABLE
   ↓
INDEXABLE
   ↓
CLEAR ENTITY
   ↓
STRONG LOCAL SIGNALS
   ↓
USEFUL SERVICE CONTENT
   ↓
INTERNAL LINKS
   ↓
STRUCTURED DATA
   ↓
GOOGLE BUSINESS PROFILE
   ↓
LEGITIMATE EXTERNAL CONSISTENCY
   ↓
SEARCH CONSOLE MONITORING
```

AI visibility is downstream from much of this.

---

# 30. REQUIRED AUDIT OUTPUT

Before changing the site, produce:

## A. Current Google Result Audit

Document what is currently visible in the provided screenshot.

Specifically evaluate:

- title
- snippet
- site name
- favicon
- URL
- AI Overview
- Yelp appearance
- MapQuest appearance

## B. Homepage HTML Audit

Report:

- title
- meta description
- H1
- first 500 words
- canonical
- robots
- structured data
- Open Graph
- favicon
- internal links
- indexability

## C. Entity Audit

Report how AM Electrical is currently represented across the website.

## D. External Entity Audit

Check Google/legitimate third-party sources where accessible.

## E. Indexability Audit

Report every issue.

## F. AI Discoverability Audit

Identify:

- useful first-party content
- missing entity facts
- missing service relationships
- weak content
- inaccessible content
- structured-data problems
- local business gaps

---

# 31. REQUIRED IMPLEMENTATION

After the audit, implement the highest-value fixes.

Prioritize:

### PRIORITY 1

- Homepage title
- Homepage H1
- Homepage opening copy
- Homepage meta description
- WebSite schema
- LocalBusiness/Electrician schema
- canonical
- robots
- sitemap
- favicon
- crawlability

### PRIORITY 2

- Internal links
- service pages
- entity consistency
- local business information
- Open Graph
- service relationships
- authentic first-party content

### PRIORITY 3

- supporting location/service pages
- external listing consistency
- additional media
- advanced enhancements

---

# 32. DO NOT DESTROY THE CURRENT DESIGN

The existing website should remain visually professional.

Do not:

- turn the homepage into an SEO wall of text
- add huge keyword sections
- create ugly visible schema blocks
- add repetitive city lists
- add giant FAQ walls
- ruin mobile UX
- overload the hero
- remove strong branding

SEO improvements should be integrated into the existing design.

---

# 33. IMPORTANT BUSINESS FACTS

Use these as the intended positioning, but verify them against the actual site/business information before implementation:

- Business: AM Electrical
- Location: Lake Forest, California
- Experience: 37 years
- Licensed California electrical professional/contractor
- Residential service
- Commercial service
- Industrial experience
- 24-hour response/emergency service
- Real Lake Forest location

Do not invent or modify these facts without verification.

---

# 34. FINAL DELIVERABLE

After completing the work, provide:

## SEARCH PREVIEW

Before:

```text
Current title:
Current snippet:
Current site name:
```

After:

```text
Recommended title:
Recommended snippet:
Recommended site name:
```

## TECHNICAL

```text
Indexability:
Canonical:
Robots:
Sitemap:
Structured data:
WebSite schema:
LocalBusiness schema:
Favicon:
Open Graph:
Internal linking:
```

## AI / ENTITY

Explain:

- How the official site now communicates the business entity
- What first-party information was added
- How service/location relationships are represented
- What makes the information easier for search systems to retrieve
- What was done to improve consistency with GBP/external listings

## EXTERNAL SOURCES

List discrepancies found across:

- Google Business Profile
- Yelp
- MapQuest
- other legitimate sources

Do not claim external corrections were made unless you actually had access to make them.

## SEARCH CONSOLE

State:

- whether Search Console was accessible
- whether the site was inspected
- whether sitemap was submitted
- whether recrawl was requested
- whether AI visibility data was available

Never claim something was verified if it wasn't.

---

# FINAL PRINCIPLE

The objective is NOT:

> “Make Google AI like the website.”

The objective is:

> **Make AM Electrical the clearest, most complete, crawlable first-party representation of the real AM Electrical business on the web.**

Google's own guidance says AI search is grounded in its Search index and that foundational SEO still matters.

So build the website so Google can confidently answer:

**Who is AM Electrical?**

**Where are they?**

**What do they do?**

**What services do they provide?**

**Who do they serve?**

**How long have they been doing it?**

**How can someone contact them?**

**What evidence exists that this is a real local business?**

If the website answers those questions clearly in crawlable HTML, with consistent business information and accurate structured data, it becomes a much stronger first-party source for both traditional Google Search and Google's generative search experiences.

---

## OFFICIAL GOOGLE REFERENCES

Google — AI features and your website:
https://developers.google.com/search/docs/appearance/ai-features

Google — Optimizing for generative AI features:
https://developers.google.com/search/docs/fundamentals/ai-optimization-guide

Google — Site names:
https://developers.google.com/search/docs/appearance/site-names

Google — Title links:
https://developers.google.com/search/docs/appearance/title-link

Google — Search snippets:
https://developers.google.com/search/docs/appearance/snippet

Google — Structured data:
https://developers.google.com/search/docs/appearance/structured-data/intro

Google — Generative AI Search Console reporting:
https://developers.google.com/search/blog/2026/06/gen-ai-performance-reports
