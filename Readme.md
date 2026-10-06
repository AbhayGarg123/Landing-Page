# Notion-Inspired Workspace Landing Page

A pixel-perfect, highly responsive landing page inspired by modern workspace tools. It features a centered product preview dashboard, floating contextual widgets, and custom local asset integration.

## 🛠️ Technology Used

- **HTML5** – Structured and semantic frontend markup.
- **Tailwind CSS (v4 CLI)** – Utility-first CSS framework used for fast, modern component styling.
- **Node.js & NPM** – Dependency management and local build pipeline automation.
- **Google Fonts (Inter)** – Clean, professional geometric sans-serif typography.

## 🚀 Key Features

### 💻 Responsive Grid Layout
- Centers the core workspace dashboard flawlessly.
- Automatically repositions side-widgets from side-by-side on desktop to stacked on mobile devices.

### 🎨 Minimalist Aesthetic
- Soft off-white background tint (`#FCF9F6`) designed to reduce eye strain.
- Clean typography scales with pixel-perfect precision across all viewpoints.

### 📁 Independent Asset Architecture
- Complete offline capabilities using localized images instead of external URLs.
- Fully dynamic layout that doesn't rely on third-party CDNs.

## 📁 Project Structure

```text
├── girl1.png              # Team member avatar 1
├── user2.png              # Team member avatar 2
├── user3.png              # Team member avatar 3
├── report.png             # Core analytical dashboard illustration
├── index.html             # Main index document linked with local assets
├── output.css             # Compiled deployment-ready Tailwind stylesheet
├── package.json           # Project scripts and local dependencies
├── package-lock.json      # Locked configuration manifest
├── style.css              # Custom base layer styles
└── Readme.md              # Project documentation
```

## 💻 Local Setup & Installation

1. **Install Dependencies**  
   Ensure Node.js is installed on your machine, then execute:
   ```bash
   npm install
   ```

2. **Compile Tailwind Utilities**  
   Run the watcher command to automatically process utility classes into your output file:
   ```bash
   npx tailwindcss -i ./style.css -o ./output.css --watch
   ```

3. **Launch the Site**  
   Open `index.html` directly in your web browser or preview it using the VS Code **Live Server** extension.
