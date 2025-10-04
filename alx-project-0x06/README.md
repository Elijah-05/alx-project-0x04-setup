# Splash App

Splash App is a **Next.js** application built with **TypeScript** and **Tailwind CSS**.  
It demonstrates modern React development practices such as shared layouts, reusable components, custom error pages, and responsive design.  
This setup provides a clean foundation for extending the app with advanced features—like AI-powered tools—while maintaining scalability and maintainability.

---

## 📂 Project Structure

├── components/
│   ├── common/
│   │   └── Button.tsx # Reusable button component
│   └── layouts/
│       ├── Header.tsx # Global header
│       ├── Footer.tsx # Global footer
│       └── Layout.tsx # Shared page layout
├── interfaces/
│    └── index.ts # TypeScript interfaces
├── pages/
│    ├── index.tsx # Home page
│    └── 404.tsx # Custom error page
├── styles/
│    └── global.css # Global Tailwind styles
│   ├── .gitignore
│   ├── eslint.config.mjs
│   ├── next-env.d.ts
│   ├── next.config.ts
│   ├── package.json
│   ├── postcss.config.mjs
│   ├── README.md
│   ├── tsconfig.json

## 🚀 Getting Started

### Prerequisites
- **Node.js** ≥ 18
- **npm** or **yarn** package manager

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd alx-project-0x03

1. **Install dependencies**

   ```
   npm run dev  # or yarn install
   ```  

2. **Run the development server**

   ```
   npm run dev
   ```

   The app will be available at [http://localhost:3000](http://localhost:3000).

3. **Build for production**

   ```
   npm run build
   ```

4. **Start the production server**

   ```
   npm start
   ```