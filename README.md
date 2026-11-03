<div align="center">

# Staircase Carousel
### An interactive photo gallery for Framer

**A gallery that moves differently.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Carousel-0055FF?style=for-the-badge)](https://staircasecarousel.framer.website/)
[![Framer](https://img.shields.io/badge/Built_for-Framer-111111?style=for-the-badge)](https://www.framer.com/)
[![React](https://img.shields.io/badge/React-Component-149ECA?style=for-the-badge)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-TSX-3178C6?style=for-the-badge)](https://www.typescriptlang.org/)

**Made with 💛 by [Karim Saif](https://x.com/karimsaif0)**

</div>

---

## ✦ Live preview

**[Experience Staircase Carousel →](https://staircasecarousel.framer.website/)**

Staircase Carousel turns a standard photo gallery into a playful, editorial-style interaction. Photos slide horizontally and move between vertical steps while the selected image takes center stage. Spring-inspired transitions, animated titles, and convenient navigation make each image feel part of a visual story.

> **Less ordinary scrolling. More visual storytelling.**

## ✨ Features

| | Feature | What it does |
|---|---|---|
| 🪜 | Staircase layout | Combines horizontal progression with vertically offset cards |
| 🎞️ | Spring motion | Adjustable spring bounce, duration and step transitions |
| 🖼️ | Editable photo collection | Add, reorder and replace images through Framer controls |
| 🏷️ | Animated titles | Updates the title of the active image |
| ↔️ | Swipe gestures | Touch, mouse and pen pointer navigation |
| ⌨️ | Keyboard support | Arrow keys, Home and End navigation |
| ⬅️ | Navigation controls | Previous/next arrows and pagination dots or a counter |
| 📐 | Adaptive sizing | Adjusts the photo width to the available frame width |
| 🧘 | Reduced motion | Disables transitions when reduced motion is requested |
| 🎛️ | Framer property controls | Edit visual and interaction settings without changing code |
| 📷 | Demo imagery | Includes six example photo URLs |

## 🌟 Great for

Creative portfolios · Photography websites · Architecture and interiors · Fashion editorials · Brand storytelling · Product presentations · Experimental landing pages

## 🚀 Use in Framer

1. Open a Framer project and create a new **Code Component**.
2. Copy the complete contents of [`KarimSaifStaircaseCarousel.tsx`](./KarimSaifStaircaseCarousel.tsx) into the component file.
3. Add the component to your canvas.
4. Open its property controls to replace the example imagery and customize the experience.
5. Preview the interaction and publish your Framer project.

> This repository contains a **Framer Code Component**, not a standalone React/Vite website. Its `framer` imports and property controls require Framer.

## 🎨 Customize

| Category | Available controls |
|---|---|
| Content | Photo collection, image URLs/uploads, titles, alt text, initial slide |
| Layout | Photo width, staircase step height, card gap, corner radius |
| Motion | Spring bounce, spring duration, step duration, inactive-card scale |
| Typography | Title visibility, size, font family, weight and text color |
| Navigation | Show/hide controls, pagination, navigation colors |
| Interaction | Swipe navigation and keyboard navigation |
| Appearance | Background color and navigation surface color |
| Accessibility | Carousel label and individual image alt text |

Each control in the component includes a description to make customization easier inside Framer.

## 🛠️ Technical details

- React and TypeScript (TSX)
- Framer `addPropertyControls` and `ControlType`
- CSS transform-based animations with sampled spring easing
- `ResizeObserver`-based responsive measurements
- Reduced-motion media query support
- Accessible carousel region, navigation labels and live slide announcement
- No continuous animation frame loop or extra animation dependency

### Notes

- Example photos are hosted on Unsplash and need an internet connection. Replace them with your own properly licensed images for production.
- This is the source version supplied for the demo; Marketplace approval and behavior across all browsers have not been independently verified.
- The component supports a static Framer Canvas presentation, but published-site and device testing is recommended before a Marketplace submission.

## 💡 Design idea

Use the component as a strong visual focal point on a portfolio landing page. Pair carefully curated portrait photography with short titles, tune the spring bounce to your brand's feel, and let the images create a visual rhythm.

## 💬 Support and feedback

Questions, issues, or ideas for improvements? Reach out:

- **X / Twitter:** [@karimsaif0](https://x.com/karimsaif0)
- **Email:** [karimsaif010@gmail.com](mailto:karimsaif010@gmail.com)
- **Live demo:** [staircasecarousel.framer.website](https://staircasecarousel.framer.website/)

---

<div align="center">

**Designers, your next gallery is here.**

Made with 💛 by **Karim Saif**

[Try the Demo](https://staircasecarousel.framer.website/) · [Follow on X](https://x.com/karimsaif0)

</div>
