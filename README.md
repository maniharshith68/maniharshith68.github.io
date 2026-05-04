<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=harshith.portfolio&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=40&desc=Personal%20Portfolio%20Website%20%7C%20Data%20Scientist%20%26%20AI%2FML%20Engineer&descAlignY=62&descSize=16" width="100%"/> <br/> <!-- Live site badge — replace URL --> <a href="https://your-portfolio-url.com" target="_blank"> <img src="https://img.shields.io/badge/🌐%20Live%20Site-https://maniharshith68.github.io/-38bdf8?style=for-the-badge"/> </a> &nbsp; <img src="https://img.shields.io/badge/Status-Live%20%26%20Active-06d6a0?style=for-the-badge"/> &nbsp; <img src="https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20Vanilla%20JS-f59e0b?style=for-the-badge"/> &nbsp; <img src="https://img.shields.io/badge/Theme-Dark%20%2F%20Light-8b5cf6?style=for-the-badge"/>
<br/><br/>
<img src="https://img.shields.io/badge/Sections-9-38bdf8?style=flat-square"/> &nbsp; <img src="https://img.shields.io/badge/Projects%20Showcased-8-06d6a0?style=flat-square"/> &nbsp; <img src="https://img.shields.io/badge/Skill%20Groups-7-f59e0b?style=flat-square"/> &nbsp; <img src="https://img.shields.io/badge/No%20Framework-Zero%20Build%20Step-e2e8f0?style=flat-square"/> </div>

📸 Preview
A dark-first, fully responsive, single-page portfolio built for a Data Scientist & AI/ML Engineer — no frameworks, no build step, just one clean index.html.
📸 Add a screenshot here once deployed.
   Recommended: browser fullpage screenshot at 1440px width.
   Tools: GoFullPage (Chrome ext), shot.new, or Firefox screenshot tool.
   Suggested filename: preview.png → drop it in /assets and update this line:
<!-- Uncomment and update once you have a screenshot --> <!-- <img src="assets/preview.png" alt="Portfolio Preview" width="100%"/> -->

🗂️ Repo Structure
```
portfolio/
├── index.html              # Entire site — HTML + CSS + JS in one file
├── professional_photo.png  # Your profile photo (768×1344)
├── harshith_resume.pdf     # Resume (linked in the hero Resume button)
└── README.md               # This file
```

✨ Site Sections
#	Section	Heading	What's Inside
```
1	Hero	—	Name, role, animated avatar rings, stat pills, social links, CTA buttons
2	About	The Data Behind the Developer	Python class code card + bio + open-to-work badges
3	Experience	Battle-Tested in Production	Timeline — Software Engineer & Data Science Intern at LocoNav
4	Projects	Proof of Work	8 project cards with tech tags, GitHub & demo links
5	Skills	The Full Arsenal	7 skill groups, hot-market chips marked ★
6	Strengths	Things I'm Good At	10 strength cards with icons and real descriptions
7	Quotes	Words That Drive the Work	7-quote auto-carousel with fade transition, dot nav, prev/next buttons
8	Contact	Open a Conversation	Link cards + contact form with submit feedback
9	Footer	—	Logo, social icons, copyright
```

🚀 Projects Showcased
```
#	Project	Domain	Key Tech
1	Credit Card Churn Prediction + XAI Dashboard	Finance	XGBoost, SHAP, Streamlit
2	Healthcare Patient Readmission Risk Modeling	Healthcare	XGBoost, SQL, SHAP, AWS
3	NLP Sentiment & Topic Modeling Platform	NLP	DistilBERT, VADER, LDA, spaCy
4	Clinical Radiology Report Generation via Multimodal RAG	Healthcare / GenAI	BioMedCLIP, FAISS, RAG, ViT
5	MLOps Stock Price Forecasting with Drift Monitoring	MLOps	Airflow, Evidently AI, Docker, CI/CD
6	QLoRA Fine-Tuning Pipeline for Medical Q&A	GenAI / LLM	QLoRA, LLaMA-3, PEFT, vLLM, FastAPI
7	NLP-Driven Job Market Intelligence Platform	NLP / LLM	BERTopic, NER, PostgreSQL, OpenAI
8	Automated Time-Series Stock Forecasting with Cloud Deployment	Finance / MLOps	ARIMA, Prophet, PyTorch, ECR
```
🛠️ Features
Visual & Interactive
* Animated particle network canvas — connected nodes, theme-aware color
* Custom magnetic cursor with lagging ring follower
* Scroll-triggered reveal animations on all major elements
* Spinning dashed avatar rings (CSS-only)
* Project card hover lift + gradient top-border reveal
* Skill chip hover glow — ★ amber chips for hot market skills
* 7-quote auto-carousel with fade transition, dot indicators, prev/next nav
Navigation & UX
* Fixed frosted-glass navbar with active section highlighting
* Smooth scroll to all sections
* Mobile hamburger menu
* Back-to-top button (appears after 400px scroll)
* Dark / Light theme toggle — correct rendering in both browser themes
* Fully responsive across all breakpoints
Content
* 8 fully described project cards with category ribbon badges (Featured / MLOps / GenAI / NLP)
* 2-entry professional timeline with per-bullet tech tags
* 7 categorized skill groups with 60+ technologies
* 10 strength cards grounded in real project evidence
* Functional contact form with submit feedback animation
* Dynamic copyright year in footer

⚡ Getting Started
Open Locally — Zero Setup
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
Deploy on GitHub Pages (Free)
git init
git add .
git commit -m "feat: launch portfolio"
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
# Then: repo → Settings → Pages → Branch: main → / (root) → Save
# Live at: https://<your-username>.github.io/<repo-name>/
Deploy on Netlify Drop (Fastest)
1. Go to app.netlify.com/drop
2. Drag your project folder onto the page
3. Instant live URL — no account needed
Deploy on Vercel
npm i -g vercel
vercel --prod

🎨 Customization Reference
Update the Live Site URL
Replace your-portfolio-url.com in both index.html (hero + contact sections) and the badge at the top of this README.
Swap Your Photo
<!-- Already wired to professional_photo.png. If you rename it: -->
<img src="your-new-filename.png" alt="Pic Name"
     style="width:100%;height:100%;object-fit:cover;object-position:center top;border-radius:50%;"/>
object-position: center top keeps your face in frame for portrait photos.
Link Your Resume
Already wired to harshith_resume.pdf. To change:
<a href="your-resume.pdf" class="btn btn-outline" download>
Add a New Project Card
Paste inside .projects-grid in index.html:
<div class="project-card reveal">
  <div class="project-ribbon">GenAI</div>  <!-- optional ribbon -->
  <div class="project-icon"><i class="fa fa-your-icon"></i></div>
  <h3 class="project-title">Project Title</h3>
  <p class="project-desc">2–3 sentences. Problem → method → metric.</p>
  <div class="project-tags">
    <span class="project-tag">Tech 1</span>
    <span class="project-tag">Tech 2</span>
  </div>
  <div class="project-links">
    <a href="GITHUB_URL" target="_blank" class="project-link">
      <i class="fab fa-github"></i> Code
    </a>
    <a href="DEMO_URL" target="_blank" class="project-link">
      <i class="fa fa-external-link-alt"></i> Demo
    </a>
  </div>
</div>
Add a Skill Chip
<span class="skill-chip">Tool Name</span>
<span class="skill-chip hot">★ Trending Tool</span>  <!-- amber highlight -->
Add a Strength Card
<div class="strength-card reveal">
  <div class="strength-icon" style="background:rgba(56,189,248,0.12)">
    <i class="fa fa-icon-name" style="color:var(--accent)"></i>
  </div>
  <h4>Strength Title</h4>
  <p>One or two sentences tied to a real project or outcome.</p>
</div>
Add a Quote
In the <script> block, find the quotes array:
{ text: "Your quote.", author: "Author Name" },
Change the Color Theme
Edit CSS variables in :root (dark mode) and [data-theme="light"]:
Variable	Role
--accent	Cyan — primary highlights, links, borders
--accent2	Teal — secondary accents
--accent3	Amber — ★ hot skill chips, ribbons
--bg / --bg2	Page background layers
--surface / --surface2	Card backgrounds
--text / --text2 / --text3	Text hierarchy
📱 Responsive Breakpoints
Breakpoint	Layout
> 900px	2-column hero, about, contact
≤ 900px	Single column; hero visual stacks above text
≤ 700px	Hamburger nav; projects single column; strengths 2-col
≤ 480px	Strengths single column; avatar 200px; reduced padding
📦 Dependencies
All via CDN — no npm, no build step, no node_modules.
Library	Version	Purpose
Font Awesome	6.5.0	All icons
Google Fonts — Syne	latest	Display headings
Google Fonts — DM Mono	latest	Body, code, UI text
Google Fonts — Instrument Serif	latest	Quote text, role tagline
🔗 Connect
<div align="left">
￼
 
￼
 
￼
 
￼
</div>

<div align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/> <sub>Built with ♥ and a lot of data — Harshith Bhattaram · NY, USA</sub> </div>
