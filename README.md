# 📝 Online Class Feedback Form

A responsive and modern **Online Class Feedback Form** designed using HTML5 and CSS3. This project demonstrates all three ways of applying CSS (**Inline CSS**, **Internal CSS**, and **External CSS**) alongside various essential **CSS Selectors**.

---

## 🚀 Key Features

- **Clean & Modern UI**: Built with a clean card layout, smooth animations, and responsive typography.
- **Comprehensive Feedback Collection**:
  - Student & Course details (Name, Email, Course dropdown, Instructor name)
  - Interactive rating options (1 to 5 scale)
  - Class pace selection
  - Checklist for what worked well (Slides, code, doubts, video/audio)
  - Detailed comments/suggestions textarea
- **Responsive Design**: Works on mobile, tablet, and desktop screens.

---

## 🎨 CSS Styling Demonstrations

### 1. External CSS (`style.css`)
- Linked in `<head>` using `<link rel="stylesheet" href="style.css">`.
- Defines CSS custom properties (`:root` variables) for primary colors, backgrounds, borders, and shadows.
- Controls global typography, input styling, buttons, and flex layouts.

### 2. Internal CSS (`<style>` in `index.html`)
- Written inside the `<head>` tag.
- Includes keyframe animation (`@keyframes slideInUp`) for a smooth entrance effect.
- Header section border, title typography, section dividers, and media queries (`@media (max-width: 600px)`).

### 3. Inline CSS (`style="..."` attributes)
- Used directly on specific HTML elements for one-off tweaks:
  - Header badge (`display: inline-block; background-color: #dbeafe; ...`)
  - Info notice banner (`background-color: #f0fdf4; border-left: 4px solid #22c55e; ...`)
  - Required field asterisk (`color: #ef4444; font-weight: bold;`)
  - Submit button custom elevation (`box-shadow: 0 4px 14px rgba(...)`)
  - Footer security note (`text-align: center; color: #94a3b8; ...`)

---

## 🎯 CSS Selectors Used

| Selector Type | Example in Code | Description |
| :--- | :--- | :--- |
| **Universal Selector** | `*` | Resets margin, padding, and sets `box-sizing: border-box`. |
| **Element Selector** | `body`, `label`, `select`, `textarea` | Applies base styles to all HTML elements of that type. |
| **Class Selector** | `.btn`, `.form-group`, `.btn-primary` | Styles reusable components and layouts. |
| **ID Selector** | `#feedback-form`, `#rating-options` | Styles specific unique elements and animations. |
| **Attribute Selector** | `input[type="text"]`, `input[type="email"]` | Targets input elements based on their HTML attributes. |
| **Child Combinator** | `.radio-pill-group > label` | Selects direct child `label` elements inside `.radio-pill-group`. |
| **Descendant Combinator** | `.checkbox-grid .checkbox-item` | Selects `.checkbox-item` nested anywhere inside `.checkbox-grid`. |
| **Adjacent Sibling** | `input[type="radio"]:checked + span` | Targets `span` directly adjacent to a checked radio input. |
| **Pseudo-Classes** | `:hover`, `:focus`, `:checked`, `:nth-child(even)` | Applies styling based on state (hover, active focus, checked). |
| **Pseudo-Elements** | `::placeholder` | Customizes placeholder text color and style. |

---

## 📦 How to Push this Project to GitHub (Git Steps)

If you haven't initialized or pushed yet, follow these commands in your terminal:

```bash
# 1. Navigate to the project directory
cd "C:\Users\sujit\.gemini\antigravity\scratch\online-class-feedback-form"

# 2. Initialize Git repository
git init

# 3. Add all files to staging
git add .

# 4. Commit files
git commit -m "Initial commit: Online Class Feedback Form with Inline, Internal, External CSS and Selectors"

# 5. Rename default branch to main
git branch -M main

# 6. Add your GitHub remote repository (replace with your repo URL)
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

# 7. Push code to GitHub
git push -u origin main
```
