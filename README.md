Tech stack:
 Frontend Tech Stack
✅ Framework & Language
React.js – Component-based frontend library for building dynamic UIs

TypeScript – Typed superset of JavaScript for scalable, safer code

🎨 Styling & UI
Tailwind CSS – Utility-first CSS framework for fast, responsive styling

shadcn/ui – Beautifully designed, accessible UI components built on Radix and Tailwind CSS

React Icons – Icon library for easy integration of popular icon sets


 I create the deletie controlller as per your requrement in backend but because of the shortage i pushed repo without adding 
adding deletng feature 

The backend uses the cors middleware to allow requests from the frontend during development. Since the frontend can run on different ports (e.g., 3000, 3001), CORS is configured to accept multiple origins.

Location: app.js or use can reolace the cors url with array of cors url
app.use(
  cors({
    origin: ["http://localhost:3000", "http://localhost:3001"],
    credentials: true, 
  })
);


![image](https://github.com/user-attachments/assets/f1a5318a-e630-499d-b96d-b2f423574734)
these three are the routes where product are displaying on screen plss click on routes to see the filtered data fetching from backend by category name 
and type name

his is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
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

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
