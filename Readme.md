# 🎬 Movie Website Clone

A responsive movie browsing web app inspired by modern streaming platforms. This project is a front-end clone built to practice UI design, API handling, and React development skills.

## 🚀 Live Demo
https://cloneofmoviewebsite.netlify.app/

---

## ✨ Features

### 🎬 Interactive Trending Showcase
*   **Premium Stacking Order:** Custom layer arrangement using computed `z-index` values to map stylized ranking numbers cleanly *in front* of trending media poster wrappers.
*   **Cinematic Transitions:** Fluid, high-performance card interactions using hardware-accelerated cubic-bezier curves (`transform: scale(1.06)`).
*   **Dynamic Glow Highlights:** Hovering states emit custom backlighting layers on the localized selection panels.

### ⚡ UX & Architecture Improvements
*   **Corner Emoji Graphics:** The "More Reasons to Join" columns feature bottom-pinned responsive emojis that feature reactive scaling and rotation (`rotate(-8deg)`) animations when touched.
*   **Native Details Dropdowns:** The Frequently Asked Questions board relies purely on native semantic HTML `<details>` and `<summary>` vectors, executing zero-js expansion transitions smoothly.
*   **Responsive Adaptation:** Comprehensive media breaks engineered down to `320px` structures to ensure seamless navigation across mobile viewports, tablets, and ultrawide desktops.

---

## 🛠️ Technical Stack

*   **Markup:** HTML5 (Semantic Structure)
*   **Styling:** Vanilla CSS3 (Custom Variables, Advanced Gradients, Flexbox, Grid)
*   **Typography:** Google Fonts integration (Roboto Weights 400–900)
*   **Assets:** Optimized inline vector SVGs for lossless scalability

---

## 📂 Project Directory Structure

```text
├── index.html          # Main application structure & landing page layout
├── style.css           # Global typography, color variables, and animation classes
├── bg1.png             # Premium hero header perspective layout backdrop
├── 1.jpg               # Localized Trending Card Media asset 1
├── 2.jpg               # Localized Trending Card Media asset 2
├── 3.jpg               # Localized Trending Card Media asset 3
├── 4.jpg               # Localized Trending Card Media asset 4
└── 5.jpg               # Localized Trending Card Media asset 5

## 📂 Project Setup

Clone the repo:
```bash
git clone https://github.com/your-username/repo-name.git