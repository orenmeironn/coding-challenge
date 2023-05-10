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
