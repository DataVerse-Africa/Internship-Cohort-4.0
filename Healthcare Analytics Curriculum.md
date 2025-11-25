# Healthcare Analytics - Intermediate Track
## Data Analytics Curriculum | 3-Month Program
### DataVerse Africa Internship Division | Cohort 4.0

---

## 📋 **Program Overview**

**Duration:** 12 Weeks (3 Months)  
**Domain:** Healthcare Analytics  
**Track Level:** Intermediate  
**Delivery Mode:** 100% Project-Based Learning  
**Industry Focus:** Hospital Operations, Patient Care, Public Health, Clinical Research  
**Target Outcome:** Healthcare data analysts ready for hospital systems, health tech, insurance, and NGO roles

---

## 🎯 **Healthcare-Specific Learning Objectives**

By the end of this track, interns will be able to:
- Analyze patient care data and clinical outcomes
- Build hospital operational dashboards (bed occupancy, ER wait times, readmission rates)
- Work with Electronic Health Records (EHR) data structures
- Understand healthcare KPIs and quality metrics (HEDIS, HCAHPS)
- Apply epidemiological analysis techniques
- Ensure HIPAA compliance and patient data privacy
- Create disease surveillance and outbreak detection systems
- Analyze healthcare costs and resource utilization
- Build predictive models for patient risk stratification
- Communicate healthcare insights to clinical and non-clinical audiences

---

## 🏥 **Core Healthcare Metrics Covered**

- Patient admission & discharge rates
- Length of Stay (LOS) analysis
- Readmission rates (30-day, 90-day)
- Mortality rates & survival analysis
- Emergency Department (ED) wait times
- Bed occupancy & capacity planning
- Healthcare-Associated Infections (HAIs)
- Patient satisfaction scores (HCAHPS)
- Clinical quality indicators
- Cost per patient encounter
- Disease prevalence & incidence rates
- Vaccination coverage rates

---

## 📊 **Tools & Technologies Stack**

### **Primary Tools:**
- **Excel/Google Sheets:** Healthcare data cleaning & initial analysis
- **SQL:** EHR database queries, patient cohort analysis
- **Power BI:** Clinical dashboards & hospital operations reporting
- **Tableau:** Public health visualization & geographic analysis
- **Python:** Epidemiological modeling, survival analysis

### **Healthcare-Specific Tools:**
- Synthetic EHR datasets (MIMIC, Synthea)
- ICD-10 & CPT coding systems
- HL7 FHIR data standards (introduction)
- DHIS2 (for public health projects)

---

## 📅 **12-Week Curriculum Structure**

---

### **MONTH 1: HEALTHCARE FUNDAMENTALS & PATIENT CARE ANALYTICS**

---

#### **Week 1: Healthcare Analytics Foundations**

**Learning Outcomes:**
- Understand healthcare data landscape (EHR, claims, clinical trials, public health)
- Master healthcare terminology and metrics
- Learn HIPAA compliance basics
- Navigate healthcare data structures

**Key Topics:**
- Healthcare industry overview & data ecosystem
- Patient care continuum (prevention → diagnosis → treatment → follow-up)
- Healthcare Key Performance Indicators (KPIs)
- Data privacy regulations: HIPAA, GDPR in healthcare
- Healthcare data types: Structured (EHR) vs Unstructured (clinical notes)
- ICD-10 diagnosis codes & CPT procedure codes
- Healthcare data quality challenges

**Hands-On Activities:**
- Case study: Analyzing a sample EHR dataset structure
- Exercise: Mapping patient journey data points
- Quiz: Healthcare terminology & HIPAA fundamentals

**Deliverable:** 
- **Mini Project 1:** "Understanding Your Hospital Dashboard" - Analyze a sample hospital performance report and identify 10 key metrics with explanations

**Tools:** Excel, Google Sheets

---

#### **Week 2: Patient Admission & Discharge Analysis**

**🎤 DOMAIN EXPERT SESSION #1: "Real-World Hospital Data Challenges"**
- **Guest:** Hospital Data Manager / Health Informatics Director
- **Duration:** 90 minutes (Live Q&A)
- **Topics:** EHR data quality issues, working with clinical teams, career pathways
- **Assignment:** Interns prepare questions based on Week 1 learnings

**Learning Outcomes:**
- Analyze patient flow through healthcare facilities
- Calculate Length of Stay (LOS) and identify patterns
- Understand admission source and discharge disposition
- Build basic patient flow dashboards

**Key Topics:**
- Admission types (emergency, elective, urgent)
- Discharge disposition (home, rehab, skilled nursing, expired)
- Average Length of Stay (ALOS) calculations
- Peak admission times & seasonal patterns
- Bed turnover analysis
- Patient demographics in admissions

**SQL Focus:**
- JOIN operations across patient, admission, and diagnosis tables
- Date calculations for LOS
- GROUP BY for aggregating patient volumes
- Window functions for running totals

**Hands-On Activities:**
- Dataset: 5000+ patient admission records from fictional hospital
- Exercise: Calculate ALOS by department
- Exercise: Identify peak admission hours
- Exercise: Analyze readmission patterns

**Deliverable:**
- **Project 1A:** "Hospital Patient Flow Analysis Dashboard"
  - Part 1: SQL queries to extract admission metrics
  - Part 2: Power BI dashboard showing:
    - Daily admissions trend
    - ALOS by department
    - Admission source breakdown
    - Discharge disposition distribution
    - Peak admission times heatmap

**Tools:** SQL, Power BI, Excel

---

#### **Week 3: Emergency Department (ED) Performance Analysis**

**Learning Outcomes:**
- Analyze ED wait times and throughput
- Identify bottlenecks in emergency care
- Calculate ED quality metrics
- Understand triage levels and patient acuity

**Key Topics:**
- ED patient journey: Arrival → Triage → Provider → Discharge/Admit
- Door-to-Doctor time metrics
- Left Without Being Seen (LWBS) rates
- ED boarding and overcrowding
- Triage levels (ESI 1-5 system)
- ED capacity planning
- Ambulance diversion analysis

**Power BI Focus:**
- Time-based calculations (DATEDIFF)
- Creating calculated columns for wait time buckets
- Conditional formatting for target compliance
- Drill-through pages for patient-level detail

**Hands-On Activities:**
- Dataset: 10,000 ED visits with timestamps
- Exercise: Calculate door-to-doctor times
- Exercise: Identify factors contributing to long waits
- Exercise: Analyze LWBS patterns

**Deliverable:**
- **Project 1B:** "Emergency Department Performance Dashboard"
  - Average wait time by hour of day
  - LWBS rate analysis
  - Triage level distribution
  - Door-to-doctor time compliance (target: <60 mins)
  - Staff-to-patient ratio impact analysis
  - Actionable recommendations report (2-page written)

**Tools:** Power BI, SQL, Excel

---

#### **Week 4: Hospital Readmissions & Quality Metrics**

**Learning Outcomes:**
- Calculate 30-day readmission rates
- Identify high-risk patient populations
- Understand CMS quality measures
- Build predictive risk scores (basic)

**Key Topics:**
- 30-day, 60-day, 90-day readmission rates
- CMS Hospital Readmissions Reduction Program (HRRP)
- Risk factors for readmission (age, comorbidities, social determinants)
- Planned vs unplanned readmissions
- Readmission prevention strategies
- Quality metrics: Mortality rates, complication rates

**Advanced SQL:**
- Self-joins to identify readmissions
- LAG/LEAD window functions for previous admissions
- CASE statements for risk categorization
- Subqueries for complex filtering

**Hands-On Activities:**
- Dataset: 3-year patient admission history
- Exercise: Identify all readmissions within 30 days
- Exercise: Calculate readmission rate by diagnosis
- Exercise: Build a simple risk score model

**Deliverable:**
- **Major Project 1:** "Hospital Readmission Reduction Analysis"
  - SQL script to identify all readmissions
  - Power BI dashboard with:
    - Overall 30-day readmission rate
    - Readmission trends over time
    - Top diagnosis codes with highest readmission
    - High-risk patient characteristics
    - Geographic analysis (if zip codes available)
  - Written report: 5 data-driven recommendations to reduce readmissions
  - Presentation: 10-minute stakeholder briefing

**Tools:** SQL, Power BI, PowerPoint

**Week 4 Checkpoint:** Portfolio Review & Mentor Feedback Session

---

### **MONTH 2: CLINICAL OUTCOMES & PUBLIC HEALTH ANALYTICS**

---

#### **Week 5: Disease Prevalence & Epidemiological Analysis**

**🎤 DOMAIN EXPERT SESSION #2: "Public Health Data in Action"**
- **Guest Panel:** Public Health Data Scientist + Epidemiologist + NGO Program Manager
- **Duration:** 2 hours (Presentation + Workshop)
- **Topics:** 
  - How data drives disease prevention programs
  - COVID-19 response: Lessons in data surveillance
  - Working with Ministries of Health
  - Career opportunities in public health analytics
- **Interactive Activity:** Live case study - Analyzing an outbreak scenario
- **Networking:** 30-minute informal Q&A session

**Learning Outcomes:**
- Calculate disease prevalence and incidence rates
- Analyze disease distribution by demographics
- Understand epidemiological study designs
- Create disease surveillance dashboards

**Key Topics:**
- Prevalence vs Incidence calculations
- Age-standardized rates
- Disease burden analysis
- Comorbidity patterns (e.g., diabetes + hypertension)
- Geographic disease mapping
- Social determinants of health (SDOH)
- Health disparities analysis

**Tableau Focus:**
- Geographic mapping (choropleth maps)
- Dual-axis charts for comparisons
- Parameter-based filtering
- Public health visualization best practices

**Hands-On Activities:**
- Dataset: 50,000 patient records with diagnoses
- Exercise: Calculate diabetes prevalence by age group
- Exercise: Map disease prevalence by region
- Exercise: Identify comorbidity clusters

**Deliverable:**
- **Project 2A:** "Regional Disease Burden Analysis"
  - Tableau dashboard showing:
    - Disease prevalence map by county/region
    - Age-gender distribution of top 10 conditions
    - Comorbidity network visualization
    - Trend analysis over 5 years
    - Health equity analysis by socioeconomic status
  - Written brief: Key findings and public health implications

**Tools:** Tableau, SQL, Excel

---

#### **Week 6: Maternal & Child Health Analytics**

**Learning Outcomes:**
- Analyze maternal health outcomes
- Calculate infant and maternal mortality rates
- Understand prenatal care quality metrics
- Build MCH monitoring dashboards

**Key Topics:**
- Antenatal care (ANC) visit compliance
- Pregnancy complications and outcomes
- Low birth weight analysis
- Immunization coverage rates
- Maternal mortality ratio (MMR)
- Neonatal mortality rate (NMR)
- Family planning indicators
- Nutrition and growth monitoring

**Advanced Analytics:**
- Cohort analysis (pregnancy cohorts)
- Survival analysis basics
- Time-to-event calculations
- Risk-adjusted outcomes

**Hands-On Activities:**
- Dataset: Maternal health records (inspired by real African contexts)
- Exercise: Calculate ANC 4+ visit coverage
- Exercise: Identify high-risk pregnancies
- Exercise: Analyze birth outcome disparities

**Deliverable:**
- **Project 2B:** "Maternal Health Risk Detection System"
  - Power BI dashboard with:
    - ANC visit compliance tracker
    - High-risk pregnancy identification
    - Birth outcome analysis (preterm, low birth weight)
    - Maternal complications by facility
    - Geographic access to maternal care
  - Automated alert system design (conceptual)
  - Policy recommendation report

**Tools:** Power BI, SQL, Excel

---

#### **Week 7: Healthcare Cost & Resource Utilization Analysis**

**Learning Outcomes:**
- Analyze healthcare spending patterns
- Calculate cost per patient encounter
- Understand value-based care metrics
- Optimize resource allocation

**Key Topics:**
- Cost per procedure/diagnosis
- Hospital operating margins
- Payer mix analysis (insurance, out-of-pocket, government)
- Length of stay impact on costs
- High-cost patient identification
- Resource utilization (OR time, imaging, lab tests)
- Value-based care: Cost + Quality
- Budget variance analysis

**Excel/Power BI Advanced:**
- DAX measures for cost calculations
- What-if scenarios
- Financial forecasting basics
- Profitability analysis by service line

**Hands-On Activities:**
- Dataset: Hospital financial and clinical data
- Exercise: Calculate true cost per patient
- Exercise: Identify cost drivers for expensive stays
- Exercise: Build budget vs actual analysis

**Deliverable:**
- **Project 2C:** "Healthcare Cost Optimization Analysis"
  - Excel financial model with:
    - Cost per patient by department
    - Revenue vs cost analysis
    - High-cost outlier identification
  - Power BI executive dashboard:
    - Operating margin trends
    - Cost per case by diagnosis
    - Resource utilization efficiency metrics
    - ROI of quality improvement initiatives
  - Strategic recommendations: Cost reduction opportunities

**Tools:** Excel (advanced), Power BI, SQL

---

#### **Week 8: Clinical Quality Indicators & Patient Safety**

**🎤 DOMAIN EXPERT SESSION #3: "Healthcare Technology & Innovation"**
- **Guest:** Health Tech Startup Founder + Healthcare BI Consultant
- **Duration:** 90 minutes
- **Topics:**
  - Building data products for healthcare
  - AI/ML in clinical decision support
  - Healthcare analytics market landscape in Africa
  - Transitioning from analyst to product manager
- **Demo:** Live walkthrough of a commercial healthcare analytics platform
- **Career Insights:** Job hunting strategies and portfolio tips

**💼 BONUS: Industry Partner Showcase**
- **Partner:** Healthcare IT Vendor or Hospital System
- **Activity:** Interns present their Week 1-7 projects to real stakeholders
- **Feedback:** Get professional critique and improvement suggestions
- **Opportunity:** Top performers may get interview opportunities

**Learning Outcomes:**
- Track clinical quality measures
- Analyze patient safety events
- Calculate Hospital-Acquired Infection (HAI) rates
- Build quality improvement dashboards

**Key Topics:**
- HEDIS quality measures
- HCAHPS patient satisfaction scores
- Hospital-Acquired Infections (CLABSI, CAUTI, SSI)
- Medication errors and adverse events
- Fall rates and pressure ulcers
- Sepsis early warning scores
- Quality improvement methodologies (PDSA cycles)
- Benchmarking against national standards

**Statistical Analysis:**
- Control charts (SPC) for quality monitoring
- Statistical significance testing
- Confidence intervals
- Outlier detection

**Hands-On Activities:**
- Dataset: Quality metrics data from multiple hospitals
- Exercise: Calculate HAI rates
- Exercise: Create control charts for infection trends
- Exercise: Benchmark hospital performance

**Deliverable:**
- **Major Project 2:** "Clinical Quality & Patient Safety Dashboard"
  - Interactive Power BI dashboard:
    - Real-time quality metrics scorecard
    - Infection rate trends with control limits
    - Patient safety event analysis
    - HCAHPS score breakdown
    - Comparative performance vs benchmarks
  - Root cause analysis report for one quality issue
  - Quality improvement action plan
  - Executive presentation (15 minutes)

**Tools:** Power BI, SQL, Excel (statistical analysis)

**Week 8 Checkpoint:** Mid-Program Review & Portfolio Update

---

### **MONTH 3: ADVANCED HEALTHCARE ANALYTICS & CAPSTONE**

---

#### **Week 9: Predictive Analytics in Healthcare + Capstone Planning**

**🎯 CAPSTONE PROJECT LAUNCH**
- **Capstone Kickoff Session:** Introduction to final project requirements
- **Project Selection:** Interns choose their capstone topic by end of week
- **Proposal Submission:** 2-page project proposal with scope, objectives, datasets
- **Mentor Assignment:** Each intern paired with dedicated capstone mentor

**Learning Outcomes:**
- Build patient risk prediction models
- Apply machine learning basics to healthcare
- Understand predictive modeling ethics
- Create early warning systems
- Plan comprehensive capstone project

**Key Topics:**
- Risk stratification models
- Predictive modeling for readmissions
- Disease progression forecasting
- No-show prediction
- Sepsis early warning scores
- Model validation and accuracy metrics
- Ethical considerations in predictive healthcare
- Algorithmic bias in healthcare AI

**Tools Introduction:**
- Python (pandas, scikit-learn) - Optional but encouraged
- Power BI AI visuals (key influencers, decomposition tree)
- Excel regression analysis

**Hands-On Activities:**
- Dataset: Patient data with outcomes
- Exercise: Build readmission risk score in Excel
- Exercise: Use Power BI Key Influencers visual
- Exercise: Validate model performance

**Deliverable:**
- **Project 3A:** "Patient Risk Prediction Model"
  - Risk score calculator (Excel or Python)
  - Power BI dashboard showing:
    - High-risk patient identification
    - Key risk factors visualization
    - Model performance metrics
    - Clinical decision support interface mockup
  - Ethics assessment: Potential biases and mitigation strategies
  - Implementation plan for clinical use
- **Capstone Proposal:** Detailed project plan for Weeks 10-12

**Tools:** Power BI, Excel, Python (optional)

---

#### **Week 10: Healthcare Data Storytelling & Capstone Development (Phase 1)**

**🎤 DOMAIN EXPERT SESSION #4: "From Analysis to Impact"**
- **Guest:** Healthcare Policy Advisor or Ministry of Health Data Team Lead
- **Duration:** 2 hours
- **Topics:**
  - How data influences healthcare policy and funding decisions
  - Communicating with policymakers and government officials
  - Case study: Data-driven policy change in African healthcare
  - The role of analytics in Universal Health Coverage (UHC)
- **Workshop:** Interns present a healthcare issue analysis to the guest as if presenting to decision-makers
- **Feedback:** Professional critique on communication effectiveness

**Learning Outcomes:**
- Communicate complex healthcare data to non-technical audiences
- Build executive-ready presentations
- Write data-driven healthcare reports
- Master visual storytelling for health outcomes
- Execute capstone data collection and cleaning phase

**Key Topics:**
- Storytelling frameworks for healthcare
- Tailoring insights for different audiences (clinicians, executives, policymakers)
- Visualization best practices for health data
- Avoiding chart junk and misleading visuals
- Building compelling narratives from data
- Presenting sensitive health information ethically

**Communication Focus:**
- Executive summaries
- Clinical briefings
- Policy recommendations
- Patient-facing visualizations

**Capstone Phase 1 (Week 10):**
- Data collection and exploration
- Data cleaning and preparation
- Initial SQL queries and database setup
- Preliminary analysis and insights
- **Checkpoint:** Mid-capstone review with mentor (end of week)

**Hands-On Activities:**
- Exercise: Transform a complex analysis into a 1-page brief
- Exercise: Create 3 versions of same insight for different audiences
- Exercise: Peer review and feedback sessions

**Deliverable:**
- **Project 3B:** "Healthcare Data Communication Portfolio"
  - Executive dashboard (1-page, high-level)
  - Clinical deep-dive report (5-pages, detailed)
  - Policy brief (2-pages, action-oriented)
  - Patient-facing infographic
  - Video presentation (5 minutes) explaining a complex health issue
- **Capstone Checkpoint:** Data ready, preliminary insights documented

**Tools:** Power BI, PowerPoint, Canva, Loom

---

#### **Week 11: Capstone Development (Phase 2) - Analysis & Visualization**

**🎤 CAREER PREPARATION PANEL (Week 11, Day 1)**
- **Guests:** Healthcare Recruiters + Recent Alumni in Healthcare Analytics Roles
- **Duration:** 2 hours
- **Activities:**
  - Mock interviews with real recruiters
  - Resume and LinkedIn profile reviews
  - Salary negotiation workshop
  - Job search strategy session
- **Outcome:** Each intern gets personalized career action plan

**Capstone Phase 2 (Week 11):**
- Complete data analysis and modeling
- Build all dashboards and visualizations
- Develop written report (first draft)
- Create presentation slides
- **Daily Stand-ups:** 15-minute daily check-ins with mentors
- **Peer Review Session (Mid-week):** Interns present work-in-progress to peers for feedback
- **Technical Review (End of week):** Mentor validates technical accuracy

**Weekly Milestones:**
- Day 1-2: Complete all analysis and statistical tests
- Day 3-4: Build interactive dashboards
- Day 5-6: Write comprehensive report
- Day 7: Technical review and refinements

**Mentor Support:**
- Office hours every day
- Slack channel for quick questions
- Code/query review sessions

---

#### **Week 12: Capstone Finalization & Final Presentations**

**Capstone Phase 3 (Week 12, Days 1-4):**
- Finalize all deliverables
- Polish dashboards and visualizations
- Complete final report (15-20 pages)
- Prepare presentation (20-minute talk)
- Create video walkthrough
- Update GitHub repository with full documentation
- Build LinkedIn portfolio showcase post
- **Final Rehearsal (Day 4):** Practice presentation with mentors

**Capstone Final Week Schedule:**

**Day 1-2: Refinement & Quality Check**
- Incorporate mentor feedback from Week 11
- Final data validation
- Dashboard performance optimization
- Proofread report

**Day 3: Preparation & Rehearsal**
- Finalize presentation slides
- Practice delivery timing
- Prepare for Q&A scenarios
- Final mentor review

**Day 4: Dress Rehearsal**
- Full presentation run-through with mentors
- Technical setup testing
- Last-minute adjustments

**Day 5: 🏆 CAPSTONE FINAL PRESENTATIONS**
- **Audience:** Domain experts, mentors, industry partners, DataVerse leadership, fellow interns
- **Format:** 20-minute presentation + 10-minute Q&A per intern
- **Schedule:** 4-5 presentations per session (morning & afternoon sessions)
- **Judging Panel:** Mix of technical and non-technical healthcare professionals
- **Evaluation Criteria:**
  - Technical rigor and accuracy (30%)
  - Business impact and recommendations (25%)
  - Visualization quality and clarity (20%)
  - Communication effectiveness (15%)
  - Innovation and creativity (10%)

**Awards & Recognition:**
- 🥇 Best Overall Capstone Project
- 🎨 Most Innovative Solution
- 📊 Best Data Visualization
- 💬 Best Communication & Storytelling
- 🌍 Highest Social Impact Potential

**Post-Presentation:**
- Networking mixer with all guests (1.5 hours)
- One-on-one conversations with industry partners
- Group photo and celebration
- Certificate distribution ceremony

**Final Deliverables Due (Day 5, before presentations):**
- Interactive Power BI/Tableau dashboards (published online)
- Comprehensive written report (PDF, 15-20 pages)
- SQL scripts and data transformation code
- Presentation slides (PowerPoint/Google Slides)
- Video walkthrough (5-7 minutes, uploaded to YouTube/Loom)
- GitHub repository with full documentation
- LinkedIn portfolio post
- Project README file

**Capstone Project Options (Choose One):**

1. **"Hospital Operations Optimization Suite"**
   - Comprehensive dashboard covering admissions, ED, bed management, quality
   - Data pipeline from SQL to visualization
   - Strategic recommendations for hospital leadership

2. **"Public Health Disease Surveillance System"**
   - Real-time disease monitoring dashboard
   - Geographic outbreak detection
   - Predictive modeling for disease spread
   - Public health intervention recommendations

3. **"Maternal Health Outcomes Improvement Program"**
   - End-to-end analysis of maternal care in a region
   - Risk stratification model for high-risk pregnancies
   - Resource allocation recommendations
   - Impact assessment framework

4. **"Healthcare Cost-Quality Value Analysis"**
   - Comprehensive cost and quality analysis
   - Value-based care metrics
   - ROI analysis for quality initiatives
   - Strategic roadmap for value improvement

5. **"Custom Project with Real Partner"** (If available)
   - Work with actual hospital, NGO, or health ministry
   - Real-world data and business problem
   - Deliverable for actual implementation

**Capstone Requirements:**
- Data collection/cleaning (if using new data)
- SQL database queries and data transformations
- 3+ interactive dashboards
- Statistical analysis and insights
- Written report (15-20 pages)
- Final presentation (20 minutes + Q&A)
- GitHub repository with documentation
- Video walkthrough of solution

**Week 11:** Project execution, mentor check-ins
**Week 12:** Final presentation, peer review, portfolio refinement

---

## 🏆 **Assessment & Evaluation**

### **Grading Breakdown:**
- Weekly Mini-Projects: 20%
- Major Projects (3): 40%
- Capstone Project: 30%
- Participation & Peer Collaboration: 10%

### **Portfolio Deliverables:**
By program end, each intern will have:
- 8+ completed healthcare analytics projects
- 12+ dashboards (Power BI/Tableau)
- SQL query portfolio
- GitHub repository
- Professional LinkedIn portfolio showcase
- Video project walkthroughs

---

## 📖 **Required Resources**

### **Datasets:**
- MIMIC-III/MIMIC-IV (Critical Care Database)
- Synthea Synthetic Patient Data
- CDC Wonder Public Health Data
- WHO Global Health Observatory
- CMS Hospital Compare Data
- Medicare Claims Synthetic Data

### **Reading Materials:**
- "Healthcare Data Analytics" - Chandan K. Reddy
- CDC Data Visualization Guidelines
- HIPAA Compliance Guides
- Healthcare KPI Benchmarking Reports

### **Online Resources:**
- HealthData.gov
- Kaggle Healthcare Datasets
- Healthcare Analytics Blogs (Health Catalyst, HIMSS)

---

## 🎓 **Career Preparation**

### **Job Roles Prepared For:**
- Healthcare Data Analyst
- Clinical Data Analyst
- Hospital Operations Analyst
- Public Health Data Analyst
- Health Informatics Analyst
- Population Health Analyst
- Healthcare Business Intelligence Analyst

### **Skills Certified:**
- Healthcare data analysis
- HIPAA compliance
- Clinical quality metrics
- Population health management
- Healthcare visualization
- EHR data analysis

---

## 🤝 **Industry Partnerships & Guest Sessions**

### **Domain Expert Sessions Calendar:**

**Week 2 - Session #1: "Real-World Hospital Data Challenges"**
- Hospital Data Manager / Health Informatics Director
- Focus: Day-to-day analytics in hospital settings
- Format: Presentation + Live Q&A

**Week 5 - Session #2: "Public Health Data in Action"**
- Panel: Public Health Data Scientist + Epidemiologist + NGO Program Manager
- Focus: Disease surveillance, outbreak response, policy impact
- Format: Panel discussion + Interactive case study

**Week 8 - Session #3: "Healthcare Technology & Innovation"**
- Health Tech Founder + Healthcare BI Consultant
- Focus: Career pathways, industry trends, portfolio building
- Format: Fireside chat + Platform demo

**Week 8 (Bonus) - Industry Partner Showcase**
- Healthcare IT Vendor or Hospital System representatives
- Format: Intern project presentations + Professional feedback

**Week 10 - Session #4: "From Analysis to Impact"**
- Healthcare Policy Advisor or Health Minister Data Team
- Focus: How data influences healthcare policy decisions
- Format: Workshop + Case study review

**Week 11 - Career Preparation Panel**
- Healthcare recruiters + Recent graduates in healthcare analytics
- Focus: Job search strategies, interview prep, salary negotiation
- Format: Mock interviews + Resume reviews

### **Additional Industry Engagement:**

**Monthly Virtual Office Hours:**
- Rotating healthcare professionals available for 1-on-1 mentorship
- Career advice, portfolio reviews, industry questions

**LinkedIn Live Sessions:**
- Public sessions where interns showcase their projects
- Build professional brand and network

**Hospital/NGO Site Visits (If feasible):**
- Week 4: Visit local hospital data center
- Week 7: Tour public health surveillance facility
- Week 10: Attend health tech conference/meetup

---

## 📊 **Success Metrics**

- 90% project completion rate
- 100% of interns with portfolio-ready projects
- 80% report confidence in applying for healthcare analytics roles
- 70% secure interviews within 3 months of completion

---

**Program Design:** Promise Ibediogwu Ekele, Internship Coordinator  
**Last Updated:** November 2025  
**Version:** 1.0 - Healthcare Analytics Track