# Launchpad - A Minimal Astro Starter

Launchpad is a **fast**, **minimal**, and **SEO-friendly** [Astro](https://astro.build/) starter template designed to streamline your web development process. It comes with pre-configured settings, reusable components, and best practices for performance and accessibility.

## 🚀 Features

- ⚡ **Lightning Fast** – Powered by [Astro](https://astro.build/) for optimal performance
- 📄 **Prebuilt Pages** – Home, About, and other essential pages
- 🎨 **[TailwindCSS](https://tailwindcss.com/) Ready** – Pre-configured for styling
- 🌍 **SEO Optimized** – Meta tags, Open Graph, and Twitter Card setup
- 🔗 **Canonical URLs** – Pre-configured for better indexing
- 🖼️ **Image Optimization** – Astro’s built-in image handling
- 🔧 **Modular Components** – Easily reusable UI elements

## 📦 Installation

To get started with Launchpad, run the following command:

```sh
npm create astro@latest --template nnisarggada/launchpad
```

## 🛠️ Usage

Run the development server:

```sh
npm run dev
```

Build for production:

```sh
npm run build
```

Preview the production build:

```sh
npm run preview
```

## 📂 Project Structure

```
launchpad/
│── src/
│   ├── components/  # Reusable UI components
│   ├── layouts/     # Page layouts
│   ├── pages/       # Default pages
│   ├── styles/      # Global styles
│   ├── utils.ts     # Global vars/funcs
│── public/          # Static assets
│── astro.config.mjs # Astro configuration
│── package.json     # Dependencies
```

## 🔧 Configuration

### **SEO Metadata**
Modify `metaData` in `src/utils.ts`:

```js
export const metaData = {
  title: "Launchpad | A minimal Astro Starter by Nnisarg Gada",
  description: "Launchpad is a fast, minimal, and SEO-friendly Astro starter template designed for modern web projects.",
  image: "https://nnisarg.in/images/og_image.jpg",
  author: "Nnisarg Gada",
};
```

## 📜 License

This project is open-source and available under the **<license>**.

## 💡 Author

Created by **[Nnisarg Gada](https://nnisarg.in)**. Feel free to reach via [contact@nnisarg.in](mailto:contact@nnisarg.in)!

---

🚀 **Start building with Launchpad today!**

