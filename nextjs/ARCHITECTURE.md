# NextGen Agency Portal - Architecture Overview

## Overview
The NextGen Agency Portal is a modern web application built with Next.js, designed to manage agency projects and client interactions.

## Tech Stack
- **Framework:** [Next.js](https://nextjs.org/) (App Router)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** Vanilla CSS
- **Deployment:** Vercel (recommended)

## Directory Structure
- `src/app`: Contains the application routes and layouts (App Router).
- `src/components`: (To be created) Shared UI components.
- `src/styles`: (To be created) Global and component-specific styles.
- `public`: Static assets like images and fonts.

## Design Principles
1. **Performance First:** Minimize bundle size and utilize Next.js server components where possible.
2. **Type Safety:** Ensure all data structures and component props are strictly typed.
3. **Clean Code:** Follow ESLint and Prettier configurations to maintain high code quality.
4. **Accessible UI:** Aim for high accessibility standards (WCAG).

## Key Components
- `RootLayout`: The top-level layout that wraps all pages, providing global styles and fonts.
- `Home`: The landing page of the portal.
