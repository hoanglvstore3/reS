<p align="center">
  <a href="http://var-meta.com/" target="blank"><img src="https://www.var-meta.com/images/logo_light.svg" width="200" alt="Var meta Logo" /></a>
</p>

# 🚀 Rabid Admin Frontend

> A modern and powerful admin interface providing an optimal management experience for the Rabid system with intuitive design and advanced features.

## 🛠️ Core Technologies

- **Frontend**: Next.js + React + TypeScript
- **Styling**: TailwindCSS with Radix UI components
- **Data Management**: Apollo Client + TanStack Query + Zustand
- **Form Handling**: React Hook Form with Zod validation

## 📦 Installation

### Prerequisites
- Node.js (v18+)
- pnpm package manager

### Setup

1. **Clone and install dependencies**
```bash
git clone <repository-url>
cd admin-fe
pnpm install
```

2. **Environment configuration**
```bash
# Copy environment template
cp .env.example .env

# Configure your environment variables:
# - API endpoints
# - Authentication providers
# - External service keys
```

## 🚀 Running the Application

### Development Mode

```bash
# Development server (watch mode)
pnpm run dev

# Type checking
pnpm run type-check

# Linting and formatting
pnpm run lint
pnpm run format:check
```

The application will start on [http://localhost:3000](http://localhost:3000).

### Production Mode

```bash
# Build the application
pnpm run build

# Start production server
pnpm run start
```

## 🏁 Getting Started

1. Follow the [Installation](#-installation) steps
2. Run the development server using commands in [Running the Application](#-running-the-application)
3. Open [http://localhost:3000](http://localhost:3000) to view the application
4. Start editing `app/page.tsx` - the page auto-updates as you edit

## 📚 Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## 🌐 Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details
