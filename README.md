
# LAW — Legal Services Website

A modern, responsive landing page for a law firm, built with HTML5 and CSS3. The project focuses on presenting legal services through a clean layout, elegant typography, and a professional visual identity.

<p align="center">
  <img src="img/carousel-1.jpg" alt="LAW Website Preview" width="100%">
</p>

## ✨ Features

- **Modern Hero Section** — An attractive landing section with a background image and call-to-action.
- **Sticky Navigation** — A navigation header that remains visible while scrolling.
- **About Section** — An introduction to the law firm.
- **Practice Areas** — Dedicated cards for different legal specializations.
- **Features Section** — Highlights the firm's key values and advantages.
- **Responsive Layout** — Flexible layouts using CSS Grid and Flexbox.
- **Custom Typography** — Locally hosted Roboto and EB Garamond fonts.
- **Reusable CSS Utilities** — A custom framework for consistent styling and faster development.
- **Font Awesome Icons** — Icons for visual enhancement.

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Structuring website content |
| CSS3 | Styling and visual presentation |
| CSS Grid | Responsive grid layouts |
| Flexbox | Flexible component alignment |
| CSS Variables | Reusable design tokens |
| Font Awesome | Icons |
| Roboto | Primary typography |
| EB Garamond | Heading typography |

## 📁 Project Structure

```text
LAW/
│
├── Fonts/
│   ├── EB_Garamond/
│   └── Roboto/
│
├── css/
│   ├── all.min.css
│   ├── framework.css
│   └── style.css
│
├── img/
│   ├── about.jpg
│   ├── carousel-1.jpg
│   ├── carousel-2.jpg
│   ├── carousel-3.jpg
│   ├── feature.jpg
│   └── ...
│
├── webfonts/
│
├── index.html
├── README.md
└── .gitignore
```

## 🚀 Getting Started

### Prerequisites

You only need:

- A modern web browser.
- A code editor such as Visual Studio Code.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/abdAlazez-99/LAW.git
```

2. Navigate to the project directory:

```bash
cd LAW
```

3. Open the project:

Open `index.html` directly in your browser, or use the Live Server extension in Visual Studio Code.

**No additional dependencies or build tools are required.**

## 🎨 Design System

The project uses a custom color palette defined through CSS custom properties.

| Variable | Value | Description |
|---|---|---|
| `--c-primary` | `#aa9166` | Gold accent |
| `--c-dark` | `#121518` | Dark background |
| `--c-grey` | `#666666` | Grey text |
| `--c-secondary` | `#999999` | Secondary grey |
| `--c-white` | `#ffffff` | White |
| `--c-light` | `#f8f9fa` | Light background |

### Typography

- **Roboto:** Used for general content and body text.
- **EB Garamond:** Used for headings to create an elegant editorial appearance.

## 📱 Responsive Design

The layout uses modern CSS techniques, including:

- CSS Grid for multi-column sections.
- Flexbox for flexible alignment.
- CSS media queries for smaller screens.
- Fluid typography using `clamp()`.
- Flexible containers and spacing utilities.

## 📦 CSS Framework

The project includes a lightweight custom CSS utility framework in `css/framework.css`.

It provides reusable classes for:

- Display and layout.
- Flexbox and Grid.
- Spacing (margin and padding).
- Colors and backgrounds.
- Typography.
- Borders and border radius.
- Positioning.
- Transitions.
- Reusable components.

This approach helps maintain consistent styling and reduces repetitive CSS declarations.

## 🌐 Live Demo

Check out the live website:

[LAW — Live Demo](https://abdAlazez-99.github.io/LAW/)

## 🔧 Customization

You can easily customize the website:

1. Edit `index.html` to modify the content and page structure.
2. Edit `css/style.css` to customize the main design.
3. Edit `css/framework.css` to modify reusable utility classes.
4. Replace images inside the `img/` directory.
5. Update the font files and `@font-face` declarations if needed.
