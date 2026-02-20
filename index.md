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

/* Remove GitHub constraints */
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
  width:min(1150px, calc(100vw - 80px));
  margin:0 auto;
  padding:80px 0;
}

.section{
  margin:120px 0;
}

.section-title{
  font-size:14px;
  letter-spacing:.2em;
  text-transform:uppercase;
  color:rgba(255,255,255,.6);
  margin-bottom:10px;
}

h1{
  font-size:56px;
  font-weight:800;
  margin:0 0 15px 0;
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
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  border-radius:999px;
  margin:20px 0 35px 0;
}

p{
  font-size:19px;
  line-height:1.9;
  color:var(--muted);
  margin-bottom:22px;
}

.card{
  background:linear-gradient(180deg,rgba(17,26,47,.95),rgba(15,23,42,.9));
  border:1px solid var(--border);
  border-radius:18px;
  padding:45px;
  margin-bottom:40px;
  box-shadow:0 20px 60px rgba(0,0,0,.35);
}

.card h3{
  font-size:24px;
  margin:0 0 8px 0;
}

.meta{
  font-size:15px;
  color:rgba(255,255,255,.6);
  margin-bottom:14px;
}

.smalllink{
  font-size:15px;
  margin:0 0 16px 0;
}

ul{
  padding-left:24px;
  margin-top:15px;
}

li{
  margin-bottom:14px;
  font-size:18px;
  line-height:1.8;
  color:var(--muted);
}

.tags{
  margin-top:20px;
  font-size:15px;
  color:rgba(255,255,255,.6);
}

.skill-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:35px;
}

.contact{
  text-align:center;
  margin-top:120px;
}

.contact h3{
  font-size:28px;
  margin-bottom:25px;
}

.contact-list{
  list-style:none;
  padding:0;
}

.contact-list li{
  margin:18px 0;
  font-size:18px;
}

a{
  color:var(--accent2);
  text-decoration:none;
}

a:hover{ text-decoration:underline; }

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
  I am a Master’s graduate in Artificial Intelligence at the University at Buffalo with 5+ years of professional software engineering experience across backend systems and distributed architectures. My industry background shaped how I approach systems — focusing on reliability, scalability, and thoughtful design.
  </p>

  <p>
  During my graduate studies, I collaborated with Machinery Monitoring Systems LLC on a predictive maintenance project involving real motor hardware, vibration data acquisition, structured experimentation, and iterative deep learning refinement under real-world constraints.
  </p>

  <p>
  Through coursework and personal projects, I built LLM-powered systems including a Retrieval-Augmented Generation (RAG) conversational assistant and an agentic multimodal retrieval system combining semantic search, vector embeddings, hybrid retrieval, and agent-based reasoning.
  </p>

  <p>
  I am focused on building practical deep learning and Generative AI systems, particularly RAG and agent-based architectures designed for measurable, reliable real-world deployment.
  </p>
</div>

<!-- SKILLS -->
<div class="section">
  <div class="section-title">Technical Skills</div>
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
      <p>RAG · ReAct Agents · Prompt Engineering · OpenCLIP · LangChain · ChromaDB · OpenAI API</p>
    </div>

    <div class="card">
      <h3>Data & Systems</h3>
      <p>Pandas · NumPy · OpenCV · PySpark · Hadoop</p>
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
    <h3>Deep Learning-Based Predictive Maintenance of Rotating Machinery</h3>
    <div class="meta">(University – Industry Collaboration)</div>
    <ul>
      <li>Engineered a triaxial vibration data acquisition pipeline on a custom rotor test rig, generating 100K+ vibration signals across multiple fault conditions.</li>
      <li>Developed a custom dual-encoder 1D CNN combining time-domain waveforms with FFT-based frequency features using channel-wise attention mechanisms.</li>
      <li>Implemented multi-window signal processing to capture fault progression trends and reduce sensitivity to transient noise.</li>
      <li>Applied contrastive self-supervised pretraining, achieving 91% downstream classification accuracy while reducing labeled data dependence.</li>
    </ul>
    <div class="tags">PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention</div>
  </div>

  <div class="card">
    <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>
    <div class="smalllink"><a href="https://github.com/abc/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git">View Source Code</a></div>
    <ul>
      <li>Developed an agentic multimodal RAG system using OpenCLIP, LangChain, ChromaDB, and OpenAI API, indexing 8K+ image-text pairs.</li>
      <li>Achieved 84.5% Recall@5 and 0.81 MRR on text-to-image retrieval evaluation.</li>
      <li>Architected a ReAct-based LLM agent with tool-driven retrieval and grounded reasoning, achieving 9.06/10 faithfulness and 3.3% refusal rate.</li>
      <li>Designed a hybrid ranking pipeline combining dense embeddings with lexical re-scoring to reduce semantic drift and improve grounding robustness.</li>
      <li>Implemented CUDA-accelerated embedding and batch indexing workflow for scalable high-dimensional vector storage.</li>
      <li>Developed an evaluation framework measuring retrieval accuracy and LLM generation quality to ensure grounding and reliability.</li>
    </ul>
    <div class="tags">OpenCLIP · LangChain · ChromaDB · LLM Agents · Hybrid Retrieval</div>
  </div>

  <div class="card">
    <h3>LLM-Powered RAG Conversational Assistant (Wikipedia)</h3>
    <ul>
      <li>Built an LLM-powered conversational assistant using Retrieval-Augmented Generation (RAG) over Wikipedia content.</li>
      <li>Combined semantic search, vector embeddings, and retrieval evaluation to generate grounded, reliable responses.</li>
      <li>Integrated tool-based reasoning patterns to reduce hallucinations and improve answer traceability.</li>
    </ul>
    <div class="tags">RAG · Semantic Search · Vector Embeddings · Grounded Generation</div>
  </div>

  <div class="card">
    <h3>Scene Recognition with Deep CNNs (MIT Indoor67)</h3>
    <div class="smalllink"><a href="https://github.com/abc/Scene-Recognition-with-Deep-CNNs">View Source Code</a></div>
    <ul>
      <li>Implemented a custom DenseNet-like teacher model from scratch and improved representation quality using SE blocks.</li>
      <li>Built a lighter Hybrid CNN + SE student model and applied knowledge distillation to learn richer decision boundaries.</li>
      <li>Ensembled predictions across models (teacher + distilled student + additional CNN variants) to improve robustness.</li>
      <li>Achieved a project-high 76% F1-score with soft and weighted ensemble voting.</li>
    </ul>
    <div class="tags">PyTorch · CNN · SE Blocks · Knowledge Distillation · Ensemble Learning</div>
  </div>

  <div class="card">
    <h3>Sustainable Energy Management in Smart Homes (CityLearn RL)</h3>
    <div class="smalllink"><a href="https://github.com/abc/Sustainable-Energy-Management-with-Reinforcement-Learning.git">View Source Code</a></div>
    <ul>
      <li>Explored intelligent battery storage control in CityLearn environment to minimize energy cost and carbon emissions.</li>
      <li>Implemented and compared Rule Based Control, PPO, and SAC agents.</li>
      <li>SAC achieved best energy efficiency and lowest peak demand across experiments.</li>
    </ul>
    <div class="tags">PyTorch · CityLearn · Reinforcement Learning · PPO · SAC</div>
  </div>

</div>

<!-- PROFESSIONAL -->
<div class="section">
  <div class="section-title">Professional Experience</div>
  <h2 class="accent">Industry Background</h2>
  <div class="rule"></div>

  <div class="card">
    <h3>Tata Consultancy Services, India | IT Analyst</h3>
    <div class="meta">Apr 2018 – Dec 2019</div>
    <ul>
      <li>Developed and maintained Java-based backend systems supporting trade management and settlement workflows.</li>
      <li>Optimized SQL queries and stored procedures for large relational databases, improving execution efficiency and reliability in production environments.</li>
      <li>Collaborated in an Agile environment to meet project objectives and deliver results within tight deadlines.</li>
    </ul>
  </div>

  <div class="card">
    <h3>Capgemini, India | Associate Consultant</h3>
    <div class="meta">Nov 2013 – Mar 2018</div>
    <ul>
      <li>Designed and implemented RESTful Java microservices for operational dashboards and support workflows.</li>
      <li>Provided production support and debugging for distributed systems, resolving performance bottlenecks and integration issues.</li>
    </ul>
  </div>
</div>

<!-- CONTACT -->
<div class="contact">
  <h3>Contact</h3>
  <p>
    Email: sarayusd31@gmail.com &nbsp;&nbsp;|&nbsp;&nbsp;
    GitHub: <a href="https://github.com/sarayusd">https://github.com/sarayusd</a> &nbsp;&nbsp;|&nbsp;&nbsp;
    LinkedIn: <a href="https://www.linkedin.com/in/sarayusd/">https://www.linkedin.com/in/sarayusd/</a>
  </p>
</div>



