# Product Requirements Document (PRD)

## The Bud & Bloom — Flower Education & Bouquet Shop

---

## 1. Overview

### 1.1 Project Name
**The Bud & Bloom**

### 1.2 Client
Nely Molendyk — aspiring florist and owner of The Bud & Bloom.

### 1.3 Purpose
A clean, modern flower education and bouquet building website that helps users learn about flowers, create bouquets with compatible flowers, purchase arrangements, and sign up for in-person floral arrangement classes.

### 1.4 Target Audience
- Florists
- Gardeners
- Mothers and grandmothers
- Gift shoppers
- Anyone interested in flower or bouquet design

---

## 2. Goals & Success Metrics

### 2.1 Launch Date
**Friday, June 12, 2026**

### 2.2 Business Goals
- Build Nely's brand as a florist and educator
- Drive class sign-ups for in-person bouquet making classes
- Enable direct purchases of bouquets and plants (pay now)
- Serve as an educational resource for flower and plant care

### 2.3 Success Metrics
- Number of class sign-ups per week
- Number of product purchases (bouquets/plants)
- Contact form submissions

---

## 3. Pages / Sections

| # | Page | Description | Status |
|---|------|----------|--------|
| 1 | **Homepage** | Welcome hero, featured bouquets, call-to-action for classes and shop | ✅ Implemented |
| 2 | **Flower Library** | Educational reference — flower name, description, climate/growing conditions, image, care instructions, suggested pairings | ✅ Implemented |
| 3 | **Bouquet Arrangements** | Catalog of bouquets — name, description, image, flowers included, care instructions, pairing explanations | ✅ Implemented |
| 4 | **Plant Guide** | Plant types, weather/climate needs, care instructions | ✅ Implemented |
| 5 | **Shop / Storefront** | E-commerce page to browse and purchase bouquets/plants with immediate payment | ✅ Implemented (UI only) |
| 6 | **Cart** | Shopping cart interface for managing selected items | ✅ Implemented |
| 7 | **About** | Nely's story, the brand's mission, background | ✅ Implemented |
| 8 | **Contact / Class Sign-Up** | Registration form for in-person bouquet making classes, contact information, business hours | ✅ Implemented |

---

## 4. Features & Functionality

### 4.1 E-Commerce
- ✅ Product listings for bouquets and plants (UI implemented)
- ✅ Shopping cart interface
- ⏳ Checkout with payment processing (Stripe or Square — Future implementation)
- ⏳ Pay-now purchasing model (Requires payment gateway setup)

Implementation details:
- ✅ Client-side cart implemented using `localStorage` to persist items across pages
- ✅ "Checkout" currently clears the cart and redirects users to the Contact page to finalize orders (no payment integration)

### 4.2 Classes
- ✅ Online sign-up / registration form
- ⏳ Set dates and times (to be configured by Nely)
- ⏳ Pricing (to be determined)

### 4.3 Contact Form
- ✅ Contact form for general inquiries, custom bouquet requests, and plant purchase inquiries
- ⏳ Email delivery automation (Requires backend setup)

### 4.4 Educational Content
- ✅ Flower library with descriptions and care instructions
- ✅ Flower compatibility and pairing suggestions
- ✅ Plant guide with weather/climate information
- ✅ Care instructions for flowers and plants

---

## 5. Design & Brand Identity

### 5.1 Brand Name
**The Bud & Bloom**

### 5.2 Logo
- Custom text-based logo using "The Bud & Bloom"
- Clean but welcoming font style

### 5.3 Visual Style
- **Layout:** Clean, symmetrical, easy-to-navigate
- **Colors:** Pastel palette — pink, purple, yellow, light blue, light green (spring-themed, natural floral vibes)
- **Typography:** Clean, easy-to-read fonts (sans-serif body, complementary heading font)
- **Imagery:** Large, clear images; placeholder images used at launch where Nely's own photos are not yet available

### 5.4 Design Inspiration
- **UrbanStems** — symmetry, clean grid, large images, clear navigation tabs (Occasions, Types, Collections). Changes Nely wants: lighter color palette, better bouquet descriptions with pairing explanations, class sign-up page added.
- **Farmgirl Flowers** — Nely liked the large images and easy-to-see layout. Did not like the dark color scheme.
- **ProFlowers** — Nely liked the simple tab names and subpages. Did not like the font, messy layout, or limited flower options.

---

## 6. Content

### 6.1 Status
| Content Type | Status |
|-------------|--------|
| Flower names & descriptions | ✅ Created |
| Bouquet names & descriptions | ✅ Created |
| Care instructions | ✅ Created |
| Class descriptions | ✅ Created |
| Flower photos | Placeholder images in use |
| Bouquet photos | Placeholder images in use |
| Plant photos | Placeholder images in use |

### 6.2 Imagery Strategy
- Placeholder images used at launch for consistency
- Nely can replace with her own photos over time
- All images are properly sized and optimized for web display

---

## 7. Technical Requirements

### 7.1 Frontend Implementation
- ✅ **Semantic HTML5:** Proper use of `<header>`, `<nav>`, `<section>`, `<footer>`, `<main>` elements
- ✅ **Responsive Layout:** CSS Grid and Flexbox for adaptable layouts
- ✅ **Mobile-First Design:** Responsive breakpoints for tablets (768px) and mobile (480px)
- ✅ **Favicon:** Custom SVG favicon with flower emoji (🌸)
- ✅ **External Stylesheet:** Centralized CSS at `css/style.css` (~500+ lines)
- ✅ **Accessibility:** ARIA labels, semantic structure, keyboard navigation support

### 7.2 Hosting
- **Platform:** GitHub Pages
- **Repository:** nely-flower-shop
- **Status:** Ready for deployment

### 7.3 Domain
- No custom domain yet — will use GitHub Pages URL initially
- Custom domain can be added later

### 7.4 Payment Processing
- ⏳ Needs to be set up (Stripe or Square)
- ⏳ Pay-now model for bouquets and plants (Future implementation)

### 7.5 Contact / Class Sign-Up
- ✅ Contact form HTML structure in place
- ⏳ Email delivery automation (Requires backend service — Formspree, SendGrid, or custom backend)

---

## 8. Timeline

| Milestone | Date |
|-----------|------|
| PRD finalized | June 8, 2026 |
| Development complete | June 11, 2026 |
| **Launch** | **June 12, 2026 (Friday)** |

---

## 9. Future Considerations (Post-Launch)
- Custom domain name purchase and configuration
- Real photos replacing placeholders
- Expanded class schedule and pricing
- Additional flower/bouquet/plant content
- Email automation for class confirmations
- Potential online class offerings

## Sketch
website-sketch.jpg (included in repository root)
# Product Requirements Document (PRD)

## The Bud & Bloom — Flower Education & Bouquet Shop

---

## 1. Overview

### 1.1 Project Name
**The Bud & Bloom**

### 1.2 Client
Nely Molendyk — aspiring florist and owner of The Bud & Bloom.

### 1.3 Purpose
A clean, modern flower education and bouquet building website that helps users learn about flowers, create bouquets with compatible flowers, purchase arrangements, and sign up for in-person floral arrangement classes.

### 1.4 Target Audience
- Florists
- Gardeners
- Mothers and grandmothers
- Gift shoppers
- Anyone interested in flower or bouquet design

---

## 2. Goals & Success Metrics

### 2.1 Launch Date
**Friday, June 12, 2026**

### 2.2 Business Goals
- Build Nely's brand as a florist and educator
- Drive class sign-ups for in-person bouquet making classes
- Enable direct purchases of bouquets and plants (pay now)
- Serve as an educational resource for flower and plant care

### 2.3 Success Metrics
- Number of class sign-ups per week
- Number of product purchases (bouquets/plants)
- Contact form submissions

---

## 3. Pages / Sections

| # | Page | Description | Status |
|---|------|----------|--------|
| 1 | **Homepage** | Welcome hero, featured bouquets, call-to-action for classes and shop | ✅ Implemented |
| 2 | **Flower Library** | Educational reference — flower name, description, climate/growing conditions, image, care instructions, suggested pairings | ✅ Implemented |
| 3 | **Bouquet Arrangements** | Catalog of bouquets — name, description, image, flowers included, care instructions, pairing explanations | ✅ Implemented |
| 4 | **Plant Guide** | Plant types, weather/climate needs, care instructions | ✅ Implemented |
| 5 | **Shop / Storefront** | E-commerce page to browse and purchase bouquets/plants with immediate payment | ✅ Implemented (UI only) |
| 6 | **Cart** | Shopping cart interface for managing selected items | ✅ Implemented |
| 7 | **About** | Nely's story, the brand's mission, background | ✅ Implemented |
| 8 | **Contact / Class Sign-Up** | Registration form for in-person bouquet making classes, contact information, business hours | ✅ Implemented |

---

## 4. Features & Functionality

### 4.1 E-Commerce
- ✅ Product listings for bouquets and plants (UI implemented)
- ✅ Shopping cart interface
- ⏳ Checkout with payment processing (Stripe or Square — Future implementation)
- ⏳ Pay-now purchasing model (Requires payment gateway setup)

Implementation details:
- ✅ Client-side cart implemented using `localStorage` to persist items across pages
- ✅ "Checkout" currently clears the cart and redirects users to the Contact page to finalize orders (no payment integration)

### 4.2 Classes
- ✅ Online sign-up / registration form
- ⏳ Set dates and times (to be configured by Nely)
- ⏳ Pricing (to be determined)

### 4.3 Contact Form
- ✅ Contact form for general inquiries, custom bouquet requests, and plant purchase inquiries
- ⏳ Email delivery automation (Requires backend setup)

### 4.4 Educational Content
- ✅ Flower library with descriptions and care instructions
- ✅ Flower compatibility and pairing suggestions
- ✅ Plant guide with weather/climate information
- ✅ Care instructions for flowers and plants

---

## 5. Design & Brand Identity

### 5.1 Brand Name
**The Bud & Bloom**

### 5.2 Logo
- Custom text-based logo using "The Bud & Bloom"
- Clean but welcoming font style

### 5.3 Visual Style
- **Layout:** Clean, symmetrical, easy-to-navigate
- **Colors:** Pastel palette — pink, purple, yellow, light blue, light green (spring-themed, natural floral vibes)
- **Typography:** Clean, easy-to-read fonts (sans-serif body, complementary heading font)
- **Imagery:** Large, clear images; placeholder images used at launch where Nely's own photos are not yet available

### 5.4 Design Inspiration
- **UrbanStems** — symmetry, clean grid, large images, clear navigation tabs (Occasions, Types, Collections). Changes Nely wants: lighter color palette, better bouquet descriptions with pairing explanations, class sign-up page added.
- **Farmgirl Flowers** — Nely liked the large images and easy-to-see layout. Did not like the dark color scheme.
- **ProFlowers** — Nely liked the simple tab names and subpages. Did not like the font, messy layout, or limited flower options.

---

## 6. Content

### 6.1 Status
| Content Type | Status |
|-------------|--------|
| Flower names & descriptions | ✅ Created |
| Bouquet names & descriptions | ✅ Created |
| Care instructions | ✅ Created |
| Class descriptions | ✅ Created |
| Flower photos | Placeholder images in use |
| Bouquet photos | Placeholder images in use |
| Plant photos | Placeholder images in use |

### 6.2 Imagery Strategy
- Placeholder images used at launch for consistency
- Nely can replace with her own photos over time
- All images are properly sized and optimized for web display

---

## 7. Technical Requirements

### 7.1 Frontend Implementation
- ✅ **Semantic HTML5:** Proper use of `<header>`, `<nav>`, `<section>`, `<footer>`, `<main>` elements
- ✅ **Responsive Layout:** CSS Grid and Flexbox for adaptable layouts
- ✅ **Mobile-First Design:** Responsive breakpoints for tablets (768px) and mobile (480px)
- ✅ **Favicon:** Custom SVG favicon with flower emoji (🌸)
- ✅ **External Stylesheet:** Centralized CSS at `css/style.css` (~500+ lines)
- ✅ **Accessibility:** ARIA labels, semantic structure, keyboard navigation support

### 7.2 Hosting
- **Platform:** GitHub Pages
- **Repository:** nely-flower-shop
- **Status:** Ready for deployment

### 7.3 Domain
- No custom domain yet — will use GitHub Pages URL initially
- Custom domain can be added later

### 7.4 Payment Processing
- ⏳ Needs to be set up (Stripe or Square)
- ⏳ Pay-now model for bouquets and plants (Future implementation)

### 7.5 Contact / Class Sign-Up
- ✅ Contact form HTML structure in place
- ⏳ Email delivery automation (Requires backend service — Formspree, SendGrid, or custom backend)

---

## 8. Timeline

| Milestone | Date |
|-----------|------|
| PRD finalized | June 8, 2026 |
| Development complete | June 11, 2026 |
| **Launch** | **June 12, 2026 (Friday)** |

---

## 9. Future Considerations (Post-Launch)
- Custom domain name purchase and configuration
- Real photos replacing placeholders
- Expanded class schedule and pricing
- Additional flower/bouquet/plant content
- Email automation for class confirmations
- Potential online class offerings

# Sketch 
C:\Users\amolendyk1\Desktop\ally-flower-shop\ally-flower-shop\website-sketch.jpg 