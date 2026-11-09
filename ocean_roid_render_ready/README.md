# Ocean Roid — Store + Management System

This ZIP now contains the existing customer store PLUS an integrated Staff/Manager Management System.

## What is included
- Customer store at `/`
- Customer orders saved by the backend
- Management dashboard at `/admin.html`
- Admin / Manager / Staff roles
- Staff
- Managers
- Products
- Orders
- Tasks
- Production
- Inventory
- Sales
- Expenses
- Attendance
- Reports
- Basic email + password login for the management dashboard

## Run FREE on your computer
1. Install Node.js 18+.
2. Open a terminal inside `backend`.
3. Run `npm start`.
4. Open `http://localhost:3000` for the customer website.
5. Open `http://localhost:3000/admin.html` for management.

### First management login
Email: `admin@oceanroid.local`
Password: `admin12345`

Change this before putting the system on the public internet. This MVP uses a local JSON backend and in-memory login sessions; it is intended as a starter, not a production security system.

## Important
- The customer store sends orders to the backend and WhatsApp.
- Management data is stored in `backend/data/*.json`.
- No paid API is required for this local version.
- For multi-device online use, the next step should be moving data/auth to Supabase or another hosted database.
- AI/API, payment gateway, courier API and automated WhatsApp are intentionally not included yet.
