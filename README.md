# 🧑‍💻 Benjiilee.dev — Developer Portfolio

This is my personal developer portfolio built with [Next.js](https://nextjs.org/) App Router, TypeScript, and Tailwind CSS. It showcases projects, blogs, and information about me as a full-stack freelance developer.

---

## ⚙️ Tech Stack

- **Framework**: [Next.js 14+](https://nextjs.org/) (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Linting/Formatting**: ESLint + Prettier
- **Deployment**: [Vercel](https://vercel.com/)
- **Content**: Markdown/MDX (optional), CMS-ready

---

## 📁 Project Structure

src/
├── app/ # App Router structure (pages and layouts)
│ ├── layout.tsx # Root layout (header/footer etc.)
│ ├── page.tsx # Home page
│ ├── blog/ # Blog section (MDX or CMS-backed)
│ ├── about/ # About me page
│ └── projects/ # Portfolio projects
│
├── components/ # Reusable UI components
│ ├── layout/ # Structural components (Navbar, Footer)
│ └── ui/ # Atomic design elements (Button, Card, etc.)
│
├── lib/ # Utility functions and server/client helpers
│
├── styles/ # Global styles and Tailwind config overrides
│
├── data/ # Static data files (e.g., JSON project list)
│
├── content/ # Markdown/MDX blog posts (if using file-based content)
│
├── hooks/ # Custom React hooks
│
├── types/ # TypeScript types and interfaces
│
└── config/ # Global config (site metadata, constants, SEO)


---

## 🚀 Getting Started

```bash
# Install dependencies
npm install

# Start the dev server
npm run dev


Then visit: http://localhost:3000
📦 Deployment

This app is ready for deployment on Vercel. Push to GitHub and import your repo into Vercel for instant CI/CD.
✍️ Author

Benjamin Lee
https://benjiilee.dev
Full-stack Dev | Microservices | Open Source