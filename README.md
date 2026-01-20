Here’s the README content:

---
# TechWave Podcast Website

## Overview

**TechWave** is a responsive, modern, and visually engaging podcast website designed to showcase a technology-focused podcast. It features a hero section, about section, featured episodes, host details, and multiple call-to-action buttons. The website is built using **HTML5** and **CSS3**, with responsive design considerations for small, medium, and large devices.

The overall aesthetic combines dark, vibrant gradients with neon highlights for a tech-inspired visual appeal.

---

## Table of Contents

* [Features](#features)
* [Technologies Used](#technologies-used)
* [File Structure](#file-structure)
* [HTML Structure](#html-structure)
* [CSS Styling](#css-styling)
* [Responsive Design](#responsive-design)
* [How to Use](#how-to-use)

---

## Features

1. **Navbar with Logo and Links**

   * Sticky and visually prominent logo with gradient text.
   * Navigation links for Home, About, Episodes, and Host sections.
   * Subscribe button with gradient hover effect.
   * Hamburger menu for mobile responsiveness.

2. **Hero Section**

   * Large central hero image with circular microphone overlay.
   * "NEW" badge highlight.
   * Call-to-action buttons for Spotify and subscription.
   * Engaging hero text with title and description.

3. **About Section**

   * Introduction to the podcast.
   * Podcast statistics displayed in a grid (monthly listeners, episodes, ratings, industry experts).

4. **Why TechWave Section**

   * Features grid highlighting podcast benefits like premium audio, mobile-friendliness, global community, exclusive interviews, and rich resources.
   * Grid layout adapts to screen size for responsiveness.
   * Supports both image icons and FontAwesome icons.

5. **Featured Episodes Section**

   * Embedded YouTube videos for episodes.
   * Episode title, description, and duration.
   * Interactive hover effects with subtle scaling and shadows.

6. **Host Section**

   * Host image and biography.
   * Social media links with hover animation effects.

7. **Footer / Banner Section**

   * Podcast platform icons for Spotify, Apple Podcasts, YouTube, and Twitter.
   * Gradient text for logo.
   * Footer text with copyright information.

---

## Technologies Used

* **HTML5** – Semantic structure and accessibility-friendly elements.
* **CSS3** – Modern styling with gradients, flexbox, grid layouts, and hover effects.
* **Font Awesome** – For custom icons in the features section.
* **Google Fonts** – Inter font family for clean typography.
* **Responsive Design** – Mobile-first approach with media queries for small, medium, and large devices.

---

## File Structure

```
TechWave/
├── assets/
│   ├── hero-circle.png
│   ├── hero-bg.png
│   ├── microphone.png
│   ├── headphone.png
│   ├── device.png
│   ├── location.png
│   ├── resource.png
│   ├── host.png
│   ├── spotify.png
│   ├── apple-podcast.png
│   ├── youtube-podcast.png
│   ├── twitter.png
│   ├── linkedin.png
│   └── instagram.png
├── styles/
│   └── style.css
├── index.html
└── README.md
```

---

## HTML Structure

The HTML is organized into sections for modularity and semantic meaning:

1. **Header / Navbar**

   * `.navbar`: Contains logo, navigation links, hamburger menu, and subscribe button.

2. **Hero Section**

   * `.hero`: Main landing section with background image, circular hero element, mic overlay, badge, heading, description, and CTA buttons.

3. **About Section**

   * `.about`: Includes podcast introduction, description paragraphs, a divider line, and stats grid.

4. **Why TechWave Section**

   * `.why-techwave`: Features grid of cards, each highlighting a podcast feature. Supports both image and icon-based cards.

5. **Featured Episodes Section**

   * `.featured`: Grid of embedded YouTube episodes with titles, descriptions, and duration indicators.

6. **Host Section**

   * `.host`: Card containing host image, bio, and social links.

7. **Footer / Banner Section**

   * `.techwave-banner`: Includes background image, gradient title, platform icons, and footer text.

---

## CSS Styling

### General

* **Reset and Base Styles**: Universal selector removes margin/padding and sets `box-sizing: border-box`.
* **Font Family**: "Inter" applied across the site for consistency.
* **Color Scheme**: Dark backgrounds with neon green/purple/gradient accents.
* **Typography**: Bold headings for emphasis, readable paragraph text.

### Navbar

* Flexbox used for alignment.
* Hover effects for subscribe button.
* Hamburger menu displayed only on mobile devices using media queries.

### Hero Section

* Centered content using flexbox.
* Hero circle uses `position: relative` for mic overlay and badge positioning.
* Background image with `cover` ensures full-width coverage.

### About Section

* Radial gradient background.
* Stats displayed using CSS grid.
* Divider line implemented with subtle opacity.

### Why TechWave / Features Grid

* CSS Grid with `grid-template-areas` to match custom design.
* Card styling with padding, border-radius, and flex column layout.
* Image and FontAwesome icon support.
* Hover animations for interactivity.

### Featured Episodes

* Responsive grid layout.
* Hover scaling and shadow for interactive effect.
* Iframes embedded for YouTube episodes.

### Host Section

* Flexbox layout for host image and content.
* Social icons with hover animation and gradient background.
* Circular host image with `object-fit: cover`.

### Footer

* Gradient text for logo.
* Flexbox for social/platform icons.
* Background image with overlay for styling.

---

## Responsive Design

The project uses **media queries** to adapt layouts across different screen sizes:

* **Small devices (<576px)**: Single-column layouts for features, episodes, and host sections. Navbar converts to hamburger menu. Buttons and hero elements resize.
* **Medium devices (576px–992px)**: Two-column layouts for features and episodes. Hero content adjusts font size.
* **Large devices (992px–1200px)**: Padding and spacing adjustments for hero, features, and host sections.

The responsive approach ensures a consistent experience on mobile, tablet, and desktop devices.

---

## How to Use

1. Clone or download the repository.
2. Ensure the `assets` folder contains all images/icons referenced in the HTML.
3. Open `index.html` in any modern browser to view the website.
4. Optionally, customize colors, fonts, or images by editing `style.css`.
5. The YouTube iframe links can be replaced with your own podcast episode videos.
6. Social links and subscription buttons can be updated to match your own podcast accounts.

---

## Notes

* All external fonts and icons are loaded via **Google Fonts** and **Font Awesome CDN**.
* Background images and icons should be placed in the `assets` folder for proper referencing.
* Designed for dark-mode aesthetic with neon accents for a modern tech look.

---