
# HTML & CSS Mini-Projects

A collection of frontend web development projects exploring responsive layouts, complex CSS animations, and UI replication using **HTML5** and **CSS3**.

## 📂 Project Structure

This repository is divided into three main categories:

1.  **Animation**: CSS-heavy animations for buttons and loading states.
2.  **Landing Page**: Responsive web page layouts.
3.  **YouTube Clone**: A static replica of the YouTube homepage.

---

## 1. Animation

This directory contains experiments with CSS Keyframes, transitions, and SVG manipulation.

### 🔘 Buttons (`/Animation/button/`)
* **`button-1.html`**: A clean, interactive button with hover and active states.
    * **Tech**: CSS `transition` for smooth box-shadow and transform effects.
* **`skip-button.html`**: A complex "Skip" button animation.
    * **Tech**: 
        * **SVG Animation**: Uses `stroke-dashoffset` to draw a border around the button.
        * **Keyframes**: Sequences multiple animations (`rainbowBG`, `button2`) to transform the icon into a full button.
* **`sample-btn.html`**: A glowing button variant.
    * **Tech**: Uses linear gradients with `filter: blur()` to create a neon glow effect and SVG border drawing.

### ⏳ Loading (`/Animation/loading/`)
* **`loading-1.html`**: A classic circular loading spinner.
    * **Tech**: Infinite CSS rotation using `@keyframes` and `transform: rotate()`.

---

## 2. Landing Page

Responsive layouts demonstrating modern positioning and grid systems.

### 📄 Files
* **`sample_website.html`**: A custom responsive landing page.
    * **Features**: Sticky navigation, flexbox hero section, feature columns with FontAwesome icons, and a responsive grid "ribbon" section.
* **`official.html`**: A product layout style inspired by PureCSS.
    * **Features**: Split-screen splash intro, fixed background styling, and a multi-column grid system (`pure-g`).
* **`fuck.html`**: A draft layout example demonstrating a simple image-text split component using Flexbox.

### 🛠️ Tech Stack
* **Layout**: Flexbox, CSS Grid.
* **Styling**: Media Queries for mobile responsiveness.
* **Icons**: FontAwesome integration.

---

## 3. YouTube Clone

A visual clone of the YouTube desktop interface, focusing on grid alignment and fixed positioning.

### 📄 Key Components
* **`youtube.html`**: The main entry point combining the header, sidebar, and video grid.
* **Styles**:
    * **`header.css`**: Manages the sticky top navigation bar, search input, and user icons.
    * **`side-menu.css`**: Controls the fixed left sidebar navigation.
    * **`video.css`**: Handles the responsive video grid layout using `grid-template-columns`.
* **Responsiveness**:
    * **Tablet**: Grid reduces to 2 columns.
    * **Desktop**: Grid expands to 3 or 4 columns based on width.

---

## 🚀 How to Run

1.  **Clone the repository** (or download the files).
2.  Navigate to the desired project folder.
3.  Open the `.html` file directly in your web browser.

## 📦 Assets
* **Images**: Local thumbnails and avatars are stored in `images/` directories.
* **Icons**: Projects use FontAwesome scripts and local SVG files.