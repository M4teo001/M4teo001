# Mateo Ramírez

**Founder & Full-Stack Engineer** — building production SaaS end-to-end at [**Nuvnext**](https://nuvnext.com).

I run a small studio that designs, ships, and operates digital products across SaaS, fintech, restaurant tech, sports management, real estate, and AI agents. I write most of the code, lead the architecture, and take products from blank Figma to production.

> Currently shipping: AI outreach agents, private proposal portals with email-gate, and a multi-tenant social media engine.

---

## Products

| | Stack |
|---|---|
| **[Nuvnext](https://nuvnext.com)** — studio + internal ERP (agenda, HR, finance, tickets, training, social media, private proposals, hiring, AI agents, community & investor portals) | Next.js 16 · React 19 · TypeScript · Supabase · Stripe · Sentry · Resend |
| **[Ristochain · ONTable](https://github.com/M4teo001/ristochain-showcase)** — operating system for restaurant groups (menu, reservations, POS, delivery, kitchen, butchery, HR) | Next.js · TypeScript · PostgreSQL |
| **[Sportiq](https://github.com/M4teo001/sportiq-showcase)** — multi-tenant system for sports clubs (members, reservations, billing, mobile app) | Next.js · Supabase · Expo |
| **[Abarrotech](https://github.com/M4teo001/abarrotech-showcase)** — operations SaaS + embedded fintech + supplier marketplace for grocery stores | Next.js · TypeScript · Expo |
| **[Objetivapp](https://github.com/M4teo001/objetivapp-showcase)** — real estate portfolio and commission management | Next.js · TypeScript · Expo |
| **[Leadera](https://github.com/M4teo001/leadera-showcase)** — AI-native digital sales agent for B2B verticals | Next.js · TypeScript · Claude API |
| **Vértice** — B2B2C institutional talent platform for universities | Next.js · TypeScript |
| **OpenClaw** — open-source OCR / document pipeline | Python · Ollama |

Other products in development: Jarvis, Tymon, and a couple unannounced.

---

## Stack

### Languages
<p>
<img src="https://skillicons.dev/icons?i=ts,js,py,html,css,bash,sql" alt="Languages" />
</p>

### Frontend
<p>
<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,html,css" alt="Frontend frameworks" />
<img src="https://img.shields.io/badge/React_19-149ECA?style=for-the-badge&logo=react&logoColor=white" />
<img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
<img src="https://img.shields.io/badge/TipTap-000000?style=for-the-badge&logo=tiptap&logoColor=white" />
</p>

### Mobile
<p>
<img src="https://skillicons.dev/icons?i=react" alt="React Native" />
<img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white" />
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
</p>

### Backend
<p>
<img src="https://skillicons.dev/icons?i=nodejs,django,fastapi,flask" alt="Backend" />
<img src="https://img.shields.io/badge/Server_Actions-000000?style=for-the-badge&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/Edge_Middleware-000000?style=for-the-badge&logo=vercel&logoColor=white" />
<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" />
</p>

### Databases & ORM
<p>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,supabase,firebase,prisma,redis" alt="Databases" />
</p>

### AI & ML
<p>
<img src="https://img.shields.io/badge/Anthropic_Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white" />
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch" alt="ML" />
</p>

### Payments & Comms
<p>
<img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/Resend-000000?style=for-the-badge&logo=resend&logoColor=white" />
<img src="https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=twilio&logoColor=white" />
<img src="https://img.shields.io/badge/WhatsApp_Business-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" />
</p>

### Infra & DevOps
<p>
<img src="https://skillicons.dev/icons?i=vercel,cloudflare,docker,aws,gcp,githubactions,nginx,linux" alt="Infra" />
<img src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white" />
</p>

### Tools
<p>
<img src="https://skillicons.dev/icons?i=vscode,figma,git,github,postman,notion" alt="Tools" />
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
</p>

---

## Engineering practices

- **Server-driven architecture** — heavy use of Server Components, Server Actions, and Edge Middleware
- **RLS-first data modeling** — every table has Row Level Security; service role is reserved for audited server actions only
- **Idempotent migrations** — every SQL change is versioned and safe to re-run
- **Semantic versioning** — every working session ends with a structured changelog and a version bump
- **Multi-provider AI routing** — Claude / Gemini / OpenAI / Ollama with fallback; BYOK pass-through for clients
- **Agentic CI** — Red Team / Blue Team agents review every push; tickets are auto-created from incidents
- **Observability from day one** — Sentry on every project, with auto-ticket creation from webhooks

---

## GitHub stats

<p>
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=M4teo001&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=M4teo001&layout=compact&hide_border=true&count_private=true&langs_count=10" />
</p>

<p>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=M4teo001&hide_border=true" />
</p>

> Most repositories are private (client work and proprietary product code). The pinned repositories are public showcases of the products listed above.

---

## Get in touch

<p>
<a href="https://nuvnext.com"><img src="https://img.shields.io/badge/Web-nuvnext.com-0c0c0c?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="mailto:servicio@nuvnext.com"><img src="https://img.shields.io/badge/Email-servicio@nuvnext.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

For partnerships, technical advisory, or to talk about products — reach out.
