This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.


### My Note 

next.js
A framework for building fast & search-engine friendly applications 


React(A library for building interactive UIs) ---> Next.js(A framework=libs+tools+conventions) 

Compiler(Transform & minify JS code) ---> CLI (Build & start apps) ---> Node.js Runtimem(Execute JS code)

Web Browser (Front-end)
Node.js Runtime (Back-end)

Server-side Rendering (Fast , Search-engine Friendly)


Static Site Generation (Fast)


==============
create project 
npx create-next-app@latest

run project
npm run dev 


===============
Rendering Environments 

Client (web browser)
Server (Node.js Runtime)

================
Client-side Rendering 
* Large bundles
* Resource intensive 
* No SEO 
* Less secure 

Server-side Rendering 
* Smaller bundles 
* Resource efficient 
* SEO 
* More secure 

===============
Server Components cannot 
* Listen to browser events 
* Access browser APIs 
* Maintain state 
* Use effects 

================
Fetching on the Client 
useState() + useEffect()
React Query

(x) Large bundles 
(x) Resource intensive 
(x) No SEO 
(x) Less secure 
(x) Extra roundtrip to server 

================
Data Fetching 

* Caching 
Storing data somewhere that is faster to access 

Data Sources 
    Memory , File system, Network 


================
Static and Dynamic Rendering 

Static Rendering ( Render at build time )
Dynamic Rendering ( Render at request time )


Rendering
    Client-side 
    Server-side 
        Static ( at build time)
        Dynamic ( at requst time)


https://daisyui.com/