---
layout: default
title: Sarayu Sivakumar Dhaya
---
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap');

/* ============================= */
/* COLOR SYSTEM — PURPLE + GOLD */
/* ============================= */
:root{
  --bg:#08060f;
  --panel:#121022;
  --panel-2:#0e0b18;
  --border:rgba(255,255,255,.08);

  --text:#f5f4fa;
  --muted:#b8b4cc;

  --accent:#c6a84f;   /* gold */
  --accent2:#7b3fe4;  /* purple */
}

/* ============================= */
/* GLOBAL RESET */
/* ============================= */
*{ box-sizing:border-box; }

html, body{
  margin:0;
  padding:0;
  font-family:'Inter',sans-serif;
  color:var(--text);

  background:
    radial-gradient(900px 400px at 70% 0%, rgba(123,63,228,.25), transparent 60%),
    radial-gradient(700px 300px at 20% 20%, rgba(198,168,79,.12), transparent 60%),
    linear-gradient(180deg,#120c1f 0%, #08060f 70%, #000000 100%);

  overflow-x:hidden;
}

/* Remove Cayman layout constraints */
.main-content,
.container,
.container-lg,
.markdown-body,
article{
  max-width:none !important;
  padding:0 !important;
  margin:0 !important;
}

footer,
.site-footer,
.page-footer{
  display:none !important;
}

/* ============================= */
/* HEADER */
/* ============================= */
.page-header{
  background: linear-gradient(
    135deg,
    #2a1244 0%,
    #3b1e5c 40%,
    #b8860b 75%,
    #000000 100%
  ) !important;

  padding:100px 20px 120px 20px !important;
  border-bottom:none !important;
}

.project-name{
  font-size:56px !important;
  font-weight:800 !important;
  color:#ffffff !important;
  letter-spacing:-1px;
}

.project-tagline{
  font-size:20px !important;
  color:rgba(255,255,255,0.85) !important;
}

/* ============================= */
/* LAYOUT */
/* ============================= */
.wrapper{
  width:min(1120px, calc(100vw - 64px));
  margin:0 auto;
  padding:64px 0 88px;
}

.section{
  margin:88px 0;
}

/* ============================= */
/* UNIFIED SECTION HEADINGS */
/* ============================= */
.section-title,
.section h2{
  font-size:42px;
  font-weight:700;
  margin:0 0 20px 0;

  background: linear-gradient(90deg, var(--accent2), var(--accent));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;

  letter-spacing:-0.5px;
  text-shadow: 0 0 25px rgba(198,168,79,.15);
}

.section-title{
  text-transform:none;
}

/* Section underline */
.rule{
  width:80px;
  height:3px;
  background:linear-gradient(90deg,var(--accent2),var(--accent));
  border-radius:999px;
  margin:20px 0 35px 0;
}

/* ============================= */
/* TEXT */
/* ============================= */
p{
  max-width:940px;
  font-size:18px;
  line-height:1.78;
  color:var(--muted);
  margin:0 0 22px;
}

ul{
  max-width:960px;
  padding-left:28px;
  margin:16px 0 0;
}

li{
  margin-bottom:13px;
  font-size:17px;
  line-height:1.72;
  color:var(--muted);
}

/* ============================= */
/* CARD LAYOUT */
/* ============================= */
.card{
  background:linear-gradient(180deg,var(--panel),var(--panel-2));
  border:1px solid rgba(198,168,79,.15);
  border-radius:18px;
  padding:38px 40px 42px;
  margin-bottom:34px;
  box-shadow:0 18px 50px rgba(0,0,0,.48);
  transition:transform .25s ease,border-color .25s ease,box-shadow .25s ease;
}

.card:hover{
  transform:translateY(-3px);
  border-color:rgba(198,168,79,.35);
  box-shadow:0 24px 64px rgba(0,0,0,.56);
}

/* ===== Card Header Layout ===== */
.card-header{
  display:flex;
  justify-content:space-between;
  align-items:flex-start;
  gap:24px;
  margin-bottom:8px;
}

.card-header h3{
  margin:0;
  max-width:820px;
  font-size:25px;
  font-weight:650;
  line-height:1.34;
  flex:1;
  color:#ffffff;
}

/* ===== Repo Link ===== */
.repo-link{
  font-size:14px;
  font-weight:600;
  color:var(--accent);
  text-decoration:none;
  white-space:nowrap;
  margin-top:6px;
  transition:.25s ease;
}

.repo-link:hover{
  color:var(--accent2);
}

/* ===== Project Stack (Skills line) ===== */
.project-stack{
  font-size:13px;
  font-weight:600;
  line-height:1.65;
  margin:10px 0 20px;
  color:#d4b35a;
  letter-spacing:.35px;
  padding-bottom:10px;
  border-bottom:1px solid rgba(198,168,79,.15);
}

/* Meta */
.meta{
  font-size:14px;
  line-height:1.5;
  color:rgba(255,255,255,.56);
  margin-bottom:18px;
}

/* ============================= */
/* RESULT + ARCH BOXES */
/* ============================= */
.results-box{
  background:rgba(198,168,79,.05);
  border:1px solid rgba(198,168,79,.2);
  padding:22px 24px;
  border-radius:12px;
  margin:30px 0 32px;
}

.arch-box{
  background:#ffffff;
  padding:28px;
  border-radius:16px;
  margin-top:26px;
  box-shadow:0 16px 44px rgba(0,0,0,.48);
  overflow:hidden;
}

.demo-box{
  background:#ffffff;
  padding:28px;
  border-radius:16px;
  margin-top:32px;
  box-shadow:0 16px 44px rgba(0,0,0,.48);
  text-align:center;
}


/* ============================= */
/* PROJECT CONTENT RHYTHM */
/* ============================= */
.card > p{
  margin-top:20px;
}

.card h4{
  margin:30px 0 12px;
  font-size:18px;
  font-weight:650;
  color:#ffffff;
  letter-spacing:.1px;
}

.results-box > strong,
.arch-box > strong{
  display:block;
  margin-bottom:16px;
  font-size:18px;
  line-height:1.4;
}

.results-box ul{
  margin-top:12px;
  max-width:none;
}

.results-box li:last-child,
.card li:last-child{
  margin-bottom:0;
}

.arch-box img{
  display:block;
  width:min(92%, 900px) !important;
  max-width:900px !important;
  height:auto;
  margin:22px auto 0 !important;
  border-radius:12px;
}

.project-action{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  min-height:44px;
  padding:11px 20px;
  border:1px solid rgba(198,168,79,.34);
  border-radius:999px;
  background:rgba(198,168,79,.08);
  color:var(--accent);
  font-size:14px;
  font-weight:650;
  line-height:1;
  text-decoration:none;
  transition:transform .2s ease,background .2s ease,border-color .2s ease,color .2s ease;
}

.project-action:hover{
  transform:translateY(-2px);
  background:rgba(198,168,79,.14);
  border-color:rgba(198,168,79,.55);
  color:#ffffff;
}

/* ============================= */
/* LINKS */
/* ============================= */
a{
  color:var(--accent);
  text-decoration:none;
  transition:.2s ease;
}

a:hover{
  color:var(--accent2);
}

/* ============================= */
/* CONTACT */
/* ============================= */
.contact{
  text-align:center;
  margin-top:88px;
  padding:36px 0 18px;
  border-top:1px solid rgba(255,255,255,.08);
}

.contact h3{
  font-size:28px;
  margin-bottom:18px;
}

.contact p{
  font-size:18px;
  color:var(--muted);
  margin:0;
}

/* ============================= */
/* RESPONSIVE */
/* ============================= */
@media(max-width:900px){
  .wrapper{
    width:calc(100vw - 36px);
    padding:48px 0 70px;
  }

  .section{
    margin:68px 0;
  }

  .section-title,
  .section h2{
    font-size:30px;
  }

  .project-name{
    font-size:40px !important;
  }

  .card{
    padding:30px 26px 34px;
  }

  .card-header{
    flex-direction:column;
    gap:10px;
  }

  .repo-link{
    margin-top:0;
  }

  .arch-box{
    padding:20px 14px;
  }

  .arch-box img{
    width:100% !important;
    max-width:100% !important;
  }
}

@media(max-width:560px){
  .page-header{
    padding:72px 18px 86px !important;
  }

  .project-name{
    font-size:34px !important;
  }

  .project-tagline{
    font-size:17px !important;
  }

  .wrapper{
    width:calc(100vw - 24px);
  }

  .card{
    padding:26px 20px 30px;
    border-radius:15px;
  }

  .card-header h3{
    font-size:22px;
  }

  p{
    font-size:16px;
    line-height:1.7;
  }

  li{
    font-size:16px;
    line-height:1.65;
  }

  ul{
    padding-left:22px;
  }

  .contact p{
    line-height:1.9;
  }
}
</style>

<div class="wrapper">

<!-- ABOUT ME -->

<div class="section">

  <div class="section-title">About Me</div>
  <div class="rule"></div>

  <p>
    I am a AI software Developer with more than five years of backend development experience and a Master’s degree in Artificial Intelligence from the University at Buffalo.
  </p>

  <p>
    My recent work focuses on PyTorch-based deep learning, computer vision, vibration-based fault diagnosis, multimodal retrieval, and reinforcement learning. I have worked on projects involving rotating-machinery faults, indoor scene recognition, image retrieval, and building-energy control.
  </p>

  <p>
    I prefer to compare models, inspect failure cases, and measure what each design choice contributes. My goal is to build ML systems that are clear enough to explain, reproduce, and improve.
  </p>

</div>

<!-- PROJECTS -->
<div class="section">
  <div class="section-title">Project Experience</div>
  <div class="rule"></div>

  <!-- PREDICTIVE MAINTENANCE -->
<div class="card">

  <div class="card-header">
    <h3>Industrial Fault Diagnosis using Deep Learning</h3>

    <a class="repo-link"
       href="https://github.com/sarayusd/predictive-maintenance-rotor-ai.git">
      Source Code →
    </a>

  </div>

  <div class="project-stack">
    PyTorch · Deep Learning · Self-Supervised Learning · Time-Series · Signal Processing
  </div>

  <div class="meta">
    Machinery Monitoring Systems LLC · University Collaboration
  </div>

  <p>

    This project explores how deep representation learning can improve vibration-based
    fault diagnosis for rotating machinery. I implemented both supervised and
    self-supervised training pipelines around the same multiscale PyTorch model to
    measure how representation learning influences downstream classification.

  </p>

  <h4>Highlights</h4>

  <ul>

    <li>

      Developed a multiscale PyTorch architecture that jointly learns from raw
      vibration signals and their frequency spectra, combining complementary
      temporal and spectral information within a single model.

    </li>

    <li>

      Implemented supervised and contrastive self-supervised learning pipelines,
      using encoder pretraining to improve downstream fault classification without
      requiring additional labeled fault data.

    </li>

    <li>

      Designed a complete deep learning workflow including data preparation,
      augmentation, model training, hyperparameter tuning, evaluation, and
      comparative benchmarking against established baselines.

    </li>

    <li>

      Built an interactive Streamlit application for real-time vibration analysis
      and fault prediction using the trained PyTorch model.

    </li>

  </ul>

  <div class="results-box">

    <strong>Key Results</strong>

    <ul>

      <li>89.6K vibration windows across five industrial fault classes</li>

      <li>Supervised learning: <strong>96.9%</strong> Accuracy · <strong>0.966</strong> Macro F1</li>

      <li>Self-supervised pretraining: <strong>98.9%</strong> Accuracy · <strong>0.989</strong> Macro F1</li>

      <li>143K parameter PyTorch model</li>

    </ul>

  </div>

  <div class="arch-box">

      <strong style="color:#111;">
        Multiscale Time-Frequency Architecture
      </strong>

      <img
        src="{{ '/images/mmsp.png' | relative_url }}"
        alt="Industrial fault diagnosis architecture"
        style="width:100%; margin-top:20px; border-radius:12px;"
      >

  </div>

</div>

 <!-- MULTIMODAL RETRIEVAL PROJECT -->

<div class="card">

  <div class="card-header">
    <h3>Multimodal Image Retrieval System with Hybrid Search and Grounded Explanations</h3>


<a
  class="repo-link"
  href="https://github.com/sarayusd/Multimodal-Image-Retrieval-System-with-Hybrid-Search-and-Grounded-Explanations.git"
  target="_blank"
>
  Source Code →
</a>


  </div>

  <div class="project-stack">
    PyTorch · OpenCLIP · Vision-Language Models · ChromaDB · BM25 · Cross-Encoder Reranking · LangChain
  </div>

  <p>
    I built this project to study how retrieval quality changes when a PyTorch-based
    vision-language baseline is extended with lexical search and reranking. The system
    supports text-to-image, image-to-image, and image-to-caption retrieval over COCO
    images, with an optional grounded explanation generated from the retrieved evidence.
  </p>

  <h4>Technical Contributions</h4>

  <ul>


<li>
  Built the initial retrieval model with OpenCLIP, encoding images and text into
  a shared embedding space and ranking candidates through cosine similarity.
</li>

<li>
  Combined dense OpenCLIP scores with BM25 caption scores to recover results that
  were semantically related but poorly ranked by vector similarity alone, or that
  contained important exact objects and actions.
</li>

<li>
  Added cross-encoder reranking over the top hybrid candidates, improving final
  ordering without applying the more expensive relevance model to the full image
  collection.
</li>

<li>
  Cached image and caption embeddings and stored them in a persistent ChromaDB
  collection, avoiding repeated feature extraction when the notebook or application
  restarts.
</li>

<li>
  Implemented a fallback sequence - reranked, hybrid, dense, then BM25-only - so a
  query can still return results when an optional retrieval component is unavailable.
</li>

<li>
  Added visual verification and a LangChain explanation stage that uses retrieved
  captions as evidence rather than asking the language model to describe a scene
  without context.
</li>


  </ul>

  <div class="results-box">


<strong>Evaluation</strong>

<ul>
  <li>Compared five retrieval configurations on 300 caption-to-image queries</li>
  <li>Measured Recall@1, Recall@5, MRR, Precision@5, nDCG@5, and query latency</li>
  <li>Tracked the quality and latency added by hybrid retrieval and reranking separately</li>
  <li>Supported text-to-image, image-to-image, and image-to-caption search</li>
</ul>


  </div>

  <div style="text-align:center; margin:25px 0;">
    <a
      class="project-action"
      href="{{ '/images/test.mp4' | relative_url }}"
      target="_blank"
    >
      ▶ Watch Retrieval Demo
    </a>
  </div>

  <div class="arch-box" style="text-align:center;">


<strong style="color:#111;">
  Retrieval and Grounded Explanation Pipeline
</strong>

<img
  src="{{ '/images/multimodal.png' | relative_url }}"
  alt="Architecture of the OpenCLIP hybrid image retrieval and explanation pipeline"
  style="width:70%; max-width:750px; margin-top:20px; border-radius:12px;"
>


  </div>

</div>


  <!-- WIKIPEDIA RAG 
  <div class="card">

    <div class="card-header">
      <h3>LLM-Powered RAG Conversational Assistant (Wikipedia)</h3>
      <a class="repo-link" href="https://github.com/sarayusd/LLM-powered-Chatbot-with-RAG-using-LlamaIndex.git">
        Source Code →
      </a>
    </div>

    <div class="project-stack">
      RAG · Semantic Search · Vector Embeddings · Grounded Generation
    </div>

    <ul>
      <li>Built a conversational assistant using Retrieval-Augmented Generation over Wikipedia corpus.</li>
      <li>Integrated semantic vector search and grounded prompting to reduce hallucination risk.</li>
      <li>Implemented context-aware answer generation with evidence traceability.</li>
    </ul>

  </div>

  <div class="card">

  <div class="card-header">
    <h3>LinkedIn Job Market Analysis - Big Data Pipeline</h3>
    <a class="repo-link" href="https://github.com/sarayusd/Job-Market-Analysis-.git">
      Source Code →
    </a>
  </div>

  <div class="project-stack">
    PySpark · Hadoop (HDFS) · Spark MLlib · Python · Docker · Data Analysis
  </div>

  <ul>
    <li>Built an end-to-end big data pipeline to process ~1.3M LinkedIn job postings using Hadoop (HDFS) and PySpark, including cluster setup and data ingestion.</li>
    <li>Performed large-scale data cleaning and preprocessing, handling missing values, standardizing job titles/locations, and structuring unstructured skill data.</li>
    <li>Conducted EDA and feature engineering (TF-IDF, skill extraction) to analyze job trends, in-demand skills, and company hiring patterns.</li>
    <li>Developed ML models for classification, regression, and clustering using Spark MLlib and evaluated performance using standard metrics.</li>
  </ul>

</div>-->
 <!-- MIT INDOOR SCENE RECOGNITION -->
<div class="card">

  <div class="card-header">
    <h3>Indoor Scene Recognition with PyTorch</h3>

    <a
      class="repo-link"
      href="https://github.com/sarayusd/Scene-Recognition-with-Deep-CNNs"
      target="_blank"
    >
      Source Code →
    </a>
  </div>

  <div class="project-stack">
    PyTorch · DenseNet · ConvNeXt · Transfer Learning · Knowledge Distillation · Model Compression
  </div>

  <p>
    This project compares four approaches to classifying the 67 indoor scene
    categories in MIT Indoor67: a DenseNet-style network built from scratch,
    linear probing, full ConvNeXt-Tiny fine-tuning, and teacher–student
    knowledge distillation.
  </p>

  <h4>Technical Contributions</h4>

  <ul>
    <li>
      Implemented a 3.98M-parameter DenseNet-style model from scratch using
      dense feature reuse, bottleneck layers, transition blocks, and global
      average pooling.
    </li>

    <li>
      Evaluated transfer learning in two stages: first freezing the ConvNeXt-Tiny
      backbone for linear probing, then fine-tuning the complete model with
      separate learning rates for the pretrained backbone and classification head.
    </li>

    <li>
      Built a 1.30M-parameter student network with depthwise-separable
      convolutions, residual connections, and squeeze-and-excitation blocks,
      trained from the fine-tuned ConvNeXt teacher using softened predictions
      and ground-truth labels.
    </li>

    <li>
      Compared model quality, parameter count and
      batch-size-one inference latency, then inspected per-class metrics,
      confusion matrices, and misclassified examples.
    </li>

    
  </ul>

  <div class="results-box">
    <strong>Key Results</strong>

    <ul>
      <li>
        Fine-tuned ConvNeXt-Tiny:
        <strong>84.25%</strong> test accuracy ·
        <strong>0.825</strong> macro F1
      </li>

      <li>
        Linear probe:
        <strong>79.45%</strong> test accuracy ·
        <strong>0.767</strong> macro F1
      </li>

      <li>
        Distilled student:
        <strong>1.30M parameters</strong> ·
        <strong>5.08 MB checkpoint</strong> ·
        <strong>3.57 ms</strong> batch-size-one latency
      </li>

      <li>
        Teacher-to-student compression:
        approximately <strong>21× fewer parameters</strong> and
        <strong>21× smaller checkpoint</strong>
      </li>
    </ul>
  </div>
  <div style="text-align:center; margin:25px 0;">
    <a
      class="project-action"
      href="{{ '/images/scene-demo.mp4' | relative_url }}"
      target="_blank"
    >
      ▶ Watch Demo
    </a>
  </div>
    <div class="arch-box" style="text-align:center;">


<strong style="color:#111;">
  Scene Recognition Pipeline
</strong>

<img
  src="{{ '/images/scene-recog-arch.png' | relative_url }}"
  alt="Architecture of the  Scene Recognition Pipeline pipeline"
  style="width:70%; max-width:750px; margin-top:20px; border-radius:12px;"
>


  </div>

</div>

  <!-- CITYLEARN RL -->
  <div class="card">

    <div class="card-header">
      <h3>Sustainable Energy Management in Smart Homes (CityLearn RL)</h3>
      <a class="repo-link" href="https://github.com/sarayusd/Sustainable-Energy-Management-with-Reinforcement-Learning.git">
        Source Code →
      </a>
    </div>

    <div class="project-stack">
      Reinforcement Learning · PPO · SAC · Energy Optimization
    </div>

    <ul>
      <li>Implemented PPO and SAC reinforcement learning agents in CityLearn environment.</li>
      <li>Designed reward functions balancing energy cost, carbon emissions, and peak demand.</li>
      <li>SAC achieved highest efficiency and lowest peak demand across experiments.</li>
    </ul>

  </div>

</div>
<!-- PROFESSIONAL EXPERIENCE -->
<div class="section">

  <h2 class="accent">Professional Experience</h2>
  <div class="rule"></div>

  <div class="card">

    <h3>AI Software Developer | MatchingDonors.com</h3>

    <div class="meta">
      Remote · May 2026 – Present
    </div>

    <ul>

      <li>
        Developed analytics prototypes using Google Analytics 4 (GA4) to transform
        user behavior into page-level engagement and conversion insights for a
        nonprofit platform.
      </li>

      <li>
        Built reporting pipelines that established baseline engagement metrics and
        supported future AI-driven donor outreach and recommendation workflows.
      </li>

    </ul>

  </div>

  <div class="card">

    <h3>IT Analyst | Tata Consultancy Services</h3>

    <div class="meta">
      India · Apr 2018 – Dec 2019
    </div>

    <ul>

      <li>
        Developed Java, Spring, JMS, and Oracle-based backend services for Citi's
        global iGSR platform supporting trade processing, clearing, and settlement.
      </li>

      <li>
        Designed Oracle SQL procedures and reconciliation workflows to investigate
        production issues and automate trade rollover and settlement processing.
      </li>

      <li>
        Worked within Agile teams to deliver backend enhancements, troubleshoot
        production incidents, and improve application reliability.
      </li>

    </ul>

  </div>

  <div class="card">

    <h3>Associate Consultant | Capgemini</h3>

    <div class="meta">
      India · Nov 2013 – Mar 2018
    </div>

    <ul>

      <li>
        Developed Java REST services and Spring applications on GE Predix (AWS)
        for turbine outage monitoring and operational analytics.
      </li>

      <li>
        Built customer support and Grid Solutions web applications using
        JavaScript, jQuery, and HTML5, improving responsiveness through
        asynchronous data loading and JSON optimization.
      </li>

      <li>
        Automated regression testing using JUnit and SAHI to improve release
        quality and reduce manual validation across multiple application releases.
      </li>

    </ul>

  </div>

</div>

<!-- CONTACT -->
<div class="contact">
<h3>Contact</h3>
<p>
Email: <a href="mailto:sarayusd31@gmail.com">sarayusd31@gmail.com</a> |
GitHub: <a href="https://github.com/sarayusd">github.com/sarayusd</a> |
LinkedIn: <a href="https://linkedin.com/in/sarayusd">linkedin.com/in/sarayusd</a>
</p>
</div>

</div>
