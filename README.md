## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Database Setup (Chapter 6)

This project uses PostgreSQL. Follow these steps to set up your database:

1. **Create a Postgres database on Vercel:**
   - Go to your Vercel dashboard
   - Navigate to the Storage tab
   - Create a new Postgres database

2. **Create a `.env.local` file** in the root directory with your database credentials:

```env
POSTGRES_URL="your-postgres-url"
POSTGRES_PRISMA_URL="your-postgres-prisma-url"
POSTGRES_URL_NO_SSL="your-postgres-url-no-ssl"
POSTGRES_URL_NON_POOLING="your-postgres-url-non-pooling"
POSTGRES_USER="your-user"
POSTGRES_HOST="your-host"
POSTGRES_PASSWORD="your-password"
POSTGRES_DATABASE="your-database"
```

3. **Seed the database:**
   - Run your development server: `pnpm dev`
   - Visit `http://localhost:3000/seed` in your browser
   - You should see: "Database seeded successfully"

4. **Verify the setup:**
   - Check your Vercel Postgres dashboard to confirm tables were created
   - Tables created: `users`, `customers`, `invoices`, `revenue`
