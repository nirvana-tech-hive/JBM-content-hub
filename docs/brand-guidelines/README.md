# Brand Guidelines

## 🎨 Visual Identity System

This document establishes the visual standards for the Business Growth Content Hub. Adherence to these guidelines ensures brand consistency across all touchpoints.

---

## 🎯 Brand Positioning

### Brand Essence
**Intelligent Business Empowerment**

### Brand Promise
We deliver actionable, research-backed insights that help businesses cut costs, increase profits, and evolve with confidence.

### Brand Personality
| Trait | Expression |
|-------|------------|
| **Authoritative** | Expert knowledge, confident guidance |
| **Approachable** | Clear language, no gatekeeping |
| **Progressive** | Forward-thinking, innovation-focused |
| **Trustworthy** | Evidence-based, honest assessments |
| **Luxurious** | Premium feel, sophisticated design |

---

## 🎨 Color Palette

### Primary Colors

#### Deep Gold
```
HEX: #C9A227
RGB: 201, 162, 39
CMYK: 0, 19, 81, 21
```
**Usage:**
- Call-to-action buttons
- Accent highlights
- Important icons
- Border accents
- Premium badges

**Psychology:** Gold conveys success, achievement, and premium quality. It catches the eye without being aggressive.

---

#### Rich Blue
```
HEX: #1E3A5F
RGB: 30, 58, 95
CMYK: 68, 39, 0, 63
```
**Usage:**
- Primary headings
- Navigation elements
- Trust indicators
- Data visualizations
- Author credentials

**Psychology:** Deep blue builds trust, conveys professionalism, and creates a sense of stability and reliability.

---

### Secondary Colors

#### Premium Black
```
HEX: #1A1A1A
RGB: 26, 26, 26
CMYK: 0, 0, 0, 90
```
**Usage:**
- Body text on white backgrounds
- Primary text elements
- Borders and dividers
- Icon outlines

**Psychology:** Black provides sophistication, clarity, and excellent readability without harshness.

---

#### Pure White
```
HEX: #FFFFFF
RGB: 255, 255, 255
CMYK: 0, 0, 0, 0
```
**Usage:**
- Primary backgrounds
- Content areas
- Negative space
- Card backgrounds

**Psychology:** White creates breathing room, enhances readability, and conveys cleanliness and clarity.

---

#### Soft Gray
```
HEX: #F5F5F5
RGB: 245, 245, 245
CMYK: 0, 0, 0, 4
```
**Usage:**
- Secondary backgrounds
- Section dividers
- Disabled states
- Quote backgrounds

---

### Color Combinations

#### Approved Pairings
| Primary | Secondary | Use Case |
|---------|-----------|----------|
| White background | Black text | Body content |
| White background | Blue headings | Articles |
| Gold accent | White text | CTAs, badges |
| Blue background | White text | Headers, highlights |
| Gray background | Black text | Quotes, callouts |

#### Prohibited Combinations
- ❌ Gold text on white (low contrast)
- ❌ Blue text on black (readability issues)
- ❌ Black background for main content (not our theme)

---

## 📐 Typography

### Font Stack
```css
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
```

### Type Scale (Mobile-First)
```css
/* Mobile (base) */
h1 { font-size: 2rem; }      /* 32px */
h2 { font-size: 1.5rem; }    /* 24px */
h3 { font-size: 1.25rem; }   /* 20px */
h4 { font-size: 1.125rem; }  /* 18px */
p  { font-size: 1rem; }      /* 16px */
small { font-size: 0.875rem; } /* 14px */

/* Desktop */
@media (min-width: 768px) {
  h1 { font-size: 2.5rem; }  /* 40px */
  h2 { font-size: 1.75rem; } /* 28px */
  h3 { font-size: 1.5rem; }  /* 24px */
}
```

### Line Height
- **Headings:** 1.2-1.3
- **Body text:** 1.6-1.8
- **Lists:** 1.5

### Font Weights
- **Light (300):** Large display text only
- **Regular (400):** Body text
- **Medium (500):** Subheadings
- **Semi-Bold (600):** Important elements
- **Bold (700):** Headings, CTAs

---

## 🖼️ Imagery Guidelines

### Image Sources
**Primary Source: Unsplash Only**
All images must be sourced from Unsplash to ensure:
- High quality
- Legal compliance
- Consistent aesthetic
- Unique visual identity

### Image Selection Criteria

#### ✅ Select Images That:
- Feature business/professional settings
- Show diversity in subjects
- Have clean, uncluttered composition
- Convey positive emotions
- Are contextually relevant
- Have space for text overlay if needed

#### ❌ Avoid Images That:
- Appear staged or artificial
- Have cluttered backgrounds
- Feature dated technology
- Show controversial subjects
- Have watermarks from other sources

### Image Treatment
```css
/* Standard image treatment */
img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
}

/* Featured images */
.featured-image {
  width: 100%;
  aspect-ratio: 16/9;
  object-fit: cover;
}

/* Inline images */
.inline-image {
  margin: 24px 0;
  border: 1px solid #F5F5F5;
}
```

### Alt Text Guidelines
- Describe the image content clearly
- Include relevant keywords naturally
- Keep under 125 characters
- Don't start with "Image of..." or "Picture of..."

**Example:**
```
Good: "Business professional reviewing productivity dashboard on laptop"
Bad: "Image of a person working"
```

---

## 📱 Responsive Design Standards

### Breakpoints
```css
/* Mobile First */
/* Base styles for mobile */

/* Tablet */
@media (min-width: 768px) { }

/* Desktop */
@media (min-width: 1024px) { }

/* Large Desktop */
@media (min-width: 1280px) { }
```

### Mobile Optimization Requirements

#### Typography
- Minimum font size: 16px for body text
- Adequate line spacing (1.6+)
- Clear hierarchy

#### Touch Targets
- Minimum 44x44px for buttons
- Adequate spacing between links
- No hover-dependent interactions

#### Layout
- Single column for main content
- Adequate margins (20px minimum)
- No horizontal scrolling

#### Performance
- Optimized images (WebP when possible)
- Minimal external resources
- Fast initial load

---

## 🏷️ Content Templates

### Blog Post Structure

```
┌─────────────────────────────────────┐
│         FEATURED IMAGE              │
│    (Contextually relevant)          │
├─────────────────────────────────────┤
│  H1: MAIN TITLE                     │
│  [Category Badge] [Reading Time]    │
├─────────────────────────────────────┤
│  INTRODUCTION                       │
│  Hook + Value Proposition           │
├─────────────────────────────────────┤
│  H2: SECTION 1                      │
│  ───────────────────────            │
│  Content with H3 sub-sections       │
│                                     │
│  > Callout/Quote boxes              │
│                                     │
├─────────────────────────────────────┤
│  H2: SECTION 2                      │
│  ───────────────────────            │
│  Content continues...               │
├─────────────────────────────────────┤
│  KEY TAKEAWAYS                      │
│  • Actionable point 1               │
│  • Actionable point 2               │
│  • Actionable point 3               │
├─────────────────────────────────────┤
│  CTA SECTION                        │
│  [Deep Gold Button]                 │
├─────────────────────────────────────┤
│  AUTHOR + RELATED POSTS             │
└─────────────────────────────────────┘
```

### Callout Box Styles

```html
<!-- Quote Box -->
<blockquote style="border-left: 4px solid #C9A227; background: #F5F5F5; padding: 20px; margin: 24px 0;">
  "Quote text here"
</blockquote>

<!-- Info Box -->
<div style="background: #F5F5F5; border-radius: 8px; padding: 20px; margin: 24px 0;">
  <strong style="color: #1E3A5F;">📌 Key Insight:</strong>
  <p>Important information here...</p>
</div>

<!-- Warning Box -->
<div style="background: #FFF9E6; border-left: 4px solid #C9A227; padding: 20px; margin: 24px 0;">
  <strong>⚠️ Important:</strong>
  <p>Critical information...</p>
</div>
```

---

## 📊 Data Visualization

### Chart Colors
Use brand colors for data visualization:
- Primary data: `#1E3A5F` (Rich Blue)
- Secondary data: `#C9A227` (Deep Gold)
- Tertiary data: `#1A1A1A` (Premium Black)
- Background: `#F5F5F5` (Soft Gray)

### Chart Guidelines
- Clear titles and labels
- Legend when needed
- Mobile-responsive
- Accessible color contrast

---

## ✅ Brand Checklist

Before publishing any content, verify:

### Visual Elements
- [ ] Colors match brand palette
- [ ] Typography follows guidelines
- [ ] Images from Unsplash
- [ ] Proper alt text included

### Layout
- [ ] Mobile-first approach
- [ ] Adequate white space
- [ ] Clear hierarchy
- [ ] Touch-friendly elements

### Content
- [ ] Consistent voice and tone
- [ ] Professional appearance
- [ ] Clear CTAs in brand colors
- [ ] No competing visual elements

---

*These guidelines ensure every piece of content reflects our premium, trustworthy brand identity.*

*Last Updated: March 2026*
