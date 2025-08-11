<!-- ===================== HERO: Animated Gradient Title ===================== -->
<p align="center">
  <!-- Animated gradient text (SVG) -->
  <svg width="100%" height="120" viewBox="0 0 1200 120" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Yash Ghavghave">
    <defs>
      <linearGradient id="g1" x1="0" x2="1">
        <stop offset="0%" stop-color="#ff6a88">
          <animate attributeName="stop-color" values="#ff6a88;#ff9a6a;#9b5de5;#ff6a88" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="50%" stop-color="#9b5de5">
          <animate attributeName="stop-color" values="#9b5de5;#38ef7d;#ff6a88;#9b5de5" dur="6s" repeatCount="indefinite"/>
        </stop>
        <stop offset="100%" stop-color="#38ef7d">
          <animate attributeName="stop-color" values="#38ef7d;#ff6a88;#ff9a6a;#38ef7d" dur="6s" repeatCount="indefinite"/>
        </stop>
      </linearGradient>

      <!-- soft glow filter -->
      <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <rect width="100%" height="100%" fill="transparent" />

    <text x="50%" y="55%" text-anchor="middle" dominant-baseline="middle"
          font-family="Orbitron, Roboto, sans-serif" font-size="44" fill="url(#g1)"
          style="letter-spacing:2px; font-weight:700;" filter="url(#glow)">
      Yash Ghavghave — Developer & ML Engineer
      <animate attributeName="opacity" values="0;1;1;0.9;1" dur="5s" repeatCount="indefinite"/>
    </text>

    <!-- moving underline glow -->
    <rect x="30%" y="75" width="40%" height="6" rx="3" fill="url(#g1)" opacity="0.8">
      <animate attributeName="x" values="30%;32%;30%" dur="4s" repeatCount="indefinite"/>
      <animate attributeName="width" values="40%;42%;40%" dur="4s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<!-- ===================== TYPING SUBTITLE ===================== -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=800&color=FF7A9A&center=true&vCenter=true&width=760&lines=Building+AI+systems+%E2%80%A2+Rust+%26+Python+%E2%80%A2+Full-stack+engineering" alt="subtitle" />
</p>

<!-- ===================== LIGHTING DIVIDER ===================== -->
<p align="center">
  <!-- animated gradient divider (SVG) -->
  <svg width="90%" height="18" viewBox="0 0 1200 18" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="d1"><stop offset="0%" stop-color="#ff6a88"/><stop offset="50%" stop-color="#9b5de5"/><stop offset="100%" stop-color="#38ef7d"/></linearGradient>
      <linearGradient id="d2"><stop offset="0%" stop-color="#ffffff" stop-opacity="0"/><stop offset="50%" stop-color="#ffffff" stop-opacity="0.06"/><stop offset="100%" stop-color="#ffffff" stop-opacity="0"/></linearGradient>
      <filter id="blur"><feGaussianBlur stdDeviation="6" /></filter>
    </defs>
    <rect x="0" y="2" rx="9" width="100%" height="14" fill="url(#d1)" opacity="0.25"/>
    <rect x="-20" y="0" rx="9" width="20%" height="14" fill="url(#d2)" filter="url(#blur)">
      <animate attributeName="x" from="-20" to="1200" dur="4s" repeatCount="indefinite" />
    </rect>
  </svg>
</p>

---

## About
<div align="center">
  <!-- animated gradient card (SVG inside HTML for effect) -->
  <svg width="95%" height="110" viewBox="0 0 1000 110" xmlns="http://www.w3.org/2000/svg" style="max-width:1000px">
    <defs>
      <linearGradient id="cardGrad" x1="0" x2="1">
        <stop offset="0%" stop-color="#2dd4bf"/><stop offset="100%" stop-color="#8b5cf6"/>
      </linearGradient>
      <filter id="soft" x="-50%" y="-50%" width="200%" height="200%">
        <feDropShadow dx="0" dy="8" stdDeviation="18" flood-color="#000" flood-opacity="0.18"/>
      </filter>
    </defs>

    <rect x="0" y="0" rx="12" width="100%" height="100%" fill="url(#cardGrad)" opacity="0.12"/>
    <g font-family="Inter, Roboto, sans-serif" fill="#fff" font-weight="600">
      <text x="40" y="36" font-size="20" fill="#fff">I build performant systems & ML pipelines —</text>
      <text x="40" y="62" font-size="14" fill="#f1f1f1">From production-ready Rust CLI tools to scalable AI services.</text>
      <text x="40" y="86" font-size="13" fill="#e8e8e8">Currently exploring advanced ML architectures, model infra, and ML+web integration.</text>
    </g>
    <!-- subtle moving light -->
    <rect x="-120" y="0" width="220" height="110" rx="12" fill="white" opacity="0.02">
      <animate attributeName="x" from="-220" to="1000" dur="6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.00;0.05;0.00" dur="6s" repeatCount="indefinite"/>
    </rect>
  </svg>
</div>

---

## Skills & Technologies

<p align="center">
  <!-- Grid of SVG skill badges; each badge pulses/glows -->
  <svg width="100%" height="220" viewBox="0 0 1000 220" xmlns="http://www.w3.org/2000/svg" style="max-width:1000px">
    <defs>
      <filter id="glo" x="-50%" y="-50%" width="200%" height="200%">
        <feGaussianBlur stdDeviation="6" result="b"/>
        <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>

      <linearGradient id="p1"><stop offset="0%" stop-color="#FF7A9A"/><stop offset="100%" stop-color="#FFB86B"/></linearGradient>
      <linearGradient id="p2"><stop offset="0%" stop-color="#9B5DE5"/><stop offset="100%" stop-color="#38EF7D"/></linearGradient>
      <linearGradient id="p3"><stop offset="0%" stop-color="#00C9FF"/><stop offset="100%" stop-color="#92FE9D"/></linearGradient>
      <linearGradient id="p4"><stop offset="0%" stop-color="#FF6A88"/><stop offset="100%" stop-color="#845EC2"/></linearGradient>
      <linearGradient id="p5"><stop offset="0%" stop-color="#F9D423"/><stop offset="100%" stop-color="#FF4E50"/></linearGradient>

      <!-- animate vertical float -->
      <g id="badge">
        <rect x="0" y="0" width="160" height="44" rx="10" fill="#111827" opacity="0.9"/>
        <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, Roboto, sans-serif" fill="#fff" font-weight="700"></text>
      </g>
    </defs>

    <!-- Row 1 -->
    <g transform="translate(60,30)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="url(#p1)" filter="url(#glo)" opacity="0.95"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#111827" font-weight="800">Python</text>
      <!-- pulse -->
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="url(#p1)" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.12;0.06" dur="3s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(260,30)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="url(#p2)" filter="url(#glo)" opacity="0.94"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#fff" font-weight="800">JavaScript</text>
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="url(#p2)" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.14;0.06" dur="3.4s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(460,30)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="url(#p3)" filter="url(#glo)" opacity="0.93"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#052328" font-weight="800">Rust</text>
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="url(#p3)" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.10;0.06" dur="3.2s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(660,30)">
      <rect x="0" y="0" rx="12" width="200" height="44" fill="url(#p4)" filter="url(#glo)" opacity="0.95"/>
      <text x="100" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#fff" font-weight="800">Machine Learning</text>
      <rect x="-10" y="-10" width="220" height="64" rx="14" fill="url(#p4)" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.12;0.06" dur="3.6s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- Row 2 -->
    <g transform="translate(60,110)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="url(#p5)" filter="url(#glo)" opacity="0.95"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#111827" font-weight="800">React</text>
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="url(#p5)" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.12;0.06" dur="3s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(260,110)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="#7f7fd5" filter="url(#glo)" opacity="0.94"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#fff" font-weight="800">Tailwind CSS</text>
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="#7f7fd5" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.14;0.06" dur="3.4s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(460,110)">
      <rect x="0" y="0" rx="12" width="160" height="44" fill="#ff9a6a" filter="url(#glo)" opacity="0.94"/>
      <text x="80" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#111827" font-weight="800">Docker</text>
      <rect x="-10" y="-10" width="180" height="64" rx="14" fill="#ff9a6a" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.12;0.06" dur="3.1s" repeatCount="indefinite"/>
      </rect>
    </g>

    <g transform="translate(660,110)">
      <rect x="0" y="0" rx="12" width="200" height="44" fill="#6de7ff" filter="url(#glo)" opacity="0.95"/>
      <text x="100" y="28" text-anchor="middle" font-size="14" font-family="Inter, sans-serif" fill="#052328" font-weight="800">Databases & DevOps</text>
      <rect x="-10" y="-10" width="220" height="64" rx="14" fill="#6de7ff" opacity="0.06">
        <animate attributeName="opacity" values="0.06;0.12;0.06" dur="3.5s" repeatCount="indefinite"/>
      </rect>
    </g>
  </svg>
</p>

---

## Featured Projects

<div align="center">
  <svg width="95%" height="170" viewBox="0 0 1000 170" xmlns="http://www.w3.org/2000/svg" style="max-width:1000px">
    <defs>
      <linearGradient id="card1" x1="0" x2="1"><stop offset="0" stop-color="#ff9a6a"/><stop offset="1" stop-color="#ff6a88"/></linearGradient>
      <linearGradient id="card2" x1="0" x2="1"><stop offset="0" stop-color="#9b5de5"/><stop offset="1" stop-color="#38ef7d"/></linearGradient>
      <filter id="cardShadow"><feDropShadow dx="0" dy="10" stdDeviation="20" flood-opacity="0.12"/></filter>
    </defs>

    <!-- Project Card 1 -->
    <g transform="translate(30,20)" filter="url(#cardShadow)">
      <rect x="0" y="0" rx="12" width="460" height="130" fill="url(#card1)"/>
      <text x="22" y="36" font-family="Inter, sans-serif" font-size="18" fill="#fff" font-weight="800">AI Chatbot (adaptive)</text>
      <text x="22" y="62" font-family="Inter, sans-serif" font-size="12" fill="#fff">Real-time NLP with online adaptive pipelines.</text>
      <text x="22" y="86" font-family="Inter, sans-serif" font-size="12" fill="#fff" opacity="0.9">Stack: Python, FastAPI, Transformers</text>
    </g>

    <!-- Project Card 2 -->
    <g transform="translate(510,20)" filter="url(#cardShadow)">
      <rect x="0" y="0" rx="12" width="460" height="130" fill="url(#card2)"/>
      <text x="22" y="36" font-family="Inter, sans-serif" font-size="18" fill="#fff" font-weight="800">Realtime Analytics Dashboard</text>
      <text x="22" y="62" font-family="Inter, sans-serif" font-size="12" fill="#fff">Stream metrics and visual insights with minimal latency.</text>
      <text x="22" y="86" font-family="Inter, sans-serif" font-size="12" fill="#fff" opacity="0.9">Stack: React, Node, WebSocket</text>
    </g>
  </svg>
</div>

---

## GitHub Pulse
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yashghavghave&show_icons=false&theme=tokyonight&hide_border=true" width="45%" alt="stats"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yashghavghave&theme=tokyonight&hide_border=true" width="45%" alt="streak"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yashghavghave&theme=react-dark&hide_border=true&area=true" width="90%" alt="activity"/>
</p>

---

## Fun Facts
<details>
<summary>Reveal</summary>

- Debugging is meditative.  
- Coffee fuels my focus.  
- Dream: anime-styled AI assistant.

</details>

---

<!-- subtle bottom glow bar -->
<p align="center">
  <svg width="100%" height="18" viewBox="0 0 1200 18" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="glowbar"><stop offset="0%" stop-color="#ff6a88"/><stop offset="50%" stop-color="#9b5de5"/><stop offset="100%" stop-color="#38ef7d"/></linearGradient>
      <filter id="bblur"><feGaussianBlur stdDeviation="12"/></filter>
    </defs>
    <rect x="0" y="2" rx="9" width="100%" height="14" fill="#0b1220" opacity="0.6"/>
    <rect x="-300" y="0" width="400" height="18" rx="9" fill="url(#glowbar)" filter="url(#bblur)" opacity="0.9">
      <animate attributeName="x" from="-400" to="1200" dur="5s" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yashghavghave&style=for-the-badge&color=brightgreen&label=Profile+Views" alt="views" />
</p>
