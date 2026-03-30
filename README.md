#  Food Ordering Site--- Online

A full-stack food ordering platform built with React, TypeScript, and Supabase.

## Project Info

**Project Name:** Food Ordering Project

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or bun package manager
- Supabase account and project setup

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd "food ordering"
```

2. Install dependencies:
```bash
npm install
# or
bun install
```

3. Set up environment variables:
   - Create a `.env` file in the root directory
   - Add your Supabase credentials:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### Running the Project

#### Development Mode
```bash
npm run dev
```
This starts the Vite development server. The application will be available at `http://localhost:5173`

#### Build for Production
```bash
npm run build
```

#### Preview Production Build
```bash
npm run preview
```

### Database Setup

The project uses Supabase with pre-configured migrations:
- Run migrations automatically through Supabase CLI or dashboard
- Sample data can be inserted using `INSERT_SAMPLE_FOODS.sql`
- Admin setup: See `ADMIN_SETUP.md`

## Project Structure

- `src/pages/` - Main application pages (Dashboard, Products, Cart, Admin, etc.)
- `src/components/` - Reusable UI components
- `src/contexts/` - React contexts (CartContext, etc.)
- `src/integrations/supabase/` - Supabase configuration
- `supabase/migrations/` - Database migrations
- `supabase/functions/` - Edge functions (notifications, sync, etc.)

## Features

- User authentication and authorization
- Product browsing and search
- Shopping cart management
- Order placement and tracking
- Admin dashboard
- Customer reviews and ratings
- Wishlist functionality
- Customer segmentation analytics

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Technologies Used

- **Frontend:** React, TypeScript, Vite, Tailwind CSS
- **Backend:** Supabase (PostgreSQL, Edge Functions)
- **Authentication:** Supabase Auth
- **State Management:** React Context API


