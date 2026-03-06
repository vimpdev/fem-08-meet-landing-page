# 🚀 Frontend Mentor - Meet landing page solution

![Frontend Mentor Challenge](https://img.shields.io/badge/Frontend%20Mentor-Challenge-blue)
![Status](https://img.shields.io/badge/status-completed-success)

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR).  
The goal of this project was to build a responsive landing page with hover states and reproduce the design as closely as possible while maintaining good accessibility and semantic structure.

---

## 🎬 Demo

![Meet landing page demo](./docs/demo.gif)

---

## 🎯 The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

---

## 📸 Screenshot

### 📱 Mobile

![Mobile layout of the Meet landing page](./docs/mobile-default.avif)

### 📲 Tablet

![Tablet layout of the Meet landing page](./docs/tablet-default.avif)

### 🖥️ Desktop

![Desktop layout of the Meet landing page](./docs/desktop-default.avif)

### 🖥️ Desktop interaction &ndash; Hover & Focus-Visible

![Desktop view showing hover and focus-visible states](./docs/desktop-interaction.avif)

---

## 🔗 Links

- 🌎 [Live site](https://vimpdev.github.io/fem-08-meet-landing-page/)

- 🧑‍💻 [View solution on Frontend Mentor](https://www.frontendmentor.io/solutions/meet-landing-page-mobile-first-and-accessible-OdzYrzERJn)

---

## 🛠️ Built with

- Semantic HTML5
- Mobile-first workflow
- CSS custom properties
- Flexbox
- CSS Grid
- Variable font
- Modern CSS features:
  - `clamp()`
  - `text-wrap`
  - `overflow: clip`
- Focus on accessibility and keyboard navigation

---

## 🧠 What I learned

This project helped reinforce several modern CSS and accessibility practices.

### 📌 Managing decorative overflow with `overflow-x: clip`

The hero images intentionally extend outside the viewport in the desktop design.  
Using overflow-x: clip prevents horizontal scrolling while still allowing the visual effect.
```css
.hero {
  overflow-x: clip;
}
```

### 📌 Creating accessible focus styles
```css
:focus-visible {
  outline: 2px dotted var(--clr-outline);
  outline-offset: 2px;
}
```
Using `:focus-visible` ensures that keyboard users receive visible focus indicators without affecting mouse interactions.

---

## 🔄 Continued Development

- CSS architecture and component reuse
- Advanced accessibility patterns
- More modern CSS features
- Performance optimization

---

## 📖 Useful Resources

- [`:focus-visible`](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Selectors/:focus-visible) – Accessibility guide.
- [Open Graph](https://www.opengraph.xyz/) – Meta tags generator.
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) – For validating color accessibility.

---

## 🤖 AI Collaboration

AI was used as a **technical assistant and reviewer**, not as an automatic generator.

- Reviewed semantic structure.
- Validated accessibility decisions.
- Helped refine commit strategy.
- Assisted in improving documentation quality.

All implementation decisions were reviewed and understood before being applied.

---

## 👤 Author

- Frontend Mentor – [@vimpdev](https://www.frontendmentor.io/profile/vimpdev)

---

## 👏 Acknowledgments

Thanks to the Frontend Mentor community for providing high-quality challenges that help developers improve through real-world projects.