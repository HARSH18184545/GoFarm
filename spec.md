# Specification

## Summary
**Goal:** Build the full GoFarm AI Agriculture Platform landing UI with a sticky navbar, hero section, feature cards, and a minimal Motoko backend with stub functions.

**Planned changes:**
- Sticky top navbar with GoFarm brand name and leaf icon, center links (Products, Equipment, Labour), Login button, and green Get Started CTA; collapses to hamburger menu on mobile
- Full-width hero section with bold headline "Trade. Equip. Connect.", subtext "AI-powered platform for smart farming ecosystem.", and a microphone icon button for voice support
- Three large premium feature cards in a row: Product Exchange (AI Powered) with leaf icon, AI badge, sparkline price chart, AI confidence indicator, smart recommendation hint, and feature list; Equipment Exchange with tractor icon and feature list; Labour Connect with worker icon and feature list; each with a green Open button and hover lift animation
- Four smaller secondary feature cards in a row: Crop Disease Detection, Waste Management, Reports & Insights, and Community Posts — each with icon, title, descriptor, and Open button
- Cohesive soft green theme: sage/forest greens, white backgrounds, 16px+ rounded corners, subtle box shadows, smooth hover transitions, modern sans-serif typography
- Fully responsive layout across desktop (1280px+), tablet, and mobile; touch-friendly 44px buttons
- Minimal Motoko backend actor with stub functions: `addProduce`, `browseProduce`, `addEquipment`, `viewEquipment`, `postLabourRequirement`, `findLabour`

**User-visible outcome:** Users can view the GoFarm landing page with a navigable sticky navbar, an engaging hero, three primary feature module cards with AI elements, four secondary feature cards, and a consistent green agricultural design — all fully responsive across devices.
