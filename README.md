<!-- ===========================
     Haibo Xie — Dark Profile
     Copy this complete file into your GitHub profile README.md
     Replace placeholders: your-github-username, your-portfolio-link, your-profile, your-email@example.com
   =========================== -->

<div align="center">
  <!-- Avatar with animated border (SVG) -->
  <!-- Replace the src URL below with your avatar if you want a custom image; GitHub will serve your avatar automatically via: https://github.com/<username>.png -->
  <a href="https://github.com/your-github-username" target="_blank" rel="noopener">
    <svg width="160" height="160" viewBox="0 0 160 160" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Haibo Xie Avatar">
      <defs>
        <clipPath id="circleView">
          <circle cx="80" cy="80" r="66" />
        </clipPath>

        <!-- Animated gradient for border -->
        <linearGradient id="g1" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#7C4DFF">
            <animate attributeName="stop-color" values="#7C4DFF; #00E5FF; #FF7AC6; #7C4DFF" dur="6s" repeatCount="indefinite"/>
          </stop>
          <stop offset="50%" stop-color="#00E5FF">
            <animate attributeName="stop-color" values="#00E5FF; #FF7AC6; #7C4DFF; #00E5FF" dur="6s" repeatCount="indefinite"/>
          </stop>
          <stop offset="100%" stop-color="#FF7AC6">
            <animate attributeName="stop-color" values="#FF7AC6; #7C4DFF; #00E5FF; #FF7AC6" dur="6s" repeatCount="indefinite"/>
          </stop>
        </linearGradient>

        <!-- Border glow filter -->
        <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
          <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
          <feMerge>
            <feMergeNode in="coloredBlur"/>
            <feMergeNode in="SourceGraphic"/>
          </feMerge>
        </filter>
      </defs>

      <!-- Animated ring -->
      <circle cx="80" cy="80" r="74" fill="none" stroke="url(#g1)" stroke-width="6"
              stroke-linecap="round" filter="url(#glow)">
        <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0 80 80" to="360 80 80" dur="14s" repeatCount="indefinite" />
      </circle>

      <!-- Avatar image clipped to circle -->
      <image x="14" y="14" width="132" height="132" preserveAspectRatio="xMidYMid slice"
             xlink:href="https://github.com/your-github-username.png" clip-path="url(#circleView)"/>

      <!-- Subtle inner ring -->
      <circle cx="80" cy="80" r="66" fill="none" stroke="#0f1724" stroke-width="4" />
    </svg>
  </a>

  <h1 style="margin:8px 0 4px 0; color:#E6EEF3;">👋 Hi, I'm <strong style="color:#FFF">Haibo Xie</strong></h1>

  <!-- Typing SVG (animated headline) -->
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=2000&color=FFFFFF&background=0F1724&center=true&width=640&lines=Full-Stack+Developer;Open-Source+Contributor;Cloud+Engineer;Learning+Rust+%26+System+Design" alt="Typing SVG"/>

  <!-- Short bio -->
  <p style="color:#AAB8C7; max-width:700px; margin-top:12px;">
    Full-Stack Developer · Building reliable & scalable cloud apps · Passionate about clean code, system design, and developer experience.
  </p>

  <!-- Badges (Portfolio / LinkedIn / Email) -->
  <p>
    <a href="https://your-portfolio-link" target="_blank" rel="noopener">
      <img alt="portfolio" src="https://img.shields.io/badge/🌐-Portfolio-111827?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgo=" />
    </a>
    <a href="https://linkedin.com/in/your-profile" target="_blank" rel="noopener">
      <img alt="linkedin" src="https://img.shields.io/badge/💼-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:your-email@example.com">
      <img alt="email" src="https://img.shields.io/badge/📧-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
  </p>

  <!-- Visitor count + top-langs small preview -->
  <p style="margin-top:6px;">
    <!-- Visitor badge (live) -->
    <img src="https://visitor-badge.laobi.icu/badge?page_id=your-github-username" alt="visitor badge" />

    <!-- Compact Top Languages (small) -->
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=your-github-username&layout=compact&theme=tokyonight&hide_border=true" alt="top languages" style="margin-left:8px; vertical-align:middle;" />
  </p>
</div>

---

<!-- Dark section background: main details -->
<div style="background: #0b1220; padding:20px; border-radius:12px; margin-top:18px; color:#B9CAD8;">

## 🔭 What I'm Working On
- Building scalable **cloud-native** systems and improving developer DX.
- Learning **Rust** and architectural patterns for high-concurrency services.
- Improving observability & CI/CD pipelines for production systems.

## 🛠️ Tech Stack
- **Frontend:** React, Vue, TypeScript  
- **Backend:** Node.js, Python, PostgreSQL  
- **Infra:** Docker, Kubernetes, AWS (EKS / Lambda)  
- **Other:** GitHub Actions, Terraform, Prometheus / Grafana

## 📊 GitHub Stats
<div align="center">
  <!-- Main GitHub stats (dark theme) -->
  <img src="https://github-readme-stats.vercel.app/api?username=your-github-username&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Haibo's GitHub stats" />

  <!-- Streaks or extra: contribution graph -->
  <img src="https://github-readme-activity-graph.cyclic.app/graph?username=your-github-username&theme=react-dark&hide_border=true" alt="contribution graph" style="margin-top:8px;" />
</div>

## 🚀 Highlights
- Contributor to open-source projects & libraries.
- Experienced building microservices and event-driven systems.
- Focus on reliability, automation, and observability.

## 💬 Quote
> "Great code feels like magic — crafted with persistence and curiosity."

</div>

---

## 🔧 How to customize quickly
1. Replace `your-github-username` with your GitHub username everywhere.  
2. Replace links for portfolio / LinkedIn / email.  
3. Optional: change the typing text by editing the `readme-typing-svg` `lines=` param in the img URL.

---

## ⚙️ Notes & Optional Upgrades
- **Dynamic avatar image** uses `https://github.com/your-github-username.png` — it auto-updates if you change your GitHub avatar.  
- **Typing SVG** uses `readme-typing-svg.herokuapp.com` — you can change fonts/lines/size by modifying the URL params.  
- **Visitor badge** `visitor-badge.laobi.icu` provides a simple counter; some users prefer `visitor-badge.vercel.app` clones — both work.  
- **GitHub Stats** require `your-github-username` to be visible (public profile). If you want private stats included, enable Count Private in the stats service (requires token for some tools).  
- If you want the **colored badges** to perfectly match the dark theme, I can produce a monochrome set for a cleaner look.

---

### ✅ Done — Next?
如果你希望我 **替你把占位符都替换好（包含 username / portfolio / LinkedIn / email）**，把对应内容发给我，我立刻生成已填好信息的最终 README，并再次微调样式（比如更紧凑或更“黑金”风格）。想要我直接替你填好吗？只需回复：

`填好：username, portfolio-link, linkedin-handle, email`

例如：
`填好：xiehaobo, https://haibo.me, xiehaobo, haibo@example.com`

我会立即把最终可直接粘贴的 README 发给你。
