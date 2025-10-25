# React.js & Next.js Setup Guide

## React.js with Vite

### What is React.js?

React is a JavaScript library for building user interfaces. It lets you create reusable components and efficiently update the UI when data changes.

**Created by:** Facebook (Meta)

**Key Features:**
- Component-based architecture
- Virtual DOM for fast rendering
- Large ecosystem and community
- Used for building single-page applications (SPAs)

### What is Vite?

Vite is a modern build tool that provides extremely fast development server and optimized production builds. It's much faster than traditional bundlers like Webpack.

**Key Benefits:**
- Lightning-fast hot module replacement (HMR)
- Instant server start
- Optimized build output
- Modern and simple configuration

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager
- Basic knowledge of HTML, CSS, and JavaScript

### Installation & Setup

**Check Node.js installation:**
```bash
node --version
npm --version
```

**Create a new React + Vite app:**
```bash
npm create vite@latest my-react-app -- --template react
```

**Navigate to project:**
```bash
cd my-react-app
```

**Install dependencies:**
```bash
npm install
```

**Start development server:**
```bash
npm run dev
```

Your React app will open at `http://localhost:5173`

### Project Structure
```
my-react-app/
  ├── node_modules/
  ├── public/
  ├── src/
  │   ├── App.jsx
  │   ├── App.css
  │   ├── main.jsx
  │   └── index.css
  ├── index.html
  ├── package.json
  └── vite.config.js
```

---

## Next.js

### What is Next.js?

Next.js is a React framework that adds powerful features like server-side rendering, static site generation, and file-based routing. It makes building production-ready React applications easier.

**Created by:** Vercel

**Key Features:**
- Server-side rendering (SSR)
- Static site generation (SSG)
- File-based routing
- API routes
- Built-in optimization
- Image optimization
- TypeScript support

### Prerequisites

- Node.js (v18.17 or higher)
- npm or yarn package manager
- Basic React knowledge

### Installation & Setup

**Create a new Next.js app:**
```bash
npx create-next-app@latest my-nextjs-app
```

During setup, you'll be asked:
- TypeScript? (Yes/No)
- ESLint? (Yes/No)
- Tailwind CSS? (Yes/No)
- `src/` directory? (Yes/No)
- App Router? (Yes/No - recommended)
- Import alias? (Yes/No)

**Navigate to project:**
```bash
cd my-nextjs-app
```

**Start development server:**
```bash
npm run dev
```

Your Next.js app will open at `http://localhost:3000`

### Project Structure
```
my-nextjs-app/
  ├── node_modules/
  ├── public/
  ├── app/
  │   ├── page.js
  │   ├── layout.js
  │   └── globals.css
  ├── package.json
  └── next.config.js
```

---

## Common Commands

### React + Vite Commands
```bash
npm run dev        # Start development server
npm run build      # Build for production
npm run preview    # Preview production build locally
```

### Next.js Commands
```bash
npm run dev        # Start development server
npm run build      # Build for production
npm start          # Start production server
npm run lint       # Run linter
```

---

## When to Use What?

**Use React.js when:**
- Building single-page applications
- You need maximum flexibility
- You want to choose your own routing solution
- Client-side rendering is sufficient

**Use Next.js when:**
- SEO is important
- You need server-side rendering
- You want built-in routing
- Building a full-stack application
- You need optimal performance out of the box

---

## Additional Resources

- **React Documentation:** https://react.dev/
- **Next.js Documentation:** https://nextjs.org/docs
- **Node.js Download:** https://nodejs.org/
