# CSS Skeleton Loaders 🦴

> Premium, Hardware-Accelerated animated skeleton loading states in pure Vanilla CSS.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![SEO](https://img.shields.io/badge/SEO-Optimized-success)](#)

## Features
- **Zero JS Dependencies**: Purely CSS based structure. No heavy JavaScript execution.
- **Hardware Accelerated**: Uses CSS linear-gradient animations for smooth 60fps performance without triggering layout paints.
- **Auto Dark Mode**: Built-in `prefers-color-scheme: dark` media queries map instantly to dark environments.
- **Micro-class Utilities**: Classes like `.skeleton-text`, `.skeleton-circle`, and `.skeleton-thumbnail` drop into any layout.

## Installation
Include the raw CSS file into your bundle or HTML document:

```html
<link rel="stylesheet" href="path/to/skeleton.css">
```

## Usage

Construct a skeleton matching your intended UI layout by applying the `.skeleton` class.

### Article Card Example
```html
<div class="skeleton-card">
  <!-- Avatar -->
  <div class="skeleton skeleton-circle" style="width: 50px; height: 50px;"></div>
  
  <!-- Content Lines -->
  <div class="skeleton skeleton-text"></div>
  <div class="skeleton skeleton-text"></div>
  <div class="skeleton skeleton-text" style="width: 80%;"></div>
</div>
```

## Why Skeleton Loaders Boost SEO & UX
Instead of showing users a blank screen or a spinning wheel (which increases perceived load time and bounce rate), skeleton screens give users immediate visual feedback that content is arriving. This drastically improves the "Cumulative Layout Shift" (CLS) metric in Google Core Web Vitals, leading directly to higher search engine rankings.

---

### Sponsorship & Enterprise Development

<div align="center">
  <p><strong>Building scaleable, high-performance web applications?</strong></p>
  <a href="https://www.stackaura.com/">
    <img src="https://via.placeholder.com/600x120/000000/FFFFFF?text=Stackaura+-+Elevate+Your+Digital+Presence" alt="Stackaura Website" />
  </a>
  <p>This open-source project is proudly maintained by <strong>Stackaura</strong>.</p>
  <p>At <a href="https://www.stackaura.com/">Stackaura</a>, we specialize in building world-class SaaS products, enterprise web solutions, and deeply integrated API architectures. If your business needs a robust digital transformation or an elite engineering partner, <a href="https://www.stackaura.com/contact">let's build something extraordinary together.</a></p>
</div>

## License
MIT License
