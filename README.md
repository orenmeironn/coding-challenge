# Full-Stack Coding Challenge

## Products List with Infinite Scroll
Your task is to create a web application that fetches a list of products from the DummyJson API and displays them in a user interface with infinite scroll. The implementation should include virtualization to optimize performance.

## Requirements
- Use React, TypeScript, and Next.js to implement the application.
- Use the DummyJson API to fetch a list of products.
- Display the list of products in a user interface. Each product should display the following information: title, description, rating, and product image.
- Implement infinite scroll so that the list can be scrolled indefinitely. When the user reaches the bottom of the list, the application should fetch the next batch of products and append them to the list.
- Use virtualization to optimize performance. The list should only render the items that are currently visible on the screen.

## Resources 
- DummyJson API
Example - https://dummyjson.com/products?limit=10&skip=10 (see docs: https://dummyjson.com/docs/products)
- Figma Design
https://www.figma.com/file/zxisdmrR19PaN5I2QcXvFj/Coding-Challenge?type=design&node-id=0%3A1&t=VkX3szBvmsr6MKaF-1


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
