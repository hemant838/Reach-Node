This is a Group Chatting Web App where you can create server according to the topics you want to talk about.

## Getting Started

First, run the development server:

```bash
npm install

npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## How to Setup in Local Enviornment

To connect the database you can use docker enviornment
Run this in terminal to initialise Mysql Database Locally

```bash
docker compose up
```
Then
```bash

#install prisma
npm install prisma --save-dev

npx prisma init

npx prisma generate

#push database schema
npx prisma db push

#install prisma client
npm install @prisma/client

#Run prisma studio
npx prisma studio
```
