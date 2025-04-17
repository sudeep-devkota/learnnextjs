✅ Day 1: What is Next.js?
Why Next.js over React?

Pages, Routing, SSR vs CSR vs SSG
routing: dynamic routing ()


# js concept: 
1) spread operator 
b) destructring : a={c:3 , d:4}
{c,d}=a
c:3
d:4
c) async: the async function will be delayed or exectted after the other 



Set up your first app:

bash
Copy
Edit
npx create-next-app@latest nextjs-bootcamp --typescript
📚 Learn from:

Next.js Docs - Intro

Traversy Crash Course

✅ Day 2: File-based Routing & Pages
Understand pages/ folder

# create a page 
  
is the ui that rendered on specific route 
eg: folder: app
file page.js( /app, /)=> this is how it rendered 

# creating a layout 

layout helps to preserve state eg



Dynamic routes: [id].tsx
# routes 
# (1) nested routes 
> /(root segment )
>/blog(segment)
>[slug](leaf segment)







Linking pages with <Link />

404 pages

✍️ Build:

A simple 3-page portfolio with internal links

✅ Day 3: Static Site Generation (SSG) & getStaticProps
Fetch API data at build time

Use getStaticProps, getStaticPaths

Revalidation (revalidate)

✍️ Build:

Static blog homepage that lists posts from a JSON or API

✅ Day 4: Server-Side Rendering (SSR)
getServerSideProps explained

Difference between SSR and SSG

Real-time data fetching

✍️ Build:

A page that shows real-time user data from an API

✅ Day 5: Layouts and Components
Shared layouts with _app.tsx

Custom components

Global styles, Tailwind setup

✍️ Build:

A navbar, footer, and reusable card component

✅ Day 6: API Routes (Backend with Next.js)
Create APIs in pages/api/

RESTful routes

Send JSON responses

✍️ Build:

A simple feedback form with a POST API route

✅ Day 7: Forms, Validation, and Client API Calls
Handling form input with useState/useForm

Submitting to backend routes

Toasts and form validations

✍️ Build:

A contact form that stores submitted data in an API

✅ Day 8: Authentication (JWT or Clerk/Auth.js)
Basic auth strategy

Sessions using cookies/JWT

OR use next-auth for OAuth

✍️ Build:

Sign in / Sign up flow with protected dashboard route

✅ Day 9: Deploy + Project Setup
Host on Vercel (1-click Next.js deploy)

Setup .env for secrets

Add SEO metadata

✅ Day 10: Build Your Final Project
Choose a project and start it with everything you've learned:

🔧 Project Ideas:
Project	Features
📝 Blog Platform	Markdown/blog post editor, comments, auth, protected admin
📋 Job Tracker	Add/edit jobs, filters, API backend, auth
📚 Course App	List of courses, progress tracking, user dashboard
🛍️ Shop Catalog	Products page, add to cart, checkout (mocked)
🔑 Tools You’ll Use:
Next.js (with TypeScript)

Tailwind CSS

next-auth (optional)

Axios / fetch

Vercel for deploy