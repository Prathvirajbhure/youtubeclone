---

# 📺 YouTube Homepage Clone (UI/UX)

A pixel-perfect recreation of the YouTube Homepage interface. This project focuses on high-fidelity frontend development, utilizing modern CSS techniques to build a responsive, modular, and scalable user interface.

---

## 🎨 Design Overview

The goal of this project was to master complex web layouts by dissecting one of the most recognizable interfaces in the world. It replicates the core user experience, from the fixed navigation headers to the fluid video discovery grid.

### **Core Components:**

* **🛠️ Modular Header:** Includes a functional search bar layout, voice search integration, and utility icons (Upload, Notifications, Profile).
* **📂 Collapsible Sidebar:** A vertical navigation system that organizes user subscriptions and library shortcuts.
* **🖼️ Dynamic Video Grid:** Built with **CSS Grid** to handle multiple aspect ratios and metadata overlays (Duration, Channel Branding).
* **📱 Responsive Fluidity:** The interface adjusts seamlessly across different viewport widths using relative units and flexible containers.

---

## 🏗️ Architecture & Style Logic

Unlike basic clones, this project uses a **Modular CSS Strategy**. Styles are broken down by component to ensure the code is maintainable and easy to debug.

```text
youtube-clone/
├── index.html          # Semantic HTML5 Structure
├── styles/             # Modular Stylesheets
│   ├── general.css     # Global resets and typography (Roboto)
│   ├── header.css      # Navigation & Search functionality styles
│   ├── video.css       # Video grid & thumbnail card logic
│   └── sidebar.css     # Sidebar layout & hover states
├── icons/              # Scalable Vector Graphics (SVG)
└── thumbnails/         # Image assets for the video feed

```

---

## 🛠️ Technical Implementation

* **CSS Grid:** Utilized for the main video feed to ensure perfectly aligned columns that adapt to screen size.
* **Flexbox:** Used within the Header and Sidebar for precise alignment of icons and text.
* **Positioning:** Implemented `fixed` and `sticky` positioning to replicate YouTube's top-bar and sidebar behavior during scrolling.
* **Hover Effects:** Interactive states on thumbnails and buttons to mimic the native YouTube desktop experience.

---

## 🚀 Getting Started

### 1. Clone the Interface

```bash
git clone https://github.com/Prathvirajbhure/youtubeclone.git
cd youtubeclone

```

### 2. View in Browser

No build tools or compilers required. Simply open the `index.html` file in any modern browser (Chrome, Firefox, or Edge recommended for best CSS Grid rendering).

---

## 🔮 Roadmap

* [ ] **Dark Mode:** Implement CSS Variables to toggle between light and dark themes.
* [ ] **Search Logic:** Add JavaScript to filter video titles based on search input.
* [ ] **Video Player Page:** Build a dedicated `watch.html` with a sidebar of recommended videos.
* [ ] **Skeleton Loading:** Add CSS animations to simulate content loading states.

---

## ⚠️ Disclaimer

This project is built strictly for **educational purposes** to demonstrate frontend design skills. All design rights, logos, and trademarks belong to **YouTube/Google**.

---

## ⭐ Support

If this UI clone helped you understand Flexbox or Grid better, please consider giving the repo a **Star**!

---



<img width="1251" alt="Screenshot 2025-01-13 at 3 15 03 PM" src="https://github.com/user-attachments/assets/103f8697-e63d-4e2f-8b19-f2baf7e40158" />
