# Zephirin’s Bakery - Elementor Pro Implementation Guide

This guide outlines how to build the designed screens using WordPress, Elementor Pro, and the Hello Elementor theme.

## 1. Global Site Settings
*   **Fonts (Global Fonts):**
    *   **Primary (Headings):** Poppins (Bold/Semi-bold)
    *   **Secondary (Body):** Figtree (Regular/Medium)
    *   **Accent:** Plus Jakarta Sans (for UI elements/labels)
*   **Colors (Global Colors):**
    *   **Primary:** `#5C4033` (Deep Cocoa)
    *   **Secondary:** `#8B5E3C` (Warm Cinnamon)
    *   **Accent:** `#D2691E` (Burnt Orange)
    *   **BG Main:** `#FAF3E0` (Cream)
    *   **BG Accent:** `#EDE0D4` (Soft Sand)
*   **Layout:**
    *   **Content Width:** 1200px (standard) / 1440px (wide)
    *   **Widgets Spacing:** 0px (use Container padding/gaps)

## 2. Global Templates (Theme Builder)
*   **Header:** 
    *   Structure: 3-column Container (Sticky).
    *   Widgets: Site Logo, WordPress Menu, Button.
    *   Motion Effects: Scrolling Effects -> Transparency / Background Color change.
*   **Footer:**
    *   Structure: 4-column Grid Container.
    *   Widgets: Image (Logo), Text Editor (Brand statement), Nav Menu (Quick Links), Icon List (Social), Form (Newsletter).
*   **Single Product:**
    *   Dynamic Tags: Use 'Post Title', 'Featured Image', and 'Post Content' or custom fields (ACF) for ingredients and nutrition.

## 3. Key Section Implementations
### Hero Sections (Home & Mini-Heros)
*   **Widget:** Container with Background Image/Video.
*   **Floating Elements:** Use 'Image' widgets set to `Position: Absolute`.
*   **Animation:** Apply 'Floating' custom CSS (provided below) or Elementor Motion Effects (Vertical Scroll).

### Product & Recipe Grids
*   **Widget:** Loop Grid (Elementor Pro).
*   **Design:** Custom Loop Item template with Image, Heading, and Button.
*   **Hover:** Container -> Style -> Hover -> Scale/Box Shadow.

## 4. "Antigravity" Custom CSS
Add these snippets to **Elementor -> Custom Code** or a specific container's **Advanced -> Custom CSS**.

### Floating Bread Animation
```css
selector {
    animation: floatBread 6s ease-in-out infinite;
}

@keyframes floatBread {
    0% { transform: translateY(0px) rotate(0deg); }
    50% { transform: translateY(-20px) rotate(3deg); }
    100% { transform: translateY(0px) rotate(0deg); }
}
```

### Premium Button Glow
```css
selector .elementor-button {
    transition: all 0.4s cubic-bezier(0.25, 1, 0.5, 1);
}

selector .elementor-button:hover {
    transform: translateY(-4px);
    box-shadow: 0 15px 30px rgba(210, 105, 30, 0.3);
}
```

## 5. Responsive Strategy
*   **Containers:** Use 'Wrap' for mobile to stack columns.
*   **Images:** Use WebP format for fast loading on mobile.
*   **Motion:** Disable heavy parallax on mobile devices via the 'Motion Effects' settings to preserve battery and performance.
