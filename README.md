# HyperFrame — Creative Agency & Digital Studio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://en.wikipedia.org/wiki/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://en.wikipedia.org/wiki/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Design-Responsive-success?style=flat)](#features)
[![Brand](https://img.shields.io/badge/Brand-HyperFrame-ff799e?style=flat)](#brand-identity--contact-details)

**HyperFrame** is a premium, responsive multi-page digital agency and creative studio website template. Built for modern design agencies, marketing firms, tech studios, and creative freelancers, HyperFrame delivers a bold aesthetic, fluid parallax animations, touch-enabled carousels, and modular showcases for services and portfolios.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Brand Identity & Contact Details](#brand-identity--contact-details)
- [Page Directory](#page-directory)
- [Project Structure](#project-structure)
- [Technologies & Libraries](#technologies--libraries)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Running Locally](#running-locally)
- [Customization Guide](#customization-guide)
  - [Updating Brand & Logo](#updating-brand--logo)
  - [Updating Contact Details](#updating-contact-details)
  - [Color Palette](#color-palette)
- [Browser Compatibility](#browser-compatibility)
- [License](#license)

---

## 🌟 Overview

HyperFrame offers a complete digital web solution with multiple homepage options, comprehensive service breakdowns, multi-layout portfolio showcases, an editorial blog ecosystem, and dedicated contact workflows. Designed with a clean dark-accent aesthetic (`#15192b`), vibrant pink highlights (`#ff799e`), and typography powered by Google Fonts (*Poppins*, *DM Sans*, *Roboto*).

---

## 🚀 Key Features

- **Multi-Layout Homepages**: Choose between two unique homepage experiences featuring hero sliders, agency metrics, and interactive service cards.
- **Off-Canvas Slide Drawer**: Persistent hidden navigation bar (`.hidden-bar`) providing instant access to agency overview, working hours, and direct contact details from any page.
- **Showcase Portfolios**: 5 distinct portfolio layouts (Classic, 2-Column, 3-Column, 4-Column Grid, and Single Case Study Detail).
- **Comprehensive Blog System**: Standard Blog, Classic Layout, Sidebar View with Search & Categories, and Single Article Read with Comment Form.
- **Interactive Components**:
  - Parallax background scrolling (`parallax.min.js`, `jquery.paroller.min.js`)
  - Smooth entrance animations on scroll (`wow.js` & `animate.css`)
  - Owl Carousel touch sliders (`owl.js`)
  - Fancybox modal lightboxes for media previews (`jquery.fancybox.js`)
  - Circular animated skill counters (`knob.js`)
- **Interactive Contact Features**: Direct `tel:` and `mailto:` links, embedded Google Maps iframe, and responsive contact / newsletter forms.

---

## 🏢 Brand Identity & Contact Details

All files across the HyperFrame template use cohesive, alternative business details:

| Detail | Information |
| :--- | :--- |
| **Brand Name** | **HyperFrame** |
| **Tagline** | Creative Agency & Digital Studio |
| **Physical Address** | 450 Lexington Avenue, Suite 1400, New York, NY 10017, USA |
| **Toll-Free / Office Phone** | [+1 (800) 497-3726](tel:+18004973726) |
| **Direct / Inquiries Phone** | [+1 (212) 555-0144](tel:+12125550144) |
| **General Inquiries** | [hello@hyperframe.com](mailto:hello@hyperframe.com) |
| **Business / Partnerships** | [info@hyperframe.com](mailto:info@hyperframe.com) |
| **Client Support** | [support@hyperframe.com](mailto:support@hyperframe.com) |
| **Office Hours** | Monday – Friday: 09:00 AM – 06:00 PM<br>Saturday – Sunday: Closed |

---

## 📄 Page Directory

| File Name | Description | Key Modules |
| :--- | :--- | :--- |
| [`index.html`](index.html) | **Homepage 01** | Hero slider, agency overview, service boxes, portfolio teaser, testimonials, recent news, newsletter. |
| [`index-2.html`](index-2.html) | **Homepage 02** | Modern SaaS / Agency alternative layout with interactive service cards, client metrics, and extended footer. |
| [`about.html`](about.html) | **About Us** | Agency journey, video reel modal, strategic approach, client brand slider, milestone counters. |
| [`team.html`](team.html) | **Our Team** | Executive leadership, designers, developers grid with social media links. |
| [`service.html`](service.html) | **Services Overview** | Grid of core capabilities: Brand Design, Web Development, UI/UX, Strategy. |
| [`service-detail.html`](service-detail.html) | **Service Detail** | In-depth service breakdown, process timeline, interactive FAQ accordion, call-to-action banner. |
| [`portfolio.html`](portfolio.html) | **Portfolio 01** | Filterable gallery grid showcasing client case studies. |
| [`portfolio-2.html`](portfolio-2.html) | **Portfolio 02** | 2-column wide portfolio showcase. |
| [`portfolio-3.html`](portfolio-3.html) | **Portfolio 03** | 3-column balanced portfolio grid. |
| [`portfolio-4.html`](portfolio-4.html) | **Portfolio 04** | 4-column high-density creative showcase. |
| [`portfolio-single.html`](portfolio-single.html) | **Portfolio Detail** | Single case study page with project brief, challenges, imagery gallery, and results. |
| [`blog.html`](blog.html) | **Blog Grid** | Multi-card magazine layout of agency news and insights. |
| [`blog-classic.html`](blog-classic.html) | **Blog Classic** | Traditional vertical feed layout with full post summaries. |
| [`blog-sidebar.html`](blog-sidebar.html) | **Blog Sidebar** | Editorial layout with right sidebar containing search, category filters, and popular tags. |
| [`blog-single.html`](blog-single.html) | **Blog Single** | Detailed article view with rich typography, blockquotes, author biography, and comment submission. |
| [`news-detail.html`](news-detail.html) | **News Detail** | Press releases and company announcements. |
| [`contact.html`](contact.html) | **Contact Us** | Direct phone/email cards, interactive contact form, and Google Maps location embed. |
| [`not-found.html`](not-found.html) | **404 Page** | Custom branded page for missing routes with redirect navigation. |

---

## 📁 Project Structure

```text
HyperFrame/
├── index.html                   # Main landing page (Homepage 01)
├── index-2.html                 # Alternative landing page (Homepage 02)
├── about.html                   # About the agency
├── team.html                    # Team profiles
├── service.html                 # Service offerings
├── service-detail.html          # Individual service deep-dive
├── portfolio.html               # Portfolio layout 1
├── portfolio-2.html             # Portfolio layout 2 (2 Columns)
├── portfolio-3.html             # Portfolio layout 3 (3 Columns)
├── portfolio-4.html             # Portfolio layout 4 (4 Columns)
├── portfolio-single.html        # Individual project case study
├── blog.html                    # Blog archive
├── blog-classic.html            # Classic blog stream
├── blog-sidebar.html            # Blog with interactive sidebar
├── blog-single.html             # Full article reading page
├── news-detail.html             # Company news details
├── contact.html                 # Contact page with map & form
├── not-found.html               # Custom 404 page
├── README.md                    # Project documentation
│
├── css/                         # Stylesheets
│   ├── bootstrap.css            # Bootstrap 4 grid and utility classes
│   ├── main.css                 # Primary custom template stylesheet
│   ├── responsive.css           # Mobile and tablet media queries
│   ├── animate.css              # CSS animation library
│   ├── custom-animate.css       # Custom keyframe animations
│   ├── font-awesome.css         # FontAwesome icon font styles
│   ├── flaticon.css             # Flaticon vector icon styles
│   ├── owl.css                  # Owl Carousel slider styling
│   ├── jquery.fancybox.min.css  # Lightbox viewer styling
│   ├── jquery-ui.css            # jQuery UI widgets
│   └── jquery.mCustomScrollbar.min.css # Custom scrollbar styling
│
├── js/                          # JavaScript libraries and custom scripts
│   ├── jquery.js                # Core jQuery library
│   ├── popper.min.js            # Popper.js tooltip & popover positioning
│   ├── bootstrap.min.js         # Bootstrap bundle script
│   ├── script.js                # Main template initialization script
│   ├── owl.js                   # Owl Carousel slider plugin
│   ├── wow.js                   # WOW.js scroll trigger animation
│   ├── appear.js                # Element viewport detection
│   ├── jquery.fancybox.js       # Lightbox modal viewer
│   ├── jquery.paroller.min.js   # Parallax scrolling library
│   ├── parallax.min.js          # Mouse parallax effect
│   ├── knob.js                  # Animated circular progress gauges
│   ├── jquery-ui.js             # jQuery UI components
│   └── jquery.mCustomScrollbar.concat.min.js # Smooth scrollbars
│
├── images/                      # Graphics, icons, and backgrounds
│   ├── logo.png                 # Main brand logo (Dark version for light headers)
│   ├── logo-3.png               # Sidebar drawer brand logo
│   ├── footer-logo.png          # Footer brand logo (Light version for dark footers)
│   ├── favicon.png              # Browser tab icon
│   ├── background/              # Hero, section, and pattern backgrounds
│   ├── resource/                # Content photos, case studies, team portraits
│   └── icons/                   # UI glyphs, arrows, and vector badges
│
└── fonts/                       # Embedded web fonts and icon font files
```

---

## 🛠 Technologies & Libraries

- **Markup & Layout**: [HTML5](https://html.spec.whatwg.org/), [Bootstrap 4.x](https://getbootstrap.com/)
- **Styling**: [CSS3](https://www.w3.org/Style/CSS/), Flexbox, Grid
- **Fonts**: [Google Fonts (Poppins, DM Sans, Roboto)](https://fonts.google.com/)
- **Icons**: [FontAwesome 5](https://fontawesome.com/), [Flaticon](https://www.flaticon.com/)
- **Core Scripting**: [jQuery v3.x](https://jquery.com/)
- **Animation**: [WOW.js](https://wowjs.uk/) & [Animate.css](https://animate.style/)
- **Sliders & Lightbox**: [Owl Carousel 2](https://owlcarousel2.github.io/OwlCarousel2/), [Fancybox 3](https://fancyapps.com/fancybox/3/)

---

## 💻 Getting Started

### Prerequisites

No build tools, compiler, or database are required. HyperFrame is a pure static website and runs directly in any modern browser.

### Running Locally

#### Option 1: Direct File Open
Simply double-click [`index.html`](index.html) to open the site directly in your default browser.

#### Option 2: Using VS Code Live Server
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension.
3. Right-click `index.html` and choose **"Open with Live Server"**.

#### Option 3: Python Built-in Server
If Python is installed on your system, launch a lightweight HTTP server:

```bash
# Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000` in your browser.

#### Option 4: Node.js `npx serve`
```bash
npx serve .
```

#### Option 5: PowerShell Local Test
On Windows, you can quickly preview the site in your default browser:
```powershell
Start-Process "index.html"
```

---

## 🎨 Customization Guide

### Updating Brand & Logo
- **Logo Files**: High-resolution PNG logo files are located in `images/`:
  - `images/logo.png` (Main navigation)
  - `images/logo-3.png` (Off-canvas slide drawer)
  - `images/footer-logo.png` (Dark footer)
  - `images/favicon.png` (Browser favicon)
- **Alt & Title Text**: Ensure image tags reflect your brand name:
  ```html
  <div class="logo">
    <a href="index.html">
      <img src="images/logo.png" alt="HyperFrame" title="HyperFrame" />
    </a>
  </div>
  ```

### Updating Contact Details
To modify contact details globally, update the corresponding sections across the HTML pages:
- **Hidden Drawer (`.hidden-bar`)**:
  ```html
  <ul class="list-style-one">
      <li><span class="icon fas fa-map-marker"></span>450 Lexington Avenue, Suite 1400, New York, NY 10017, USA</li>
      <li><span class="icon fas fa-phone"></span><a href="tel:+18004973726">+1 (800) 497-3726</a></li>
      <li><span class="icon fas fa-envelope"></span><a href="mailto:hello@hyperframe.com">hello@hyperframe.com</a></li>
      <li><span class="icon fas fa-clock"></span>Mon - Fri: 09:00 AM - 06:00 PM | Sun: Closed</li>
  </ul>
  ```
- **Footer Section (`.main-footer`)**:
  ```html
  <div class="location">450 Lexington Avenue, Suite 1400, <br> New York, NY 10017, USA</div>
  <a class="email" href="mailto:hello@hyperframe.com">hello@hyperframe.com</a>
  ```
- **Contact Page Cards (`contact.html`)**:
  Update phone links and email references inside the `.info-boxed` containers.

### Color Palette

The site's visual theme can be customized in [`css/main.css`](css/main.css):

| Color Name | Hex Code | Purpose |
| :--- | :--- | :--- |
| **Accent Pink** | `#ff799e` | Brand highlight, links, buttons, active states, icons |
| **Deep Navy / Slate** | `#15192b` | Header overlays, dark cards, footer backgrounds |
| **Charcoal Dark** | `#242425` | Body headings, dark button states, solid elements |
| **Body Text Gray** | `#777777` | Paragraph text and descriptions |
| **Pure White** | `#ffffff` | Backgrounds, contrast typography |

---

## 🌐 Browser Compatibility

HyperFrame is fully tested and compatible with:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Microsoft Edge (latest)
- Apple Safari (latest)
- Mobile Browsers (iOS Safari, Android Chrome, Samsung Internet)

---

## 📜 License

This project is licensed for commercial and personal website deployments. Please refer to individual asset licenses for third-party libraries (Bootstrap, jQuery, Owl Carousel, Fancybox).
