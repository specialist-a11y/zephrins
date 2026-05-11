# Concept 2 x AI Planner Migration

The goal is to build an Elementor website that follows the structure outlined in the `Zephirin's Bakery Sitemap - AI Website Planner.pdf` while using the premium design language from `concept2.html`.

## User Review Required

> [!IMPORTANT]
> **Design Language Conflict:** The PDF brief suggests colors like `#5C4033` and fonts like `Poppins` / `Figtree`. However, `concept2.html` uses a much more premium palette (`#ff6824`, `#1e0900`, `#fff8f2`) and fonts (`Playfair Display` / `Inter`). Since you asked for "something similar to concept 2", I plan to **ignore the PDF's color/font suggestions** and strictly use Concept 2's design tokens. Please confirm this is correct.

> [!WARNING]
> **Scope of Work:** The PDF outlines a full 6-page sitemap (Home, About, Products, Locator, Contact, Recipes). Building all 6 pages at once is a massive task. I propose we build the **Home Page** first to establish the global styles, templates, and component designs. Once the Home Page is approved, we can roll out the remaining 5 subpages. 

## Open Questions

1. Do you want me to create blank placeholder pages for the other 5 pages (About, Products, Locator, Contact, Recipes) so the navigation works, or just focus entirely on building out the Home Page first?
2. Are there specific images in the WordPress media library you want me to use, or should I use the placeholder images from `concept2.html` and Openverse for now?

## Proposed Changes

### 1. Global Settings
#### [MODIFY] Elementor Global Kit
- **Colors:** Update global colors to Concept 2 (`--orange: #ff6824`, `--brown-dark: #1e0900`, `--cream: #fff8f2`, etc.)
- **Typography:** Update global typography to `Playfair Display` (Headings) and `Inter` (Body).

### 2. Pages
#### [NEW] Home Page
We will build the Home page using the sections specified in the PDF, styled like Concept 2:
- **Welcome to Zephirin's Bakery (Hero):** 100vh, dark gradient overlay, large italicized Playfair heading, dual buttons.
- **Our Heritage:** Two-column layout mimicking Concept 2's "Story" section (large watermark year, overlapping images).
- **Our Products:** Three-column loop grid using Concept 2's "Products" card design (hover lift, orange badge).
- **Join Our Community:** A sleek newsletter signup container.
- **What Our Customers Say:** Testimonial carousel styled like Concept 2's "Quote Band".
- **Get in Touch:** Two-column layout with contact info and a map (similar to Concept 2's "Locator").

## Verification Plan

### Manual Verification
- Once the Home page is built, I will provide the preview URL.
- We will review the responsive layouts and hover animations to ensure they match the premium feel of the static `concept2.html` file.
