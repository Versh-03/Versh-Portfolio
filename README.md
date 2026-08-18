# Versh — Developer Portfolio

A modern, interactive developer portfolio built with **Astro**, designed to highlight my engineering projects, technical stack, competitive programming progress, and professional journey.

 **Live Website:** [versh-portfolio.vercel.app](https://versh-portfolio.vercel.app)

---

##  Features

* **Modern & Responsive:** Smooth, mobile-first design adapted for all screen sizes.
* **Component-Driven:** Clean layout built using Astro's modular component structure.
* **Fluid Animations:** Scroll-triggered UI animations powered by GSAP and Lenis smooth scrolling.
* **Live CP & LeetCode Stats:** Real-time statistics fetched directly via the Codeforces and LeetCode APIs.
* **Project & Experience Highlights:** Dedicated sections showcasing past work, technical stacks, and professional experience.

---

##  Tech Stack

**Frontend & Styling**
* [Astro](https://astro.build/) — Static site generation & component architecture
* HTML5 / CSS3 / JavaScript

**Animations & Interactions**
* [GSAP](https://greensock.com/gsap/) — UI animations
* [Lenis](https://lenis.darkroom.engineering/) — Smooth scroll experience

**Integrations & APIs**
* Codeforces API — Live competitive programming stats
* LeetCode Statistics API — Problem-solving metrics

**Hosting & Deployment**
* Vercel & GitHub

---

##  Project Structure

```text
src/
├── components/
│   ├── HeroCard.astro
│   ├── StackCard.astro
│   ├── CompetitiveCard.astro
│   ├── GameCard.astro
│   ├── Project1.astro
│   ├── Project2.astro
│   ├── Project3.astro
│   ├── Experience.astro
│   └── Contact.astro
├── layouts/
│   └── BaseLayout.astro
└── pages/
    └── index.astro
