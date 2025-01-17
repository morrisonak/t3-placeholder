---
title: Introduction
description: Introduction to the T3 Stack
layout: ../../layouts/docs.astro
---

<a href="http://www.youtube.com/watch?v=PbjHxIuHduU" target="_blank">
  <p align="center">
    <img
      src="https://t3.gg/random/T3%20Stack%20V4.png"
      alt="Video thumbnail of Theo with an indecipherable expression on his face"
      width="320"
    />
  </p>
</a>

<a href="http://www.youtube.com/watch?v=PbjHxIuHduU" target="_blank">
  <p align="center">Watch Theo's overview on Youtube here</p>
</a>

## What is the T3 Stack?

The _"T3 Stack"_ is a web development stack made by [Theo](https://twitter.com/t3dotgg) focused on simplicity, modularity, and full-stack typesafety. It consists of:

- [**Next.js**](https://nextjs.org/)
- [**tRPC**](https://trpc.io/)
- [**Tailwind CSS**](https://tailwindcss.com/)
- [**TypeScript**](https://typescriptlang.org/)
- [**Prisma**](https://prisma.io/)
- [**NextAuth.js**](https://next-auth.js.org/)

## What is `create-t3-app`? Some kinda template?

Kind of. We love the technologies that the T3 Stack includes but we do not believe that all of them are needed in every project. So we made `create-t3-app` to do one thing: _**Simplify complex boilerplate around the core T3 Stack tech without compromising the pieces modularity.**_

## T3 Axioms

We'll be frank - this is an _opinionated project_. We share a handful of core beliefs around building and we treat them as the basis for our decisions.

### Solve Problems

It's easy to fall into the trap of "adding everything" - we explicitly don't want to do that. Everything added to `create-t3-app` should solve a specific problem that exists within the core technologies included. This means we won't add things like state libraries (`zustand`, `redux`) but we will add things like NextAuth.js and integrate Prisma and tRPC for you.

### Bleed Responsibly

We love our bleeding edge tech. The amount of speed and, honestly, fun that comes out of new shit is really cool. We think it's important to bleed responsibly, using riskier tech in the less risky parts. This means we wouldn't ⛔️ bet on risky new database tech (SQL is great!). But we happily ✅ bet on tRPC since it's just functions that are trivial to move off.

### Typesafety Isn't Optional

The stated goal of `create-t3-app` is to provide the quickest way to start a new full-stack, **typesafe** web application. We take typesafety seriously in these parts as it improves our productivity and helps us ship fewer bugs. Any decision that compromises the typesafe nature of `create-t3-app` is a decision that should be made in a different project.
