# Iloilo - Modern Financial Management Platform

A professional-grade financial management platform built with cutting-edge technologies to provide a seamless user experience for managing personal and business finances.

## 🚀 Features

- 📊 Real-time financial dashboard
- 💰 Transaction tracking and categorization
- 📈 Advanced data visualization with Recharts
- 🔐 Secure authentication with Supabase
- 📱 Responsive design for all devices
- 🌙 Dark mode support

## 🛠 Tech Stack

- **Framework:** [Next.js 14](https://nextjs.org/) with App Router
- **Database & Auth:** [Supabase](https://supabase.com/)
- **UI Components:** [shadcn/ui](https://ui.shadcn.com/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Charts:** [Recharts](https://recharts.org/)
- **Form Handling:** [React Hook Form](https://react-hook-form.com/)
- **Validation:** [Zod](https://zod.dev/)
- **State Management:** [Zustand](https://zustand-demo.pmnd.rs/)

## 📦 Development Setup

1. Ensure you have access to the repository and required credentials
2. Clone the repository (requires authentication)
3. Install dependencies:
   ```bash
   pnpm install
   ```

4. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```

5. Configure your environment variables in `.env.local`:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

6. Start the development server:
   ```bash
   pnpm dev
   ```

## 🗄️ Database Schema

The application uses Supabase with the following core tables:

- `profiles` - User profiles and preferences
- `transactions` - Financial transactions
- `categories` - Transaction categories
- `accounts` - Financial accounts
- `budgets` - Budget tracking

Each table implements Row Level Security (RLS) policies for data protection.

## 🧪 Testing

```bash
# Run unit tests
pnpm test

# Run e2e tests
pnpm test:e2e
```

## 📝 Development Guidelines

- Follow the established coding standards and architecture
- Write comprehensive tests for new features
- Update documentation for any changes
- Use conventional commit messages
- Ensure all changes pass the CI/CD pipeline

## 📄 License

This software is proprietary and confidential. Unauthorized copying, modification, distribution, or use of this software, via any medium, is strictly prohibited. For licensing inquiries, please contact travor@inspiredworkx.com.

## 🔒 Security

- All code contributions must go through security review
- Follow secure coding practices
- Report any security vulnerabilities immediately to the security team
- Keep all credentials and sensitive information confidential

## 📞 Support

For technical support or inquiries:
- Email: travor@inspiredworkx.com
- Internal Documentation: [Link to be added]