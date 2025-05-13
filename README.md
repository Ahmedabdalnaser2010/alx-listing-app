# ALX Listing App

## Overview
The **ALX Listing App** is a modern Airbnb clone built with Next.js, TypeScript, TailwindCSS, and ESLint. This project focuses on scaffolding a well-structured, scalable foundation for a property listing application. The initial milestone sets up the folder structure, reusable components, and configurations to ensure a clean and maintainable codebase.

## Project Goals
- Scaffold a production-ready Next.js application with TypeScript and TailwindCSS.
- Implement reusable components (`Card`, `Button`) for modularity.
- Organize assets and constants for easy maintenance.
- Ensure type safety and code quality with TypeScript and ESLint.

## Project Structure

alx-listing-app/
├── components/ # Reusable UI components
│ └── common/ # Shared components (Card, Button, etc.)
│ ├── Card.tsx
│ └── Button.tsx
├── interfaces/ # TypeScript interfaces
│ └── index.ts # (e.g., CardProps, ButtonProps)
├── constants/ # Project constants (API URLs, text labels)
│ └── index.ts
├── public/ # Static assets
│ └── assets/ # Images, SVGs, etc.
├── pages/ # Next.js pages
│ └── index.tsx # Homepage
├── styles/ # Global CSS
│ └── globals.css
├── tailwind.config.js # TailwindCSS configuration
├── tsconfig.json # TypeScript configuration
├── package.json # Project dependencies
└── README.md # Project documentation


## Technologies Used
- **Next.js 13+** (Pages Router)
- **TypeScript** for type safety
- **TailwindCSS** for responsive styling
- **ESLint** for code quality

## Getting Started

### Prerequisites
- Node.js v16+
- npm or yarn
- VS Code (recommended) with TypeScript and TailwindCSS extensions

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/alx-listing-app.git