<!-- ANIMATED HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,50:10b981,100:f59e0b&height=220&section=header&text=Joseph%20Edomobi&fontSize=48&fontColor=ffffff&animation=twinkling&fontAlignY=30&desc=Engineer%20Who%20Builds%20Like%20He%20Owns%20It%20%2D%2013%2B%20Shipped%20Products&descSize=16&descAlignY=52" />
</div>

<!-- TYPING ANIMATION -->
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&duration=3000&pause=1000&color=0EA5E9&center=true&vCenter=true&width=700&lines=I+ship.+Then+I+iterate.;I+treat+code+like+it's+my+own+business.;13+products.+One+mindset%3A+get+it+done.;Python+%E2%80%A2+FastAPI+%E2%80%A2+React+%E2%80%A2+Infrastructure" alt="Typing SVG" />
  </a>
</div>

<br>

<!-- METRICS STRIP - Full width, bold, unmissable -->
<div align="center">
  <table width="100%" style="max-width: 100%;">
    <tr>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#0ea5e9">13+</span><br><strong style="font-size: 0.95em;">Shipped Products</strong></td>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#10b981">+30%</span><br><strong style="font-size: 0.95em;">Conversion Lift</strong></td>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#10b981">+40%</span><br><strong style="font-size: 0.95em;">Traffic Growth</strong></td>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#0ea5e9">−20%</span><br><strong style="font-size: 0.95em;">Infra Cost Reduction</strong></td>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#0ea5e9">−31%</span><br><strong style="font-size: 0.95em;">Deploy Failures</strong></td>
      <td align="center" width="16%"><span style="font-size: 2em; font-weight: 700; color:#10b981">100%</span><br><strong style="font-size: 0.95em;">Billing Bugs Elim.</strong></td>
    </tr>
  </table>
  <strong style="font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;"><i>All numbers from shipped projects - verified, not vibes.</i></strong>
</div>

<br>

<!-- WHY I BUILD -->
<h2 align="center">Why I Build</h2>

<p align="center" style="font-size: 1.15em; line-height: 1.7; font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;">
  I don't write code for the sake of it. I build what <b>needs to exist</b> - whether that's a CDN for African developers priced in their own currency, a search engine for a faith community that needed one, or a client landing page that had to convert better.
  <br><br>
  Every project I touch gets treated like my own business. The shortcuts I wouldn't take there, I won't take here. <b>Execution is currency.</b>
</p>

<br>

<!-- SIGNATURE PROJECTS - Full-width stacked cards -->
<h2 align="center">Signature Work</h2>

<table align="center" width="100%" style="font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;">
  <tr>
    <td>
      <h3>Meldev</h3>
      <p><i>Developer File Cloud &amp; CDN - Africa's affordable Cloudinary alternative</i>
      <br>
      <a href="https://meldev.com.ng">
        <img src="https://img.shields.io/badge/Visit%20Site-0ea5e9?style=flat-square&logo=cloudflare&logoColor=white&labelColor=0f172a" />
      </a>
      </p>
      <p>Built a full cloud platform with a cross-platform <b>CLI</b> so developers can manage workflows directly from the terminal - uploads, downloads, sharing, billing, everything. Engineered an async-first Python backend that cut large-file upload latency <b>10%</b> via dedicated asyncio workers for Cloudflare R2, reduced server costs <b>20%</b>, and eliminated <b>100%</b> of concurrent billing race conditions with Unix <code>fcntl.flock</code>. Reduced auth drop-offs <b>3%</b> via a singleton Axios refresh token pattern.</p>
      <br>
      <sub>Python • FastAPI • React 19 • Cloudflare R2 • SQLAlchemy 2.0 • CLI (cross-platform)</sub>
    </td>
  </tr>
  <tr>
    <td>
      <h3>Paperless</h3>
      <p><i>AI-powered document digitization for Nigerian schools - snap a photo, get structured data</i>
      <br>
      <a href="https://paperless-two-sooty.vercel.app">
        <img src="https://img.shields.io/badge/View%20Demo-0ea5e9?style=flat-square&logo=vercel&logoColor=white&labelColor=0f172a" />
      </a>
      </p>
      <p><b>94% extraction accuracy</b> - a teacher snaps a photo of any document (admission letter, fee receipt, report card), and the system auto-reads names, dates, and amounts via a just-in-time AI pipeline. A quick human check confirms accuracy; then the document is searchable by name or year from any phone. Built with offline-first capture (Web Workers reject bad photos before upload), a fatigue-aware review lock, and stateless JWT permission links instead of user accounts. Multi-tenant data isolation via PostgreSQL Row-Level Security - no app code ever manually filters by school.</p>
      <br>
      <sub>Vue.js • FastAPI • PostgreSQL (RLS) • Qwen (OpenRouter) • Web Workers • Render</sub>
    </td>
  </tr>
  <tr>
    <td>
      <h3>BranhamSermons.ai</h3>
      <p><i>AI-powered spiritual search engine - RAG over thousands of sermons</i>
      <br>
      <a href="https://branhamsermons.ai">
        <img src="https://img.shields.io/badge/Visit%20Site-0ea5e9?style=flat-square&logo=google&logoColor=white&labelColor=0f172a" />
      </a>
      </p>
      <p>Originally founded as SpokenWord.faith; now a collaborative project I continue to contribute to. Built a RAG-based search engine that lets users ask natural questions across thousands of sermon transcripts - powered by Gemini 1.5 Pro embeddings with semantic vector search. The project uses <b>Next.js + TailwindCSS + Supabase</b> on the frontend and data layer.</p>
      <details>
        <summary>About this project</summary>
        <table>
          <tr><td>🤖</td><td>Built on Gemini 1.5 Pro embeddings with semantic vector search (RAG)</td></tr>
          <tr><td>🌍</td><td>Founded as SpokenWord.faith; now a collaborative project I contribute to</td></tr>
          <tr><td>💡</td><td>Users ask natural questions - the AI finds answers across sermon transcripts</td></tr>
        </table>
      </details>
      <br>
      <sub>Next.js • TailwindCSS • Supabase • Gemini 1.5 Pro • RAG</sub>
    </td>
  </tr>
  <tr>
    <td>
      <h3>LinkedIn Automation Framework</h3>
      <p><i>AI-driven engagement engine with <b>0</b> duplicate interactions</i>
      <br>
      <a href="https://github.com/joeygoesgrey/Linkedln-Automation-Framework">
        <img src="https://img.shields.io/badge/Source%20Code-0ea5e9?style=flat-square&logo=github&logoColor=white&labelColor=0f172a" />
      </a>
      </p>
      <p>Python 3.13 CLI-driven framework that generates <b>600+ organic impressions</b> per interaction. Features a 4-tier driver provisioning fallback chain for cross-OS compatibility, SHA-1 deduplication engine with 7-day TTL eviction (zero duplicates guaranteed), and chain-of-responsibility click fallback from native clicks to JS injectors for DOM resilience.</p>
      <br>
      <sub>Python 3.13 • LLM APIs • Selenium • Asyncio • CLI</sub>
    </td>
  </tr>
  <tr>
    <td>
      <h3>LAF Chrome Extensions</h3>
      <p><i>AI comment drafting for LinkedIn, X &amp; Reddit - never stare at a blank comment box again</i></p>
      <p>A suite of Chrome extensions (separate from the Python bot) that inject AI-powered comment drafting directly into LinkedIn, X/Twitter, and Reddit. Drove <b>960 post impressions</b> and <b>34 profile visits</b> within the first week - organic, zero ad spend.</p>
      <br>
      <sub>TypeScript • Chrome Extensions API • LLM Integration</sub>
    </td>
  </tr>
</table>

<br>

<!-- PROFESSIONAL EXPERIENCE -->
<h2 align="center">Track Record</h2>

<table align="center" width="100%" style="font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;">
  <tr>
    <td>
      <h3><a href="https://5thelement.ng">5th Element Creative Media</a></h3>
      <p><i>Software Developer | Abuja, Nigeria | May 2024 – Jan 2025</i></p>
      <ul>
        <li>Delivered <b>13+ production websites</b> using custom headless WordPress + integrated analytics (PostHog, GA)</li>
        <li>Drove <b>+30% lead generation</b> for real estate clients via conversion-focused architecture and CRO pipelines</li>
        <li>Boosted organic traffic <b>+40%</b> across client sites - server-side caching, Core Web Vitals, structured SEO</li>
        <li>Achieved <b>#2 Google ranking</b> for "luxury apartments in Abuja" (YannaApartments.com)</li>
      </ul>
      <!-- Ranking proof -->
      <div align="center">
        <a href="https://cdn.meldev.com.ng/u/651e7401-dcc4-428b-a96d-bc7e15195e80/yanna%20places.png?v=1">
          <img src="https://cdn.meldev.com.ng/u/651e7401-dcc4-428b-a96d-bc7e15195e80/yanna%20places.png?v=1" width="48%" alt="Google ranking screenshot 1" />
        </a>
        <a href="https://cdn.meldev.com.ng/u/651e7401-dcc4-428b-a96d-bc7e15195e80/yanna%202.png?v=1">
          <img src="https://cdn.meldev.com.ng/u/651e7401-dcc4-428b-a96d-bc7e15195e80/yanna%202.png?v=1" width="48%" alt="Google ranking screenshot 2" />
        </a>
        <br>
        <sub><i>Click to enlarge - verified ranking data</i></sub>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      <h3><a href="https://27thdevelopment.com">27th Development LLC</a></h3>
      <p><i>Full-Stack Web App Developer | Jan 2023 – Mar 2024</i></p>
      <ul>
        <li>Reduced deployment failures <b>−31%</b> by standardizing Docker environments across the engineering team</li>
        <li>Accelerated iteration cycles with modular PostgreSQL schemas + Django REST ↔ Vue.js frontends</li>
        <li>Enhanced system reliability through expanded test coverage and async debugging</li>
      </ul>
    </td>
  </tr>
</table>

<br>

<!-- TECHNICAL ARSENAL -->
<h2 align="center">Technical Arsenal</h2>

<div align="center">

### 🎯 Core
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white&labelColor=0f172a" />

### 🏗️ Infrastructure
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white&labelColor=0f172a" />

### 🤖 AI & Automation
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white&labelColor=0f172a" />
<img src="https://img.shields.io/badge/Quasar-1976D2?style=for-the-badge&logo=quasar&logoColor=white&labelColor=0f172a" />

</div>

<br>

<!-- OWNERSHIP MANIFESTO -->
<div align="center">
  <br>
  <blockquote>
    <p style="font-size: 1.2em; font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;"><i>"The things I wouldn't do in my own business, I won't do in yours."</i></p>
    <p><strong>- Joseph Edomobi</strong></p>
  </blockquote>
  <br>
</div>

<br>

<!-- GITHUB STATS -->
<div align="center">
  <a href="https://github.com/joeygoesgrey">
    <img width="49%" src="https://github-readme-stats.vercel.app/api?username=joeygoesgrey&show_icons=true&theme=transparent&hide_border=true&bg_color=0f172a&title_color=0ea5e9&text_color=e2e8f0&icon_color=f59e0b&ring_color=10b981&fire_color=f59e0b&count_private=true&include_all_commits=true" />
    <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=joeygoesgrey&theme=transparent&hide_border=true&background=0f172a&stroke=0ea5e9&ring=10b981&fire=f59e0b&currStreakNum=0ea5e9&currStreakLabel=10b981&sideNums=e2e8f0&sideLabels=e2e8f0" />
  </a>
</div>

<br>

<!-- CONTRIBUTION GRAPH -->
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=joeygoesgrey&theme=github-compact&bg_color=0f172a&color=0ea5e9&line=10b981&point=ffffff&area=true&hide_border=true" width="98%" />
</div>

<br>

<!-- INTRO VIDEO -->
<h2 align="center">A 60-Second Introduction</h2>

<p align="center" style="font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;">
  <i>I type fast, but some things are better said face-to-face.</i>
  <br><br>
  <a href="https://meldev.com.ng">
    <img src="https://img.shields.io/badge/▶%20Watch%20My%20Intro-0ea5e9?style=for-the-badge&logo=youtubegaming&logoColor=white&labelColor=0f172a" />
  </a>
  <br><br>
  <sub>(Video coming soon - hosted on Meldev)</sub>
</p>

<br>

<!-- LET'S CONNECT -->
<h2 align="center">Let's Build Together</h2>

<p align="center" style="font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;">
  <i>Looking for an engineer who treats your codebase like his own business? Available for hire, collaboration, and building the things that shouldn't wait.</i>
</p>

<div align="center">
  <a href="mailto:godfreydjoseph@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0f172a" />
  </a>
  <a href="https://x.com/ViceVersaAI2024">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=0f172a" />
  </a>
  <a href="https://www.linkedin.com/in/joseph-edomobi-b3b2b43b9">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0f172a" />
  </a>
  <a href="https://meldev.com.ng">
    <img src="https://img.shields.io/badge/Meldev-10b981?style=for-the-badge&logo=cloudflare&logoColor=white&labelColor=0f172a" />
  </a>
</div>

<br>

<!-- FOOTER WAVE -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:f59e0b,50:10b981,100:0ea5e9&height=120&section=footer" />
</div>

<!-- PROFILE VISITS -->
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=joeygoesgrey&style=for-the-badge&color=0ea5e9&labelColor=0f172a" />
</div>
