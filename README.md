# 🍽️ SaaS Meal Planning Platform
## 📋 Overview
**Full-stack subscription-based meal planning application with integrated payment processing and personalized dietary management.** Built with Next.js 15 and TypeScript, this SaaS platform enables users to create customized meal plans based on dietary preferences, with secure authentication and recurring subscription billing.

## 📊 Impact
- 🍴 15+ dietary preferences supported (vegetarian, vegan, keto, gluten-free, etc.)
- 💳 Seamless payment integration with Stripe for recurring subscriptions
- 🔐 Secure user onboarding with Clerk authentication
- ⚡ Server-side rendering for optimized page load performance

## ✨Key Features
- **User Authentication:** Secure sign-up, sign-in, and profile management using [Clerk](https://go.clerk.com/TFWZCy5).
- **Responsive UI:** Sleek and modern interface built with TailwindCSS.
- **Payment Processing:** Subscription management and secure payments via Stripe.
- **Type Safety:** Fully typed with TypeScript for improved maintainability.
- **Scalable Architecture:** Built on NextJS 15 with serverless functions and modern best practices.

## 🛠️ Tech Stack
- NextJS 15
- TailwindCSS
- Stripe
- TypeScript
- Clerk
- Prisma
- PostgreSQL

## Setup & Running
**Prerequisites:**
- Node.js 18+
- PostgreSQL database
- Stripe account
- Clerk account
  
## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/yourproject.git
   ```
2. **Navigate into the project directory:**
   ```bash
   cd yourproject
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Configure Environment Variables:**  
   Create a `.env.local` file in the project root and add your required variables (e.g., `STRIPE_SECRET_KEY`, `STRIPE_WEBHOOK_SECRET`, `NEXT_PUBLIC_BASE_URL`, `OPEN_ROUTER_API_KEY`, `CLERK_SECRET_KEY`, `DATABASE`, etc.).
5. **Run the Development Server:**
   ```bash
   npm run dev
   ```

## Usage
- Visit `http://localhost:3000` to view the application.
- Sign up or sign in using Clerk.
- Manage your subscriptions and explore the AI-powered features.
