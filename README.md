# Rabid Admin Frontend

## Core Technologies

- **Next.js 15.2.0** - React framework for production
- **React 19.0.0** - JavaScript library for building user interfaces
- **TypeScript 5** - Typed superset of JavaScript
- **TailwindCSS 3.4.1** - Utility-first CSS framework
- **Apollo Client** - GraphQL client with caching
- **Zustand** - State management library
- **TanStack Query (React Query)** - Data fetching and caching
- **Radix UI** - Low-level UI primitives
- **Biome** - Fast formatter and linter
- **React Hook Form** - Forms with easy validation
- **Zod** - TypeScript-first schema validation

## Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd admin-fe
   ```

2. **Install dependencies**
   ```bash
   pnpm install
   ```

   > **Note:** This project uses `pnpm` as the package manager. Make sure you have pnpm installed globally:
   ```bash
   npm install -g pnpm
   ```

## Configuration

1. **Environment Variables**
   - Copy the example configuration file (if available)
   - Set up your environment variables for API endpoints, authentication, etc.

2. **Node.js Version**
   - Ensure you have Node.js >= 18 installed
   - Check your version: `node --version`

## Development

**Run development server:**
```bash
pnpm dev
```

The application will start on [http://localhost:3000](http://localhost:3000).

**Other development commands:**
```bash
# Type checking
pnpm type-check

# Linting
pnpm lint
pnpm lint:fix

# Formatting
pnpm format:check
pnpm format:fix
```

## Production

**Build for production:**
```bash
pnpm build
```

**Start production server:**
```bash
pnpm start
```

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details
