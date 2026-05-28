# ☀️ Aadityasolar

> A modern, full-stack solar energy management platform built with React, TypeScript, and Drizzle ORM.

## 🌟 Features

- **Real-time Energy Monitoring**: Track solar panel performance in real-time
- **Analytics Dashboard**: Comprehensive insights into energy production and consumption
- **User Management**: Secure authentication and multi-user support
- **API Integration**: RESTful API for external integrations
- **Mobile Ready**: Responsive design for desktop, tablet, and mobile devices
- **Database**: Drizzle ORM with type-safe database operations
- **Build Optimization**: Vite for fast development and optimized production builds

## 🏗️ Project Structure

This is a **monorepo** using pnpm workspaces:

```
├── artifacts/          # Built/compiled outputs
├── lib/               # Shared libraries and core packages
│   ├── integrations/  # Third-party integrations
│   └── ...           # Other shared libs
├── scripts/          # Utility scripts and tools
├── package.json      # Workspace root configuration
└── pnpm-workspace.yaml  # Workspace configuration
```

## 📋 Prerequisites

- **Node.js**: v18.0.0 or higher
- **pnpm**: v9.0.0 or higher (package manager)

## 🚀 Getting Started

### Installation

```bash
# Clone the repository
git clone https://github.com/pratu1137/Aadityasolar.git
cd Aadityasolar

# Install dependencies (uses pnpm)
pnpm install
```

### Development

```bash
# Start development server
pnpm dev

# Type checking
pnpm typecheck

# Build for production
pnpm build

# Format code with Prettier
pnpm format

# Lint code
pnpm lint
```

## 📦 Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm install` | Install dependencies (pnpm required) |
| `pnpm dev` | Start development server |
| `pnpm build` | Run typecheck and build all packages |
| `pnpm typecheck` | Check TypeScript types |
| `pnpm typecheck:libs` | Type check only libraries |
| `pnpm format` | Format code with Prettier |
| `pnpm lint` | Lint code (if configured) |

## 🛠️ Tech Stack

### Core Dependencies
- **React**: 19.1.0 - UI library
- **React DOM**: 19.1.0 - React DOM binding
- **TypeScript**: 5.9.3 - Type safety
- **Vite**: 7.3.2 - Build tool and dev server
- **Tailwind CSS**: 4.1.14 - Utility-first CSS framework

### Libraries
- **Drizzle ORM**: 0.45.2 - Type-safe ORM
- **TanStack React Query**: 5.90.21 - Data fetching and caching
- **Framer Motion**: 12.23.24 - Animation library
- **Lucide React**: 0.545.0 - Icon library
- **Wouter**: 3.3.5 - Router library
- **Zod**: 3.25.76 - Schema validation
- **CVA**: 0.7.1 - Component variants

### Development Tools
- **Prettier**: 3.8.3 - Code formatter
- **TSX**: 4.21.0 - TypeScript executor

## 🔒 Security Features

- **Minimum Release Age**: Configured to 1 day (1440 minutes) to prevent supply-chain attacks
- **Trusted Exceptions**: Only Replit and specific trusted packages are exempted
- **Platform Optimization**: Excludes non-Linux platform builds for Replit deployment

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

### Development Workflow

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Make your changes and commit: `git commit -am 'Add new feature'`
3. Push to the branch: `git push origin feature/your-feature`
4. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## 📧 Contact

For questions or feedback, please contact [pratu1137](https://github.com/pratu1137).

## 🙏 Acknowledgments

- Built with ❤️ for the solar energy community
- Powered by [Replit](https://replit.com) infrastructure
- Thanks to all contributors and supporters

---

**Made with ☀️ by Aaditya**
