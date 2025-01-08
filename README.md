# Finance Dashboard

Track your income and expenses with Finance Dashboard. This web application helps you to manage and monitor your financial transactions, providing a detailed overview of your finances with real-time data.

## Features
- Dashboard for tracking your income and expenses
- Integration with Drizzle ORM for database management
- User authentication using Clerk
- Financial data visualization with Recharts
- Support for multiple financial accounts
- Easy-to-use UI with Radix UI components
- Responsive design powered by TailwindCSS

## Technologies Used
- **Next.js** for server-side rendering
- **React** for building the UI
- **Drizzle ORM** for interacting with the PostgreSQL database
- **Clerk** for user authentication
- **Radix UI** for building accessible UI components
- **TailwindCSS** for styling
- **Zod** for data validation
- **Recharts** for displaying financial data in charts
- **PostgreSQL** for database

## Setup and Installation

### 1. Clone the repository
```bash
git clone https://github.com/mamskie/Finance-Management.git
cd finance-dashboard
```

### 2. Install dependencies
Make sure you have **Node.js** and **npm** installed. Then run:
```bash
npm install
```

### 3. Configure the environment variables
Create a `.env` file in the root directory and add the necessary environment variables. Refer to `.env.example` for the required values.

### 4. Run the development server
```bash
npm run dev
```
This will start the app at [http://localhost:3000](http://localhost:3000).

### 5. Build and deploy
For production deployment, build and start the app using:
```bash
npm run build
npm run start
```

## Scripts

- **dev**: Starts the development server (Next.js)
- **build**: Builds the production app (Next.js)
- **start**: Starts the production app (Next.js)
- **lint**: Runs linting checks
- **db:generate**: Generates database schema with Drizzle ORM
- **db:migrate**: Runs database migrations with Drizzle ORM
- **db:seed**: Seeds the database with initial data
- **db:studio**: Opens Drizzle Studio for managing your database

## Contribution

Contributions are welcome! Feel free to fork the repository, submit pull requests, or report issues via the [issues page](https://github.com/mamskie/Finance-Management/issues).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
