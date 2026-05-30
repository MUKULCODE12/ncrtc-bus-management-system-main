# 1. Install dependencies
npm install

# 2. Generate Prisma client
npx prisma generate

# 3. Create all database tables
npx prisma migrate dev --name init

# 4. Seed with demo data
npm run seed

# 5. Start backend
npm run dev

# 6. (Optional) Start fake GPS simulator in a new terminal
npm run tick
