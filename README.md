# Next.js Dashboard Full-Stack Web Application

## Features
- **Styling**: The different ways to style your application in Next.js.
- **Routing**: How to create nested layouts and pages using file-system routing.
- **Optimizations**: How to optimize images, links, and fonts.
- **Data Fetching**: How to set up a Postgres database on Vercel, and best practices for fetching and streaming.
- **Search and Pagination**: How to implement search and pagination using URL search params.
- **Mutating Data**: How to mutate data using React Server Actions, and revalidate the Next.js cache.
- **Error Handling**: How to handle general and 404 not found errors.
- **Form Validation and Accessibility**: How to do server-side form validation and tips for improving accessibility.
- **Authentication**: How to add authentication to your application using NextAuth.js and Middleware.
- **Metadata**: How to add metadata and prepare your application for social sharing.

## The Process
### Chapter 1 - Getting Started
- Created a new project with the starter example.
- Explored the default file structure and understand the codebase we will modify

### Chapter 2 - CSS Styling
- Imported global stylesheet (/app/ui/global.css) into root layout (/app/layout.tsx)
- Styled an element with Tailwind classes
- Styled an element with css modules
- Explored clsx class name utility

### Chapter 3 - Optimizing Fonts and Images
- Imported google font with `next/font` 
- Applied font to site elements
- Added desktop/mobile hero images with `next/image`

### Chapter 4 - Creating Layouts and Pages
- Created dashboard routes 
- Created dashboard route layout

### Chapter 5 - Navigating Between Pages
- Used `next/link` for page navigation 
- Applied styling based on active path

### Chapter 6 - Setting Up Your Database
- Connected Neon serverless postgresSQL database

### Chapter 7 - Fetching Data
- Fetching data from db and rendering with RSC

### Chapter 8 - Static and Dynamic Rendering
- Compared static and dynamic rendering

### Chapter 9 - Streaming
- Show a loading state while fetching data (`loading.tsx`)
- Use `suspense` to handle streaming

### Chapter 10 - Partial Prerendering
- Skipped for now (experimental feature)

### Chapter 11 - Adding Search and Pagination
- Updated url with search params and synced with user input
- Query database with search params
- Optimized search with debouncing
- Implemented pagination

### Chapter 12 - Mutating Data
- Create and invoke server actions
- Handle form submissions with validation
- Modify data in the database
- create, edit, delete operations with server actions

### Chapter 13 - Handling Errors
- Handling errors with `error.tsx`
- Handling errors with notFound() and `not-found.tsx`

### Chapter 14 - Improving Accessibility
- Using eslint plugin for accessibility errors/warnings
- Client-side form validation
- Server-side form validation 
- Working with `aria-*` attributes

### Chapter 15 - Adding Authentication
- Implemented authentication with NextAuth.js
- Used `middleware.ts` for protected routes

### Chapter 16 - Adding Metadata
- Explored metadata techniques (file-based, dynamic, and static)
- Added metadata to pages

## Next.js Foundations App Router course 
For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.
