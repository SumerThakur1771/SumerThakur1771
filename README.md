<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1f6feb&height=190&section=header&text=Sumer%20Thakur&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Full-stack%20engineer%20%C2%B7%20I%20ship%20it%2C%20then%20I%20prove%20it%20works&descSize=17&descAlignY=58&animation=fadeIn" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1400&color=58A6FF&center=true&vCenter=true&width=680&lines=TypeScript+%C2%B7+React+%C2%B7+React+Native+%C2%B7+Node.js+%C2%B7+PostgreSQL;144+PRs+shipped+to+a+live+App+Store+fintech+app;2+live+apps+built+solo%2C+tested+in+CI;Open+to+full-time+roles+from+January+2027" alt="Typing intro" />

<br/>

<a href="https://www.linkedin.com/in/sumer-th/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:thakur.sum@northeastern.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://sumer-riverroom.vercel.app"><img src="https://img.shields.io/badge/River_Room-Live-2ea44f?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://iron-mind-psi.vercel.app"><img src="https://img.shields.io/badge/IronMind_AI-Live-2ea44f?style=for-the-badge&logo=vercel&logoColor=white" /></a>

</div>

<br/>

I'm a full-stack engineer in Boston, finishing my **MS in Information Systems at Northeastern** (Dec 2026). I spent six months as one of 4 engineers at a venture-backed AI fintech startup, shipping to real users on the App Store, and I've built two live products on my own.

I build fast with AI, but I don't ship on vibes. Every claim below has a test, a measurement or a replay behind it.

> Boston · Open to relocation · Looking for full-stack, frontend, mobile or product engineering roles starting **January 2027**

<br/>

## At a Glance

<table>
  <tr>
    <td align="center" width="25%"><h2>144</h2><sub>PRs merged in 6 months<br/>to a live iOS fintech app</sub></td>
    <td align="center" width="25%"><h2>$71K</h2><sub>deposit mislabeled as spending,<br/>traced and fixed in production</sub></td>
    <td align="center" width="25%"><h2>0 / 5,465</h2><sub>card leaks across messages<br/>checked in my poker server</sub></td>
    <td align="center" width="25%"><h2>272</h2><sub>recorded hands replayed to<br/>verify an AI-assisted rewrite</sub></td>
  </tr>
</table>

<br/>

## Featured Builds

<table>
  <tr>
    <td width="50%" valign="top">

### River Room
**Real-time multiplayer poker for my friends' home game**

The server deals every hand, and each player only ever receives their own cards. The AI players are personas of my actual friends.

- **0 leaks** across 5,465 checked messages · **137 tests** in CI
- Buy-in ledger that settles a night in the fewest payments, matching brute force on 400 cases
- LLM hand review that only shipped after scoring **87.1%** on a 20-hand eval
- Web Worker simulation that cut the worst UI freeze by **86%**

`TypeScript` `React` `Node.js` `Socket.IO` `PostgreSQL` `Prisma` `Vitest` `Playwright`

[**Live app**](https://sumer-riverroom.vercel.app) · [**Code**](https://github.com/SumerThakur1771/RiverRoom)

</td>
    <td width="50%" valign="top">

### IronMind AI
**An AI fitness coach that refuses to make things up**

It answers only from 50 training principles I wrote from years of lifting. If nothing in its knowledge base matches, it says so instead of guessing.

- RAG over 768-dimensional Gemini embeddings in **pgvector**
- **4-model fallback** when an AI provider fails
- Streaming chat, 9 API routes with JWT, bcrypt and rate-limited login
- Structured logs, tests on every PR, all **36** AI-assisted PRs reviewed by me

`Next.js` `TypeScript` `PostgreSQL` `pgvector` `Gemini API` `OpenRouter` `Vitest`

[**Live app**](https://iron-mind-psi.vercel.app) · [**Code**](https://github.com/SumerThakur1771/IronMind)

</td>
  </tr>
</table>

<br/>

## Experience

**Velzee** · Software Engineer Co-op · *Jan to Jun 2026*
AI personal-finance iOS app on the App Store · React Native, Expo, TypeScript, Next.js, Supabase, PostgreSQL, Plaid

- Traced Plaid sync bugs and restored **100+ mislabeled transactions**, including a $71K deposit counted as spending, with guarded backfills
- Integrated **Apple In-App Purchase** subscriptions end to end, from expo-iap to App Store webhooks and Postgres entitlements, so retries never duplicate a subscription
- Rebuilt the **AI insights tab** in React Native (29 components), with guards that keep model-leaked merchant names off screen
- Shipped an in-app **Notification Center** from Next.js routes and Postgres to the React Native inbox, with **200+ Vitest tests**
- Cut main-thread load on an animated dial by **over 80%** with a Skia shader driven by Reanimated, measured in Time Profiler
- Instrumented **85 Amplitude events** and found paying users were **4x more engaged** with core features than free users

<br/>

## How I Build

| | |
|---|---|
| **Proof over vibes** | AI writes a lot of my first drafts. I don't merge anything until a test, an eval or a replay proves it works. |
| **Measure, then build** | I instrument before I optimize, from Amplitude funnels to Time Profiler traces. |
| **Own it end to end** | Database, API, UI, tests, deploy. If it breaks in production, it's mine to fix. |

<br/>

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,py,java,react,nextjs,tailwind,vite,nodejs,express,postgres,prisma,supabase,mongodb,git,githubactions,vercel,figma&perline=9" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Plaid-111111?style=flat-square&logo=plaid&logoColor=white" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" />
  <img src="https://img.shields.io/badge/Apple_IAP-000000?style=flat-square&logo=apple&logoColor=white" />
  <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" />
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
  <img src="https://img.shields.io/badge/Amplitude-1E61F0?style=flat-square&logoColor=white" />
</p>

<br/>

## Off the Keyboard

- **Lifting for 6 years.** It's why IronMind exists, and why I care about tools that give people accurate information instead of confident nonsense.
- **I cut my own fades.** Cutting hair and debugging need the same thing: patience and noticing the small thing that's off.
- **Poker nights with the boys.** I wanted our home game in my pocket, so I built River Room.
- **Lewis Hamilton fan,** which makes me a Ferrari supporter now. F1 is applied data science with better marketing.
- **Ronaldo and Kohli** are my guys. PBKS supporter, because apparently I enjoy suffering.
- Grew up in **Ludhiana, Punjab.** Moved to Boston for my Master's.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,50:161b22,100:0d1117&height=110&section=footer" width="100%" />

</div>
