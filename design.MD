
```markdown
# Design.MD - UI/UX Enhancement & Tech-Stack Polish Blueprint

This document specifies the exact visual upgrades required for `index.html` and `treatment-of-missing-tooth.html`. 
Note : Don't touch the existing pricing table of treatment-of-missing-tooth.html file
## ⚠️ CRITICAL SITE INTEGRITY GUARDRAILS (DO NOT VIOLATE)
1. **DON'T TOUCH SHARED STRUCTURES:** Absolutely DO NOT modify, move, rewrite, or rename the `<nav>`, `<header>`, `.topbar`, or `<footer>` blocks. These are shared across all pages of the ecosystem. Changing them will break global cross-page consistency. Only update properties within the structural main content blocks.
2. **DON'T REBUILD — ENHANCE ONLY:** Do not strip out existing scripts, core elements, or native classes. Inject/override the new premium styles cleanly without destroying the working underlying setup.
3. **NO TRUNCATION:** Provide full, copy-pasteable blocks for the content areas being enhanced.

---

## 🎨 STYLING UTILITIES (The React App Premium Vibe)

Use the following exact global design tokens for the glass effects and premium dotted container borders to evoke a high-end, responsive web app design pattern:

```css
/* Core Global Palette Variables */
:root {
  --main-blue-glass: rgba(0, 109, 229, 0.3);
  --main-blue-border: rgba(0, 109, 229, 0.72);
  --neon-glow: 0 4px 30px rgba(0, 109, 229, 0.25);
  --card-radius: 16px;
}

/* Base High-End Glassmorphism Card Style */
.premium-glass-card {
  background: var(--main-blue-glass);
  border-radius: var(--card-radius);
  box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1), var(--neon-glow);
  backdrop-filter: blur(8.6px);
  -webkit-backdrop-filter: blur(8.6px);
  border: 1px solid var(--main-blue-border);
  position: relative;
  overflow: hidden;
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Premium Tech Vibe Dotted/Dashed Accents */
.premium-glass-card::before {
  content: '';
  position: absolute;
  inset: 4px; /* Creates an inner margin line */
  border: 1px dotted rgba(255, 255, 255, 0.35);
  border-radius: calc(var(--card-radius) - 4px);
  pointer-events: none;
  z-index: 2;
}

/* Interactive Hover States */
.premium-glass-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 40px rgba(0, 109, 229, 0.4);
  border-color: rgba(0, 109, 229, 0.95);
}

```
## 🛠️ CONTENT AREA UPGRADES
### 1. Hero & Video Section (Responsive & Framed)
 * **Vibe:** Clean grid structure mimicking a React dashboard dashboard.
 * **Video Card Frame:** Wrap the video block within the .premium-glass-card styling using the core blueprint colors (rgba(0, 109, 229, 0.3)).
 * Ensure a clean dotted accent ring trails the outer bounds of the play console to look like a high-tech medical instrument interface.
 * Keep headlines flexible with responsive clamp() layout configurations so titles scale natively across mobile viewports.
### 2. Pro Interactive Before/After Mask Reveal Slider
 * Replace any coordinate-shifting image sliding transitions.
 * Build a true structural image clip-path reveal wrapper. Both "Before" and "After" picture elements must remain anchored and motionless, preventing teeth misalignment.
 * Add desktop drag handlers and touch listeners (touchstart, touchmove) to keep scaling flawless on phone views.
 * Border the composite canvas using the crisp glass border profile (1px solid rgba(0, 109, 229, 0.72)).
### 3. Problems We Solve Matrix (Grid Optimization)
 * Refactor the 4 case card models into modern grid layouts (2-column desktop, 1-column mobile).
 * Inject the elegant inner dotted border token to give each case profile card a crisp, technical look.
 * **WhatsApp Integration Box:** Style with the high-contrast frosted emerald/blue overlay template linked smoothly to https://wa.me/8801611112717. Ensure the official icon is built using clean inline SVG.
### 4. Glassmorphism Tier Pricing Cards
 * Render the 3 pricing layout tiers using the precise --main-blue-glass blueprint variables.
 * **Tier 1 (Economy - ৩,০০০) & Tier 3 (Premium - ६,০০০):** Sleek minimal glass properties.
 * **Tier 2 (Standard - ৪,৫০০):** This is the flagship product layer. Draw emphasis by applying a distinctive neon glow and absolute layout badge reading "MOST POPULAR" / "সবচেয়ে জনপ্রিয়".
 * Position the mandatory compliance clause inline below the card blocks: "Note: উল্লেখিত খরচ একেকটি ফাঁকা দাঁত বন্ধ করার জন্য প্রযোজ্য।".
### 5. "Why Choose Us" Asymmetrical Component Layout
 * Upgrade this view using a fluid 2-column layout mapping.
 * **Left Column:** Row stack of feature units with custom medical/dental vector SVGs (replacing all legacy emojis completely).
 * **Right Column:** Display the static image file wcs.png wrapped in an unequal responsive border-radius mask layer (curves applied cleanly on opposite corners like top-left and bottom-right edges).
## 📱 SCREEN RESPONSIVENESS AND ACCESSIBILITY DATA
 * All layout maps must map directly into single-column stacks on viewports < 768px.
 * Prevent background blur overhead lags on older chip architectures by keeping script threads clean and lightweight.
 * Ensure text elements maintain strong contrast ratios over the semi-transparent blue glass panels for crystal-clear readability.
```
***

### 💡 আপনার জন্য প্রো-টিপ:
এই প্রম্পটে আমরা **`--main-blue-glass`** এবং **`--main-blue-border`** কে CSS Variable আকারে ডিফাইন করার নির্দেশ দিয়েছি। এর সুবিধা হলো, ফিউচারে যদি আপনি ব্লু কালারটি সামান্য চেঞ্জ করতে চান, তবে শুধু এক লাইনের কোড চেঞ্জ করলেই পুরো সাইটের কালার অটোমেটিক আপডেট হয়ে যাবে!

```
