# Phase Two (Weeks 3–6)
## Design Systems Upgrade

### 🎯 Goal

Move from “nice-looking UI” to **coherent system thinking**.

This phase focuses on:
- Understanding how mature teams constrain visual decisions
- Learning to work with limits instead of infinite choice
- Translating visual rules into reusable tokens and components

This is **not** about memorizing design systems.
It is about extracting **patterns, defaults, and constraints**.

---

## 🔁 Daily Practice (15 mins)

Rotate through **one design system per day**.

Do **not** explore randomly.  
Do **not** read entire documentation sections.

Your job is to understand:
> What visual decisions are intentionally locked down?

---

### Shopify Polaris  
**URL:** https://polaris.shopify.com/design

**Look only at:**
- Foundations → Color
- Foundations → Typography
- Foundations → Spacing

**Write down:**
- How many spacing steps exist?
- How many typography roles are allowed?
- Where is color usage intentionally restricted?
- One rule Polaris enforces to prevent inconsistency.

---

### Radix Themes  
**URL:** https://www.radix-ui.com/themes/docs/theme

**Look only at:**
- Theme tokens
- Scale system
- Radius tokens
- Shadow tokens

**Write down:**
- How many scale steps exist?
- Are tokens semantic or numeric?
- What values are intentionally not provided?
- One restraint rule enforced by the system.

---

### Material Design 3  
**URL:** https://m3.material.io/styles

**Look only at:**
- Typography
- Color
- Elevation

Ignore components.

**Write down:**
- How typography roles are defined (not sizes)
- How elevation levels are capped
- How color roles map to meaning (not decoration)
- One constraint that limits visual freedom

---

### Atlassian Design System  
**URL:** https://atlassian.design/foundations

**Look only at:**
- Spacing
- Color
- Typography

**Write down:**
- How spacing tokens are named and limited
- How density is controlled
- How consistency is enforced across products
- One rule that reduces visual chaos

---

### Fluent UI (Microsoft)  
**URL:** https://fluent2.microsoft.design/design-tokens

**Look only at:**
- Design tokens overview
- Typography
- Elevation

**Write down:**
- How defaults are chosen
- How many options are intentionally removed
- How tokens map to platform scale
- One constraint that improves consistency

---

## 📅 Weekly Build Tasks

Each week, build **one small system** in isolation.

Do **not** build a full app.  
Do **not** design screens.

The goal is to practice **constraint-first thinking**.

---

### Week 3 → Spacing & Typography System

**Build**
- A spacing scale (example: `8 / 16 / 24 / 32 / 48 / 64`)
- A typography scale (example: body / heading / display)

**Deliverables**
- Documented spacing scale
- Documented typography scale
- Clear rules for when each level is used

**Constraints**
- Maximum of six spacing steps
- Maximum of six typography roles
- No arbitrary values

---

### Week 4 → Button & Input System

**Build**
- Primary button
- Secondary button
- Text input
- Disabled and focus states

**Deliverables**
- Padding rules
- Height rules
- Border radius rule
- State definitions (default / hover / focus / disabled)

**Constraints**
- Must use spacing and typography from Week 3
- No custom values outside tokens
- One primary accent color only

---

### Week 5 → Card & List System

**Build**
- Basic card
- Card with header and content
- Simple list item

**Deliverables**
- Internal padding rules
- Vertical spacing rules
- Border and shadow usage rules

**Constraints**
- Use only existing tokens
- Calm visual density
- Avoid decorative styling

---

### Week 6 → Navigation & Layout Containers

**Build**
- Page container (max-width and padding)
- Basic navigation bar
- Section wrapper

**Deliverables**
- Content width rules
- Horizontal padding rules
- Vertical section spacing rules

**Constraints**
- Layout must work without color
- Navigation should rely on hierarchy, not decoration

---

### System Rule

Define tokens first.  
Build components only from those tokens.

---

## 📚 Recommended Resources

- *Design Systems* — Alla Kholmatova
- Radix Themes source code
- shadcn/ui source
- Tailwind UI (spacing reference)

---

## ✅ Completion Criteria

After completing Phase Two, you should be able to:

- Define spacing, typography, and color systems intentionally
- Explain why certain visual decisions must be constrained
- Build components that derive entirely from tokens
- Say “no” to arbitrary visual changes with confidence

You are now ready for:

- **Phase Three — Interaction & Motion Discipline**