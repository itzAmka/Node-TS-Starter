# TypeScript + Prisma + Node.js + Express + SQLite Starter Template

### Installation

2. Install the dependencies

   ```sh
    npm install

   or
   yarn

   or
   pnpm install
   ```

3. Create a `.env` file in the root directory and add the following environment variables:

   ```.env
   DATABASE_URL="file:./dev.db"
   ```

4. Write your Prisma schema in `prisma/schema.prisma`

5. Run the Prisma commands to generate the Prisma client and migrate the database

   ```sh
   npx prisma migrate dev --name init
   ```

6. Run the development server

   ```sh
   npm run dev

   or
   yarn dev

   or
   pnpm dev
   ```
