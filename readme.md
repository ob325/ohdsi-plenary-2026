

## Table of Contents
- [Grand visions for the plenary discussion to tie into](#grand-visions-for-the-plenary-discussion-to-tie-into)
- [2026-05-01 genAI ideas for session](#2026-05-01-genai-ideas-for-session)
  - [OHDSI Plenary: Customizing the Tool Stack — Interleaved Run-of-Show and Facilitation Plan](#ohdsi-plenary-customizing-the-tool-stack--interleaved-run-of-show-and-facilitation-plan)
- [Plenary submission](#plenary-submission)

# word bank (n=120)
absolute risk

Achilles

active comparator

as-treated

ATLAS

attributable risk

AUC

calibration

causal DAG

causal effect

censoring

characterization

clean window

cohort definition

cohort diagnostics

cohort entry

cohort exit

CohortGenerator

CohortMethod

collider

comparator cohort

competing risk

concept ancestor

concept descendant

concept set

condition era

condition occurrence

confidence interval

confounding

confounding by indication

consistency

counterfactual

covariate balance

Cox model

CPT

data partner

Data Quality Dashboard

death table

discrimination

distributed analysis

drug era

drug exposure

effect modifier

empirical calibration

era construction

estimand

EvidenceSynthesis

exchangeability

exclusion criteria

false discovery rate

FeatureExtraction

federated network

follow-up

generalizability

HADES

hazard ratio

heterogeneity

high-dimensional covariates

ICD

immortal time bias

imputation

incidence characterization

incidence rate

inclusion criteria

index date

information bias

intention-to-treat

inverse probability weighting

Kaplan-Meier

likelihood

LOINC

logistic regression

measurement

measurement error

mediator

missing data

multiple testing

negative control exposure

negative control outcome

net benefit

new-user design

observation period

odds ratio

OHDSI

OMOP CDM

outcome cohort

PatientLevelPrediction

per-protocol

person table

phenotype

Poisson regression

positivity

positive control

prediction model

prevalence

prevalent user bias

procedure occurrence

propensity score

propensity score matching

p-value

real-world evidence

regularized regression

reproducible research

residual confounding

risk difference

risk ratio

RxNorm

selection bias

SelfControlledCaseSeries

sensitivity analysis

SNOMED

source concept

standard concept

standardized mean difference

Strategus

stratification

study package

subgroup analysis

target cohort

target trial emulation

time at risk

transportability

treatment pathway

unmeasured confounding

validation

visit occurrence

vocabulary mapping

washout period

WebAPI



# word bank

causal inference

causal effect

causal question

estimand

target trial

target trial emulation

counterfactual

potential outcome

treatment effect

average treatment effect

ATT

ATE

exposure

treatment

intervention

comparator

control group

outcome

baseline

follow-up

time zero

index date

eligibility criteria

treatment strategy

assignment strategy

observation period

risk window

washout period

lookback period

grace period

censoring

competing risk

selection bias

confounding

unmeasured confounding

residual confounding

confounding by indication

immortal time bias

surveillance bias

information bias

measurement error

misclassification

missing data

exchangeability

positivity

consistency

identifiability

internal validity

external validity

transportability

generalizability

causal graph

DAG

confounder

mediator

collider

effect modifier

interaction

covariate

baseline covariate

time-varying covariate

propensity score

propensity score matching

propensity score stratification

inverse probability weighting

covariate adjustment

regression adjustment

standardization

g-computation

marginal structural model

instrumental variable

difference-in-differences

regression discontinuity

interrupted time series

case-crossover design

self-controlled design

active comparator

new-user design

active comparator new user

prevalent user

incident user

cohort study

case-control study

observational study

real-world data

real-world evidence

claims data

electronic health records

registry data

risk difference

risk ratio

odds ratio

hazard ratio

incidence rate ratio

confidence interval

standard error

sensitivity analysis

negative control

positive control

empirical calibration

OHDSI

OMOP

OMOP CDM

ATLAS

WebAPI

HADES

Achilles

ARES

Broadsea

Strategus

Circe

SqlRender

DatabaseConnector

FeatureExtraction

CohortMethod

CohortDiagnostics

PatientLevelPrediction

EvidenceSynthesis

SelfControlledCaseSeries

DataQualityDashboard

The Book of OHDSI

Cyclops

Andromeda

Eunomia

Hydra

Usagi

WhiteRabbit

RabbitInAHat

ROhdsiWebApi

ParallelLogger

ResultModelManager

OhdsiShinyModules

PheValuator

PhenotypeLibrary

Capr

CohortGenerator

IncidencePrevalence

TreatmentPatterns

DeepPatientLevelPrediction

MethodEvaluation

LEGEND

LEGEND-T2DM

LEGEND-HTN

LEGEND-AF

LEGEND-HF

EHDEN

DARWIN EU

Observational Health Data Sciences and Informatics

common data model

standard vocabulary

OMOP vocabulary

concept set

concept set expression

cohort definition

cohort generation

cohort instantiation

cohort characterization

phenotype

computable phenotype

phenotype validation

phenotype diagnostics

target cohort

comparator cohort

outcome cohort

exposure cohort

cohort table

cohort entry

cohort exit

cohort era

index event

initial event

inclusion criteria

exclusion criteria

attrition

attrition table

inclusion impact

population-level estimation

evidence network

evidence generation

network evidence

network study

distributed research network

federated analysis

study package

study protocol

analysis specification

study diagnostics

diagnostics

data quality

data characterization

source-to-concept mapping

ETL

ETL design

ETL validation

vocabulary mapping

vocabulary harmonization

clinical vocabulary

standardized data

database diagnostics

Achilles Heel

characterization dashboard

evidence explorer

open evidence

open science

reproducible research

standardized analytics

large-scale analytics

high-throughput analytics

comparative effectiveness

drug utilization

safety surveillance

incidence estimation

prevalence estimation

calibration

negative control outcome

positive control outcome

synthetic positive control

empirical null

calibrated confidence interval

calibrated p-value


# Notes from 2026-07-22 meeting
Bill & Scott 
- [ ] Bill will generate magnetic tile words, ask patrick for money
- [ ] Scott will send meeting invite ASAP, Bill will handle the meeting if Scott's away  




Below are ambitious, community-wide goals that become feasible when data are standardized to the OMOP Common Data Model and analyzed with reproducible OHDSI methods.

[ ] - Poster opportunity for follow-up 
Ask Patrick if they can have a poster automatically accepted 
Ask Patrick for magnetic tile money and board (word bank) 

[ ] - Notify our friends:
I will draft an email w basic info about lightning talks, magnetic poetry, live mad libs, Scott can send. Give a good amount of notice, a couple blocks of time. 
- Agnes (EST + 7 hrs) 
- Martin (EST) 
- Cindy (EST) 
- Hannah (EST) 
- Scott (MT)
- Bill (EST) 



# Notes from 2026-05-22 meeting

One‑sentence story (the “what and why”) “I used [tool or method] to explore [topic/problem] in [data setting] by [what you did], which helped me [result] while dealing with [constraint].”
Example: “I used a cohort tool to explore heart failure readmissions in hospital data by defining a clear patient group, which helped me spot high‑risk patterns while dealing with strict privacy rules.”
Define a group (cohort) and what you’re watching for “We defined a group of [who/criteria], looked for [outcome/event] within [time window], and made sure people had [clean period/no prior history] before counting events.”
Example: “We defined adults with new diabetes diagnoses, looked for ER visits within 90 days, and made sure they had no previous ER visits in the past year.”
Compare two groups (simple comparison) “We compared [group A] to [group B] to see if [outcome] was different. We adjusted for [important factors], and checked that groups were similar using [simple check].”
Example: “We compared people starting Drug A to those starting Drug B to see who had more falls. We adjusted for age and prior falls, and checked similarity using side‑by‑side counts.”
Build a prediction (who is likely to have something happen) “We built a prediction for [event/outcome] over [time frame]. We used [simple model type] with [key settings, if any], trained on about [size], and measured performance with [metric like accuracy/AUC].”
Example: “We built a prediction for 30‑day readmission using a simple logistic regression, trained on 50,000 patients, and measured performance with AUC.”
Make it run faster or smoother (performance) “To speed things up on [database/computer setup], we [action: sample, parallelize, cache, simplify]. Run time dropped from [X] to [Y], and memory stayed under [limit], without hurting [key metric].”
Example: “To speed things up on our shared server, we ran tasks in parallel and cached intermediate results. Run time dropped from 6 hours to 2 hours without hurting accuracy.”
Privacy and sharing (governance) “Because of [privacy rule/constraint], we kept data local and only shared [summaries/metrics/plots]. We packaged results as [format] so partners could review without seeing individual records.”
Example: “Because of local privacy rules, we kept data on site and only shared summary tables and plots as a PDF.”
Troubleshooting and wish list “The hardest part was [pain point], especially with [scale/database/tool]. If we could change one thing, we’d add [improvement], which would help [stakeholder] [benefit].”
Example: “The hardest part was slow feature creation on our big database. We’d add more parallel processing, which would help analysts finish studies faster.”
Quick prototype (30‑second version) “I used [tool] plus [small tweak] on [data] to answer [question] within [time budget], trading off [speed vs. detail] to get [useful result].”
Example: “I used a simple SQL script plus a small filter on hospital data to answer ‘Which wards have rising falls?’ in one afternoon, trading detail for speed.”
Validation and transportability (does it work elsewhere?) “We trained on [site/data A] and tested on [site/data B]. We adjusted [features/settings] to handle differences in [coding or missingness], keeping performance within [acceptable range].”
Example: “We trained at Hospital A and tested at Hospital B. We simplified features to handle missing labs, keeping AUC within 0.02 of the original.”
Clear communication (show and tell) “To explain results to [audience], we created [simple plot/report] highlighting [key comparison or trend], added notes on [uncertainty/calibration], and a short summary with [actionable takeaway].”
Example: “For clinicians, we created a bar chart showing readmissions by ward, added notes about uncertainty, and summarized the top three actions.”


# Grand visions for the plenary discussion to tie into

## 1) Safety at planetary scale (pharmacovigilance)
- Vision: An always-on, calibrated, all-by-all signal grid of every marketed drug against every clinically meaningful safety outcome.
- Enables:
  - Rapid signal detection and triage, with subgroup-specific risks (dose, age, sex, pregnancy, comorbidity).
  - Signal corroboration across independent sites and health systems.
  - Scalable assessment of drug–drug interactions.
- Why OMOP/OHDSI: Common vocabularies (RxNorm, SNOMED), standardized outcome cohorts, negative/positive control calibration, network meta-analysis, privacy-preserving distributed execution.

## 2) Effectiveness “LEGEND-style” at scale
- Vision: Systematic, unbiased comparative effectiveness for all relevant treatments across important outcomes and populations.
- Enables:
  - Class-wide and drug-vs-drug comparisons with consistent design and confounding control.
  - Transparent pipelines that can be rerun as data refresh.
- Why OMOP/OHDSI: Study packages, standardized adjustment (propensity, IPW), diagnostics (balance, overlap), calibrated inference across a federated network.

## 3) Trial emulation and regulatory-grade RWE
- Vision: Faithful target-trial emulation and external control arms that regulators and HTA bodies can scrutinize.
- Enables:
  - Faster evidence for label expansions, postmarketing commitments, and pragmatic/hybrid trials.
  - Systematic quantification of residual bias using controls and diagnostics.
- Why OMOP/OHDSI: Rigorous cohort definition (ATLAS, CohortDiagnostics), reproducible packages, transparency, multi-site replication.

## 4) Global, portable phenotype library
- Vision: A curated, versioned, performance-characterized library of computable phenotypes that transport across sites.
- Enables:
  - High-confidence cohorts/outcomes with known sensitivity/specificity and error modes.
  - Faster, higher-quality studies and reuse across disease areas.
- Why OMOP/OHDSI: Standardized vocabularies; CohortDiagnostics, PheValuator; open governance and peer review.

## 5) Patient-level prediction that transports
- Vision: A catalog of validated risk models (e.g., hospitalization, bleeding, readmission, treatment response) portable and recalibratable across institutions/geographies.
- Enables:
  - Bedside risk stratification with known transportability and fairness properties.
  - Monitoring of model drift and equity in deployment.
- Why OMOP/OHDSI: Common feature construction (FeatureExtraction), external validation across diverse databases, standardized performance reporting.

## 6) Learning health system observatories
- Vision: Always-on dashboards for treatment pathways, quality measures, and guideline adherence across conditions.
- Enables:
  - Near real-time detection of care gaps and unwarranted variation.
  - Feedback loops to clinicians and health systems to improve outcomes.
- Why OMOP/OHDSI: Uniform representation of visits, conditions, procedures, drugs, labs; reusable pathway analytics; federated aggregation.

## 7) Rare disease acceleration
- Vision: Scalable discovery/validation of rare disease phenotypes and earlier diagnostic signals.
- Enables:
  - Pan-site natural history studies, time-to-diagnosis reduction, treatment effect signals in small populations.
- Why OMOP/OHDSI: Cross-site case-finding with shared phenotypes; consistent capture of labs, genetics (via extensions), longitudinal trajectories.

## 8) Public health early-warning radar
- Vision: A privacy-preserving network for outbreak detection, vaccine safety/effectiveness, and syndromic surveillance.
- Enables:
  - Rapid, comparable situational awareness across jurisdictions.
- Why OMOP/OHDSI: Standardization across EHRs/claims; distributed analytics; reproducible designs for VE/VS studies.

## 9) Health equity and algorithmic fairness at scale
- Vision: Routine stratification of safety, effectiveness, and model performance by social determinants and protected characteristics.
- Enables:
  - Systematic bias audits and targeted remediation.
- Why OMOP/OHDSI: Common covariate construction, consistent subgroup definitions, external validation across diverse populations.

## 10) Data fitness-for-purpose scoring
- Vision: Automated, transparent scoring of each site’s data for a given study purpose (safety, cost, lab-based phenotypes).
- Enables:
  - Smart site selection and sensitivity analyses; fewer surprises post-launch.
- Why OMOP/OHDSI: DataQualityDashboard, Achilles profiling, standardized conformance/completeness/plausibility checks.

## 11) Privacy-preserving, federated analytics by default
- Vision: Question-to-evidence without moving row-level data—only code and aggregates move.
- Enables:
  - Faster multi-site collaboration, stronger privacy, simpler governance.
- Why OMOP/OHDSI: Packaged study execution, standard results schemas, meta-analysis tools; pathways to differential privacy or secure multi-party computation.

## 12) Multimodal, longitudinal evidence fabric
- Vision: Harmonized linkage of EHR, claims, registries, devices/wearables, PROs, and (where feasible) genomics—mapped to a common model.
- Enables:
  - Richer confounding control, outcome ascertainment, mechanistic insights.
- Why OMOP/OHDSI: Extensible CDM, standardized vocabularies, community conventions for linkages and provenance.

## 13) Value and access: HEOR at network scale
- Vision: Consistent, transparent cost, resource utilization, and budget impact analyses across systems and countries.
- Enables:
  - Comparable value assessments, scenario testing, policy evaluation.
- Why OMOP/OHDSI: Standard cost tables, unit harmonization, reusable economic analysis packages.

## 14) From question to answer in days—not months
- Vision: A turnkey pipeline where a clinical or policy question becomes a vetted, multi-database answer with diagnostics and sensitivity analyses in days.
- Enables:
  - Rapid decision support during shortages, safety crises, or policy windows.
- Why OMOP/OHDSI: Study-a-thon playbook, open-source methods library, containerized execution, network governance norms.

---

## Why OMOP/OHDSI makes these visions credible
- Standardized data and vocabularies ensure apples-to-apples measurement across sites.
- Reproducible open-source methods (safety, effect estimation, prediction) with diagnostics and calibration reduce avoidable bias.
- Distributed, privacy-preserving execution enables global scale without centralizing data.
- Transparent study artifacts (protocols, code, results) support scrutiny, replication, and trust.

## Pragmatic next steps to advance one of these
- Map data comprehensively to OMOP and run DataQualityDashboard to establish fitness-for-purpose.
- Contribute or adopt validated phenotypes; run CohortDiagnostics before analysis.
- Use negative/positive controls and pre-specify design choices; share full study packages for replication.
- Start with a focused “mini all-by-all” (e.g., one drug class × curated outcome set) and scale once diagnostics look strong.
- Publish study artifacts and results to foster reuse and critique.

If you had to pick one area to prioritize—safety, effectiveness, prediction, equity, or HEOR—which aligns best with your goals? I can outline a concrete, step-by-step plan and the specific OHDSI packages to use.

*This is an AI generated response.


# 2026-05-01 genAI ideas for session 

# OHDSI Plenary: Customizing the Tool Stack — Interleaved Run-of-Show and Facilitation Plan

## Session goals (unchanged)
- Showcase five real-world OHDSI customizations and their value.
- Engage the room mid-session to co-create Mad Libs that surface needs and ideas.
- Capture themes to route into OHDSI working groups, repos, and follow-up collaborations.

## 60-minute agenda (interleaved format)
- 0:00–0:04 Welcome and setup (4 min)
  - Walk-in slide with QR code/short URL for the Mad Lib form (open from the start).
  - MC frames the purpose, flow, and how to participate.
- 0:04–0:14 Lightning talks 1–2 (10 min)
  - Two presenters at ~5 minutes each. Each opens with a filled Mad Lib slide.
- 0:14–0:20 Audience Mad Lib Sprint 1 (6 min)
  - 1 min: MC instructions + quick live demo.
  - 3 min: Build time (attendees submit via form; paper fallback available).
  - 2 min: 2–3 quick share-outs (MC reads curated entries).
- 0:20–0:30 Lightning talks 3–4 (10 min)
  - Two presenters at ~5 minutes each, same format.
- 0:30–0:36 Audience Mad Lib Sprint 2 (6 min)
  - 45 sec: Prompt pivot (new template/focus).
  - 3 min: Build time.
  - 2–3 min: 2–3 quick share-outs.
- 0:36–0:41 Lightning talk 5 (5 min)
  - Final presenter at ~5 minutes.
- 0:41–0:56 Share-outs and synthesis (15 min)
  - 6–8 strong entries across both sprints (≈90 sec each): MC reads 4–5; invite 2–3 authors to add one-sentence context.
  - MC surfaces 3 themes and links to OHDSI next steps (working groups, forum thread, repos).
- 0:56–1:00 Call to action and close (4 min)
  - Where to continue discussion, how to access compiled Mad Libs, and a quick thanks.

## Round focus and templates
- Sprint 1 (after Talks 1–2): “What we changed and why it mattered”
  - Template A (implementation)
    - “We used [OHDSI tool/package] to [verb] [data type/concepts] from [source/context], enabling [capability/outcome] for [stakeholders/use case].”
- Sprint 2 (after Talks 3–4): “What we wish existed next”
  - Template D (wishlist/future)
    - “We wish [OHDSI tool/area] could [capability] so [stakeholders] can [outcome]. We can contribute [resource/commitment] to make it happen.”

## Word banks (shown in form and on slides)
- OHDSI tool/package: ATLAS, Achilles, DataQualityDashboard, CohortDiagnostics, PLP, Hydra, PheValuator, Usagi, WhiteRabbit, RabbitInAHat, HADES (R packages)
- Verbs: automated, harmonized, validated, enriched, containerized, parallelized, orchestrated, annotated, refactored
- Data types/concepts: claims, EHR, registries, devices, PROs, wearables, vocabularies, concept sets
- Source/context: multi-site network, national dataset, hospital system, payer data, research registry
- Capabilities/outcomes: faster cohort builds, reproducible pipelines, improved mapping accuracy, timely feasibility counts, transparent results, scalable computation
- Stakeholders/use cases: clinicians, researchers, data stewards, pharmacovigilance, comparative effectiveness, phenotyping, prediction
- Wishlist resources/commitments: sample data, testing time, documentation, code, governance alignment, funding, mentorship

## MC scripts and cues
- Opening (60–90 seconds)
  - “Welcome! You’ll hear five fast stories on how teams customized OHDSI—and we’ll co-create ideas in two short Mad Lib sprints. Scan the QR code now; the link is open. In each sprint, you’ll submit one sentence; we’ll share a few live and then synthesize themes and next steps.”
- Transition into Sprint 1 (10–15 seconds)
  - “You’ve heard two examples—now it’s your turn. Open the form. Pick Template A and fill in how you’ve customized or plan to customize the stack. Be specific about the tool and outcome; no sensitive data or names.”
- Sprint 1 demo (30 seconds)
  - “Example: ‘We used CohortDiagnostics to validate concept sets from a multi-site network, enabling transparent results for phenotyping.’”
- Sprint 1 share-outs (2–3 entries)
  - MC reads briskly, then one-sentence synthesis: “Theme: mapping accuracy and speed-to-insight.”
- Transition into Sprint 2
  - “Next two talks will spark ideas for what’s missing. After that, we’ll craft wish-list Mad Libs.”
- Sprint 2 prompt (45 seconds)
  - “For Sprint 2, use the wishlist template. Name a capability you wish existed and how you’d contribute. Example: ‘We wish ATLAS could version concept sets natively so data stewards can audit changes. We can contribute testing and docs.’”
- Final synthesis
  - “We’re seeing clusters around data quality visualization, automation of cohort pipelines, and vocabulary tooling. Here’s where to take these ideas…”

## Presenter guidance (unchanged, but timed)
- 2–3 slides max:
  - Slide 1: Filled Mad Lib opener (large type, single sentence).
  - Slide 2–3: Problem → customization → impact → portability/reuse and one “ask” to the community.
- Time: 4:30 talking + 30 seconds buffer. MC will cue at 4:30.

## Audience activity mechanics
- Digital capture (preferred)
  - One form with two tabs/sections (Sprint 1: Template A; Sprint 2: Template D).
  - Each blank uses a dropdown with “Other” free-text option.
  - Optional non-identifying tags: tool, use case, region, org type.
  - Back-end: moderator view to tag and pin a shortlist; large-font “reader mode” for on-stage display.
- Paper fallback
  - Half-sheet cards printed with both templates (front/back).
  - After Talks 1–2, volunteers hand cards; collect 2 minutes later.
  - Repeat after Talks 3–4.

## Curation rubric for share-outs
- Balance: at least one entry each for ETL/vocabulary, analytics/workflows, visualization/reporting.
- Diversity: different org types (academic, payer, health system) and regions when available.
- Clarity: short, specific, outcome-focused; skip anything with sensitive info or names.
- Novelty: favor ideas that could seed community contributions.

## Roles and responsibilities
- MC
  - Keep time and energy, explain sprints clearly, and enforce “no sensitive data or names.”
  - Read curated entries, invite 2–3 authors to add one sentence of context.
- Tech/ops lead
  - Manage form, tag responses, pin shortlisted entries.
  - Keep a visible 60-minute timer for the MC.
  - Prepare 6–8 seeded entries as back-up for low participation or time compression.
- Volunteers/mic runners
  - Circulate during build minutes; encourage submissions.
  - Handheld mics for brief author comments (room-size dependent).
- Presenters
  - Coordinate to avoid tool overlap; align on consistent Mad Lib slide style.

## Slide and room setup
- Walk-in / holding slide
  - Session title; QR code + short URL; “We’ll ask you to contribute twice—scan now.”
- Sprint slides
  - Template A and Template D shown in large font with word banks on the side.
  - A countdown timer on screen during build minutes helps pace the room.
- Share-out slides
  - Reader mode shows one Mad Lib at a time in very large text for on-stage reading.
- Hybrid note
  - Remote attendees submit via the same link; recognize at least one remote entry.

## Contingencies
- If Talks 1–2 run long: Convert Sprint 1 to “read pre-seeded examples” (skip build), keep Sprint 2 as live build.
- If live form fails: Switch to paper cards; MC reads 4–6 entries; shorten share-outs.
- If participation is low: MC prompts by domain (“Anyone working with wearables? vocab mapping?”) and reads pre-seeded entries to model desired responses.
- If participation is high: Extend final synthesis share-outs by 2 minutes and cut one award or reduce MC commentary between reads.

## Micro-awards (optional, fast and fun)
- Most Reproducible Idea
- Biggest Impact with Small Change
- Best Tool Hack

## Materials checklist (prepare 1 week prior)
- Presenter deck template with Mad Lib opener slide.
- Form built and tested; short URL and QR code generated.
- 100–200 printed half-sheets with both templates; markers.
- Shortlist rubric and 10–12 pre-seeded examples (clearly labeled as seeds).
- Forum thread link created for post-session recap and ongoing discussion.

## Want me to tailor the timing and prompts?
Share expected room size (and hybrid status), the five tools/customizations your speakers will cover, and whether you prefer more share-outs or more build time. I can then:
- Tune the sprint lengths and share-out counts.
- Draft exact on-screen slides and the form fields.
- Prepare a curated shortlist aligned to your speakers’ topics and target working groups.

*This is an AI generated response.


# Plenary submission 

1. Name(s) of the plenary session organizers
William J. O’Brien
Scott DuVall, PhD
________________________________________
2. Organizer email address(es)
wobrien8@its.jnj.com 
sduvall@purplelab.com 
________________________________________
3. Short description / abstract (~350 words)
Title:
"Beyond the Defaults: How the OHDSI Community is Adapting, Extending, and Reimagining Its Tools"
Abstract:
The OHDSI open-source ecosystem provides a rich toolkit for observational health data research, and some of its impactful advances emerge when organizations adapt, extend, and integrate them in novel ways to meet local needs. This plenary showcases how institutions around the world are reimagining OHDSI tools—such as ATLAS, WebAPI, HADES packages, and standardized vocabularies—to solve real-world problems beyond their default use cases. 
These adaptations create both opportunity and risk. Innovation accelerates, but heterogeneity can challenge shared standards, scalability, and sustainability. Drawing on concrete examples, this session surface common patterns across implementations, identify where approaches converge or diverge, and explore how community-driven contributions can fuel the next decade of OHDSI development.
Through a series of rapid, focused presentations, representatives from four organizations will share how they use and contribute back to the OHDSI ecosystem, including: embarking on the OHDSI Journey in emerging research settings; collaboratively optimizing OHDSI tools for performance; extending OHDSI workflows for local research pipelines; introducing new analytic methods; and adapting OHDSI tools to comply with institutional requirements.
The session will blend short keynote/lightning talks (6-8 minutes each) with an interactive, hands-on activity. Each speaker will introduce a simple “mad lib” template related to how they modified an OHDSI tool for their purpose. Attendees, working in small groups with magnetic poetry tiles, will complete these templates using their own experience, constraints, and wish lists. Selected entries from these crowd-sourced submissions will be read aloud, celebrating both the practical and the absurd, and connecting them to real‑world use cases. A curated collection will be published on the OHDSI community forum after the symposium to inspire new projects.
By pairing real-world examples with participatory engagement, this plenary aims to inspire attendees to think beyond default use cases—encouraging customization, contribution, and collaboration while strengthening OHDSI as a shared, evolving community resource.
________________________________________
4. Which OHDSI pillars are you targeting
☑ Open community data standards
☑ Open-source development
☑ Clinical applications
________________________________________
5. One-sentence pitch
"See how organizations around the globe are bending, extending, and supercharging OHDSI tools to tackle unique challenges—and get inspired to build your own custom solutions."
________________________________________
6. Names and roles of individuals who have tentatively agreed to participate
•	We are working to finalize the inclusion of a member of the OHDSI Africa community to participate 
•	Cindy Chen, Columbia University, will describe how they created new methods that fit within the OHDSI workflow
•	William J. O’Brien, Johnson & Johnson, will discuss contributing SQL refactoring and testing a new database technology within the official OHDSI stack when he was at the Department of Veterans Affairs
•	Martin Lavalee, Boehringer Ingelheim, will discuss how they modified OHDSI for their research pipeline
•	Hanieh Razzaghi, Children's Hospital of Philadelphia, will introduce how they’ve modified OHDSI tools to run in their environment
