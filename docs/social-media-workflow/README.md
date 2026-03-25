# Social Media Content Workflow

## Overview

Every blog post in the JBM Content Hub includes comprehensive social media promotion content. This document outlines the workflow for creating Facebook posts that drive traffic to blog articles.

---

## The Three-Part Facebook Post System

Due to Facebook's algorithm changes that limit the reach of posts containing external links, we use a strategic three-part approach:

### Part 1: The Facebook Post

**Purpose:** Capture attention and drive engagement

**Structure:**
- Hook: A compelling opening that stops the scroll
- Value: Key insight or teaser from the blog
- CTA: Direct readers to the comment section for the link

**Example:**
```
🤖 Your business is bleeding hours every single day.

Studies show knowledge workers spend 40% of their time on tasks that could be automated.

That's nearly HALF your workweek disappearing into the void of repetition.

What if you could reclaim 20+ hours per employee every week?

Inside this guide, I break down:
→ The automation tools that actually deliver ROI
→ Step-by-step implementation for beginners
→ Common pitfalls that sabotage automation success

👇 Check the comments for the full guide
```

**Key Elements:**
- No external links (Facebook penalizes these)
- Strong visual hook (emoji + bold statement)
- Bullet points for scannability
- Clear CTA to comments

---

### Part 2: AI Image Generation Prompt

**Purpose:** Create captivating visual content for the post

**Specifications:**
- **Platform:** Instagram post format (used on Facebook as well)
- **Dimensions:** 1080 x 1080 pixels (square)
- **Aspect Ratio:** 1:1

**Prompt Structure:**
```
Create a [STYLE] image depicting [SUBJECT]. 

The scene should convey [EMOTION/CONCEPT]. 

Include [SPECIFIC ELEMENTS] that represent [KEY THEMES].

Style: [VISUAL STYLE GUIDANCE]

Colors: Deep gold (#C9A227), rich blue (#1E3A5F), white background, premium black accents (#1A1A1A)

Mood: Professional, luxurious, trustworthy

Size: 1080x1080 pixels, Instagram post format
```

**Example Prompt:**
```
Create a professional business illustration depicting automation and efficiency. 

The scene should convey transformation and productivity—showing a professional working alongside sleek, modern technology interfaces with automated workflows visualized as connected nodes and flowing lines.

Include elements like: floating task cards being automatically sorted, calendar events organizing themselves, email icons flowing into organized folders—all rendered in a clean, modern, slightly futuristic style.

Style: Modern corporate illustration with isometric elements, clean lines, and subtle gradients. Think premium tech company aesthetic.

Colors: Deep gold (#C9A227) for accent elements and highlights, rich blue (#1E3A5F) for primary elements and trust indicators, premium black (#1A1A1A) for text and outlines, pure white (#FFFFFF) background.

Mood: Sophisticated, professional, aspirational—not cluttered or overwhelming.

Composition: Centered focal point with supporting elements radiating outward, plenty of white space, balanced asymmetry.

Size: 1080x1080 pixels, Instagram post format, square aspect ratio
```

---

### Part 3: Facebook Comment with Link

**Purpose:** Deliver the blog link while maintaining post reach

**Structure:**
- Brief hook/reminder
- The link
- Secondary CTA

**Example:**
```
📚 Here's your complete guide to task automation:

[LINK TO BLOG POST]

Inside you'll discover:
• 5 automation tools that actually work for SMBs
• Implementation steps even beginners can follow
• ROI calculator to measure your time savings

Save this post and share with someone drowning in repetitive work! 🔄
```

**Key Elements:**
- Link placed early but not first line
- Additional value bullets to encourage click
- Social prompts (save, share)

---

## File Organization Structure

Each blog post has its own dedicated folder containing all related files:

```
content/
└── [category]/
    └── posts/
        └── [YYYY-MM-DD-post-slug]/
            ├── post.md                    # Markdown blog post
            ├── post.html                  # HTML blog post (Blogger-ready)
            ├── facebook-post.txt          # Part 1: FB post text
            ├── image-prompt.txt           # Part 2: AI image generation prompt
            └── facebook-comment.txt       # Part 3: FB comment with link
```

### Example:
```
content/
└── productivity-tools/
    └── posts/
        └── 2026-04-01-ultimate-guide-task-automation-tools/
            ├── post.md
            ├── post.html
            ├── facebook-post.txt
            ├── image-prompt.txt
            └── facebook-comment.txt
```

---

## Content Creation Workflow

### Step 1: Create Blog Post
1. Write blog post in Markdown format
2. Convert to HTML format
3. Save both files in post folder

### Step 2: Create Facebook Content
1. Extract key hook and value points from blog
2. Write Facebook post (no links, strong CTA to comments)
3. Save as `facebook-post.txt`

### Step 3: Create Image Prompt
1. Identify the core concept to visualize
2. Write detailed AI image generation prompt
3. Specify 1080x1080 Instagram post dimensions
4. Include JBM brand colors (gold/blue/black/white)
5. Save as `image-prompt.txt`

### Step 4: Create Facebook Comment
1. Write brief hook
2. Add link placeholder: `[LINK TO BLOG POST]`
3. Add value bullets
4. Include social prompts
5. Save as `facebook-comment.txt`

### Step 5: Generate Image
1. Use the image prompt with AI image generator
2. Use tools like: Midjourney, DALL-E, Leonardo AI, Ideogram
3. Save generated image in the same folder
4. Recommended filename: `featured-image.png`

---

## Facebook Post Best Practices

### Do's ✅

- **Hook with emotion:** Lead with a problem, statistic, or bold statement
- **Use line breaks:** Create visual hierarchy and scannability
- **Include emojis strategically:** Use 2-4 emojis for visual interest
- **Create curiosity:** Tease what they'll learn without giving everything away
- **Be specific:** "Reclaim 20+ hours" beats "save time"
- **Direct to comments:** Explicitly tell them where to find the link

### Don'ts ❌

- **Never include links in the main post** (kills reach)
- **Don't be overly promotional** (Facebook deprioritizes)
- **Avoid walls of text** (break into readable chunks)
- **Don't give away the full value** (leave reason to click)
- **Never post without an image** (visual posts get 2.3x more engagement)

---

## Image Design Guidelines

### Brand Consistency

All images should reflect JBM's luxury brand identity:

| Element | Specification |
|---------|---------------|
| Primary Accent | Deep Gold (#C9A227) |
| Primary Color | Rich Blue (#1E3A5F) |
| Text/Outlines | Premium Black (#1A1A1A) |
| Background | Pure White (#FFFFFF) |
| Style | Clean, modern, professional |
| Mood | Sophisticated, trustworthy, aspirational |

### Image Dimensions

| Format | Dimensions | Use Case |
|--------|------------|----------|
| Instagram Post | 1080 x 1080 px | Primary social post |
| Instagram Portrait | 1080 x 1350 px | Alternative option |
| Facebook Post | 1080 x 1080 px | Same as IG post |

### Visual Elements to Include

- Clean, uncluttered compositions
- Professional business imagery
- Technology/automation visual metaphors
- Plenty of white space
- Subtle gradients and depth
- Modern typography (if text included)

### Visual Elements to Avoid

- Cluttered or busy compositions
- Dated technology imagery
- Cheesy stock photo vibes
- Excessive text on images
- Low contrast elements
- Inconsistent color palettes

---

## Quality Checklist

Before publishing, verify:

### Blog Post
- [ ] Markdown file complete
- [ ] HTML file generated and formatted
- [ ] SEO meta description included
- [ ] Featured image sourced/created

### Facebook Content
- [ ] Post has strong hook (first line)
- [ ] No links in main post
- [ ] CTA directs to comments
- [ ] Line breaks for readability
- [ ] Emojis used appropriately

### Image Prompt
- [ ] Subject clearly described
- [ ] Style and mood specified
- [ ] Brand colors included
- [ ] 1080x1080 dimensions specified
- [ ] Enough detail for consistent results

### Facebook Comment
- [ ] Link placeholder included
- [ ] Value bullets present
- [ ] Social prompts (save/share) included
- [ ] Tone matches main post

---

## AI Image Generator Tool Recommendations

| Tool | Best For | Notes |
|------|----------|-------|
| Midjourney | Artistic, premium quality | Best for complex scenes |
| DALL-E 3 | Accurate prompt following | Good for text on images |
| Leonardo AI | Business illustrations | Free tier available |
| Ideogram | Text on images | Excellent typography |
| Adobe Firefly | Commercial safe | Integrated with Creative Cloud |

---

## Sample Complete Post Package

### Folder: `2026-04-01-ultimate-guide-task-automation-tools/`

**facebook-post.txt:**
```
🤖 Your business is bleeding hours every single day.

Studies show knowledge workers spend 40% of their time on tasks that could be automated.

That's nearly HALF your workweek disappearing into the void of repetition.

What if you could reclaim 20+ hours per employee every week?

Inside this guide, I break down:
→ The automation tools that actually deliver ROI
→ Step-by-step implementation for beginners
→ Common pitfalls that sabotage automation success

👇 Check the comments for the full guide
```

**image-prompt.txt:**
```
Create a professional business illustration depicting automation and efficiency. 

The scene should convey transformation and productivity—showing a professional working alongside sleek, modern technology interfaces with automated workflows visualized as connected nodes and flowing lines.

Include elements like: floating task cards being automatically sorted, calendar events organizing themselves, email icons flowing into organized folders—all rendered in a clean, modern, slightly futuristic style.

Style: Modern corporate illustration with isometric elements, clean lines, and subtle gradients. Think premium tech company aesthetic.

Colors: Deep gold (#C9A227) for accent elements and highlights, rich blue (#1E3A5F) for primary elements and trust indicators, premium black (#1A1A1A) for text and outlines, pure white (#FFFFFF) background.

Mood: Sophisticated, professional, aspirational—not cluttered or overwhelming.

Composition: Centered focal point with supporting elements radiating outward, plenty of white space, balanced asymmetry.

Size: 1080x1080 pixels, Instagram post format, square aspect ratio
```

**facebook-comment.txt:**
```
📚 Here's your complete guide to task automation:

[LINK TO BLOG POST]

Inside you'll discover:
• 5 automation tools that actually work for SMBs
• Implementation steps even beginners can follow
• ROI calculator to measure your time savings

Save this post and share with someone drowning in repetitive work! 🔄
```

---

*Last Updated: March 2026*
*JBM - Jovira Business Machine*
