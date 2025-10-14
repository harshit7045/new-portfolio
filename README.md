# Portfolio Frontend

A modern, responsive portfolio website built with React, TypeScript, and Tailwind CSS.

## 🚀 Features

- **Modern UI/UX**: Built with Radix UI components and Tailwind CSS
- **Responsive Design**: Mobile-first approach with responsive breakpoints
- **TypeScript**: Full type safety and better development experience
- **Performance**: Optimized with Vite for fast builds and development
- **Animations**: Smooth animations with Framer Motion
- **Dark Mode**: Built-in theme switching with next-themes

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS + Radix UI
- **Build Tool**: Vite
- **Routing**: Wouter
- **State Management**: React Query + React Hook Form
- **Validation**: Zod
- **Animations**: Framer Motion
- **Icons**: Lucide React + React Icons

## 📦 Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd newportfolio
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🏗️ Build

To build for production:

```bash
npm run build
```

The build output will be in the `dist/` directory.

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Vercel will automatically detect the Vite configuration and deploy

### Manual Deployment

1. Build the project: `npm run build`
2. Upload the contents of the `dist/` folder to your hosting provider
3. Configure your hosting provider to serve `index.html` for all routes (SPA routing)

## 📁 Project Structure

```
newportfolio/
├── client/                 # Frontend source code
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility functions
│   │   ├── data/          # Static data and content
│   │   ├── App.tsx        # Main app component
│   │   └── main.tsx       # App entry point
│   ├── public/            # Static assets
│   └── index.html         # HTML template
├── attached_assets/        # Additional assets
├── vite.config.ts         # Vite configuration
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
├── vercel.json            # Vercel deployment configuration
└── package.json           # Dependencies and scripts
```

## 🔧 Configuration

### Vite Configuration
The project uses Vite for fast development and optimized builds. Key configurations:
- React plugin for JSX support
- Path aliases for clean imports
- Optimized build output with code splitting

### Tailwind CSS
Custom Tailwind configuration with:
- Typography plugin
- Custom color schemes
- Responsive breakpoints
- Animation utilities

## 📱 Responsive Design

The portfolio is built with a mobile-first approach:
- **Mobile**: Single column layout
- **Tablet**: Two-column grid for projects
- **Desktop**: Three-column grid with enhanced spacing

## 🎨 Customization

### Colors and Themes
Update the color scheme in `tailwind.config.ts` and `src/index.css`

### Content
Modify the content in the `src/data/` directory

### Components
Customize UI components in the `src/components/` directory

## 🚀 Performance

- **Code Splitting**: Automatic chunk splitting for better loading
- **Tree Shaking**: Unused code is automatically removed
- **Optimized Assets**: Images and fonts are optimized during build
- **Lazy Loading**: Components are loaded on demand

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

If you have any questions or need help, feel free to open an issue or reach out!
