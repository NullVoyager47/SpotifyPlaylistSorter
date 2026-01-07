# SvelteKit Project Instructions

This is a SvelteKit application with TypeScript, ESLint, and Prettier configured.

## Project Structure

- `/src` - Source code directory
  - `/routes` - Page routes and endpoints
  - `/lib` - Reusable components and utilities
  - `+page.svelte` - Home page component
- `/static` - Static assets
- `svelte.config.js` - SvelteKit configuration
- `vite.config.ts` - Vite build configuration

## Getting Started

1. **Development Server**: Run `npm run dev` to start the development server (typically on http://localhost:5173)
2. **Build**: Run `npm run build` to create a production build
3. **Preview**: Run `npm run preview` to preview the production build locally

## Available Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run format` - Format code with Prettier
- `npm run check` - Run SvelteKit type checks

## Testing

The project is configured with Vitest for unit testing and Playwright for E2E testing.

- `npm run test` - Run unit tests
- `npm run test:ui` - Run tests in UI mode
- `npm run test:e2e` - Run end-to-end tests

## Code Quality

- **ESLint** is configured for code linting
- **Prettier** is configured for code formatting
- **TypeScript** is enabled for type safety
