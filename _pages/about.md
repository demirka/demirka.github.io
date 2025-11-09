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

.page__content p, .page__content li {
  color: #444;
  line-height: 1.65;
}

.page__content strong {
  font-weight: 600;
  color: #222;
}

.page__content ul {
  margin-top: 0.6em;
  margin-bottom: 1em;
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

My PhD research established novel theoretical foundations for multi-objective machine learning, bridging evolutionary computation with statistical learning theory. This work advances our understanding of how to systematically navigate complex trade-offs in AI systems—essential for real-world deployment where multiple objectives (accuracy, fairness, efficiency) compete.

**Adversarial Robustness via Many-Objective Optimisation**  
Developed the first evolutionary framework for structured adversarial attacks on multi-label systems, proving that many-objective optimisation can systematically expose vulnerabilities across label dependencies. This work demonstrates how evolutionary algorithms can generate sophisticated test cases that reveal model brittleness in ways gradient-based methods cannot capture. [*IEEE Trans. on Evolutionary Computation, 2025*]

**Theoretical Guarantees for Feature Selection**  
Established mathematical proof that maximising Lebesgue measure in objective space guarantees convergence to Bayes-optimal predictors across multiple loss functions simultaneously. This theorem provides the first rigorous justification for using hypervolume-based evolutionary algorithms in representation learning, connecting measure theory to practical ML optimisation. [View proof formulation](files/extra_content/proof.tex)

**Dual-Structured Representation Learning**  
Designed a particle swarm framework that jointly optimises feature sparsity and label structure, incorporating graph regularisation to preserve semantic relationships. The dual subspace architecture enables simultaneous discovery of relevant features and label dependencies—a critical capability for domains like medical diagnosis where both feature economy and output structure matter. [Visualisation](files/extra_content/lebesgue1.pdf)

**Multi-Objective ML Methodology**  
Created comprehensive frameworks mapping the landscape of multi-objective machine learning approaches, taxonomising when different evolutionary strategies (decomposition, dominance-based, indicator-based) are theoretically optimal for different problem structures. [Framework diagram](files/extra_content/flowchart_mlmap.pdf)

These contributions bridge academic rigour with practical AI engineering—proving that sophisticated optimisation theory directly translates to more robust, interpretable, and deployable ML systems.

</details>