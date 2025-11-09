---
permalink: /
title: "Dr. Kaan Demir"
<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Source+Serif+Pro:wght@300;400;600;700&display=swap');

:root {
  --ink: #1f2a37;
  --muted: #738195;
  --accent: #263659;
  --line: #e4e8f3;
}

body {
  font-family: 'Source Serif Pro', serif;
  font-size: 1.02em;
  background: #f7f8fc;
  color: var(--ink);
  text-rendering: optimizeLegibility;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.sidebar {
  background: #ffffff;
  border-radius: 22px;
  padding: 2.4em 2.6em;
  box-shadow: 0 24px 48px rgba(31, 42, 55, 0.08);
}

.sidebar .author__avatar img {
  border-radius: 18px;
  margin-bottom: 1.6em;
  box-shadow: 0 18px 36px rgba(15, 23, 42, 0.12);
}

.sidebar .author__name {
  font-family: 'Playfair Display', serif;
  font-size: 2em;
  letter-spacing: 0.06em;
  margin-bottom: 0.2em;
  color: var(--ink);
}

.sidebar .author__bio {
  text-transform: uppercase;
  letter-spacing: 0.22em;
  font-size: 0.72em;
  color: var(--muted);
  margin-bottom: 1.8em;
}

.author__urls-wrapper > .btn {
  display: none;
}

.author__urls {
  margin-top: 0;
  padding-left: 0;
  list-style: none;
}

.author__urls li {
  margin-bottom: 0.9em;
  font-size: 0.92em;
  color: var(--ink);
}

.author__urls i {
  color: var(--muted);
  margin-right: 0.75em;
}

.author__urls a {
  color: var(--ink);
  text-decoration: none;
}

.author__urls a:hover {
  color: var(--accent);
}

.page__inner-wrap {
  background: #ffffff;
  border-radius: 26px;
  padding: 3.2em 3.4em 4em;
  box-shadow: 0 24px 56px rgba(31, 42, 55, 0.08);
}

@media (max-width: 768px) {
  .page__inner-wrap {
    padding: 2.4em 1.8em;
  }
}

.page__content {
  line-height: 1.7;
  max-width: 760px;
  margin: 0 auto;
}

.page__content h1,
.page__content h2,
.page__content summary {
  font-family: 'Playfair Display', serif;
  font-weight: 600;
  color: var(--accent);
}

.page__content h2 {
  font-size: 0.95em;
  text-transform: uppercase;
  letter-spacing: 0.22em;
  margin-top: 3em;
  margin-bottom: 2em;
}

.page__content h3 {
  font-family: 'Source Serif Pro', serif;
  font-size: 1.15em;
  font-weight: 600;
  margin-top: 1.6em;
  margin-bottom: 0.6em;
  color: var(--ink);
}

.page__content p {
  color: var(--ink);
  line-height: 1.75;
  text-align: justify;
  text-justify: inter-word;
  margin-bottom: 1.2em;
}

.page__content li {
  color: var(--ink);
  margin-bottom: 0.5em;
}

.page__content strong {
  font-weight: 600;
  color: var(--ink);
}

.page__content ul {
  padding-left: 1.1em;
}

.accordion {
  border-top: 1px solid var(--line);
  padding: 2em 0;
}

.accordion summary {
  text-transform: uppercase;
  letter-spacing: 0.24em;
  font-size: 0.88em;
  display: flex;
  align-items: center;
  gap: 0.9em;
  position: relative;
  padding-right: 2.4em;
  cursor: pointer;
}

.accordion summary::-webkit-details-marker {
  display: none;
}

.accordion summary::after {
  content: '\203A';
  font-size: 1.4em;
  font-weight: 300;
  color: var(--muted);
  position: absolute;
  right: 0;
  transition: transform 0.25s ease, color 0.25s ease;
}

.accordion[open] summary::after {
  transform: rotate(90deg);
  color: var(--accent);
}

.accordion summary:hover {
  color: var(--ink);
}

.accordion-body,
.accordion p {
  margin-top: 1.4em;
}

.pdf-preview {
  width: 100%;
  height: 320px;
  border: 1px solid #dfe3e8;
  border-radius: 14px;
  box-shadow: 0 14px 32px rgba(31, 42, 55, 0.12);
  margin: 1.6em 0 0.6em 0;
  background: #ffffff;
}

@media (max-width: 640px) {
  .pdf-preview {
    height: 240px;
  }
}

.pdf-caption {
  font-size: 0.85em;
  color: var(--muted);
  text-align: center;
  margin-bottom: 1.8em;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.equation {
  font-size: 0.78em;
  text-align: center;
  overflow-x: auto;
  padding: 0.6em 0;
}

.equation::-webkit-scrollbar {
  height: 6px;
}

.equation::-webkit-scrollbar-thumb {
  background: #cbd5f5;
  border-radius: 3px;
}
</style>
.equation {
  font-size: 0.78em;
  text-align: center;
  overflow-x: auto;
  padding: 0.6em 0;
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

<iframe src="{{ '/files/extra_content/flowchart_mlmap.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" class="pdf-preview" title="CMA-ES adversarial training flowchart"></iframe>
<p class="pdf-caption">CMA-ES orchestrated adversarial training pipeline across proxy and target multi-label models.</p>

<iframe src="{{ '/files/extra_content/structured_adversarial.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" class="pdf-preview" title="Structured adversarial perturbation analysis"></iframe>
<p class="pdf-caption">Visual analysis of structured adversarial examples demonstrating concealability across correlated labels.</p>

### Consistent Lebesgue Measure Multi-Label Learner (CLML)
Surrogate losses often undermine multi-label consistency. CLML maximises a Lebesgue hypervolume to align simultaneously with conflicting loss functions, delivering a provably consistent learner that still runs on lightweight feed-forward architectures. The approach outperforms graph-enhanced and perturbation-heavy baselines, showing that principled measure design can eclipse brute-force model complexity.

<iframe src="{{ '/files/extra_content/lebesgue1.pdf#toolbar=0&navpanes=0&scrollbar=0' | relative_url }}" class="pdf-preview" title="Lebesgue measure illustration"></iframe>
<p class="pdf-caption">Geometric interpretation of the Lebesgue measure maximisation that underpins CLML.</p>

#### Excerpts from the Consistency Proof
The key result links hypervolume maximisation to convergence towards Bayes predictors across three loss families:

<div class="equation">
$$
\lim_{n \to \infty} \lambda\big(H(F^{(n)}, R)\big) = \lambda\big(H(\mathbb{P}^{B}, R)\big) \implies \bigwedge_{v \in \{1,2,3\}} R_{\mathcal{L}_v}\big(f^{(n)}\big) \to R^{B}_{\mathcal{L}_v}(f).
$$
</div>

Pareto dominance ensures every non-Bayes solution is strictly outperformed along at least one loss surface:

<div class="equation">
$$
\forall i: L_i(f_\beta) \leq L_i(f_\gamma) \land \exists k: L_k(f_\beta) < L_k(f_\gamma), \quad f_\beta \in \mathbb{P}^{B},\; f_\gamma \notin \mathbb{P}^{B}.
$$
</div>

These theorems anchor the empirical findings and give decision-makers confidence that performance gains stem from sound statistical guarantees.

</details>