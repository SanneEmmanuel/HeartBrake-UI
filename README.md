# 💔 HeartBrake UI

**HeartBrake UI** is a hybrid CSS design system that merges the best parts of Material Design, Apple Human Interface Guidelines (HIG), and Bootstrap — while fixing their individual limitations.

It is lightweight, framework-agnostic, fully responsive, and ships with built-in support for theming, animations, accessibility, and scalable UI components.

---

## 🚀 Features

- ✅ Atomic token system (colors, spacing, elevation, motion)
- 🎨 Custom theming (light/dark modes)
- 💻 Responsive grid system (Bootstrap-inspired)
- 🧩 Reusable UI components (buttons, cards, modals, inputs)
- 🎞 Stunning CSS animations (from natural to experimental)
- 🌓 Theme toggle with no JavaScript dependencies required
- ⚡ Pure CSS — no frameworks or build tools needed

---

## 📁 Files

| File               | Purpose                                                     |
|--------------------|-------------------------------------------------------------|
| `heartbrake.min.css` | All-in-one CSS file with tokens, components, animations, themes |
| `demo.html`          | A preview demo showing all features and animations          |
| `README.md`          | You are here. Documentation and usage instructions          |

---

## 🧪 Demo

Open `demo.html` in your browser to see all the available components and animations in action.

---

## 🌈 Theming

HeartBrake UI uses `CSS custom properties` and the `data-theme` attribute for easy theming:

```html
<html data-theme="dark"> <!-- Use 'light' or 'dark' -->
````

Toggle theme via a simple JS snippet:

```js
document.documentElement.setAttribute(
  'data-theme',
  document.documentElement.getAttribute('data-theme') === 'dark' ? 'light' : 'dark'
);
```

---

## 📦 Usage

Include it in your HTML:

```html
<link rel="stylesheet" href="heartbrake.min.css">
```

Then use utility classes like:

```html
<button class="btn btn--secondary animate-fadeIn">Click Me</button>
```

---

## 📚 Components

* `.btn`, `.btn--secondary`
* `.input`
* `.card`
* `.modal`
* `.container`, `.row`, `.col`, `.col-6`
* Animation classes:

  * `.animate-fadeIn`
  * `.animate-slideUp`
  * `.animate-zoomIn`
  * `.animate-bounce`
  * `.animate-ghostTrail`
  * `.animate-rotate3D`
  * `.animate-quantum`
  * `.animate-stutter`
  * `.animate-portal`

---

## 🛠 Customization

HeartBrake UI is modular. You can extend it by:

* Overriding CSS variables
* Creating your own components in the same style
* Adding additional animation classes

---

## 🧠 Credits

Designed by **Sanne Karibo**
Inspired by:

* 🟦 Material Design (Google)
* 🍏 Apple Human Interface Guidelines
* 🔵 Bootstrap CSS Framework
  Built with ❤️ in 2025

```
```
