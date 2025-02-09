# BudgetTracker

A comprehensive budget management application built with TypeScript, Next.js, and PostgreSQL. Track your income, expenses, and investments with an intuitive interface and powerful visualization tools.

## Features

- Category Management for organizing financial data
- Transaction tracking and monitoring
- Monthly and yearly data aggregation with visual charts
- CSV export functionality
- Secure authentication with Clerk
- Responsive and modern UI with Shadcn UI components

## Tech Stack

- TypeScript
- Next.js
- PostgreSQL
- Prisma ORM
- TanStack React Query
- Tailwind CSS
- Recharts
- Clerk Auth
- Zod Validation
- Shadcn UI
- Lucide React

## Prerequisites

- Node.js 18 or higher
- PostgreSQL database
- npm or pnpm package manager

## Local Development Setup

1. Clone the repository:
```bash
git clone https://github.com/Sachita007/Budget_Tracker.git
cd Budget_Tracker
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Create a `.env` file in the root directory with the following variables:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=*****************************
CLERK_SECRET_KEY=*****************************
POSTGRES_PRISMA_URL=*****************************
POSTGRES_URL_NON_POOLING=*****************************
```

4. Set up the database:
```bash
npx prisma generate
npx prisma db push
```

5. Start the development server:
```bash
npm run dev
# or
pnpm dev
```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.
