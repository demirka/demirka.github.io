---
permalink: /
title: "Dr. Kaan Demir"
excerpt: "AI & Data Engineer"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
body {
  font-size: 0.88em;
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.page__content {
  line-height: 1.6;
  max-width: 100%;
  padding-left: 1em;
  padding-right: 1em;
}

.page__inner-wrap {
  max-width: 100%;
}

.page__content h2 {
  margin-top: 1.8em;
  margin-bottom: 0.8em;
  font-weight: 600;
  border-bottom: 2px solid #f0f0f0;
  padding-bottom: 0.3em;
}

.page__content h3 {
  margin-top: 1.4em;
  margin-bottom: 0.4em;
  font-weight: 600;
  color: #333;
}

.page__content p {
  color: #444;
  line-height: 1.65;
  text-align: justify;
  text-justify: inter-word;
}

.page__content li {
  color: #444;
  line-height: 1.6;
}

.page__content strong {
  font-weight: 600;
  color: #222;
}

.page__content ul {
  margin-top: 0.6em;
  margin-bottom: 1em;
}

.pdf-preview {
  width: 100%;
  height: 420px;
  border: 1px solid #dfe3e8;
  border-radius: 6px;
  box-shadow: 0 6px 18px rgba(17, 24, 39, 0.08);
  margin: 1.2em 0 0.4em 0;
}

.pdf-caption {
  font-size: 0.85em;
  color: #5a626d;
  text-align: center;
  margin-bottom: 1.4em;
}

/* Accordion styles */
.accordion {
  border-top: 1px solid #e6e6e6;
  margin-top: 1.6em;
  padding-top: 1em;
}

.accordion:first-of-type {
  border-top: 1px solid transparent;
}

.accordion summary {
  list-style: none;
  cursor: pointer;
  font-weight: 600;
  font-size: 1.3em;
  color: #2c3e50;
  position: relative;
  padding-right: 2.5em;
}

.accordion summary::-webkit-details-marker {
  display: none;
}

.accordion summary::after {
  content: '›';
  position: absolute;
  right: 0;
  font-size: 1.4em;
  font-weight: 300;
  color: #b0b0b0;
  transform: rotate(90deg);
  transition: transform 0.2s ease, color 0.2s ease;
}

.accordion[open] summary::after {
  transform: rotate(270deg);
  color: #2c3e50;
}

.accordion summary:hover {
  color: #1b2a41;
}

.accordion-body {
  margin-top: 1em;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function () {
  const accordions = Array.from(document.querySelectorAll('.accordion'));

  accordions.forEach((accordion) => {
    accordion.addEventListener('toggle', function () {
      if (this.open) {
        accordions.forEach(other => {
          if (other !== this) {
            other.removeAttribute('open');
          }
        });
      }
    });
  });

  if (accordions.length > 0) {
    accordions[0].setAttribute('open', '');
  }
});
</script>

## Professional Profile

Senior data and AI expert with over 7 years of combined experience spanning government, consulting, and academic sectors. Deep knowledge of AI from an academic perspective with practical delivery of cloud-native, production-ready solutions in consulting/public sector scenes. Proven in leading client-facing, high-impact AI projects from concept to deployment, driving innovation and responsible governance.

## Expertise

- **AI Engineering & Fine-Tuning**: RLHF, SFT, PPO, DPO, deliberative alignment, guardrails, Chain-of-Thought (CoT) for policy compliance
- **LLMs & Advanced AI**: AutoGen, LangChain, Agentic AI, RAG, NER, LoRA, Transformers, PyTorch
- **Cloud & DevOps**: Azure App Services, Databases, Storage, AI Foundry, Infrastructure-as-Code
- **MLOps & AI Governance**: ISO 42001, Responsible AI frameworks, model lifecycle management
- **Data Engineering**: ETL/ELT, Star Schema, SQL, pipeline optimisation
- **Software Development**: Python, Java, R, Pandas, REST APIs, asynchronous programming, front-end and back-end integration (React, TS, Next.JS, Streamlit)
- **Leadership & Strategy**: Project planning, stakeholder engagement, ROI modeling, Agile/PRINCE2
- **Research & Thought Leadership**: 10+ publications in internationally recognised AI venues

<details class="accordion" open markdown="1">
<summary>Experience</summary>

### AI & Data Engineer
**DataSing** | 2025 - Current

- **End-to-end Solution Lead**: Delivered end-to-end AI PoCs and MVPs for enterprise clients, covering frontend, backend, Azure provisioning, DevOps, and MLOps
- **Agentic Automation**: Engineered asynchronous backend job orchestration, reducing analysis time from months to hours through agentic AI frameworks
- **Front-End Integration**: Delivered secure, client-facing LLM applications using React/TypeScript and Streamlit, integrated with Azure App Services
- **Solutions Architecture**: Designed ingestion pipelines with Infrastructure-as-Code, security, and compliance principles
- **Governance & Alignment**: Contributed to ISO 42001 research and implemented deliberative alignment and Chain-of-Thought (CoT) reasoning for policy compliance
- **R&D Leadership**: Standardised internal frameworks for automated coding agents, reducing development cycles by 70+%
- **Client Management**: Supported client engagement, scoping, and technical presentations—recognised by leadership and clients for professionalism and clarity

### Data Analyst (AI & Strategic Projects Lead)
**Financial Intelligence Unit, New Zealand Police** | 2024 - 2025 (18 Months)

- **LLM Applications**: Prototyped retrieval-augmented generation (RAG) solutions using LangChain and HuggingFace for legislative ingestion
- **ETL Optimisation**: Led large-scale ETL performance improvement initiative across mission-critical pipelines
- **Governance**: Designed governance frameworks for NLP models, incorporating responsible AI principles and compliance guardrails
- **Strategic Delivery**: Managed end-to-end solution lifecycle from business case to proof-of-concept, leveraging MLOps platforms (DataRobot) for deployment
- **Senior Leadership Engagement**: Presented strategic insights to governance groups, impacting digital transformation
- **Business Case Development**: Led a cost-benefit and return on investment analysis that informed a business case for AI infrastructure investment
- **Cross-Sector Partnership**: Brokered a strategic partnership with ESR to enable high-performance computing for the FIU

### Senior Machine-Learning Researcher
**Victoria University of Wellington, School of Engineering and Computer Science** | 2021 - 2024 (Full Time)

- **State-of-the-art Machine-learning and AI**: Designed custom transformers, self-attention mechanisms, multi-variate optimisation methods, and disentangled autoencoders for various state-of-the-art methods in AI research
- **State-of-the-art Representation Learning**: Designed and implemented evolutionary learning approaches for structured multi-label data representations
- **Independent Research Leadership**: Managed full research lifecycle including planning, experimentation, and thesis development
- **AI Research Leadership**: Published 12 papers in top AI venues; contributor to OpenReview discussions for ICLR, ICML, IJCAI, AAAI; reviewer in top venues such as TEVC, TKDD, GECCO

### AI & Data Science Researcher (Contract)
**Victoria University of Wellington** | 2021 - 2024

- **Leading Applied AI Research**: Led applied AI research for multi-agency projects, including genetic algorithm-based feature selection for marine biomass analysis
- **Cross-Sector Collaboration**: Coordinated research with Callaghan Innovation and New Zealand Plant & Food Research

### Head Graduate Teaching Assistant (Contract)
**Victoria University of Wellington** | 2020 - 2024

- **Course Management**: Managed and trained 30+ tutors; standardised marking and teaching processes across courses

### AI & Data Science Researcher (Contract)
**Victoria University of Wellington, School of Mathematics & Statistics** | 2018 - 2019

- **Statistical and Data Analysis**: Performed analysis of data using traditional statistical and data science methods
- **Research Assistant**: Implemented analysis methodology and generated experiments for output to aid in research

</details>

<details class="accordion" markdown="1">
<summary>Education</summary>

**PhD in Computer Science & Artificial Intelligence**  
*Victoria University of Wellington* | 2021 - 2024  
Thesis: *Evolutionary Representation Learning of Structured Multi-label Data*

**Honours in Computer Science & Artificial Intelligence**  
*Victoria University of Wellington* | 2020 - 2021

**Bachelor of Science in Computer Science & Artificial Intelligence**  
*Victoria University of Wellington* | 2017 - 2019

</details>

<details class="accordion" markdown="1">
<summary>Selected Publications</summary>

- K. Demir, B. H. Nguyen, B. Xue and M. Zhang, "Multi-Label Black-Box Attacks via Evolutionary Structured Many-Objective Adversarial Perturbations," in *IEEE Transactions on Evolutionary Computation*, 2025.
- K. Demir, B. H. Nguyen, B. Xue and M. Zhang, "Dual Sparse Structured Subspaces and Graph Regularisation for Particle Swarm Optimisation-Based Multi-Label Feature Selection," in *IEEE Computational Intelligence Magazine*, 2024.
- K. Demir, B. H. Nguyen, B. Xue and M. Zhang, "Co-operative Co-evolutionary Many-objective Embedded Multi-label Feature Selection with Decomposition-based PSO," in *Proceedings of the Genetic and Evolutionary Computation Conference (GECCO '23)*, 2023.

</details>

<details class="accordion" markdown="1">
<summary>Research Highlights</summary>

My research pairs theoretical guarantees with production-grade AI engineering, building trustworthy systems for high-stakes environments.

### Evolutionary Adversarial Training for Multi-Label Security (TEVC 2025)
Multi-label models carry real security risk when malicious actors tamper with co-occurring labels. I developed a CMA-ES driven adversarial training framework that operates in tabulated domains, crafting structured yet concealable perturbations without needing access to the target model. The many-objective formulation balances attack success (81–100% in evaluation), robustness, and stealth—giving public-sector teams a realistic picture of how resilient their classifiers truly are.

<object data="{{ '/files/extra_content/flowchart_mlmap.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" type="application/pdf" class="pdf-preview">
  <p>Inline preview unavailable. <a href="{{ '/files/extra_content/flowchart_mlmap.pdf' | relative_url }}" target="_blank" rel="noopener">Open the adversarial training flowchart</a>.</p>
</object>
<p class="pdf-caption">CMA-ES orchestrated adversarial training pipeline across proxy and target multi-label models.</p>

<object data="{{ '/files/extra_content/structured_adversarial.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" type="application/pdf" class="pdf-preview">
  <p>Inline preview unavailable. <a href="{{ '/files/extra_content/structured_adversarial.pdf' | relative_url }}" target="_blank" rel="noopener">Open adversarial perturbation analysis</a>.</p>
</object>
<p class="pdf-caption">Visual analysis of structured adversarial examples demonstrating concealability across correlated labels.</p>

### Consistent Lebesgue Measure Multi-Label Learner (CLML)
Surrogate losses often undermine multi-label consistency. CLML maximises a Lebesgue hypervolume to align simultaneously with conflicting loss functions, delivering a provably consistent learner that still runs on lightweight feed-forward architectures. The approach outperforms graph-enhanced and perturbation-heavy baselines, showing that principled measure design can eclipse brute-force model complexity.

<object data="{{ '/files/extra_content/lebesgue1.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" type="application/pdf" class="pdf-preview">
  <p>Inline preview unavailable. <a href="{{ '/files/extra_content/lebesgue1.pdf' | relative_url }}" target="_blank" rel="noopener">Open Lebesgue measure illustration</a>.</p>
</object>
<p class="pdf-caption">Geometric interpretation of the Lebesgue measure maximisation that underpins CLML.</p>

#### Excerpts from the Consistency Proof
The key result links hypervolume maximisation to convergence towards Bayes predictors across three loss families:

$$
\lim_{n \to \infty} \lambda\big(H(F^{(n)}, R)\big) = \lambda\big(H(\mathbb{P}^{B}, R)\big) \implies \bigwedge_{v \in \{1,2,3\}} R_{\mathcal{L}_v}\big(f^{(n)}\big) \to R^{B}_{\mathcal{L}_v}(f).
$$

Pareto dominance ensures every non-Bayes solution is strictly outperformed along at least one loss surface:

$$
\forall i: L_i(f_\beta) \leq L_i(f_\gamma) \land \exists k: L_k(f_\beta) < L_k(f_\gamma), \quad f_\beta \in \mathbb{P}^{B},\; f_\gamma \notin \mathbb{P}^{B}.
$$

These theorems anchor the empirical findings and give decision-makers confidence that performance gains stem from sound statistical guarantees.

</details>