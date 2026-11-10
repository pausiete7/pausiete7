# Pau Sevilla

Full-stack and mobile developer in Barcelona. I'm a fourth-year Informatics Engineering student at FIB (UPC), and since December 2024 I've worked at inLab FIB, the faculty's research and innovation lab. I also build and publish my own apps.

Most of my code lives in private repositories, so this page describes what I've built. The apps are public and you can try them. The code you can read here is [porfolio-pau](https://github.com/pausiete7/porfolio-pau), the source of my website.

## At inLab FIB

- **LaCàN library** (C++, Python). I'm refactoring the open-source computational engineering library of LaCàN, UPC's numerical computing lab: modern C++, Python bindings and tests.
- **MATLAB to C++.** Over two semesters I ported a data compression algorithm to C++ and optimised it, reworking its data structures to use less memory.
- **HPC portal** (Angular, Node.js, Slurm). A web app for submitting Slurm jobs, used by the BIT group at the Barcelona School of Civil Engineering in the European E-Med project. I built the frontend, the backend and the job queue.
- **TurnItOn** (Angular, Laravel). The lab's new web app for switching on computers remotely and connecting to them. I built the frontend and backend.

## My apps

I built these on my own, except Flipebooks, which I made with another developer.

- **Vademecum** (Flutter, Supabase, RevenueCat). Drug reference app based on official data from AEMPS, Spain's medicines regulator. I rebuilt it from scratch, with an encrypted on-device database, real-time sync and subscriptions. 10,000+ downloads on Google Play, rated 4.8 on the App Store (13 ratings). [App Store](https://apps.apple.com/es/app/id1187696022) · [Google Play](https://play.google.com/store/apps/details?id=es.impulsit.vademecum)
- **Manipulador Hoy** (Expo, React Native, TypeScript, Supabase, Stripe). Web and mobile app for getting the Spanish food handler certificate: free exam, Stripe payments, a QR-verifiable certificate and an assistant built on the Claude API. Launched in 2026 and already making sales. [manipuladorhoy.es](https://manipuladorhoy.es)
- **Vademecum Veterinario** (Flutter, Node.js, GitHub Actions). Over 3,700 veterinary medicines, available offline. A daily job downloads, validates and publishes the catalogue and opens a GitHub issue if anything fails; I cut its download time from 29 to 16 minutes. [App Store](https://apps.apple.com/es/app/id6817796985) · [Google Play](https://play.google.com/store/apps/details?id=es.impulsit.vademecumvet)
- **Apto** (Flutter, SQLite, Python). Practice tests for the Spanish driving theory exam, with every question citing its official source. Question packs are built with Python, linted in CI and signed before they reach the app. [App Store](https://apps.apple.com/es/app/id6813851821) · [Google Play](https://play.google.com/store/apps/details?id=es.impulsit.apto)
- **Parcelario** (Flutter, MapLibre). Map viewer for Spanish land parcels from the SIGPAC farm register and the Cadastre, with plot measuring. A scheduled workflow checks twice a day that the public APIs it relies on are still up. [App Store](https://apps.apple.com/es/app/id6822248499) · [Google Play](https://play.google.com/store/apps/details?id=es.impulsit.parcelassigpac)
- **Flipebooks** (Next.js, Supabase, Vercel AI SDK). Turns PDFs into interactive flipbooks, with paid plans, automatic translation and chat with the document. [flipebooks.com](https://flipebooks.com)

## How I use AI

For the past year I've developed with AI agents (Claude Code and Codex), always under my supervision. I set up the agents, skills and instructions for each project and review the code they write. Everything passes the tests before it ships.

## Tools

Flutter (Dart), React Native (Expo), TypeScript, Angular, Node.js, Next.js, Laravel, C++, Python, PostgreSQL, Supabase, SQLite, GitHub Actions, Playwright.

## Contact

For job offers or projects, email me at pau.sevilla@icloud.com. My CV and more are at [pausevilla.com](https://pausevilla.com), and I'm on [LinkedIn](https://www.linkedin.com/in/pau-sevilla). I speak Catalan and Spanish natively, and English at an intermediate level.
