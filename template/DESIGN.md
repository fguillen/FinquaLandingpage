```markdown
# Design System Document: The Editorial Intelligence

## 1. Overview & Creative North Star

### Creative North Star: "The Digital Curator"
This design system is not a standard SaaS dashboard; it is a premium, data-driven intelligence tool. The "Digital Curator" philosophy treats every screen as a high-end academic report or a bespoke financial dossier. We reject the "bubbly" aesthetics of modern consumer apps in favor of a structured, documentary-style interface that suggests precision, expertise, and exclusivity.

To move beyond a generic template, we utilize **intentional asymmetry** and **high-contrast typography scales**. We create visual interest through "The Rule of the Ledger"—where data points are given the same typographic importance as prose, and layout density is used to signal "expert-level" depth.

---

## 2. Colors

The palette is designed to mimic high-quality paper stocks and permanent ink. It emphasizes readability and authority over vibrancy.

### Palette Strategy
- **Base Surface (`background`, `surface`):** `#fbf9f4`. This light cream/off-white is the foundation. It provides a warmer, more premium feel than pure white, reducing eye strain during deep work.
- **Ink (`primary`):** `#171818`. A deep charcoal that provides maximum contrast for data and headlines.
- **The Ochre Accent (`secondary`):** `#745b21`. Used sparingly for tags (e.g., "Adequate," "Found") to draw the eye to critical statuses without the urgency of a warning color.
- **Semantic Indicators:** Subtle, desaturated greens (`on_secondary_container`) and deep reds (`tertiary`) are used for comparison indicators and error states.

### The "No-Line" Rule
**Explicit Instruction:** Do not use 1px solid borders to section off large areas of the UI. Separation must be achieved through:
1.  **Background Shifts:** Use `surface_container_low` against `surface` to define regions.
2.  **Tonal Transitions:** Use the color tiers to "nest" content.
3.  **Negative Space:** Leverage the spacing scale to create invisible boundaries.

### Signature Textures & Glassmorphism
For floating elements (modals, dropdowns), use **Glassmorphism**. Apply a semi-transparent `surface_container_lowest` with a `backdrop-blur`. This ensures the "paper" feel remains integrated and sophisticated, allowing the structure of the data below to bleed through slightly.

---

## 3. Typography

Typography is the backbone of this system. It balances the authoritative weight of a traditional journal with the technical clarity of a data sheet.

- **Display & Headline (Newsreader):** A refined serif used for primary headers. It conveys the "Academic" and "Expert" personality. Use `display-lg` for report titles to establish a strong editorial hierarchy.
- **Titles & Body (Work Sans):** A clean, modern sans-serif. It provides high legibility for long-form property descriptions and shopper notes. 
- **Labels & Data (Space Grotesk):** A monospaced-adjacent sans-serif used for numerical values, IDs, and metadata tags (`label-md`). This suggests "Machine Precision."

---

## 4. Elevation & Depth

We eschew traditional drop shadows. Elevation is conveyed through **Tonal Layering** and **Surface Stacking**.

### The Layering Principle
Depth is achieved by stacking `surface_container` tiers.
- **Base:** `surface` (#fbf9f4)
- **Primary Layout Blocks:** `surface_container_low` (#f5f3ee)
- **Interactive Cards/Active Elements:** `surface_container_highest` (#e4e2dd)

### Ambient Shadows
If a "floating" effect is mandatory (e.g., a critical property card being compared), use an **Ambient Shadow**:
- **Color:** A 6% opacity tint of `on_surface` (#1b1c19).
- **Blur:** Large (20px - 40px) with 0 spread to mimic natural, diffused lighting on paper.

### The "Ghost Border"
Borders are only permitted as "Ghost Borders." Use the `outline_variant` (#c4c7c7) at **15% opacity**. This creates a hint of structure for complex data tables without cluttering the visual field.

---

## 5. Components

### Buttons
- **Primary:** High-contrast `primary` (#171818) background with `on_primary` (#ffffff) text. **0px corner radius.**
- **Secondary:** `outline` (#747878) "Ghost Border" with `secondary` (#745b21) text.
- **Tertiary/Ghost:** No background or border; uses `label-md` uppercase with a 1px underline on hover.

### Inputs & Fields
- **Styling:** Forgo the "box" look. Use a `surface_container_low` background with a 1px bottom border using `outline_variant`.
- **States:** Focused states shift the bottom border to `secondary` (muted gold). 

### Cards & Lists
- **Rule:** **Forbid the use of horizontal divider lines.** 
- **Alternative:** Use vertical white space (`spacing-8`) or a subtle shift to `surface_container_lowest` for list item backgrounds. Data should be aligned to a strict vertical grid to maintain the "documentary" feel.

### Status Chips
- Inspired by the reference images, chips are rectangular (**0px radius**) with a `secondary_container` background and `on_secondary_container` text. Use for property statuses like "Under Review" or "Matched."

---

## 6. Do's and Don'ts

### Do
- **Use Sharp Corners:** All containers, buttons, and chips must have a `0px` radius. Roundness contradicts the "Expert" personality.
- **Prioritize Information Density:** Real estate shoppers need data. Don't be afraid of "busy" screens as long as the hierarchy is clear.
- **Embrace Monospaced Data:** Use `Space Grotesk` for all prices, square footage, and dates.
- **Align to the Grid:** Ensure all text elements align to a hard vertical axis, mimicking a printed ledger.

### Don't
- **Don't Use Heavy Shadows:** Avoid anything that looks "floaty" or like a standard mobile app.
- **Don't Use Pure Black:** Use `primary` (#171818) for text to keep the "ink on paper" feel.
- **Don't Use Standard Dividers:** Avoid `1px #CCCCCC` lines. They make the UI look like a generic template. Use tonal shifts or whitespace.
- **Don't Round Anything:** No rounded corners on inputs, cards, or buttons. Precision is represented by sharp edges.```