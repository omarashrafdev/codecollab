# CodeCollab — Frontend

**CodeCollab** is a real-time collaborative coding arena where developers can compete, learn, and spectate competitive programming matches together. This is the **frontend** project built with **Next.js (App Router)** and **TypeScript**.

> 🚀 Collaborative coding meets esports.  
> 💬 Live chat, 🎥 video, 🧠 shared editor, and 🏆 ranked challenges.

---

## 📦 Tech Stack

- **Framework:** [Next.js 15 (App Router)](https://nextjs.org/docs)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Editor:** [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- **Linting & Formatting:** ESLint + Prettier
- **Pre-commit Hooks:** Husky + lint-staged
- **Package Manager:** npm
- **Deployment:** [Vercel](https://vercel.com)

---

## 🧱 Project Structure

```
src/
├── app/                # Next.js App Router layout & routes
│   ├── layout.tsx      # Global layout
│   ├── page.tsx        # Home page
│   └── globals.css     # Global styles (Tailwind + custom)
│
├── components/         # Shared UI components (e.g., Button, Navbar)
├── hooks/              # Custom React hooks
├── styles/             # Tailwind config, custom styles (if needed)
├── utils/              # Utility functions/helpers
```

---

## 🛠️ Setup Instructions

### 1. Clone the Project

```bash
git clone https://github.com/omarashrafdev/codecollab.git
cd codecollab/frontend
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the Dev Server

```bash
npm run dev
```

---

## 🧹 Code Quality: ESLint + Prettier

- ESLint is configured with the latest **Flat Config API**
- Prettier is integrated using `eslint-plugin-prettier` and `eslint-config-prettier`
- Lint files:
  ```bash
  npm run lint
  ```

---

## 🔒 Pre-commit Hook: Husky + Lint-Staged

- Prevent bad code from being committed by auto-fixing with ESLint + Prettier.

---

## 🧠 VSCode Collaboration

**Recommended Extensions:**

- ESLint (`dbaeumer.vscode-eslint`)
- Prettier (`esbenp.prettier-vscode`)

**.vscode/settings.json**

```json
{
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": "always"
  },
  "editor.defaultFormatter": "esbenp.prettier-vscode"
}
```

**.vscode/extensions.json**

```json
{
  "recommendations": ["dbaeumer.vscode-eslint", "esbenp.prettier-vscode"]
}
```

---

## 🧪 Testing (Coming Soon)

We plan to add:

- Unit Tests (with Jest + React Testing Library)
- Component Tests (Playwright/Cypress)

---

## 💡 Contribution Guide

1. Create a branch:  
   `git checkout -b feature/your-feature-name`
2. Make changes and commit:  
   `git commit -m "feat: add your feature"`
3. Push and open a PR!

Please follow the code style enforced by ESLint/Prettier and use components/hooks/utils to keep the codebase clean and reusable.

---

## 📄 License

This project is under the MIT License.

---

Made with ❤️ by the CodeCollab Team
