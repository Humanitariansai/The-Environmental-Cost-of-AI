#  The Environmental Cost of AI

*A Work-in-Progress Course Built by Volunteers Learning by Teaching*
A program of **Humanitarians AI**, a 501(c)(3) nonprofit for ethical, accessible AI.

---

# **Course Overview**

Enterprises are scaling AI models across operations, but the environmental footprint—energy, water, carbon, hardware waste—continues to grow. This course teaches volunteers, students, and nonprofit partners how to understand AI’s environmental impact and how organizations can adopt more **sustainable**, **efficient**, and **responsible** AI systems.

The course blends research, case studies, and hands-on analyses.
Each lesson includes:

* A YouTube micro-lecture
* A hands-on lab (using open data / open tools)
* A case study
* A short reflective assignment

---

# **Course Learning Goals**

By the end of this course, learners will be able to:

1. Explain the environmental footprint of AI (energy, water, carbon, hardware).
2. Compare training vs. inference energy demand.
3. Evaluate sustainable AI architectural choices (MoE, quantization, pruning, distillation).
4. Analyze enterprise strategies for clean energy, cooling, and data center optimization.
5. Assess the role of AI in sustainable marketing and customer experience.
6. Understand new efficiency innovations, including DeepSeek’s training methods.
7. Build sustainability checklists and reporting templates for real organizations.

---

# **Course Structure**

**Part I — Understanding AI’s Environmental Impact**
**Part II — Enterprise Strategies for Sustainable AI**
**Part III — Case Studies (BLOOM, DeepSeek, Microsoft, Google)**
**Part IV — Future Directions & Responsible Innovation**

---

# **Part I — The Environmental Footprint of AI**

---

## **Module 1 — Why AI Sustainability Matters**

*YouTube Lecture:* “The Hidden Costs of AI Innovation”
Topics:

* Explosion of AI compute demand
* Global energy projections (through 2030)
* Why enterprises can’t ignore sustainability
* Ethical + regulatory momentum (SEC, EU, ESG)

**Hands-On Lab:**
Measure the CO₂ estimate of running an open-source model using tools like CodeCarbon.

**Visuals Needed:**
Bar chart: compute demand doubling every 100 days
Infographic: data center → energy → water → emissions pipeline

---

## **Module 2 — Energy Use: Training vs. Inference**

*YouTube Lecture:* “Why Inference, Not Training, Dominates Energy Use”
Topics:

* GPT-3, GPT-4 training cost comparisons
* Why inference is ~80% of lifetime energy
* Electricity cost per query
* Image generation vs text generation energy profiles

**Hands-On Lab:**
Simulate inference load: estimate annual CO₂ for a chatbot used by 10,000 customers.

**Show & Tell Demo:**
“How a single ChatGPT query uses 10× a Google search.”

---

## **Module 3 — Water Usage & Cooling**

*YouTube Lecture:* “The AI Water Crisis: Cooling Our Compute”
Topics:

* Microsoft Iowa case (11.5 million gallons / month)
* Google Council Bluffs water usage
* Water cost per 20–50 AI queries
* Why evaporative cooling dominates today
* Risks in drought regions

**Hands-On Lab:**
Calculate water usage for 1M daily queries using published cooling coefficients.

**Visuals:**
Doodle of a server rack “sweating” water into a cooling tower.

---

## **Module 4 — AI’s Carbon Footprint & Hardware Waste**

*YouTube Lecture:* “AI, Carbon, and the Next E-Waste Crisis”
Topics:

* CO₂ emissions from training large models
* Electricity source: clean grid vs. fossil grid
* E-waste projections (12,000 Eiffel Towers worth by 2050)
* Rare earth mining and geopolitics

**Hands-On Lab:**
Compare carbon emissions of GPT-3 training vs BLOOM vs DeepSeek.

---

# **Part II — Enterprise Strategies for Responsible AI**

---

## **Module 5 — Energy-Efficient AI Architecture**

*YouTube Lecture:* “How to Make AI Leaner: MoE, Pruning, Distillation”
Topics:

* Mixture-of-Experts (MoE)
* Quantization (4-bit, 8-bit)
* Knowledge distillation
* Right-sizing models vs mega-models
* Automating “small model first” policies

**Hands-On Lab:**
Quantize a model and measure speed/energy improvements.

**Case Study:**
How BLOOM reduced emissions 95% vs GPT-3 by using low-carbon supercomputing.

---

## **Module 6 — Responsible Data Center & Hardware Choices**

*YouTube Lecture:* “Smarter Chips, Cooler Servers”
Topics:

* TPUs vs GPUs (energy per FLOP comparison)
* Liquid cooling & submersion cooling
* Zero-water cooling (Microsoft 2024 design)
* Thermal optimization with AI
* Scheduling jobs during renewable energy surplus

**Hands-On Lab:**
Simulated data center: optimize workloads for peak solar availability.

---

## **Module 7 — Renewables, Offsets, and Grid-Smart AI**

*YouTube Lecture:* “How Enterprises Can Power AI Responsibly”
Topics:

* Clean energy procurement
* Carbon-free cooling regions
* Dynamic training schedules
* Offsetting vs direct decarbonization
* Why geographic placement matters

**Hands-On Lab:**
Map data center regions to renewable grids; choose optimal hosting location.

---

## **Module 8 — AI for Environmental Impact Reduction**

*YouTube Lecture:* “AI as a Climate Tool, Not Just a Climate Burden”
Topics:

* Climate modeling
* Emissions tracking
* AI-optimized supply chains
* AI in conservation & biodiversity
* Applying sustainability models inside marketing and CX

**Hands-On Lab:**
Build a simple supply-chain emissions estimator using open data.

---

# **Part III — Industry Case Studies**

---

## **Module 9 — Microsoft & Google: Toward Zero-Water Data Centers**

*YouTube Lecture:* “Big Tech’s Race to Cool AI Sustainably”
Topics:

* Microsoft’s closed-loop cooling
* Google DeepMind energy optimization
* WUE (Water Usage Effectiveness) metrics
* What enterprises can learn

---

## **Module 10 — BLOOM vs GPT-3: A Sustainability Comparison**

*YouTube Lecture:* “When Open Science Beats Big Budgets”
Topics:

* BLOOM’s nuclear-powered training cluster
* Why emissions were only 5% of GPT-3
* What this means for enterprise model selection

**Lab:**
Replicate BLOOM vs GPT-3 emissions calculation.

---

## **Module 11 — DeepSeek: The Shockwave of Efficient AI**

*YouTube Lecture:* “DeepSeek: A Blueprint for Energy-Efficient LLMs?”
Topics:

* MoE + reinforcement learning recipe
* 2,000 H800 GPUs vs 16,000+ H100s
* How they achieved < $6M training cost
* Distillation controversy
* Why inference latency is still a challenge
* Implications for enterprise models

**Hands-On Lab:**
Analyze a DeepSeek-style MoE layout (simple simulation).

---

## **Module 12 — AI in Advertising & Marketing Efficiency**

*YouTube Lecture:* “AI Marketing: Performance Gains Without Energy Waste”
Topics:

* Chatbots, recommendation engines
* Predictive targeting
* AI measurement of advertising carbon footprint
* TPUs in ad bidding
* IPG Interact’s AI Console (case study)

**Hands-On Lab:**
Use a mock dataset to build a sustainability-aware ad budget optimizer.

---

# **Part IV — Tools, Reporting, and the Future of Sustainable AI**

---

## **Module 13 — Transparency & AI Sustainability Reporting**

*YouTube Lecture:* “How to Build AI Sustainability Scorecards”
Topics:

* Energy metrics (MWh, FLOPs, PUE, WUE)
* Model carbon disclosure
* Vendor sustainability requirements
* Enterprise compliance templates

**Deliverable:**
Sustainability reporting template for your organization.

---

## **Module 14 — Building a Corporate Sustainable AI Policy**

*YouTube Lecture:* “From Principles to Practice: Policy That Works”
Topics:

* Governance
* Procurement rules
* Energy-efficient model selection
* Ethical considerations
* Avoiding Jevons paradox through policy

**Hands-On Assignment:**
Draft a 2-page Responsible AI Sustainability Policy.

---

## **Module 15 — The Future of Energy-Efficient AI**

*YouTube Lecture:* “The Next 5 Years: Leaner Models, Smarter Compute”
Topics:

* Post-transformer research
* Tiny models + edge inference
* AI-optimized chips
* Distributed micro-training
* The possibility of net-positive AI

**Capstone Project:**
“Design a Sustainable AI Strategy for a Fortune 500 Company.”
Team project with structured templates.
