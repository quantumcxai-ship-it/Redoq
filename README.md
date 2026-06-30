# Redoq

Redoq is a premium, high-performance static landing page engineered for next-generation SaaS platforms and intelligent cloud architectures. It features immersive 3D WebGL graphics, kinetic typography, and fluid responsive layouts.

Designed as a modern, minimalist marketing showcase, this project highlights three key proprietary platforms:
1. **Kuick Studio** — A visual drag-and-drop web layout and interface builder.
2. **Kuick Connect** — A secure, fast remote-access and IT administration utility.
3. **Kuick Food** — An AI-driven order-dispatch and kitchen optimization system.

---

## ⚡ Core Features

- **Immersive 3D Visuals**: Powered by `Three.js` (WebGL), featuring a responsive foreground particle cluster that spins and disperses dynamically on scroll.
- **Kinetic Scroll Typography**: A scroll-synchronized word reveal system that plays in forward and reverse as the viewport moves, providing a highly tactile reading experience.
- **Smooth Scroll Integration**: Uses `Lenis` smooth scrolling to guarantee fluid frame transitions across all modern devices and trackpads.
- **SVG Animation Engines**: Embedded vector assets featuring custom keyframe-driven floating, drawing, and pulse animations.
- **Full Mobile Responsiveness**: Designed using a responsive font-scaling system (Sarabun) and layout overrides, preventing any text or element clipping on small viewports.
- **Production-Ready SEO**:
  - Highly descriptive indexing titles and metadata.
  - Complete OpenGraph and Twitter card previews for social sharing.
  - Embedded `JSON-LD` structured organization schema for search console optimization.

---

## 🛠️ Technology Stack

- **Graphics**: WebGL via [Three.js](https://threejs.org/)
- **Scroller**: [Lenis](https://lenis.darkroom.engineering/) (Smooth Scroll)
- **Typography**: Sarabun (Google Fonts)
- **Styling**: Modern CSS3 grid and flex systems
- **Structure**: Semantic HTML5 markup

---

## 🚀 Local Development

To run this project locally, simply clone the repository and serve the files.

### Option 1: Serve via Dev Server (Recommended)
You can run it with any node-based development server like `lite-server`, `serve`, or `live-server`:
```bash
# Example using npx (requires Node.js)
npx serve .
```

### Option 2: Run with Yarn/NPM (Vite Starter)
If deploying via npm, install the dev dependencies and run the server:
```bash
yarn install
yarn dev
```

---

## 🌐 Production Deployment

This project is fully optimized for static hosting platforms like **Vercel**, **Netlify**, or **GitHub Pages**.

### Deploy to Vercel
1. Connect your GitHub account to [Vercel](https://vercel.com).
2. Click **Import** on the `Redoq` repository.
3. Vercel will automatically detect the static project files and deploy it instantly.
