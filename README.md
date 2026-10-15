# Hi, I'm Balbir 👋

**Graduate software engineer in Luton, UK.** I build useful software with a little personality.

[**balbir.dev**](https://balbir.dev) · [LinkedIn](https://www.linkedin.com/in/balbir-singh-cse24/) · [singh.techie24@gmail.com](mailto:singh.techie24@gmail.com)

> I started on the frontend because I like pretty things.
> I learned the backend because a pretty button is useless if it doesn't save your data.

&nbsp;

## A bit about me

I spent four years in India writing algorithms and making sure my logic was solid, then packed exactly two bags and moved to the UK for my **MSc in Web and Mobile Development Technologies** at Northumbria University London.

These days I build products end to end: the idea, the interface, the database and the deployment. Most of them started with something annoying in my own life, like two jobs with two rotas and no easy way to tell if I could afford rent.

I'm looking for **graduate and junior software engineering roles in the UK**.

&nbsp;

## Things I've shipped

Every project has a full case study on [balbir.dev/work](https://balbir.dev/work): the problem, the decisions, what broke, and what I learned.

&nbsp;

### 🟢 Hustle · *public early access*

**A live web app for UK workers with more than one job.**
I was checking Microsoft Teams for one rota and a terrible web portal for the other, doing mental gymnastics to work out if I had Friday off. Hustle pulls both rotas into one calendar and estimates take-home pay for each payday, using each job's pay rules plus UK PAYE and National Insurance. Rotas can be imported from a screenshot with AI.

- Launched in October 2026: public sign-up, real accounts, free during early access
- 3,500+ automated tests across unit, render, security-rules and browser checks
- AI rota imports are checked before anything is saved

`Next.js` `TypeScript` `Firebase` `OpenAI` `Google Cloud KMS` `Vitest` `Playwright`

[Visit hustlepay.co.uk](https://www.hustlepay.co.uk) · [Read the case study](https://balbir.dev/work/hustle) · source is private

&nbsp;

### 🟣 EchoFlow · *public beta*

**A local AI voice-dictation app for Windows.**
Hold a shortcut, speak, release. Your speech is transcribed on your own PC, optionally polished by a local AI model, and typed wherever you were working, with no cloud service involved.

- Installer cut from 297.9 MB to 11.2 MB
- 5 local speech models and 4 local AI models to choose from
- 308 automated Playwright tests on the product website, with tested auto-updates

`Tauri v2` `Rust` `React` `TypeScript` `whisper.cpp` `llama.cpp` `Vulkan`

[Visit echoflow.uk](https://echoflow.uk) · [Read the case study](https://balbir.dev/work/echoflow) · source is private

&nbsp;

### 🔵 HealthAssist · *MSc dissertation prototype*

**An AI health and wellness companion.**
Everyday health tools rarely talk to each other, so HealthAssist puts contextual AI chat, live voice, mood and medication tracking, nutrition information and an emergency simulation in one place. After building it, I audited it so its memory, limits and safety wording match what the interface claims.

- 146 tests across three suites, all passing in the final run
- AI rules and usage limits moved behind a Cloudflare Worker, out of the browser
- Live voice sessions of up to 3 minutes

`React 19` `TypeScript` `Vite` `Tailwind CSS` `Cloudflare Workers` `Firebase` `OpenAI Realtime`

[Try the live demo](https://healthassist-mvp.vercel.app/) · [Read the case study](https://balbir.dev/work/healthassist) · source is private

> An educational, non-clinical prototype. It doesn't diagnose anything or replace professional healthcare.

&nbsp;

### ⚪ Doctor Appointment · *portfolio project*

**Find a doctor, pick a time, manage the booking.**
A familiar booking flow that still has to stay coherent across sign-in, availability, ownership and cancellation. I later revisited my own early code and hardened it.

- Appointments now go through authenticated server routes that check who owns them
- No API tokens left in the browser after the hardening pass
- Deployed with synthetic data, so anyone can try it safely

`Next.js` `React` `Kinde` `Strapi` `PostgreSQL` `Tailwind CSS`

[Try the live demo](https://doctor-appointment-booking-web-nextjs-two.vercel.app/) · [Read the case study](https://balbir.dev/work/doctor-appointment) · [View the code](https://github.com/singhtechie24/Doctor-Appointment-Booking-Web-Nextjs)

&nbsp;

## How I work

I build with **Claude, Codex and Antigravity**, and I use them a lot. They write code fast; my job is making sure it's the right code.

I decide what gets built, notice when the output is wrong, test it until it breaks, and debug it until I understand why. Every engineering story on my site started with something breaking and ended with me understanding why, because if I can't explain a piece of my own project, it isn't finished.

&nbsp;

## Toolkit

| | |
|---|---|
| **Frontend** | `TypeScript` `JavaScript` `React` `Next.js` `Tailwind CSS` |
| **Backend and data** | `Node.js` `Firebase` `PostgreSQL` `Strapi` `Cloudflare Workers` |
| **Desktop** | `Rust` `Tauri` |
| **Motion and design** | `GSAP` `Framer Motion` `Figma` |
| **Testing** | `Vitest` `Playwright` |
| **AI** | `OpenAI APIs` `whisper.cpp` `llama.cpp` |

&nbsp;

## Off the keyboard

🎸 Teaching myself guitar, because I thought it would make me look cool. It's ridiculously hard (sincere apologies to my neighbours).
🏋️ A highly inconsistent, love-hate relationship with the gym.
🐛 Ask me about the CSS bugs at 2am.

&nbsp;

---

**If your team needs someone who understands database transactions but will also lose sleep over an unaligned pixel, [let's talk](https://balbir.dev/contact).**
