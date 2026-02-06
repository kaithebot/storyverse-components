# StoryVerse UI Components

A collection of reusable, customizable UI components for the StoryVerse Hub platform. Built with pure HTML and CSS - no JavaScript frameworks required.

## 🎨 Components

### 1. Button Component (`components/button.html`)
Versatile buttons with multiple variants and states.

**Features:**
- Primary and secondary styles
- Multiple sizes (small, default, large)
- Icon support
- Loading state
- Shine hover effect
- Fully accessible

**Usage:**
```html
<!-- Primary Button -->
<button class="sv-btn sv-btn-primary">Click Me</button>

<!-- Large Button with Shine -->
<button class="sv-btn sv-btn-primary sv-btn-large sv-btn-shine">
    Get Started
</button>

<!-- Loading State -->
<button class="sv-btn sv-btn-primary sv-btn-loading">Processing</button>
```

---

### 2. Card Component (`components/card.html`)
Flexible card layouts for products, stories, and content.

**Features:**
- Standard and horizontal layouts
- Image with hover zoom
- Badge support
- Price display
- Dark variant
- Story book preview style

**Usage:**
```html
<!-- Standard Product Card -->
<div class="sv-card">
    <img src="book.jpg" alt="Book" class="sv-card-image">
    <div class="sv-card-content">
        <h3 class="sv-card-title">Book Title</h3>
        <p class="sv-card-description">Description...</p>
        <div class="sv-card-footer">
            <span class="sv-card-price">$29.99</span>
            <button class="sv-btn sv-btn-primary">Buy</button>
        </div>
    </div>
</div>

<!-- Story Preview Card -->
<div class="sv-story-card">
    <img src="story.jpg" alt="Story">
    <div class="sv-story-card-overlay">
        <h4 class="sv-story-card-title">Story Title</h4>
        <p class="sv-story-card-author">Created for Child</p>
    </div>
</div>
```

---

### 3. Hero Section (`components/hero.html`)
Eye-catching hero sections for landing pages.

**Features:**
- Two-column responsive layout
- Animated floating image
- Stats display
- Gradient backgrounds
- Light and dark variants
- Decorative background elements

**Usage:**
```html
<section class="sv-hero">
    <div class="sv-hero-content">
        <div class="sv-hero-text">
            <div class="sv-hero-badge">✨ Trusted by 10k+</div>
            <h1 class="sv-hero-title">Your Title <span>Highlight</span></h1>
            <p class="sv-hero-description">Description...</p>
            <div class="sv-hero-buttons">
                <button class="sv-btn sv-btn-primary">CTA</button>
            </div>
        </div>
        <div class="sv-hero-image">
            <img src="hero.jpg" alt="Hero">
        </div>
    </div>
</section>
```

---

## 🚀 Quick Start

### Option 1: Copy & Paste
1. Open the component HTML file
2. Copy the CSS from the `<style>` block
3. Copy the HTML structure you need
4. Paste into your project

### Option 2: Link Stylesheet (Coming Soon)
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kaithebot/storyverse-components@main/dist/storyverse-components.css">
```

---

## 🎨 Design System

### Colors
- **Primary:** `#6366f1` (Indigo)
- **Secondary:** `#8b5cf6` (Purple)
- **Accent:** `#d946ef` (Pink)
- **Text Dark:** `#1e1b4b`
- **Text Light:** `#4b5563`
- **Background:** `#fef3c7` (Warm cream)

### Typography
- **Headings:** Playfair Display
- **Body:** Quicksand

### Spacing
- Card padding: `1.5rem`
- Button padding: `0.875rem 2rem`
- Border radius: `20px` (cards), `50px` (buttons)

---

## 📦 File Structure

```
storyverse-components/
├── README.md
├── components/
│   ├── button.html
│   ├── card.html
│   └── hero.html
└── examples/ (coming soon)
    ├── landing-page.html
    └── product-page.html
```

---

## 🎯 Use Cases

- **Landing Pages:** Use Hero + Button components
- **Product Listings:** Use Card components
- **E-commerce:** Combine Cards with Buttons
- **Portfolio:** Use Story Cards for projects

---

## 🔧 Customization

All components use CSS custom properties for easy theming:

```css
:root {
    --sv-primary: #6366f1;
    --sv-secondary: #8b5cf6;
    --sv-accent: #d946ef;
    /* Override these to customize */
}
```

---

## 📱 Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

---

## 🤝 Contributing

1. Fork the repository
2. Create a new component in `/components/`
3. Include usage examples
4. Submit a pull request

---

## 📄 License

MIT License - Free for personal and commercial use.

---

## 🎨 StoryVerse Hub

These components are part of the StoryVerse Hub platform - creating magical personalized stories for children.

**Repository:** https://github.com/kaithebot/storyverse-components

Built with ❤️ by the StoryVerse team.
