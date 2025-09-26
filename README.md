🪑 Shiv Furniture Cloud

📊 Complete Accounting & Inventory Solution for Furniture Manufacturing

Shiv Furniture Cloud is a full-stack accounting and inventory management solution designed specifically for furniture manufacturers. It helps businesses streamline their operations by combining sales, purchases, invoicing, payments, inventory tracking, and financial reporting into a single cloud-based platform.

The system supports two roles — Admin and User — ensuring secure, role-based access. Admins can manage products, contacts, transactions, and reports, while Users can handle day-to-day operations like orders and invoices.

With real-time analytics, responsive design, and Supabase integration, Shiv Furniture Cloud provides manufacturers with the tools to simplify workflows, maintain accurate records, and gain actionable insights for smarter decision-making.

🚀 Key Features

🔐 User Authentication – Secure sign-up/login with Supabase

👥 Contacts Management – Store and manage customer & supplier details

🛋 Product Catalog – Add, update, and organize furniture items with stock tracking

📦 Sales Workflow – Sales Orders → Invoices → Payments (auto inventory updates)

📥 Purchase Workflow – Purchase Orders → Bills → Payments

📊 Reports & Analytics – Real-time insights (P&L, Balance Sheet, Stock Reports, Partner Ledger)

📱 Mobile Responsive – Works seamlessly on desktop, tablet, and mobile

🛠 Tech Stack
🔹 Frontend


TypeScript

Vite ⚡

Tailwind CSS 🎨

Shadcn UI + Radix UI

TanStack Query

Recharts 📊

🔹 Backend & Database

Supabase (PostgreSQL, Authentication, Storage)

⚙️ Installation

Clone the Repository

git clone <repository-url>
cd Shiv-Furniture-Cloud


Install Dependencies

npm install
# or
bun install


Configure Environment Variables
Create a .env file in the root directory and add your Supabase credentials:

VITE_SUPABASE_URL="YOUR_SUPABASE_URL"
VITE_SUPABASE_ANON_KEY="YOUR_SUPABASE_ANON_KEY"


Run Development Server

npm run dev
# or
bun run dev


👉 Accessible at http://localhost:5173

📖 Usage Guide

🔑  Login to your account(The system supports two roles — Admin and User)

👥 Manage Contacts (customers & suppliers)

🛋 Add Furniture Products with stock levels & tax settings

📦 Create Sales Orders → Convert to Invoices → Track Payments

📥 Record Purchases via Purchase Orders & Bills

📊 Generate Reports for finance, inventory, and business health

📂 Project Structure
Shiv-Furniture-Cloud/
├── public/               # Static assets
├── src/
│   ├── App.tsx
│   ├── components/       # UI components
│   ├── hooks/            # Custom hooks (e.g., auth, queries)
│   ├── integrations/     # Supabase & external services
│   ├── lib/              # Utility functions
│   ├── pages/            # Pages (Auth, Products, Orders, Reports, etc.)
│   └── main.tsx
├── supabase/             # Config & migrations
├── .env                  # Environment variables
├── package.json          # Dependencies & scripts
├── tailwind.config.ts    # Tailwind setup
├── vite.config.ts        # Vite build config
└── README.md             # Documentation

🎥 Demo

📺 Watch the demo video here: 👉 https://youtu.be/phUE_kJ-SBY?

👥 Contributors

Rakesh G
Rishan Menezes
Nagaraju HL
Prithvi HN
