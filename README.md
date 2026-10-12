# rova-api
Backend API for the Rova bike sharing app

## Requirements
- Nodejs20
- PostgreSQL15 running locally
##setup
1. Clone: 'git clone https://github.com/<org>/rova-api.git
2. Install: 'npm install'
3. Create env file:  cp .env.example .env
4. In '.env' set Database_URL= postgresql://localhost:5432/rova_dev
5. run migrations before starting: npm run db:migrate
6. Start: 'npm start' (port 4000)

   ##Troubleshooting
   **Error: DATABASE_URL is not set**: you skipped step 3 or 4

   ##Contributing
   See [CONTRIBUTING.MD](contributing.md).


