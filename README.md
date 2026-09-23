# Budget Tracker – CSS Visual Design

This document explains the CSS work done for the **Visual Design Challenge**.

The goal of this stage was to improve the visual appearance of the existing Budget Tracker using only CSS — no new HTML structure or JavaScript was added.

---

## Design Goals

- Create a clean and professional look
- Use a consistent color palette
- Improve readability with custom typography
- Style the form and expense table properly
- Apply the CSS Box Model to create clear visual sections (cards)

---

## 1. Color Palette

A simple teal-based color palette was chosen for a modern and professional feel.

| Role              | Color     | Hex Code  |
|-------------------|-----------|-----------|
| Primary           | Teal      | `#0d9488` |
| Primary Dark      | Dark Teal | `#0f766e` |
| Page Background   | Light Teal| `#f0fdfa` |
| Card Background   | White     | `#ffffff` |
| Heading Text      | Dark Teal | `#134e4a` |
| Body Text         | Soft Gray | `#334155` |
| Borders           | Light Teal| `#99f6e4` |
| Table Header      | Teal      | `#0d9488` |
| Alternating Rows  | Very Light Teal | `#f0fdfa` |

These colors were applied consistently to:
- Page background
- Headings
- Buttons
- Table header
- Borders and cards

---

## 2. Typography

Two Google Fonts were used to create clear visual hierarchy:

- **Poppins** → Used for all headings (`h1`, `h2`, `h3`) and the button
- **Inter** → Used for body text, form inputs, table content, and labels

This combination improves readability and gives the page a more polished appearance compared to default browser fonts.

---

## 3. Form and Table Styling

### Add Expense Form
- Consistent padding inside inputs and select
- Rounded corners (`border-radius: 8px`)
- Light background and soft borders
- Clear focus state with teal outline
- Styled button with hover effect

### Expense Table
- Styled table header with teal background and white text
- Proper padding inside cells
- Borders for better structure
- Alternating row colors for easier reading
- Hover effect on rows
- Rounded card container around the whole table

---

## 4. CSS Box Model

The Box Model was used intentionally to organize the page:

- **Margin** → Creates space between different sections
- **Padding** → Adds comfortable space inside cards and form elements
- **Border** → Defines the edges of each section
- **Border-radius** → Gives a modern, softer look

The following parts of the page were styled as distinct **cards**:

1. Add Expense form section
2. Expense Table section
3. “How to use” details section
4. Budgeting Tips video section

Each card has:
- White background
- Soft teal border
- Rounded corners
- Subtle box-shadow
- Consistent internal padding

---

## Files

- `style.css` → Contains all the visual design styles
- `index.html` → Existing structure (not modified in this stage)

---

## Summary of CSS Techniques Used

- CSS Custom Properties (variables) for the color palette
- Google Fonts integration
- Flexbox for form layout
- Table styling (`border-collapse`, `nth-child`, hover)
- Box Model properties (`margin`, `padding`, `border`, `border-radius`)
- Hover and focus states for better interactivity
- Responsive adjustments for smaller screens

---

## Result

The Budget Tracker now has a clean, consistent, and professional appearance that is easier to read and more pleasant to use, while fully meeting the Visual Design Challenge requirements.
