---
layout: default
title: Sarayu Sivakumar Dhaya
---

<style>
:root{
  --bg0:#0b1120;
  --bg1:#0f172a;
  --card: rgba(15, 23, 42, 0.65);
  --border: rgba(148, 163, 184, 0.18);
  --muted:#94a3b8;
  --text:#e2e8f0;

  --accent1:#38bdf8;
  --accent2:#818cf8;
  --accent3:#22c55e;
}

body {
  font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  background: radial-gradient(900px 600px at 10% 10%, rgba(56,189,248,0.18), transparent 55%),
              radial-gradient(800px 520px at 90% 20%, rgba(129,140,248,0.16), transparent 60%),
              radial-gradient(700px 520px at 80% 95%, rgba(34,197,94,0.10), transparent 55%),
              linear-gradient(180deg, var(--bg1) 0%, var(--bg0) 100%);
  color: var(--text);
  margin: 0;
}

.section {
  padding: 96px 12%;
}

.hero {
  display: grid;
  grid-template-columns: 1.25fr 0.75fr;
  gap: 56px;
  align-items: start;
  min-height: 92vh;
  padding-top: 84px;
  border-bottom: 1px solid rgba(148, 163, 184, 0.14);
}

.hero-left { max-width: 920px; }

.hero-right {
  padding: 34px 32px;
  border-radius: 18px;
  background: rgba(30, 41, 59, 0.45);
  border: 1px solid var(--border);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  box-shadow: 0 20px 60px rgba(0,0,0,0.25);
  position: sticky;
  top: 24px;
}

h1 {
  font-size: 54px;
  line-height: 1.08;
  margin: 0 0 14px 0;
  font-weight: 750;
  letter-spacing: -0.02em;
  background: linear-gradient(90deg, var(--accent1), var(--accent2));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.subtitle {
  font-size: 18px;
  color: var(--muted);
  margin-bottom: 28px;
}

.divider {
  width: 72px;
  height: 3px;
  border-radius: 2px;
  background: linear-gradient(90deg, var(--accent1), var(--accent2));
  margin: 22px 0 34px 0;
  opacity: 0.9;
}

h2 {
  font-size: 30px;
  margin: 0 0 30px 0;
  font-weight: 700;
  letter-spacing: -0.01em;
}

p {
  line-height: 1.85;
  color: rgba(226, 232, 240, 0.92);
  font-size: 16.8px;
  margin: 0 0 18px 0;
}

.muted {
  color: var(--muted);
}

.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 22px;
}

.card {
  background: rgba(30, 41, 59, 0.55);
  padding: 26px 26px;
  border-radius: 16px;
  transition: transform 0.25s ease, border-color 0.25s ease, box-shadow 0.25s ease;
  border: 1px solid rgba(148, 163, 184, 0.14);
  box-shadow: 0 14px 40px rgba(0,0,0,0.18);
}

.card:hover {
  transform: translateY(-6px);
  border-color: rgba(56, 189, 248, 0.45);
  box-shadow: 0 22px 70px rgba(0,0,0,0.26);
}

.card strong {
  display: block;
  font-size: 16.5px;
  letter-spacing: 0.01em;
  margin-bottom: 10px;
  color: rgba(226, 232, 240, 0.98);
}

.card p {
  color: rgba(203, 213, 225, 0.92);
  margin: 0;
  font-size: 15.8px;
  line-height: 1.75;
}

.tech {
  font-size: 13.8px;
  color: var(--muted);
  margin-top: 14px;
}

.hero-right .label {
  font-size: 12.5px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: rgba(148, 163, 184, 0.9);
  margin-bottom: 16px;
}

.focus-item {
  font-size: 16.5px;
  padding: 12px 0;
  border-bottom: 1px solid rgba(148, 163, 184, 0.14);
  color: rgba(226, 232, 240, 0.92);
}

.focus-item:last-child { border-bottom: none; }

a {
  color: rgba(129, 140, 248, 0.95);
  text-decoration: none;
}

a:hover { text-decoration: underline; }

/* Responsive */
@media (max-width: 980px) {
  .section { padding: 76px 8%; }
  .hero { grid-template-columns: 1fr; min-height: auto; }
  .hero-right { position: relative; top: auto; }
  h1 { font-size: 44px; }
}
</style>

<div class="section hero">

  <div class="hero-left">
    <h1>Summary</h1>
    <div class="subtitle">MS in Artificial Intelligence | 5+ Years Software Engineering</div>
    <div class="divider"></div>

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

  <div class="hero-right">
    <div class="label">Core Focus</div>
    <div class="focus-item">Deep Learning</div>
    <div class="focus-item">Large Language Models</div>
    <div class="focus-item">Generative AI</div>
    <div class="focus-item">RAG & Agents</div>
  </div>

</div>

<div class="section">

  <h2>Technical Skills</h2>

  <div class="grid">

    <div class="card">
      <strong>Programming</strong>
      <p>Python · Java · SQL</p>
    </div>

    <div class="card">
      <strong>Deep Learning & AI</strong>
      <p>PyTorch · TensorFlow · Scikit-learn · Computer Vision · NLP</p>
    </div>

    <div class="card">
      <strong>LLMs & Generative AI</strong>
      <p>RAG · ReAct Agents · OpenCLIP · LangChain · ChromaDB · OpenAI API</p>
    </div>

    <div class="card">
      <strong>Systems & Deployment</strong>
      <p>Docker · Kubernetes · CI/CD · CUDA · GPU Training</p>
    </div>

  </div>

</div>

<div class="section">

  <h2>Project Experience</h2>

  <div class="grid">

    <div class="card">
      <strong>Deep Learning-Based Predictive Maintenance</strong>
      <p>
        Engineered a vibration data pipeline generating 100K+ signals and built a dual-encoder 1D CNN with FFT features and attention mechanisms. Applied contrastive self-supervised pretraining achieving 91% accuracy.
      </p>
      <div class="tech">PyTorch · Signal Processing · Self-Supervised Learning</div>
    </div>

    <div class="card">
      <strong>Agentic Multimodal RAG</strong>
      <p>
        Built an agentic RAG system indexing 8K+ image-text pairs. Achieved 84.5% Recall@5 and 0.81 MRR. Designed hybrid retrieval and evaluation frameworks for grounded LLM reasoning.
      </p>
      <div class="tech">OpenCLIP · LangChain · ChromaDB · LLM Agents</div>
    </div>

    <div class="card">
      <strong>Sustainable Energy Management</strong>
      <p>
        Implemented and benchmarked PPO and SAC agents in CityLearn for cost and carbon optimization. SAC achieved highest energy efficiency.
      </p>
      <div class="tech">PyTorch · RL · Python</div>
    </div>

    <div class="card">
      <strong>Scene Recognition (MIT Indoor67)</strong>
      <p>
        Built custom CNN architectures with knowledge distillation and ensemble learning, achieving 76% F1-score.
      </p>
      <div class="tech">PyTorch · CNN · SE Blocks · Ensemble Learning</div>
    </div>

  </div>

</div>

<div class="section">

  <h2>Professional Experience</h2>

  <div class="grid">

    <div class="card">
      <strong>Tata Consultancy Services | IT Analyst</strong>
      <p>Java backend systems, SQL optimization, high-volume trade workflows, Agile delivery.</p>
    </div>

    <div class="card">
      <strong>Capgemini | Associate Consultant</strong>
      <p>RESTful Java microservices, production support, distributed systems debugging.</p>
    </div>

  </div>

</div>

<div class="section">

<h2>Contact</h2>
<p>
GitHub: <a href="https://github.com/sarayusd"> https://github.com/sarayusd> </a><br>
LinkedIn: <a href=" https://www.linkedin.com/in/sarayusd/">https://www.linkedin.com/in/sarayusd/</a><br>
Email: sarayusd31@gmail.com
</p>

</div>
