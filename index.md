---
layout: default
title: Sarayu Sivakumar Dhaya
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#070b18;
  --panel:#111a2f;
  --border:rgba(255,255,255,.10);
  --text:#e6edf7;
  --muted:#b3c0d4;
  --accent:#22c55e;
  --accent2:#38bdf8;
}

*{ box-sizing:border-box; }

html, body{
  margin:0;
  padding:0;
  font-family:'Inter',sans-serif;
  color:var(--text);
  background:
    radial-gradient(1200px 600px at 20% 10%, rgba(56,189,248,.20), transparent 60%),
    radial-gradient(1000px 600px at 80% 20%, rgba(34,197,94,.15), transparent 60%),
    linear-gradient(180deg,#060913 0%,#070b18 100%);
  overflow-x:hidden;
}

/* Remove GitHub container constraints */
.main-content,
.container,
.container-lg,
.markdown-body,
article{
  max-width:none !important;
  padding:0 !important;
  margin:0 !important;
}

/* Remove GitHub footer */
footer,
.site-footer,
.page-footer{
  display:none !important;
}

.wrapper{
  width:min(1200px, calc(100vw - 80px));
  margin:0 auto;
  padding:80px 0;
}

.section{
  margin:100px 0;
}

.section-title{
  font-size:14px;
  letter-spacing:.2em;
  text-transform:uppercase;
  color:rgba(255,255,255,.6);
  margin-bottom:12px;
}

h1{
  font-size:56px;
  font-weight:800;
  letter-spacing:-.02em;
  margin:0 0 10px 0;
}

h2{
  font-size:42px;
  font-weight:700;
  margin:0 0 20px 0;
}

.accent{
  color:var(--accent);
}

.rule{
  width:80px;
  height:3px;
  border-radius:999px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  margin:20px 0 30px 0;
}

p{
  font-size:19px;
  line-height:1.9;
  color:var(--muted);
  margin-bottom:20px;
}

.card{
  background:linear-gradient(180deg,rgba(17,26,47,.95),rgba(15,23,42,.9));
  border:1px solid var(--border);
  border-radius:18px;
  padding:40px;
  margin-bottom:30px;
  box-shadow:0 15px 50px rgba(0,0,0,.35);
}

.card h3{
  margin:0 0 10px 0;
  font-size:22px;
}

.meta{
  color:rgba(255,255,255,.6);
  font-size:15px;
  margin-bottom:15px;
}

ul{
  padding-left:22px;
  margin:15px 0;
}

li{
  margin-bottom:12px;
  font-size:18px;
  line-height:1.7;
  color:var(--muted);
}

.tags{
  margin-top:15px;
  font-size:15px;
  color:rgba(255,255,255,.6);
}

.skill-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:30px;
}

.contact{
  text-align:center;
  margin-top:120px;
}

.contact h3{
  font-size:26px;
  margin-bottom:25px;
}

.contact-list{
  list-style:none;
  padding:0;
}

.contact-list li{
  margin:15px 0;
  font-size:18px;
}

a{
  color:var(--accent2);
  text-decoration:none;
}

a:hover{
  text-decoration:underline;
}

@media(max-width:900px){
  .wrapper{ width:calc(100vw - 40px); }
  h1{ font-size:40px; }
  h2{ font-size:30px; }
  .skill-grid{ grid-template-columns:1fr; }
}
</style>

<div class="wrapper">

<!-- HERO -->
<div class="section">
  <h1>Sarayu Sivakumar Dhaya</h1>
  <p>MS in Artificial Intelligence (Dec 2025) · 5+ Years Software Engineering Experience</p>
</div>

<!-- SUMMARY -->
<div class="section">
  <div class="section-title">Summary</div>
  <h2 class="accent">Applied AI · Deep Learning · LLM Systems</h2>
  <div class="rule"></div>

  <p>
  I am a Master’s graduate in Artificial Intelligence at the University at Buffalo with 5+ years of professional software engineering experience across backend systems and distributed architectures. My industry background shaped how I approach systems — with a focus on reliability, scalability, and thoughtful design.
  </p>

  <p>
  During my graduate studies, I collaborated with Machinery Monitoring Systems LLC on a predictive maintenance project involving real motor hardware, vibration data collection, and iterative deep learning model refinement under real-world constraints.
  </p>

  <p>
  Through coursework and personal projects, I built LLM-powered systems including a Retrieval-Augmented Generation (RAG) conversational assistant and an agentic multimodal retrieval system combining vector embeddings, hybrid retrieval, and agent-based reasoning.
  </p>

  <p>
  I am focused on building practical deep learning and LLM-based systems, particularly in Generative AI, RAG, and agent architectures designed for real-world deployment.
  </p>
</div>

<!-- SKILLS -->
<div class="section">
  <div class="section-title">Skills</div>
  <h2 class="accent">Tooling & Frameworks</h2>
  <div class="rule"></div>

  <div class="skill-grid">
    <div class="card">
      <h3>Programming</h3>
      <p>Python · Java · SQL</p>
    </div>

    <div class="card">
      <h3>Deep Learning & AI</h3>
      <p>PyTorch · TensorFlow · Scikit-learn · Computer Vision · NLP</p>
    </div>

    <div class="card">
      <h3>LLMs & Generative AI</h3>
      <p>RAG · ReAct Agents · OpenCLIP · LangChain · ChromaDB · OpenAI API</p>
    </div>

    <div class="card">
      <h3>Systems & Deployment</h3>
      <p>Docker · Kubernetes · CI/CD · CUDA · GPU Training</p>
    </div>
  </div>
</div>

<!-- PROJECTS -->
<div class="section">
  <div class="section-title">Project Experience</div>
  <h2 class="accent">Selected Work</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Deep Learning-Based Predictive Maintenance</h3>
    <div class="meta">(University – Industry Collaboration)</div>
    <ul>
      <li>Engineered a triaxial vibration data pipeline generating 100K+ signals across multiple fault conditions.</li>
      <li>Developed a dual-encoder 1D CNN combining time-domain and FFT features with attention mechanisms.</li>
      <li>Applied contrastive self-supervised pretraining achieving 91% downstream accuracy.</li>
    </ul>
    <div class="tags">PyTorch · Signal Processing · Self-Supervised Learning</div>
  </div>

  <div class="card">
    <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>
    <ul>
      <li>Built an agentic RAG system indexing 8K+ image-text pairs.</li>
      <li>Achieved 84.5% Recall@5 and 0.81 MRR in retrieval evaluation.</li>
      <li>Designed hybrid ranking and evaluation frameworks for grounded LLM reasoning.</li>
    </ul>
    <div class="tags">OpenCLIP · LangChain · ChromaDB · LLM Agents</div>
  </div>
</div>

<!-- PROFESSIONAL -->
<div class="section">
  <div class="section-title">Professional Experience</div>
  <h2 class="accent">Industry Background</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Tata Consultancy Services | IT Analyst</h3>
    <div class="meta">Apr 2018 – Dec 2019</div>
    <ul>
      <li>Developed Java backend systems for trade management and settlement workflows.</li>
      <li>Optimized SQL queries and stored procedures for high-volume databases.</li>
    </ul>
  </div>

  <div class="card">
    <h3>Capgemini | Associate Consultant</h3>
    <div class="meta">Nov 2013 – Mar 2018</div>
    <ul>
      <li>Designed RESTful Java microservices for operational dashboards.</li>
      <li>Provided production support and resolved distributed system issues.</li>
    </ul>
  </div>
</div>

<!-- CONTACT -->
<div class="contact">
  <h3>Contact</h3>
  <ul class="contact-list">
    <li><strong>Email:</strong> sarayusd31@gmail.com</li>
    <li><strong>GitHub:</strong> <a href="https://github.com/sarayusd">https://github.com/sarayusd</a></li>
    <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sarayusd/">https://www.linkedin.com/in/sarayusd/</a></li>
  </ul>
</div>


