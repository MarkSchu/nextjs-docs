# Next JS Notes and References 

## Pages Router vs Apps Router
When you go to the docs, you'll notice on the top left that you're able to select "Using Pages Router: Features available in /pages" and "App Router: Features available in /app". When select one over the other, the available documentation topics change. What's going on here 

App Router is the new Next.js router. Page Router is the original Next.js router.

App Router came out in version 13 of Next.js in late 2022. It has new features like Server Components and Streaming. 

The Page Router, though older, is nevertheless supported (as of June 28, 2024).

Next.js recommends that you use App Router. 

### Starting Tutorial 
This tutorial walks you through all the basics: https://nextjs.org/learn

### Building An App from Scratch 
The recommended way to start an app is with the following commands. There are many template and options that you can set. The language defaults to `TypeScript`.

```bash
    npx create-next-app@latest
```
or with pnpm 
```bash 
    pnpm create next-app@latest
```

Then, run locally with: 
```bash
    npm run dev
```
or 
Then, run locally with: 
```bash
    pnpm run dev
```

### pnpm, npx, npm? 
In the docs and tutorial, you'll see references to these all over the place (including others, e.g. yarn). What's the difference? 

npm is a package manager. It allows you to download packages. 

npx is a package runner. It allows you run packages without having to globally install them. 

npm is a package manager. It is an optimization; it does things like minimize disk usage, accelerates installation, etc.

Which should you use? Check out this helpful article: https://earthly.dev/blog/npm-vs-npx-vs-pnmp/