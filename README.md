# HCD206-Human-Center-Design

# Bloom Cafe | AI Menu Ordering App
### HCD206 Human Centred Design for Software Engineering | Assessment 3

---

## Overview

This project is an interactive prototype of an AI-based restaurant menu ordering app designed for **Bloom Cafe**, a casual brunch restaurant. It was built as part of Assessment 3 for HCD206 at Torrens University Australia.

The app allows diners to browse and order from an Entree, Mains and Desserts menu on a restaurant tablet or personal mobile device. An AI engine filters recommendations based on dietary preferences, and a persistent cart in the header keeps the diner informed of their order at all times.

---

## Live Demo

Open `https://bloom-cafe-soksereyvathna-uk.vercel.app/` directly in any browser. No installation or server required.

---

## Features

- **3 linked screens** | Entrees, Mains and Desserts, all navigable in any order
- **AI recommendations** | Chef's Pick badges highlight personalised pairings
- **Working dietary filters** | Vegetarian, Gluten-Free, Dairy-Free, Halal and Nut-Free chips that actually show and hide cards in real time
- **Persistent cart in header** | always visible item count and running total, just like Uber Eats or Mr Yum
- **Order review panel** | slide-in panel showing all items across all courses with editable quantities
- **Empty order validation** | Send to Kitchen is blocked if the cart is empty
- **Accessibility** | WCAG 2.1 AA compliant tap targets, icon plus text labels, colour and shape allergen tags
- **Real image slots** | every food card has an image placeholder ready for your own photos

---

## How to Add Your Own Food Photos

1. Put your image files in the same folder as the HTML file
2. Name each image exactly as shown in the placeholder label on each card

| Card | Expected filename |
|------|------------------|
| Avocado Toast | `ENTREE_1_AVOCADO_TOAST.jpg` |
| Seasonal Fruit Platter | `ENTREE_2_FRUIT_PLATTER.jpg` |
| Mushroom Bruschetta | `ENTREE_3_MUSHROOM_BRUSCHETTA.jpg` |
| Acai Bowl | `ENTREE_4_ACAI_BOWL.jpg` |
| Heirloom Tomato Soup | `ENTREE_5_TOMATO_SOUP.jpg` |
| Green Smoothie Bowl | `ENTREE_6_SMOOTHIE_BOWL.jpg` |
| Poached Eggs on GF Sourdough | `MAIN_1_POACHED_EGGS.jpg` |
| Smashed Avo Bowl | `MAIN_2_SMASHED_AVO_BOWL.jpg` |
| Wild Mushroom Risotto | `MAIN_3_MUSHROOM_RISOTTO.jpg` |
| Roasted Veggie Frittata | `MAIN_4_VEGGIE_FRITTATA.jpg` |
| Quinoa Power Bowl | `MAIN_5_QUINOA_BOWL.jpg` |
| GF Lemon Tart | `DESSERT_1_LEMON_TART.jpg` |
| Vanilla Panna Cotta | `DESSERT_2_PANNA_COTTA.jpg` |
| Dark Choc Mousse | `DESSERT_3_CHOC_MOUSSE.jpg` |
| Mini Pavlova | `DESSERT_4_PAVLOVA.jpg` |
| Sorbet Trio | `DESSERT_5_SORBET.jpg` |
| Matcha Tiramisu | `DESSERT_6_MATCHA.jpg` |

---

## File Structure

```
/
├── Bloom_Cafe_Prototype.html   # Full interactive prototype (single file)
├── HCD206_A3_Report.docx       # 500-word report with journey map and checklist
└── README.md                   # This file
```

---

## Technologies Used

- HTML5
- CSS3 (no frameworks)
- Vanilla JavaScript (no libraries)
- Google Fonts | Playfair Display and DM Sans

---

## HCD Principles Applied

| Norman (2013) Principle | Where Applied |
|------------------------|---------------|
| Mapping | Dietary preference icons directly represent their meaning |
| Feedback | Cart updates immediately when an item is added |
| Visibility of System Status | Cart always visible in header across all screens |
| Constraints | Only items matching active filters are shown |
| Affordance | Send to Kitchen button size and placement communicate its function |

---

## Assessment Details

| Field | Details |
|-------|---------|
| Subject | HCD206 Human Centred Design for Software Engineering |
| Assessment | Assessment 3: System Implementation |
| Weighting | 40% |
| Institution | Torrens University Australia |

---

## Academic Integrity

This prototype was built entirely by the student as part of a graded assessment. All code was written from scratch. No templates, frameworks or AI-generated code were used in the final submission.

---

*Bloom Cafe prototype | HCD206 Assessment 3*


