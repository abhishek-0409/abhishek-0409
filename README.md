<div align="center">

<img src="assets/hero.svg" width="100%" alt="Abhishek Kumar, React Native Developer and Full-Stack Engineer, over floating isometric 3D cubes on a midnight grid" />

<a href="https://github.com/abhishek-0409">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=500&size=17&duration=2800&pause=1000&color=22D3EE&center=true&vCenter=true&width=760&height=34&lines=Cross-platform+mobile+apps+with+React+Native+%2B+Expo;TypeScript+APIs+with+NestJS%2C+Node.js+and+PostgreSQL;Real-time+calling+with+Socket.IO+and+WebRTC" alt="Rotating tagline: cross-platform mobile apps, TypeScript APIs, real-time calling" />
</a>

<p>
  <a href="https://abhishek04-portfolio.netlify.app/"><img src="https://img.shields.io/badge/portfolio-abhishek04--portfolio.netlify.app-22d3ee?style=flat-square&labelColor=0b1030" alt="Portfolio" /></a>
  <a href="mailto:abhi040901@gmail.com"><img src="https://img.shields.io/badge/email-abhi040901%40gmail.com-8b5cf6?style=flat-square&labelColor=0b1030" alt="Email" /></a>
  <a href="https://github.com/abhishek-0409"><img src="https://img.shields.io/badge/github-abhishek--0409-a3e635?style=flat-square&labelColor=0b1030" alt="GitHub" /></a>
</p>

</div>

<br/>

## `01` About

I build cross-platform mobile apps and the TypeScript backends behind them. Most of my work sits where the app meets the server: authentication, REST APIs, database design, and real-time features such as video calling.

```ts
const abhishek = {
  based: "Pune, India",
  role: ["React Native Developer", "Full-Stack Engineer"],
  works_across: [
    "Cross-platform mobile apps (React Native, Expo)",
    "TypeScript full-stack systems (NestJS, Express, Next.js)",
    "REST APIs and PostgreSQL schema design",
    "Real-time communication (Socket.IO, WebRTC)",
    "Auth, third-party integrations, product engineering",
  ],
  currently: "Building Med4U, a healthcare platform (patient app, doctor app, NestJS API)",
  prefers: "Clear module boundaries and honest status notes over big claims",
};
```

<br/>

## `02` Technology

<table>
  <tr>
    <td width="130"><sub><code>MOBILE</code></sub></td>
    <td>
      <img src="https://img.shields.io/badge/React_Native-0b1030?style=for-the-badge&logo=react&logoColor=61dafb" height="40" alt="React Native" />
      <img src="https://img.shields.io/badge/Expo-0b1030?style=for-the-badge&logo=expo&logoColor=white" height="40" alt="Expo" />
    </td>
  </tr>
  <tr>
    <td><sub><code>FRONTEND</code></sub></td>
    <td><img src="https://skillicons.dev/icons?i=react,nextjs,ts,tailwind&theme=dark" height="40" alt="React, Next.js, TypeScript, Tailwind CSS" /></td>
  </tr>
  <tr>
    <td><sub><code>BACKEND</code></sub></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,nestjs,express&theme=dark" height="40" alt="Node.js, NestJS, Express" /></td>
  </tr>
  <tr>
    <td><sub><code>DATA + INFRA</code></sub></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,redis,supabase,docker&theme=dark" height="40" alt="PostgreSQL, Redis, Supabase, Docker" /></td>
  </tr>
  <tr>
    <td><sub><code>REAL-TIME + MEDIA</code></sub></td>
    <td>
      <img src="https://img.shields.io/badge/Socket.IO-0b1030?style=for-the-badge&logo=socketdotio&logoColor=white" height="32" alt="Socket.IO" />
      <img src="https://img.shields.io/badge/WebRTC-0b1030?style=for-the-badge&logo=webrtc&logoColor=white" height="32" alt="WebRTC" />
      <img src="https://img.shields.io/badge/Cloudinary-0b1030?style=for-the-badge&logo=cloudinary&logoColor=3448c5" height="32" alt="Cloudinary" />
    </td>
  </tr>
  <tr>
    <td><sub><code>TOOLS</code></sub></td>
    <td><img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" height="40" alt="Git, GitHub, VS Code" /></td>
  </tr>
</table>

<br/>

## `03` Featured projects

### NextTrip

<img src="assets/cover-nexttrip.svg" width="100%" alt="NextTrip project cover: three stacked app screens joined by a dashed travel route" />

A full-stack travel marketplace connecting travelers, vendors and administrators, with a dedicated React Native app for each role.

`3 role-specific apps` · `95 REST endpoints` · `17 backend service modules` · `22 PostgreSQL tables`

**Stack:** React Native · Expo · Node.js · Express · TypeScript · Supabase · PostgreSQL · Cloudinary · TanStack Query · Zustand

[Repository](https://github.com/abhishek-0409/NextTrip)

<details>
<summary>More about NextTrip</summary>

<br/>

- Package discovery by destination, category, price, duration, rating and amenities
- Vendor portal: package management, Cloudinary images, itinerary builder, seasonal pricing
- Admin portal: approvals, moderation, bookings, reviews, categories, locations, payouts
- JWT authentication with role-based access for travelers, vendors and admins
- Append-only audit logs and Expo push notifications

</details>

<br/>

### Med4U

<img src="assets/cover-med4u.svg" width="100%" alt="Med4U project cover: a glowing pulse line beside floating 3D cubes" />

A healthcare platform covering doctor discovery, appointments, video consultation, prescriptions, medicine ordering and lab-test requests, built as a patient app, a doctor app and a NestJS API.

`3 codebases` · `19 database migrations` · `549 automated tests passing at last full run`

**Stack:** React Native · Expo · NestJS · TypeScript · PostgreSQL · Redis · Socket.IO · WebRTC

> **Status:** working prototype for a final-year project, not production-ready. Video calls are covered by automated tests with mocked WebRTC but have not been verified on two physical devices, and the seeded doctors and medicines are demo data.

<!-- Repository link omitted: the Med4U repositories were not publicly reachable when this README was written.
     Add [Repository](https://github.com/abhishek-0409/<repo>) once it is public. -->

<details>
<summary>More about Med4U</summary>

<br/>

- Phone OTP login (hashed codes, expiry, rate limits) with JWT access tokens and rotating refresh tokens
- Doctor discovery, availability and appointment booking with database-level protection against double booking
- Video consultation: REST room authorization, Socket.IO signaling (offer, answer, ICE), two-person rooms, time-window checks
- Doctor-issued prescriptions with versioned amendments, patient report uploads, and a pharmacy order flow
- Doctor registration with an admin review workflow
- Not yet done: on-device end-to-end verification, TURN relay, real-user testing, ML report analysis

</details>

<br/>

### API Directory

<img src="assets/cover-apidirectory.svg" width="100%" alt="API Directory project cover: curly braces framing a grid of glowing API tiles" />

A Next.js platform for discovering and exploring free public APIs, with search, category and authentication filters, detail pages and a submission form.

`30 curated APIs` · `13 categories` · `35 prerendered pages in the reported production build`

**Stack:** Next.js 14 · React 18 · TypeScript · Tailwind CSS

[Repository](https://github.com/abhishek-0409/api.directory)

<br/>

## `04` GitHub activity

<div align="center">

<a href="https://github.com/abhishek-0409">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=abhishek-0409&theme=tokyonight&hide_border=true" width="49%" alt="GitHub contribution streak for abhishek-0409" />
</a>
<a href="https://github.com/abhishek-0409?tab=repositories">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhishek-0409&layout=compact&theme=tokyonight&hide_border=true" width="49%" alt="Most used languages across public repositories" />
</a>

<sub>Widgets are third-party and may be briefly unavailable. <a href="https://github.com/abhishek-0409">See live activity on GitHub</a>.</sub>

</div>

<br/>

## `05` Contact

<div align="center">

<a href="https://abhishek04-portfolio.netlify.app/"><b>Portfolio</b></a> &nbsp;·&nbsp; <a href="https://github.com/abhishek-0409"><b>GitHub</b></a> &nbsp;·&nbsp; <a href="mailto:abhi040901@gmail.com"><b>abhi040901@gmail.com</b></a>

<sub>GitHub Markdown cannot run interactive 3D, so the interactive side lives on the portfolio.</sub>

<img src="assets/footer.svg" width="100%" alt="Abstract 3D cube footer reading: for interactive 3D, see the portfolio" />

</div>
