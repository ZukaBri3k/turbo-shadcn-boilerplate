# Turbo Monorepo Boilerplate

A modern, scalable monorepo boilerplate built with Turborepo that provides reusable UI components from **Shadcn-ui** and styling packages for rapid application development.

## 🚀 Features

- **Turborepo**: High-performance build system optimized for JavaScript and TypeScript codebases
- **Shared TailwindCSS Package**: Pre-configured Tailwind CSS setup that can be easily integrated into any app
- **Shared UI Package**: Collection of reusable components built with shadcn/ui
- **Type Safety**: Full TypeScript support across all packages
- **Development Experience**: Hot reload, fast builds, and optimized caching

## 📦 Package Structure

```
packages/
├── tailwindcss/          # Shared TailwindCSS configuration
│   ├── tailwind.config.js
│   ├── globals.css
│   └── package.json
├── ui/                   # Shared UI components (shadcn/ui)
│   └── src/
│       ├── components/
│       ├── lib/
│       └── package.json
apps/                
└── web/                # Example web application
```

## 🎨 Packages

### `@repo/tailwindcss`

A pre-configured TailwindCSS package that includes:
- Base Tailwind configuration
- Global CSS styles
- Design system tokens
- Easy integration with any application

### `@repo/ui`

A comprehensive UI component library featuring:
- shadcn/ui components
- Consistent design system
- Accessible components
- Tree-shakeable imports
- TypeScript definitions

## 🛠️ Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended) or npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ZukaBri3k/turbo-shadcn-boilerplate.git
cd turbo-shadcn-boilerplate
```

2. Install dependencies:
```bash
pnpm install
```

3. Start development:
```bash
pnpm dev
```

## 🔧 Usage

Every package is documented in its own directory. You can find the documentation in the `README.md` file of each package.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test if it works
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Turborepo](https://turbo.build/) for the amazing monorepo tooling
- [shadcn/ui](https://ui.shadcn.com/) for the beautiful component library
- [TailwindCSS](https://tailwindcss.com/) for the utility-first CSS framework