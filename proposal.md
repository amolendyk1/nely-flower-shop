## Client Brief

**Client:** Nely Molendyk — owner of The Bud & Bloom (florist & educator)

**Purpose:** A clean, modern flower education and bouquet shop that helps users learn about flowers, build bouquets with compatible flowers, purchase arrangements, and sign up for in-person floral arrangement classes.

**Audience:** Florists, gardeners, mothers and grandmothers, gift shoppers, and hobbyists who want flower-care guidance, bouquet inspiration, or hands-on classes.

**Key action (primary):** Sign up for in-person bouquet-making classes.

**Key action (secondary):** Purchase bouquets and plants via the shop.

**Pages / sections needed:**
- Homepage — hero, featured bouquets, primary CTA for classes and shop (implemented)
- Flower Library — educational reference (name, image, care, suggested pairings) (implemented)
- Bouquet Arrangements — catalog with images, included flowers, pairing notes (implemented)
- Plant Guide — plant care and climate info (implemented)
- Shop / Storefront — product listings and buy flow (UI implemented, payment integration pending)
- Cart — shopping cart UI using `localStorage` (implemented)
- About — Nely's story and brand mission (implemented)
- Contact / Class Sign-Up — contact form and class registration (implemented)

**Content status:**
- Flower names & descriptions: ✅
- Bouquet names & descriptions: ✅
- Care instructions: ✅
- Class descriptions: ✅
- Product/plant images: Placeholder images in use (all stored in `images/`) — can be replaced by Nely later

**Style preferences:**
- Colors: Pastel palette (soft pinks, blush, cream, light greens) — implemented via CSS variables in `css/style.css`.
- Typography: Headings use Cormorant Garamond; body uses DM Sans (Google Fonts).
- Vibe: Light, clean, airy, approachable — large imagery and generous white space (see `index.html`).

**Inspiration sites:**
- UrbanStems — clean grid, large images; keep symmetry and clarity, lighten the palette.
- Farmgirl Flowers — strong imagery and simple browsing; keep large photos, avoid dark theme.
- ProFlowers — simple tabbed navigation; keep straightforward page names but improve typography and spacing.

## Layout Plan

- Sketch: The hand-drawn/layout sketch is committed as [website-sketch.jpg](website-sketch.jpg) in the repo root.
- Reference to emulate: `index.html` structure (hero with two CTAs, featured product grid, class CTA, about preview, footer) — see [index.html](index.html).
- What to keep from references: large product imagery, clear navigation labels (Flowers, Bouquets, Plants, Shop), symmetrical grid for product listings, sticky header with hamburger on mobile.
- What to change: use a lighter pastel palette, add richer bouquet pairing descriptions, make class sign-up a prominent conversion path.
- AI prompt / starting description used for layout generation: "Hero with tagline 'We tell stories with flowers', two CTAs (Explore Flowers, Shop Bouquets), a featured bouquets grid (card layout, image + desc + price + add-to-cart), a dedicated class CTA section, about preview with image, and an accessible footer — responsive mobile-first design."