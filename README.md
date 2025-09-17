# 📊 Data Science Portfolio – Lee Minki

## 👋 About Me
- Data Scientist with expertise in **machine learning, optimization, and large-scale data systems**  
- Ph.D. in Computer Science & Engineering (Seoul National University)  
- Experience across **advertising technology (ad tech), computer vision**, and **time-series data quality & anomaly detection (sensor/log data)**  
- Passionate about turning data into actionable insights that drive real-world impact  

---

## 🛠 Technical Skills
- **Programming:** Python, C, C++, Java, SQL  
- **ML/AI Frameworks:** PyTorch, TensorFlow  
- **Data & Tools:** BigQuery, Airflow, Docker, Looker, GitHub  

---

## 📂 Case Studies

### 1) Campaign Anomaly Detection (Moloco, 2023–2025)
**Context:** Hidden performance issues in large-scale campaigns can quickly erode efficiency and ROI if left undetected.  
**Approach:** I designed and implemented an anomaly detection system that combined rule-based logic with statistical models. Supporting pipelines and monitoring workflows were built on **BigQuery** and **Airflow** and ran as **scheduled jobs** (hourly or daily), aggregating campaign metrics, applying detection logic, and emitting alerts for follow-up. The detection thresholds and logic were iteratively refined to expand coverage and improve accuracy while maintaining interpretability for stakeholders.  
**Impact:** The system detected **60%+** of campaign issues at **85%+** precision, enabling earlier escalation and corrective actions, reducing performance degradation, and strengthening client trust.  
**Key Learnings:** In high-volume environments, well-designed **scheduled pipelines** can strike a pragmatic balance among scalability, accuracy, and operational cost without always requiring real-time streaming.

---

### 2) Campaign Performance Estimation Under Budget Changes (Moloco, 2022)
**Context:** Advertisers needed to understand how key KPIs would change under different budget scenarios to make informed allocation decisions.  
**Approach:** I developed an estimation model to predict campaign KPIs under varying budget levels and validated robustness via controlled **A/B tests** across **100+ campaigns**, measuring accuracy and consistency across settings.  
**Impact:** The model achieved **90%+** prediction accuracy and became a reliable guide for budget adjustments, reducing the risk of under- or over-investment.  
**Key Learnings:** Forecasting in dynamic ad environments requires strong statistical modeling **and** rigorous experimental validation to ensure business actionability.

---

### 3) Campaign Optimization (Moloco, 2022–2025)
**Context:** Advertisers needed actionable strategies to improve efficiency and maximize ROI.  
**Approach:** I analyzed performance metrics, market trends, and competitor benchmarks to identify optimization levers, designed and executed controlled experiments to validate hypotheses, and partnered with clients to translate findings into concrete strategy changes.  
**Impact:** The work delivered measurable improvements in **key campaign KPIs** and supported client **budget expansions** by demonstrating sustainable ROI.  
**Key Learnings:** Effective optimization blends rigorous analytics with business context so insights translate into tangible performance gains.

---

### 4) AI for Multimedia Enhancement (Samsung Electronics, 2020–2021)

#### 4-1) Deep Learning for Video Enhancement
**Context:** Consumer **display devices** demand smoother playback and higher frame quality, yet efficient frame enhancement is challenging.  
**Approach:** Rather than adopt a single SOTA model, I **surveyed multiple cutting-edge papers** and **evaluated their released codes** to map strengths and weaknesses across scenarios. From these findings, I proposed a **new architecture** that overcame key limitations and engineered it to balance accuracy with computational efficiency for product-oriented use.  
**Impact:** Although the model was **not immediately deployed** on devices, it **outperformed prior SOTA** on challenging video test cases and **laid the groundwork** for future product integration as a **preliminary/advanced research** effort.  
**Key Learnings:** Advancing beyond SOTA often requires critical evaluation of existing methods and **novel architectural ideas** tuned for real-world deployment constraints.

#### 4-2) Deep Learning-based Music Generation
**Context:** Certain **display devices** required large volumes of **copyright-safe BGM**, and manual production was resource-intensive.  
**Approach:** I adapted **language-model architectures** to musical sequence modeling to generate scalable, copyright-free BGM; tracks were curated and applied to product use cases (the model itself was not embedded). Listening sessions indicated the music did not sound “AI-generated.”  
**Impact:** Demonstrated a practical path for copyright-safe content production; exploratory scope with limited footprint relative to core projects.

---

### 5) Observational Data Quality & Anomaly Correction (Ph.D. + National Weather Agency Collaboration, 2014–2018)
**Context:** Sensor-based **observational data** (e.g., weather observations) often contain anomalies from device faults and transmission errors, which distort downstream analysis and forecasting.  
**Approach:** In collaboration with the national weather agency, I developed ML approaches (e.g., **Support Vector Regression**) to detect anomalies in **observational data** and implemented automatic correction mechanisms to replace abnormal values with valid estimates—focusing on scalable pipelines and data credibility for downstream users.  
**Impact:** The work improved dataset reliability used for national-scale forecasting and decision making, and was published in peer-reviewed venues (IEEE SMC 2014, Advances in Meteorology 2018).  
**Key Learnings:** In data-critical domains, **input quality assurance** via anomaly detection/correction is as vital as improving predictive models.

---

### 6) Semiconductor Process Optimization (Ph.D. + Samsung Collaboration)
**Context:** Efficiently allocating processes across equipment is a core challenge in semiconductor manufacturing with direct implications for throughput and cost.  
**Approach:** I applied **Genetic Algorithms** to optimize process–equipment allocation under realistic production constraints, modeling domain rules to ensure adoptability on the floor.  
**Impact:** The approach improved manufacturing efficiency and throughput and demonstrated how optimization research can transfer into industry settings.  
**Key Learnings:** Algorithmic innovation delivers impact when it is aligned with real-world constraints and operational realities.

---

### 7) Smart Grid Power Consumption Modeling (Ph.D. + Samsung Collaboration)
**Context:** Smart grid systems require efficient device-level power management to balance cost and energy stability.  
**Approach:** I modeled household/device-level consumption patterns and designed scheduling and output-level adjustment algorithms that balanced **productivity (efficiency)** with **continuity (minimal disruption to existing usage)**.  
**Impact:** The algorithms enabled more efficient, reliable power management in smart-grid settings and illustrated the value of AI-driven optimization for large-scale energy systems.  
**Key Learnings:** Integrating predictive modeling with optimization is crucial where **efficiency and stability** must improve together.

---

## 📄 Publications
- **Detecting Anomalies in Meteorological Data Using Support Vector Regression** — *Advances in Meteorology (SCIE), 2018*  
- **Correcting Abnormalities in Meteorological Data by Machine Learning** — *IEEE International Conference on Systems, Man, and Cybernetics, 2014*  

---

## 📬 Contact
- 📧 Email: **imradris@gmail.com**  
- 🔗 LinkedIn: **https://www.linkedin.com/in/minki-lee-3083bb193/**
