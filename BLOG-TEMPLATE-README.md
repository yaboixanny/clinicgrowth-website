# Blog Post Template Guide

This guide explains how to use the `blog-post-template.html` file to create new blog posts for the ClinicGrowth website.

## Quick Start

1. Copy `blog-post-template.html` and rename it to your blog post slug (e.g., `how-to-optimize-google-ads-for-pain-clinics.html`)
2. Search for all `[BRACKETED PLACEHOLDERS]` and replace them with your content
3. Save and push to GitHub

## Template Structure

### 1. Meta Information (Lines 1-15)
Replace these placeholders:
- `[META DESCRIPTION]` - 150-160 character summary for search engines
- `[BLOG POST TITLE]` - The main title that appears in browser tabs and search results

**Example:**
```html
<meta name="description" content="Learn how Google Ads delivers immediate patient flow for pain management clinics while SEO, referrals, and social media take months to produce results.">
<title>Why Google Ads is the Fastest Way to Fill Your Appointment Calendar | ClinicGrowth</title>
```

### 2. Hero Section
Replace:
- `[CATEGORY]` - e.g., "Practice Growth Insights", "Marketing Strategy", "Patient Acquisition"
- `[BLOG POST TITLE]` - The H1 heading (can be same or different from meta title)
- `[MONTH YEAR]` - Publication date (e.g., "January 2026")
- `[CATEGORY NAME]` - Category for organizational purposes

**Example:**
```html
<span class="section-label">Practice Growth Insights</span>
<h1 class="hero-title" style="font-size: clamp(2rem, 5vw, 3.5rem);">
    Why Google Ads is the Fastest Way to Fill Your Appointment Calendar
</h1>
<div class="blog-meta">
    Published: January 2026 | Category: Patient Acquisition Strategy
</div>
```

### 3. Blog Content Structure

#### Lead Paragraph
Use the `.lead` class for a larger, eye-catching opening:
```html
<p class="lead">Running a pain management clinic requires more than clinical expertise — it demands predictable patient flow.</p>
```

#### Main Sections (H2 Headings)
Use this format for major section headings:
```html
<h2 style="font-family: var(--font-display); font-size: 2rem; font-weight: 700; color: var(--color-navy); margin-top: var(--spacing-lg); margin-bottom: var(--spacing-md);">
    The Marketing Timeline Reality
</h2>
```

#### Subpoints
Use this format for emphasized subpoints within sections:
```html
<p><strong style="color: var(--color-navy); font-size: 1.1rem;">SEO: 3-6 Months (Slow Build)</strong><br>
Search engine optimization is valuable for long-term organic visibility...</p>
```

#### Bulleted Lists
Use this format for lists:
```html
<ul style="margin-left: 2rem; margin-top: var(--spacing-sm); margin-bottom: var(--spacing-md); line-height: 1.8;">
    <li style="margin-bottom: 0.75rem;"><strong>Seasonal fluctuations</strong> in patient volume</li>
    <li style="margin-bottom: 0.75rem;"><strong>New location launches</strong> that need immediate visibility</li>
</ul>
```

#### Internal Links
Always include 2-3 internal links with keyword-rich anchor text:
```html
<a href="google-ads.html" style="color: var(--color-coral); font-weight: 600; text-decoration: underline;">Google Ads for pain management clinics</a>
```

#### CTA Box
The highlighted call-to-action box at the end of the post:
```html
<div style="margin-top: var(--spacing-lg); padding: var(--spacing-md); background-color: var(--color-light-gray); border-left: 4px solid var(--color-coral);">
    <p style="margin: 0;"><strong>Ready to fill your appointment calendar?</strong> Our <a href="google-ads.html">Google Ads service</a> can have your campaign live within days.</p>
</div>
```

## SEO Best Practices

### Filename
Use descriptive, keyword-rich filenames:
- ✅ `why-google-ads-fastest-way-fill-appointment-calendar.html`
- ❌ `blog-post-1.html`

### Internal Linking
- Include 2-3 internal links to service pages
- Use natural, keyword-rich anchor text
- Link to relevant service pages: `google-ads.html`, `meta-ads.html`, `seo.html`

### Content Length
Aim for 800-1500 words for optimal SEO performance

### Headers
- One H1 (in the hero section)
- 3-5 H2s for main sections
- Use descriptive, benefit-focused headings

## Related Services Section

The template includes three service cards by default. Adjust which services to highlight based on the blog post topic:

```html
<!-- Example: For a Google Ads blog post, feature Google Ads first -->
<div class="service-card">
    <div class="service-icon">🎯</div>
    <h3>Google Ads Management</h3>
    <p>Launch targeted campaigns that bring qualified patients to your clinic</p>
    <a href="google-ads.html" class="btn btn-secondary">Learn More →</a>
</div>
```

## Style Guide

### Tone
- Professional but conversational
- Focus on business outcomes, not technical jargon
- Speak directly to pain clinic owners/managers

### Formatting
- Keep paragraphs 2-4 sentences
- Use bold for emphasis on key points
- Break up long sections with subheadings
- Use lists to improve scannability

### Keywords
Naturally incorporate relevant keywords:
- Pain management clinics
- Patient acquisition
- Google Ads for healthcare
- Medical practice marketing
- Clinic growth

## Checklist Before Publishing

- [ ] All `[PLACEHOLDERS]` replaced
- [ ] Meta description is 150-160 characters
- [ ] Title tag is compelling and includes primary keyword
- [ ] H1 in hero section is clear and benefit-focused
- [ ] 2-3 internal links with keyword anchor text
- [ ] Lead paragraph hooks the reader
- [ ] 3-5 H2 section headings
- [ ] CTA box at end with strong call-to-action
- [ ] Filename is descriptive and SEO-friendly
- [ ] Content is 800+ words
- [ ] Grammar and spelling checked
- [ ] Pushed to GitHub

## Example Blog Posts

Reference these existing blog posts for examples:
- `why-google-ads-fastest-way-fill-appointment-calendar.html`

## Need Help?

If you need assistance creating blog posts, refer to the original brief or contact the development team.
