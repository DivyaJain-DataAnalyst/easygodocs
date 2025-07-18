# EasyGoDocs

**Effortless, elegant, and powerful documentation for your Go projects.**

---

## 🚀 Vision

EasyGoDocs is designed to make documentation as easy and enjoyable as writing code.  
Our mission is to empower teams and open-source communities to create, share, and maintain world-class documentation with minimal friction and maximum clarity.

- **Minimalistic & Modern UI:** Clean, distraction-free, and accessible by default.
- **Go-First, but Flexible:** Built for Go projects, but easily adaptable to any tech stack.
- **Powered by Next.js & MDX:** Enjoy fast, interactive docs with the flexibility of React and Markdown.
- **Community-Driven:** Contributions are easy, transparent, and celebrated.

---

## ✨ Features

- 📄 **MDX & Markdown Support:** Write docs in Markdown, extend with React components.
- 🧩 **Component-Based:** Modular, reusable UI for docs, guides, and API references.
- 🗂 **Structured Navigation:** Sidebar, table of contents, and search for easy exploration.
- 🌗 **Accessible & Responsive:** Looks great on all devices, with a focus on accessibility.
- ⚡ **Instant Preview:** Hot reload and instant updates during development.
- 🔒 **Ready for Auth:** Example flows for protected docs and user guides.
- 🛠 **Easy Customization:** Theming, branding, and structure are all developer-friendly.

---

## 🏗️ Project Structure

```
├── public/
│   └── easygodocs-logo.svg         # Project logo (SVG, minimal, Figma-ready)
├── src/
│   ├── app/
│   │   ├── (main)/                 # Main app routes and layouts
│   │   ├── (nav-items)/            # Features, Pricing, About, Solution pages
│   │   ├── all-docs/               # Docs overview page
│   │   ├── contribution-guide/     # Contribution guide (MDX/TSX)
│   │   └── ...                     # Other Next.js app routes
│   ├── components/
│   │   ├── documentation/          # Documentation rendering components
│   │   ├── page-components/        # Hero, footer, about, etc.
│   │   └── ui/                     # Reusable UI (buttons, nav, etc.)
│   ├── db/
│   │   └── ai-introduction-db.json # Example docs data (JSON)
│   │   └── ubuntu-installation.json# Example docs data (JSON)
│   └── lib/                        # Utilities
├── package.json
├── next.config.ts
└── ...
```

---

## 🛠️ Getting Started

1. **Install dependencies:**
   ```bash
   pnpm install
   # or
   npm install
   ```

2. **Run the development server:**
   ```bash
   pnpm dev
   # or
   npm run dev
   ```

3. **Open your browser:**  
   Visit [http://localhost:3000](http://localhost:3000) to see EasyGoDocs in action.

---

## 📝 Contributing

We love contributions!  
To add or update documentation:

1. **Add a new JSON file** in `src/db/` for your doc topic.
2. **Create a matching TSX file** in `src/components/documentation/` to render your JSON data.
3. **Update navigation** if needed (sidebar, TOC).
4. **Open a pull request** with a clear description.

For more details, see the [Contribution Guide](./src/app/contribution-guide/page.tsx).

---

## 💡 Why EasyGoDocs?

- **For maintainers:** Keep docs up-to-date, beautiful, and easy to extend.
- **For contributors:** Add new docs with just a JSON and a TSX file—no complex setup.
- **For users:** Find what you need, fast, on any device.

---

## 📦 Built With

- [Next.js](https://nextjs.org/) (App Router, MDX)
- [Tailwind CSS](https://tailwindcss.com/) (utility-first styling)
- [Lucide Icons](https://lucide.dev/) and [React Icons](https://react-icons.github.io/react-icons/)
- [Framer Motion](https://www.framer.com/motion/) (animations)
- [TypeScript](https://www.typescriptlang.org/)
- [Shadcn](https://ui.shadcn.com/)

---

## 🖼️ Logo

Our logo is a minimal, modern document with a checkmark or arrow—representing clarity, completion, and the Go spirit.  
See `/public/easygodocs-logo.svg` and variants in `/public/`.

---

## 📄 License

[MIT](LICENSE)

---

## 🙌 Acknowledgements

EasyGoDocs is an original solution to the pain point of documentation—designed and built from the ground up to make documentation truly easy, beautiful, and maintainable for everyone.

Special thanks to all contributors and the Go community!

---

**EasyGoDocs — Documentation made easy.**



