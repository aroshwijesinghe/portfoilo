# Portfolio - Arosh Nimantha Wijesinghe

A modern, interactive React portfolio showcasing projects, skills, and experience in AI/ML and Full-Stack Development.

## 📋 Project Structure

```
portfolio/
├── public/                 # Static files, favicon, manifest
├── src/
│   ├── components/         # Reusable React components
│   ├── pages/              # Page components
│   ├── styles/             # CSS/SCSS stylesheets
│   ├── assets/
│   │   ├── images/         # Project images, screenshots
│   │   └── icons/          # Icon files
│   ├── data/               # Configuration data (profile, projects, skills)
│   ├── utils/              # Utility functions and helpers
│   ├── App.jsx             # Main App component
│   ├── index.jsx           # React entry point
│   └── index.css            # Global styles
├── .gitignore
├── package.json            # Project dependencies
├── README.md               # This file
└── vite.config.js          # Build configuration (if using Vite)
```

## 🚀 Prerequisites

Before you begin, ensure you have the following installed on your system:

- **Node.js** (v14.0.0 or higher) - [Download](https://nodejs.org/)
- **npm** (v6.0.0 or higher) - Comes with Node.js
- **Git** (optional, for version control) - [Download](https://git-scm.com/)

## 📦 Installation

### Step 1: Navigate to the Project Directory

```bash
cd "path/to/ml project/portfoilo"
```

### Step 2: Install Dependencies

```bash
npm install
```

This command reads `package.json` and installs all required packages.

## 🏃 Running the Portfolio

### Development Mode

To run the portfolio locally with hot reload:

```bash
npm start
```

Or if using Vite:

```bash
npm run dev
```

The portfolio will automatically open in your browser at `http://localhost:3000` (or `http://localhost:5173` for Vite).

### Production Build

To create an optimized production build:

```bash
npm run build
```

This generates a `build/` or `dist/` folder with optimized files ready for deployment.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## 🛠️ Project Setup Guide

### 1. Configure Your Profile
- Edit your profile information in `src/data/profile.js` or directly in the main component
- Update name, email, social links, and bio

### 2. Add Your Projects
- Create project data in `src/data/projects.js`
- Add project images to `src/assets/images/`
- Include descriptions, technologies used, and live links

### 3. Update Skills
- Modify skills list in `src/data/skills.js`
- Add relevant programming languages, frameworks, and tools

### 4. Customize Styling
- Edit global styles in `src/index.css`
- Component-specific styles are in `src/styles/`
- Update colors, fonts, and layout as needed

### 5. Add Your Assets
- Place profile picture in `src/assets/images/`
- Add project screenshots in `src/assets/images/`
- Store icons in `src/assets/icons/`

## 📱 Features

- ✨ Modern, responsive design
- 🎨 Customizable color schemes
- 📊 Skills and expertise showcase
- 🚀 Project portfolio section
- 📧 Contact information
- 🔗 Social media links
- 📱 Mobile-friendly layout

## 🔧 Available Scripts

| Script | Command | Purpose |
|--------|---------|---------|
| Start | `npm start` | Run development server |
| Build | `npm run build` | Create production build |
| Preview | `npm run preview` | Preview production build |
| Lint | `npm run lint` | Check code quality (if configured) |

## 📝 Environment Variables

If your project requires environment variables, create a `.env` file in the root directory:

```
REACT_APP_API_URL=your_api_url
REACT_APP_VERSION=1.0.0
```

## 🌐 Deployment

### Deploy to Vercel (Recommended)
1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com/)
3. Import your GitHub repository
4. Click "Deploy"

### Deploy to Netlify
1. Push your code to GitHub
2. Go to [netlify.com](https://netlify.com/)
3. Connect your repository
4. Click "Deploy site"

### Deploy to GitHub Pages
```bash
npm run build
npm run deploy
```

## 🐛 Troubleshooting

### Issue: `npm install` fails
**Solution:** Delete `node_modules` folder and `package-lock.json`, then run `npm install` again

### Issue: Port 3000 already in use
**Solution:** Use a different port:
```bash
PORT=3001 npm start
```

### Issue: Changes not reflecting
**Solution:** Clear browser cache or do a hard refresh (Ctrl+Shift+R)

## 📚 Useful Resources

- [React Documentation](https://react.dev/)
- [Create React App Docs](https://create-react-app.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [npm Documentation](https://docs.npmjs.com/)
- [Tailwind CSS](https://tailwindcss.com/) (if using Tailwind)

## 📄 License

This project is open source and available under the MIT License.

## 💬 Contact

For questions or suggestions, reach out at:
- Email: aroshnimantha386@gmail.com
- GitHub: [github.com/aroshwijesinghe](https://github.com/aroshwijesinghe)
- LinkedIn: [linkedin.com/in/arosh-wijesinghe](https://www.linkedin.com/in/arosh-wijesinghe-078423341/)

---

**Happy coding!** 🎉
