# ☕ Ali7usse1n Coffee - Luxury Coffee Shop Landing Page

A sophisticated, responsive landing page for a luxury coffee shop built with React, TypeScript, and Tailwind CSS.

## 🌟 Features

- **Luxury Minimalism Design** - Dark sophisticated theme with warm gold accents
- **Fully Responsive** - Mobile, tablet, and desktop optimized
- **Bilingual Support** - Arabic and English content ready
- **Single Page Application** - Fast, smooth experience without page reloads
- **Accessible Components** - Built with Radix UI for WCAG compliance
- **Custom Theme System** - Easy theme switching (dark/light mode ready)
- **Modern Tech Stack** - React 19, TypeScript, Vite, Tailwind CSS 4

## 🎨 Design System

### Color Palette
- **Primary Accent**: Warm Gold (oklch(0.55 0.15 45))
- **Background**: Deep Charcoal (oklch(0.1 0.01 30))
- **Foreground**: Cream (oklch(0.95 0.01 0))
- **Card**: Slightly Lighter Charcoal (oklch(0.15 0.02 30))

### Typography
- **Headings**: Playfair Display (font-weight: 600-800)
- **Body**: Lora (font-weight: 400-600)

## 📦 Tech Stack

- **Framework**: React 19.2.1
- **Language**: TypeScript 5.6.3
- **Styling**: Tailwind CSS 4.1.14
- **UI Components**: Radix UI (25+ components)
- **Build Tool**: Vite 7.1.7
- **Routing**: Wouter 3.3.5
- **Animation**: Framer Motion 12.23.22
- **Package Manager**: pnpm 10.4.1

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- pnpm 10+

### Installation

```bash
# Clone the repository
git clone https://github.com/ali7usse1nn/ali7usse1nn.git
cd ali7usse1nn

# Install dependencies
pnpm install

# Start development server
pnpm dev
```

The site will be available at `http://localhost:5173`

### Build for Production

```bash
# Build the project
pnpm build

# Preview production build locally
pnpm preview

# Start production server
npm run start
```

## 📁 Project Structure

```
├── App.tsx              # Main app component with routing
├── Home.tsx             # Landing page component
├── index.html           # HTML entry point
├── index.css            # Global styles and theme configuration
├── package.json         # Dependencies and scripts
└── src/
    ├── components/      # Reusable UI components
    ├── pages/           # Page components
    ├── contexts/        # React contexts (Theme, etc.)
    └── main.tsx         # React DOM render entry
```

## 🌐 Deployment

### GitHub Pages
This project is configured for automatic deployment to GitHub Pages via GitHub Actions.

- **Live Site**: https://ali7usse1nn.github.io/ali7usse1n-coffee
- **Deployment**: Automatic on push to `main` branch
- **Workflow**: `.github/workflows/deploy.yml`

### Manual Deployment
```bash
# Build and deploy
pnpm build
# The `dist` folder is ready for deployment
```

## 📋 Available Scripts

| Script | Description |
|--------|-------------|
| `pnpm dev` | Start development server with hot reload |
| `pnpm build` | Build for production (Vite + Node server) |
| `pnpm preview` | Preview production build locally |
| `pnpm start` | Run production server (NODE_ENV=production) |
| `pnpm check` | Type-check TypeScript without emitting |
| `pnpm format` | Format code with Prettier |

## 🎯 Features Showcase

### Landing Page (`Home.tsx`)
- Coffee shop branding with custom SVG coffee cup logo
- Daily offer card with product image and pricing
- Bilingual navigation (Arabic/English)
- Mobile-friendly hamburger menu
- PDF menu download functionality
- Elegant animations and transitions

### Responsive Design
- **Mobile**: Optimized for small screens with touch-friendly buttons
- **Tablet**: Enhanced layout for medium screens
- **Desktop**: Full-featured layout with optimal spacing and typography

### Dark Theme
- Sophisticated dark background with subtle gradients
- Gold accent colors for luxury feel
- Optimized for reduced eye strain
- Consistent color scheme across all components

## 🔧 Configuration

### Environment Variables
Create a `.env` file for optional configuration:
```env
VITE_ANALYTICS_ENDPOINT=your_analytics_endpoint
VITE_ANALYTICS_WEBSITE_ID=your_website_id
```

### Theme Customization
Edit `index.css` to customize colors:
```css
:root {
  --primary: oklch(0.55 0.15 45); /* Modify gold accent */
  --background: oklch(0.1 0.01 30); /* Modify background */
  --foreground: oklch(0.95 0.01 0); /* Modify text color */
}
```

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

**Ali7usse1n Coffee Shop**
- Phone: +966 50 123 4567
- Email: contact@ali7usse1n.coffee
- Website: https://ali7usse1nn.github.io/ali7usse1n-coffee

---

**Created with ☕ by Ali7usse1nn**
