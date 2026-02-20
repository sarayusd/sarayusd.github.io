---
layout: default
title: Sarayu Sivakumar Dhaya
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

:root{
  --bg:#0a0f1f;
  --card:#121a2e;
  --border:rgba(255,255,255,0.08);
  --text:#e2e8f0;
  --muted:#94a3b8;
  --accent:#22c55e;
}

*{ box-sizing:border-box; }

/* ---- Remove GitHub theme layout constraints ---- */
.main-content,
.page-content,
.container-lg,
.markdown-body,
article{
  max-width:none !important;
  padding:0 !important;
  margin:0 !important;
  overflow:visible !important;
}

/* ---- Remove GitHub footer ---- */
footer,
.site-footer,
.page-footer{
  display:none !important;
}

/* ---- Remove extra bottom space ---- */
body{
  margin:0;
  padding:0;
  font-family:'Inter',sans-serif;
  background:radial-gradient(circle at 20% 20%, #0f1a3a 0%, #0a0f1f 50%, #050814 100%);
  color:var(--text);
  overflow-x:hidden;
}

/* ---- Center content properly ---- */
.container{
  width:min(1320px, calc(100vw - 80px));
  margin:0 auto;
  padding:80px 0 60px 0;
}

/* ---- Section spacing ---- */
.section{
  margin:100px 0;
}

/* ---- Headings ---- */
h2{
  font-size:34px;
  font-weight:750;
  margin:0 0 18px 0;
  letter-spacing:-0.02em;
}

.section-title{
  color:var(--accent);
  font-size:15px;
  letter-spacing:2px;
  text-transform:uppercase;
  margin-bottom:16px;
}

/* ---- Summary Layout ---- */
.summary-grid{
  display:grid;
  grid-template-columns:1.6fr 1fr;
  gap:60px;
  align-items:start;
}

.summary-text p{
  color:var(--muted);
  line-height:1.8;
  font-size:17px;
  margin-bottom:22px;
}

/* ---- Core Focus Box ---- */
.focus-box{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:16px;
  padding:32px;
}

.focus-box h4{
  font-size:14px;
  letter-spacing:2px;
  text-transform:uppercase;
  color:var(--muted);
  margin-bottom:20px;
}

.focus-box p{
  padding:14px 0;
  border-bottom:1px solid var(--border);
  margin:0;
}

.focus-box p:last-child{
  border-bottom:none;
}

/* ---- Skill Grid ---- */
.skill-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:30px;
}

.card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:16px;
  padding:30px;
  transition:0.3s ease;
}

.card:hover{
  border-color:var(--accent);
  transform:translateY(-4px);
}

.skill-tags{
  margin-top:18px;
  display:flex;
  flex-wrap:wrap;
  gap:10px;
}

.tag{
  background:rgba(255,255,255,0.05);
  padding:8px 14px;
  border-radius:20px;
  font-size:14px;
  color:var(--muted);
}

/* ---- Project Layout ---- */
.project-grid{
  display:grid;
  gap:28px;
  max-width:1100px;
  margin:0 auto;
}

.project-card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:18px;
  padding:40px;
}

.project-card h3{
  color:var(--accent);
  margin-bottom:10px;
}

.project-card ul{
  margin-top:18px;
  padding-left:20px;
}

.project-card li{
  margin-bottom:14px;
  color:var(--muted);
  line-height:1.7;
}

/* ---- Professional Section ---- */
.prof-grid{
  display:grid;
  gap:24px;
  max-width:1100px;
  margin:0 auto;
}

.prof-card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:16px;
  padding:30px;
}

/* ---- Contact Section ---- */
.contact{
  text-align:center;
  margin-top:80px;
  padding-bottom:0;
}

.contact a{
  color:var(--accent);
  text-decoration:none;
  font-weight:600;
}

.contact a:hover{
  text-decoration:underline;
}

/* ---- Responsive ---- */
@media(max-width:1000px){
  .summary-grid{
    grid-template-columns:1fr;
  }

  .skill-grid{
    grid-template-columns:1fr;
  }

  .container{
    width:calc(100vw - 40px);
  }
}
</style>

<div class="container">

  <!-- SUMMARY -->
  <div class="section summary">
    <div class="kicker">Summary</div>
    <h2>Applied AI · Deep Learning · LLM Systems</h2>
    <div class="divider"></div>

    <div class="summary-grid">
      <div>
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

      <!-- Keep this block OR delete it if you don't want Core Focus -->
      <div class="core">
        <div class="title">Core Focus</div>
        <div class="item">Deep Learning</div>
        <div class="item">Large Language Models</div>
        <div class="item">Generative AI</div>
        <div class="item">RAG & Agents</div>
      </div>
    </div>
  </div>

  <!-- TECHNICAL SKILLS -->
  <div class="section">
    <div class="kicker">Technical Skills</div>
    <h2>Tooling and frameworks I work with</h2>
    <div class="divider"></div>

    <div class="skills-grid">
      <div class="card">
        <div class="skill-title">Programming</div>
        <div class="chips">
          <span class="chip">Python</span>
          <span class="chip">Java</span>
          <span class="chip">SQL</span>
        </div>
      </div>

      <div class="card">
        <div class="skill-title">Deep Learning & AI</div>
        <div class="chips">
          <span class="chip">PyTorch</span>
          <span class="chip">TensorFlow</span>
          <span class="chip">Scikit-learn</span>
          <span class="chip">Computer Vision</span>
          <span class="chip">NLP</span>
        </div>
      </div>

      <div class="card">
        <div class="skill-title">LLMs & Generative AI</div>
        <div class="chips">
          <span class="chip">RAG</span>
          <span class="chip">ReAct Agents</span>
          <span class="chip">OpenCLIP</span>
          <span class="chip">LangChain</span>
          <span class="chip">ChromaDB</span>
          <span class="chip">OpenAI API</span>
        </div>
      </div>

      <div class="card">
        <div class="skill-title">Systems & Deployment</div>
        <div class="chips">
          <span class="chip">Docker</span>
          <span class="chip">Kubernetes</span>
          <span class="chip">CI/CD</span>
          <span class="chip">CUDA</span>
          <span class="chip">GPU Training</span>
        </div>
      </div>
    </div>
  </div>

  <!-- PROJECT EXPERIENCE -->
  <div class="section">
    <div class="kicker">Project Experience</div>

    <div class="divider"></div>

    <div class="project-grid">

      <div class="card">
        <h3>Deep Learning-Based Predictive Maintenance of Rotating Machinery</h3>
        <div class="meta">(University - Industry Collaboration)</div>
        <ul>
          <li>Engineered a triaxial vibration data acquisition pipeline on a custom rotor test rig, generating <strong>100K+ vibration signals</strong> across multiple fault conditions.</li>
          <li>Developed a custom <strong>dual-encoder 1D CNN</strong> combining time-domain waveforms with FFT-based frequency features using channel-wise attention mechanisms.</li>
          <li>Implemented multi-window signal processing to capture fault progression trends and reduce sensitivity to transient noise.</li>
          <li>Applied <strong>contrastive self-supervised pretraining</strong>, achieving <strong>91% downstream classification accuracy</strong> while reducing labeled data dependence.</li>
        </ul>
        <div class="techline"><strong>Tech:</strong> PyTorch · Signal Processing · Self-Supervised Learning · CNN Architectures · Attention</div>
      </div>

      <div class="card">
        <h3>Agentic Multimodal RAG with Hybrid Retrieval</h3>
        <div class="meta"><a href="https://github.com/abc/Agentic-Multimodal-RAG-with-Hybrid-Retrieval.git" target="_blank">View Source Code</a></div>
        <ul>
          <li>Built an agentic multimodal Retrieval-Augmented Generation system using OpenCLIP, LangChain, ChromaDB, and OpenAI API, indexing <strong>8K+ image-text pairs</strong>.</li>
          <li>Achieved <strong>84.5% Recall@5</strong> and <strong>0.81 MRR</strong> in text-to-image retrieval evaluation.</li>
          <li>Architected a ReAct-based LLM agent with tool-driven retrieval and grounded reasoning, achieving <strong>9.06/10 faithfulness</strong> and <strong>3.3% refusal rate</strong>.</li>
          <li>Designed a hybrid ranking pipeline combining dense embeddings with lexical re-scoring to reduce semantic drift and improve grounding robustness.</li>
          <li>Implemented a CUDA-accelerated embedding and batch indexing workflow for efficient high-dimensional vector storage and scalable retrieval.</li>
          <li>Developed an evaluation framework measuring retrieval accuracy and LLM generation quality to ensure grounding and reliability.</li>
        </ul>
        <div class="techline"><strong>Tech:</strong> OpenCLIP · LangChain · ChromaDB · LLM Agents · Hybrid Retrieval</div>
      </div>

      <div class="card">
        <h3>Sustainable Energy Management in Smart Homes with Reinforcement Learning</h3>
        <div class="meta"><a href="https://github.com/abc/Sustainable-Energy-Management-with-Reinforcement-Learning.git" target="_blank">View Source Code</a></div>
        <ul>
          <li>Explored intelligent battery storage control in CityLearn environment to minimize energy cost and carbon emissions.</li>
          <li>Implemented and compared <strong>Rule Based Control</strong>, <strong>PPO</strong>, and <strong>SAC</strong> agents.</li>
          <li><strong>SAC</strong> achieved best energy efficiency and lowest peak demand.</li>
        </ul>
        <div class="techline"><strong>Tech:</strong> PyTorch · CityLearn · RL · Python</div>
      </div>

      <div class="card">
        <h3>Scene Recognition with Deep CNNs (MIT Indoor67)</h3>
        <div class="meta"><a href="https://github.com/abc/Scene-Recognition-with-Deep-CNNs" target="_blank">View Source Code</a></div>

        <p><strong>1. Dense like Teacher (Strong Backbone)</strong></p>
        <ul>
          <li>Implemented a custom DenseNet-like architecture from scratch.</li>
          <li>Used <strong>SE (Squeeze and Excitation)</strong> in bottleneck blocks to improve channelwise attention.</li>
        </ul>

        <p><strong>2. Hybrid CNN + SE (Student) with Knowledge Distillation</strong></p>
        <ul>
          <li>Built a lighter Hybrid CNN with SE blocks for faster inference.</li>
          <li>Distilled soft targets from the Dense-like teacher so that the student learned richer class boundaries than from hard labels alone.</li>
        </ul>

        <p><strong>3. Ensemble Learning</strong></p>
        <ul>
          <li>Final predictions were ensembled across all trained models: Dense-like teacher, distilled Hybrid CNN + SE, and other experimental CNN variants.</li>
          <li>Achieved a project-high <strong>76% F1-score</strong> using soft and weighted ensemble voting.</li>
        </ul>

        <div class="techline"><strong>Tech:</strong> PyTorch · CNN · SE blocks · Knowledge distillation · Ensemble voting</div>
      </div>

    </div>
  </div>

  <!-- PROFESSIONAL EXPERIENCE -->
  <div class="section">
    <div class="kicker">Professional Experience</div>
    <h2>Industry background</h2>
    <div class="divider"></div>

    <div class="card">
      <h3>Tata Consultancy Services, India | IT Analyst</h3>
      <div class="meta">Apr 2018 – Dec 2019</div>
      <ul>
        <li>Developed and maintained Java-based backend systems supporting trade management, settlement workflows and optimized SQL queries and stored procedures for large relational databases, improving execution efficiency and reliability in production environments.</li>
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
  <div class="section">
    <div class="kicker">Contact</div>
    <h2>Let’s Connect</h2>
    <div class="divider"></div>

    <div class="card">
      <div class="contact-row">
        <div>
          <div class="contact-label">Email</div>
          <p><a href="mailto:sarayusd31@gmail.com">sarayusd31@gmail.com</a></p>
        </div>

        <div>
          <div class="contact-label">GitHub</div>
          <p><a href="https://github.com/sarayusd" target="_blank">https://github.com/sarayusd</a></p>
        </div>

        <div>
          <div class="contact-label">LinkedIn</div>
          <p><a href="https://www.linkedin.com/in/sarayusd/" target="_blank">https://www.linkedin.com/in/sarayusd/</a></p>
        </div>
      </div>
    </div>
  </div>

</div>


