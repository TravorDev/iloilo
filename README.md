# Iloilo - Modern Financial Management Platform

A robust and scalable financial management platform built with cutting-edge technologies to provide a seamless user experience for managing personal and business finances.

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

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TravorDev/iloilo.git
   cd iloilo
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   ```

4. Update `.env.local` with your Supabase credentials:
   ```
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

5. Start the development server:
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

- Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification
- Write tests for new features
- Update documentation when making changes
- Follow the established code style and architecture

## 🤝 Contributing

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes
4. Run tests: `pnpm test`
5. Commit your changes: `git commit -m 'feat: add new feature'`
6. Push to the branch: `git push origin feature/your-feature`
7. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js Documentation](https://nextjs.org/docs)
- [Supabase Documentation](https://supabase.com/docs)
- [shadcn/ui Components](https://ui.shadcn.com/docs)
- [Tailwind CSS](https://tailwindcss.com/docs)