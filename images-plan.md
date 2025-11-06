# Emergency HVAC Repair Website - Image Strategy & Implementation Plan
## Birmingham, Alabama Focus

---

## Table of Contents
1. [Hero Section Images](#hero-section-images)
2. [Service Images](#service-images)
3. [Trust & Credibility Images](#trust-credibility-images)
4. [Icons & Graphics](#icons-graphics)
5. [Image Optimization Guidelines](#image-optimization-guidelines)
6. [File Naming Convention](#file-naming-convention)
7. [Stock Photo Sources & Search Strategy](#stock-photo-sources)
8. [Implementation Checklist](#implementation-checklist)

---

## Hero Section Images

### Image 1: Primary Hero - Emergency HVAC Technician at Work
**Purpose:** First impression, establish trust and urgency, showcase professionalism

**Ideal Image Description:**
- Professional HVAC technician in clean uniform (preferably blue or red company colors)
- Working on residential AC unit or furnace
- Daytime setting with clear, bright lighting
- Modern home setting (Southern architecture if possible)
- Technician should appear focused, competent, and professional
- Tools visible (gauges, multimeter, or tablet)
- Close to medium shot showing technician and equipment
- Warm, welcoming expression if face is visible

**Stock Photo Search Terms:**
- Primary: "hvac technician emergency repair"
- Secondary: "air conditioning technician residential"
- Alternative: "furnace repair professional", "ac technician work", "heating cooling technician"
- Location-specific: "hvac technician southern home", "air conditioning repair house"

**Recommended Sources:**
- Unsplash: Search "HVAC technician", "air conditioning repair"
- Pexels: Search "technician repair", "hvac professional"
- Pixabay: Search "air conditioner repair", "hvac service"
- Premium alternatives: Shutterstock, Adobe Stock (search "emergency hvac repair Birmingham")

**File Name:** `hero-emergency-hvac-technician-birmingham-al.jpg`

**Alt Text:** "Emergency HVAC technician repairing air conditioning unit in Birmingham AL home with professional tools and equipment"

**Optimization Requirements:**
- Dimensions: 1920x1080px (16:9 ratio) or 2400x1600px for retina displays
- Format: WebP (primary) with JPG fallback
- Compression: 80-85% quality
- File size target: <200KB (WebP), <300KB (JPG)
- Lazy loading: No (above fold)

**HTML Placement:**
```html
<section class="hero" id="hero">
  <picture>
    <source srcset="images/hero-emergency-hvac-technician-birmingham-al.webp" type="image/webp">
    <img src="images/hero-emergency-hvac-technician-birmingham-al.jpg"
         alt="Emergency HVAC technician repairing air conditioning unit in Birmingham AL home with professional tools and equipment"
         width="1920" height="1080"
         class="hero-image">
  </picture>
</section>
```

### Image 2: Secondary Hero/Above Fold - Service Truck
**Purpose:** Establish local presence, professional appearance

**Ideal Image Description:**
- Clean, professional HVAC service truck/van
- Suburban residential setting
- Daytime with good lighting
- White or light-colored vehicle preferred
- Company branding area visible (can overlay text later)
- Parked in driveway or street

**Stock Photo Search Terms:**
- "hvac service truck", "air conditioning service van"
- "plumbing truck driveway", "service vehicle residential"
- "contractor van house"

**File Name:** `service-truck-emergency-hvac-birmingham.jpg`

**Alt Text:** "24/7 emergency HVAC service truck ready for AC and furnace repairs in Birmingham Alabama"

**Optimization Requirements:**
- Dimensions: 1200x800px
- Format: WebP with JPG fallback
- Compression: 80-85% quality
- File size: <150KB
- Lazy loading: Yes

---

## Service Images

### Image 3: Air Conditioning Repair
**Purpose:** Showcase AC repair expertise, visual for AC service section

**Ideal Image Description:**
- Technician working on outdoor AC condenser unit
- Residential setting (backyard/side of house)
- Technician using diagnostic tools (gauges, multimeter)
- Clean uniform, professional appearance
- Summer/warm weather context
- Clear view of AC unit components

**Stock Photo Search Terms:**
- "air conditioning repair outdoor unit"
- "hvac technician ac condenser", "cooling system repair"
- "ac unit maintenance technician"
- "air conditioner repair residential"

**File Name:** `ac-repair-service-birmingham-emergency.jpg`

**Alt Text:** "Professional HVAC technician diagnosing and repairing residential air conditioning unit in Birmingham AL during emergency service call"

**Optimization Requirements:**
- Dimensions: 800x600px or 1200x900px
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <120KB
- Lazy loading: Yes

**HTML Placement:**
```html
<section class="services" id="ac-repair">
  <div class="service-card">
    <img src="images/ac-repair-service-birmingham-emergency.webp"
         alt="Professional HVAC technician diagnosing and repairing residential air conditioning unit in Birmingham AL during emergency service call"
         loading="lazy"
         width="800" height="600">
  </div>
</section>
```

### Image 4: Furnace/Heating Repair
**Purpose:** Showcase heating expertise, winter service visual

**Ideal Image Description:**
- Technician working on residential furnace (indoor/basement setting)
- Opening furnace panel or checking components
- Interior home setting (basement, utility room, or garage)
- Professional tools visible
- Good lighting showing detail
- Focus on safety and expertise

**Stock Photo Search Terms:**
- "furnace repair technician", "heating system maintenance"
- "gas furnace repair", "hvac furnace service"
- "heating repair professional", "home furnace technician"

**File Name:** `furnace-repair-heating-service-birmingham.jpg`

**Alt Text:** "Emergency furnace repair technician servicing residential heating system in Birmingham Alabama home for optimal winter comfort"

**Optimization Requirements:**
- Dimensions: 800x600px or 1200x900px
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <120KB
- Lazy loading: Yes

### Image 5: Technician with Tools/Equipment
**Purpose:** Show professionalism, expertise, and preparedness

**Ideal Image Description:**
- HVAC technician with tool bag or carrying equipment
- Professional uniform/branded shirt
- Confident, friendly demeanor
- Walking toward camera or home entrance
- Tools clearly visible (gauge set, toolbag, tablet)
- Bright, professional lighting

**Stock Photo Search Terms:**
- "hvac technician tools equipment"
- "professional technician tool bag", "service technician arriving"
- "repairman tools residential", "contractor equipment"

**File Name:** `hvac-technician-professional-tools-birmingham.jpg`

**Alt Text:** "Licensed HVAC technician with professional tools arriving for emergency heating and cooling repair in Birmingham AL"

**Optimization Requirements:**
- Dimensions: 600x800px (portrait) or 800x600px (landscape)
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <100KB
- Lazy loading: Yes

### Image 6: Technician Working Detail Shot
**Purpose:** Show technical expertise and attention to detail

**Ideal Image Description:**
- Close-up of hands working on HVAC components
- Using diagnostic tools (multimeter, gauges, temperature probe)
- Clear focus on technical work
- Professional appearance
- Good lighting showing detail

**Stock Photo Search Terms:**
- "hvac technician hands tools", "air conditioner repair close up"
- "technician multimeter hvac", "hvac diagnostic tools"
- "repair hands tools professional"

**File Name:** `hvac-repair-detail-diagnostic-birmingham.jpg`

**Alt Text:** "Detailed HVAC diagnostic and repair work by certified Birmingham Alabama emergency technician using professional equipment"

**Optimization Requirements:**
- Dimensions: 800x600px
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <100KB
- Lazy loading: Yes

---

## Trust & Credibility Images

### Image 7: Certified Technician Portrait
**Purpose:** Build trust, show professionalism and credibility

**Ideal Image Description:**
- Professional headshot or upper-body portrait
- HVAC technician in clean company uniform
- Friendly, confident smile
- Arms crossed or holding tools professionally
- Neutral or service vehicle background
- Direct eye contact with camera
- Diverse representation when possible

**Stock Photo Search Terms:**
- "professional hvac technician portrait"
- "technician uniform smiling", "service professional headshot"
- "contractor portrait confident", "repairman professional"

**File Name:** `certified-hvac-technician-birmingham-alabama.jpg`

**Alt Text:** "Licensed and insured HVAC technician providing emergency heating and cooling repairs throughout Birmingham Alabama"

**Optimization Requirements:**
- Dimensions: 600x800px (portrait) or 500x500px (square)
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <80KB
- Lazy loading: Yes

**HTML Placement:**
```html
<section class="trust-section" id="about">
  <div class="technician-card">
    <img src="images/certified-hvac-technician-birmingham-alabama.webp"
         alt="Licensed and insured HVAC technician providing emergency heating and cooling repairs throughout Birmingham Alabama"
         loading="lazy"
         width="600" height="800">
  </div>
</section>
```

### Image 8: Service Truck (Alternative Angle)
**Purpose:** Reinforce professional presence and availability

**Ideal Image Description:**
- Professional HVAC service vehicle
- Front or side angle showing cab and cargo area
- Clean, well-maintained appearance
- Can be in motion or parked
- Suburban/residential background

**Stock Photo Search Terms:**
- "service van street", "hvac truck neighborhood"
- "white service vehicle residential", "contractor van"

**File Name:** `emergency-service-vehicle-birmingham-hvac.jpg`

**Alt Text:** "Emergency HVAC service vehicle delivering fast 24/7 heating and AC repair throughout Birmingham Alabama neighborhoods"

**Optimization Requirements:**
- Dimensions: 1200x800px
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <120KB
- Lazy loading: Yes

### Image 9: Satisfied Customer/Handshake
**Purpose:** Show customer satisfaction and relationship

**Ideal Image Description:**
- Technician shaking hands with homeowner or speaking with customer
- Front of house setting or doorway
- Both parties appearing pleased/satisfied
- Professional interaction
- Natural, genuine expressions
- Daylight setting

**Stock Photo Search Terms:**
- "technician customer handshake", "homeowner contractor satisfied"
- "service professional customer happy", "repairman handshake homeowner"
- "hvac customer service", "contractor client satisfied"

**File Name:** `satisfied-customer-hvac-service-birmingham.jpg`

**Alt Text:** "Satisfied Birmingham AL homeowner receiving professional emergency HVAC repair service with guaranteed satisfaction"

**Optimization Requirements:**
- Dimensions: 800x600px or 1000x750px
- Format: WebP with JPG fallback
- Compression: 85% quality
- File size: <100KB
- Lazy loading: Yes

### Image 10: Certification/License Badge (Stock or Custom)
**Purpose:** Visual credibility indicator

**Ideal Image Description:**
- Professional certification badge or seal
- Industry certifications (NATE, EPA, etc.)
- Clean, professional design
- Can be graphic/illustration rather than photo

**Stock Photo Search Terms:**
- "certification badge professional", "quality seal guarantee"
- "certified professional badge", "license seal"

**File Name:** `hvac-certified-licensed-badge-birmingham.png`

**Alt Text:** "Certified and licensed HVAC professionals serving Birmingham Alabama with emergency heating and cooling repairs"

**Optimization Requirements:**
- Dimensions: 200x200px to 400x400px
- Format: PNG with transparency
- Compression: Lossless PNG optimization
- File size: <30KB
- Lazy loading: Yes

---

## Icons & Graphics

### Icon Set Requirements

All icons should be:
- Format: SVG (scalable, small file size)
- Style: Modern, clean, professional line icons or filled icons (consistent style)
- Colors: Match brand colors or monochrome with CSS color control
- Size: 64x64px minimum viewBox

### Icon 1: 24/7 Service
**Description:** Clock with "24/7" or circular clock face

**Search Terms:**
- "24 hours icon", "24/7 service icon svg"
- "round the clock icon", "24 hour clock icon"

**Sources:**
- Font Awesome (Free): fas fa-clock
- Heroicons: clock icon
- Flaticon: "24/7 service"
- Icons8: "24 hours"

**File Name:** `icon-24-7-service.svg`

**Alt Text:** "24/7 emergency HVAC service available"

**Usage:** Feature sections, header, footer

### Icon 2: Fast Response/Speed
**Description:** Lightning bolt, speedometer, or running figure with motion

**Search Terms:**
- "lightning bolt icon", "speed icon svg"
- "fast service icon", "rapid response icon"

**Sources:**
- Font Awesome: fas fa-bolt
- Heroicons: bolt icon
- Flaticon: "fast service"

**File Name:** `icon-fast-response.svg`

**Alt Text:** "Fast emergency HVAC response time"

**Usage:** Feature highlights, service benefits

### Icon 3: Licensed Professional
**Description:** Certificate, diploma, or badge with checkmark

**Search Terms:**
- "certificate icon", "licensed badge icon"
- "professional certification icon", "diploma icon svg"

**Sources:**
- Font Awesome: fas fa-certificate
- Heroicons: badge-check
- Flaticon: "license certificate"

**File Name:** `icon-licensed-certified.svg`

**Alt Text:** "Licensed HVAC professionals"

**Usage:** Trust section, credentials display

### Icon 4: Insured/Protection
**Description:** Shield with checkmark or protective emblem

**Search Terms:**
- "shield icon", "insurance protection icon"
- "security shield svg", "protected icon"

**Sources:**
- Font Awesome: fas fa-shield-alt
- Heroicons: shield-check
- Flaticon: "insurance shield"

**File Name:** `icon-insured-protected.svg`

**Alt Text:** "Fully insured HVAC service"

**Usage:** Trust indicators, footer credentials

### Icon 5: Air Conditioning
**Description:** AC unit or snowflake icon

**Search Terms:**
- "air conditioner icon", "cooling icon svg"
- "ac unit icon", "snowflake cooling"

**Sources:**
- Font Awesome: fas fa-snowflake
- Flaticon: "air conditioner"
- Icons8: "air conditioning"

**File Name:** `icon-air-conditioning.svg`

**Alt Text:** "Air conditioning repair service"

**Usage:** Service section, navigation

### Icon 6: Heating/Furnace
**Description:** Flame or furnace icon

**Search Terms:**
- "flame icon", "heating icon svg"
- "furnace icon", "fire heating"

**Sources:**
- Font Awesome: fas fa-fire
- Heroicons: fire
- Flaticon: "heating furnace"

**File Name:** `icon-heating-furnace.svg`

**Alt Text:** "Furnace and heating repair service"

**Usage:** Service section, navigation

### Icon 7: Phone/Contact
**Description:** Phone handset or mobile phone

**Search Terms:**
- "phone icon", "call icon svg"
- "telephone icon", "contact phone"

**Sources:**
- Font Awesome: fas fa-phone
- Heroicons: phone
- Flaticon: "phone call"

**File Name:** `icon-phone-call.svg`

**Alt Text:** "Call for emergency HVAC service"

**Usage:** CTA buttons, header, footer

### Icon 8: Location/Service Area
**Description:** Map pin or location marker

**Search Terms:**
- "location icon", "map pin icon svg"
- "location marker", "gps pin"

**Sources:**
- Font Awesome: fas fa-map-marker-alt
- Heroicons: map-pin
- Flaticon: "location pin"

**File Name:** `icon-location-birmingham.svg`

**Alt Text:** "Birmingham Alabama service area"

**Usage:** Service area section, contact info

### Icon 9: Tools/Repair
**Description:** Wrench and screwdriver crossed or tool icon

**Search Terms:**
- "tools icon", "wrench icon svg"
- "repair tools icon", "maintenance tools"

**Sources:**
- Font Awesome: fas fa-tools
- Heroicons: wrench
- Flaticon: "repair tools"

**File Name:** `icon-repair-tools.svg`

**Alt Text:** "Professional HVAC repair tools"

**Usage:** Service descriptions, features

### Icon 10: Checkmark/Guarantee
**Description:** Checkmark or verified icon

**Search Terms:**
- "checkmark icon", "verified icon svg"
- "check circle icon", "approved icon"

**Sources:**
- Font Awesome: fas fa-check-circle
- Heroicons: check-circle
- Flaticon: "checkmark"

**File Name:** `icon-guarantee-check.svg`

**Alt Text:** "Satisfaction guaranteed"

**Usage:** Benefits list, guarantees, features

---

## Image Optimization Guidelines

### General Optimization Rules

1. **Format Strategy:**
   - Use WebP for modern browsers (85-90% compression)
   - Provide JPG fallback for older browsers (80-85% quality)
   - Use PNG only for images requiring transparency
   - Use SVG for all icons and simple graphics

2. **Responsive Images:**
   - Provide multiple sizes using srcset
   - Use appropriate sizes attribute
   - Example sizes: 400w, 800w, 1200w, 1920w

3. **Compression Tools:**
   - TinyPNG.com (lossy compression, excellent quality)
   - Squoosh.app (WebP conversion and compression)
   - ImageOptim (Mac) or FileOptimizer (Windows)
   - Online: Compressor.io, Optimizilla

4. **Lazy Loading:**
   - Use `loading="lazy"` for all below-fold images
   - Do NOT lazy load hero/above-fold images
   - Consider using Intersection Observer for advanced lazy loading

5. **Dimensions Best Practices:**
   - Always specify width and height attributes
   - Prevents layout shift (CLS optimization)
   - Use aspect-ratio CSS for responsive sizing

### SEO Optimization

1. **Alt Text Guidelines:**
   - Describe image content accurately
   - Include primary keywords naturally (Birmingham, HVAC, emergency, etc.)
   - Keep under 125 characters when possible
   - Be specific, not generic
   - Don't start with "Image of..." or "Picture of..."

2. **File Names:**
   - Use descriptive, keyword-rich names
   - Use hyphens, not underscores
   - Include location (birmingham, alabama, al)
   - Include service type (hvac, ac, furnace, emergency)
   - Use lowercase
   - Example: `emergency-ac-repair-birmingham-al-technician.jpg`

3. **Image Sitemaps:**
   - Include all important images in XML sitemap
   - Provide image title, caption, geo-location
   - Update sitemap after adding images

### Performance Targets

- **Hero Image:** <200KB
- **Service Images:** <120KB each
- **Trust Images:** <100KB each
- **Icons:** <10KB each (SVG), <30KB (PNG)
- **Total Page Weight (images):** <1.5MB
- **LCP Target:** <2.5 seconds
- **CLS Target:** <0.1

---

## File Naming Convention

### Standard Format
`[category]-[subject]-[location]-[variant].[ext]`

### Categories:
- `hero-` : Hero section images
- `service-` : Service-specific images
- `trust-` : Credibility/trust images
- `icon-` : Icons and small graphics
- `bg-` : Background images
- `team-` : Team member photos

### Location Tags:
- `birmingham` or `birmingham-al` or `alabama`

### Service Tags:
- `hvac`, `ac`, `furnace`, `heating`, `cooling`, `emergency`, `repair`

### Examples:
- `hero-emergency-hvac-technician-birmingham-al.jpg`
- `service-ac-repair-birmingham-residential.jpg`
- `trust-certified-technician-birmingham-alabama.jpg`
- `icon-24-7-emergency-service.svg`

### Folder Structure
```
/images
  /hero
    - hero-emergency-hvac-technician-birmingham-al.jpg
    - hero-emergency-hvac-technician-birmingham-al.webp
  /services
    - ac-repair-service-birmingham-emergency.jpg
    - ac-repair-service-birmingham-emergency.webp
    - furnace-repair-heating-service-birmingham.jpg
    - furnace-repair-heating-service-birmingham.webp
  /trust
    - certified-hvac-technician-birmingham-alabama.jpg
    - satisfied-customer-hvac-service-birmingham.jpg
  /icons
    - icon-24-7-service.svg
    - icon-fast-response.svg
    - icon-licensed-certified.svg
  /backgrounds
    (optional decorative backgrounds)
```

---

## Stock Photo Sources & Search Strategy

### Free Stock Photo Sites

#### 1. Unsplash.com
**Best For:** High-quality, professional photography
**Search Strategy:**
- Start broad: "hvac technician"
- Narrow down: "air conditioning repair", "furnace technician"
- Related searches: "contractor", "repairman", "home service"
**License:** Free for commercial use, attribution appreciated
**Image Quality:** Excellent (high resolution)
**Quantity:** Large library

#### 2. Pexels.com
**Best For:** Wide variety, good HVAC-related content
**Search Strategy:**
- Primary: "technician", "hvac", "air conditioner"
- Secondary: "repair", "contractor", "service professional"
- Video option available for hero sections
**License:** Free for commercial use, no attribution required
**Image Quality:** Very good to excellent
**Quantity:** Growing library

#### 3. Pixabay.com
**Best For:** Icons, illustrations, and stock photos
**Search Strategy:**
- Photos: "air conditioner", "technician", "repair"
- Vectors: Great for icons and simple graphics
- Illustrations: Background elements
**License:** Pixabay License (free for commercial use)
**Image Quality:** Good to very good
**Quantity:** Very large library

#### 4. Burst.shopify.com
**Best For:** Business and professional imagery
**Search Strategy:**
- "professional", "contractor", "service"
- "handshake", "business professional"
**License:** Free for commercial use
**Image Quality:** Very good
**Quantity:** Smaller, curated library

### Premium Stock Photo Sites (Paid)

#### 1. Shutterstock.com
**Best For:** Comprehensive HVAC-specific imagery
**Cost:** Subscription or on-demand pricing
**Search Strategy:**
- "hvac technician emergency"
- "air conditioning repair Birmingham"
- Advanced filters: people, orientation, color
**Advantages:**
- Largest library
- Very specific technical images
- Model and property releases included

#### 2. Adobe Stock
**Best For:** High quality, integrates with Adobe Creative Cloud
**Cost:** Subscription or credit packs
**Search Strategy:**
- "emergency hvac repair"
- "furnace technician residential"
- Use filters for orientation and people
**Advantages:**
- Excellent quality
- Good integration with Photoshop/editing
- Similar image suggestions

#### 3. Getty Images / iStock
**Best For:** Premium quality, specific scenarios
**Cost:** Higher-priced premium or budget iStock option
**Search Strategy:**
- iStock for budget-friendly options
- Getty for premium exclusive images
**Advantages:**
- Very high quality
- Exclusive content available
- Strong editorial collection

### Specialized HVAC Photo Resources

#### 1. HVAC Company Marketing Sites
- Look for stock photo packages specifically for HVAC companies
- Often include complete sets with consistent styling

#### 2. Industry Associations
- ACCA (Air Conditioning Contractors of America)
- May have image resources for members

### Search Strategy Best Practices

1. **Start Broad, Then Narrow:**
   - Begin: "technician"
   - Add specifics: "hvac technician repair"
   - Add location context: "residential technician south"

2. **Use Related Terms:**
   - HVAC, air conditioning, heating, cooling
   - Furnace, AC unit, condenser
   - Technician, contractor, repairman, professional

3. **Filter Effectively:**
   - Orientation: Landscape for hero, portrait for team
   - Color: Match your brand colors when possible
   - People: Include people for trust-building images

4. **Check Multiple Sources:**
   - Same search on 3-4 sites yields different results
   - Mix free and premium for best value

5. **Download Highest Quality:**
   - Always get the largest size available
   - Easier to compress down than upscale

6. **Consider Image Sets:**
   - Look for photographers who have multiple HVAC images
   - Creates visual consistency

### Curated Search Terms by Category

**HVAC Technician Work:**
- "hvac technician working"
- "air conditioning repair outdoor"
- "furnace repair technician"
- "hvac diagnostic tools"
- "ac unit maintenance"

**Professional Portraits:**
- "contractor portrait"
- "professional technician uniform"
- "service professional smiling"
- "repairman confident"

**Residential Settings:**
- "residential hvac"
- "home air conditioning"
- "suburban house exterior"
- "modern home exterior"

**Trust & Service:**
- "customer satisfaction handshake"
- "service truck residential"
- "professional service vehicle"
- "technician homeowner"

**Tools & Equipment:**
- "hvac tools equipment"
- "multimeter technician"
- "gauge set hvac"
- "service tools professional"

---

## Implementation Checklist

### Pre-Launch Image Preparation

- [ ] Download all required images from stock sources
- [ ] Rename files according to naming convention
- [ ] Resize images to target dimensions
- [ ] Compress JPG files to 80-85% quality
- [ ] Convert and compress WebP versions
- [ ] Optimize PNG files (if any)
- [ ] Optimize SVG icons
- [ ] Create responsive image sizes (400w, 800w, 1200w, 1920w)
- [ ] Organize images into folder structure
- [ ] Write alt text for all images
- [ ] Test all images load correctly
- [ ] Verify file sizes meet targets

### HTML Implementation

- [ ] Add picture elements with WebP/JPG fallbacks
- [ ] Include width and height attributes
- [ ] Add loading="lazy" for below-fold images
- [ ] Implement srcset for responsive images
- [ ] Add descriptive alt text
- [ ] Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test on mobile devices
- [ ] Verify no layout shift (CLS)

### SEO Implementation

- [ ] Create image sitemap or add to existing sitemap
- [ ] Include geo-location data for Birmingham, AL
- [ ] Add structured data (Schema.org) for images
- [ ] Optimize Open Graph images for social sharing
- [ ] Add Twitter Card image tags
- [ ] Test images in Google Search Console
- [ ] Verify images appear in Google Images search

### Performance Testing

- [ ] Run Google PageSpeed Insights (target 90+ score)
- [ ] Check Largest Contentful Paint (LCP < 2.5s)
- [ ] Verify Cumulative Layout Shift (CLS < 0.1)
- [ ] Test on slow 3G connection
- [ ] Measure total page weight with images
- [ ] Verify lazy loading works correctly
- [ ] Check image CDN delivery (if using CDN)

### Accessibility Checks

- [ ] All images have meaningful alt text
- [ ] Decorative images have empty alt=""
- [ ] Images don't rely on color alone for information
- [ ] Test with screen reader (NVDA, JAWS, or VoiceOver)
- [ ] Verify image text contrast if overlaying text
- [ ] Check focus indicators on linked images

---

## Additional Recommendations

### Brand Consistency
- Use consistent lighting style (warm, professional)
- Prefer similar color palettes across images
- Choose same-gender/diversity representation if using multiple technician photos
- Consider custom photography for unique local Birmingham presence

### Local Birmingham Touches
- If possible, use recognizable Birmingham architecture in backgrounds
- Southern-style homes (brick, traditional architecture)
- Consider seasonal context (hot summers = AC focus)
- Local landmarks in background (if feasible and not distracting)

### Conversion Optimization
- Use images of people looking at CTA buttons (eye-tracking studies)
- Show satisfied customers, not just technicians
- Use warm, inviting images to reduce anxiety about service calls
- Include images of modern, clean equipment (not old/dirty)

### Future Image Needs
- Seasonal updates (summer AC focus, winter heating focus)
- Before/after images (if capturing real work)
- Customer testimonial photos (with permission)
- Team expansion photos
- New service offerings

### Legal Considerations
- Verify commercial license for all stock photos
- Keep records of licenses and downloads
- Don't modify images in ways that violate license terms
- Consider model releases for premium stock
- Never use images from Google Image Search without verification

---

## Quick Reference: Priority Images

### Must-Have (Launch Critical):
1. Hero technician image
2. AC repair service image
3. Furnace repair service image
4. Certified technician portrait
5. 24/7 icon
6. Fast response icon
7. Licensed icon
8. Phone/call icon

### Nice-to-Have (Phase 2):
9. Service truck image
10. Customer satisfaction image
11. Tools/equipment detail shot
12. Additional service images
13. Decorative icons
14. Background images

---

## Budget Considerations

### Free Stock Photo Approach:
- **Cost:** $0
- **Time Investment:** 3-5 hours searching and downloading
- **Quality:** Good to very good
- **Limitation:** Less HVAC-specific imagery

### Premium Stock Photo Approach:
- **Cost:** $50-200 for image pack or monthly subscription
- **Time Investment:** 1-2 hours
- **Quality:** Excellent
- **Advantage:** Very specific HVAC imagery

### Hybrid Approach (Recommended):
- **Cost:** $50-100
- **Strategy:**
  - Use free stock for general images (hero, team, trust)
  - Purchase premium for specific technical HVAC shots
  - Buy icons from Flaticon or similar ($5-10 for pack)
- **Best Value:** High quality where it matters most

### Custom Photography:
- **Cost:** $500-2000+ (professional photographer)
- **Advantage:**
  - Unique, authentic images
  - Exact Birmingham locations
  - Real team members
  - Perfect brand match
- **Consideration:** Future investment after site launch and revenue generation

---

## Contact & Next Steps

After implementing this image plan:

1. **Track Performance:**
   - Monitor bounce rate on pages with images
   - Track engagement with image-heavy sections
   - A/B test different hero images

2. **Gather Analytics:**
   - Heat maps showing where users look
   - Scroll depth to verify image visibility
   - Conversion rates from image-driven CTAs

3. **Iterate and Improve:**
   - Replace underperforming images
   - Add new images based on new services
   - Update seasonal images quarterly

4. **Build Image Library:**
   - Collect customer permission for real project photos
   - Document actual Birmingham service calls
   - Create authentic before/after galleries

---

**Document Version:** 1.0
**Created:** November 6, 2025
**Project:** Emergency HVAC Repair Website - Birmingham, AL
**Purpose:** Comprehensive image strategy and implementation guide
