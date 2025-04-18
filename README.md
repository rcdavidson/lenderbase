# Lenderbase

A modern SaaS application built with Wasp, React, and TypeScript. This project provides a full-stack solution with features like authentication, payment processing, admin dashboard, and more.

## Features

- 🔐 Full-stack Authentication
- 💳 Payment Processing (Stripe & LemonSqueezy)
- 📊 Admin Dashboard
- 📱 Responsive Design
- 📧 Email Verification
- 🔄 Background Jobs
- 📈 Analytics Integration
- 🗄️ PostgreSQL Database
- 🎨 Modern UI with Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- PostgreSQL
- Docker
- Wasp CLI

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rcdavidson/lenderbase.git
   cd lenderbase
   ```

2. Install dependencies:
   ```bash
   cd my-saas-app/app
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.server.example` to `.env.server`
   - Copy `.env.client.example` to `.env.client`
   - Update the environment variables with your values

4. Start the development database:
   ```bash
   wasp db start
   ```

5. Apply database migrations:
   ```bash
   wasp db migrate-dev
   ```

6. Start the development server:
   ```bash
   wasp start
   ```

The application will be available at http://localhost:3000

## Project Structure

- `/my-saas-app/app` - Main application code
  - `/src` - Source code
    - `/client` - Frontend React components
    - `/server` - Backend logic
    - `/shared` - Shared types and utilities
  - `main.wasp` - Wasp configuration file
  - `schema.prisma` - Database schema

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

