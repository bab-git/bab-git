# Bob Hosseini  
**Senior Data Scientist | GenAI & ML Systems | Team Lead**  
*Designing AI systems that scale and teams that ship.
*

### 💬 Let’s Connect   
Feel free to reach out for collaboration, professional opportunities, or just to swap ideas on building better GenAI systems.   
📫 [Email](mailto:bbkhosseini@gmail.com) • [LinkedIn](https://www.linkedin.com/in/bhosseini)

---

## 🔧 What I Do
- Lead development of GenAI systems using LLMs, RAG, and agentic pipelines
- Architect ML solutions from experimentation to scalable production
- Drive data product strategy and cross-functional execution in e-commerce
- Mentor data teams and implement best practices for ML/AI delivery
- Translate complex business problems into real-world AI products

---
---

## 🏢 Real-World AI Systems (Professional)

### 📞 LLM-Based Call Summarization

***Problem:*** Manual call logging was time-consuming and error-prone.   
***Solution:*** Developed a generative AI system summarizing 2,000+ calls/month using LLMs and audio transcripts.   
***Impact:*** Increased productivity and customer satisfaction.   
**Backend Tech:** OpenAI, LangChain, AWS Lambda, AWS S3, AWS CloudWatch, AWS SAM, Audio Preprocessing, Prompt Engineering, SQL    
**DevOps:** CLI, Bash
<!--
Impact: Increased productivity by 40% and improved customer satisfaction by 70%.
-->

---
<!--
### 📨 AI-Powered CRM Query System

***Problem:*** Customer support faced delays in processing email queries.
***Solution:*** Automated email classification and response generation with LLMs.
***Impact:*** Reduced workload by 60% and boosted response accuracy by 40%.
***Tech:*** LLMs, Email Parsing, FastAPI, LangChain

---
-->

### 📊 Data Analytics Assistant

***Problem:*** Business teams lacked real-time insights from complex data.   
***Solution:*** Built an LLM-powered dashboard enabling natural-language querying of business metrics.   
***Impact:*** Accelerated insight generation and decision-making.    
**Backend Tech:** LangChain, Google Cloud, LangGraph, SQL, Pandas, Prompt Eng.    
**Frontend Tech:**  Data Visualization, Streamlit

---
<!--
### 🧠 Intelligent Knowledge Base

***Problem:*** Internal knowledge was scattered across tickets and documents.
***Solution:*** Created a RAG-based knowledge system from historical conversations and documentation.
***Impact:*** Increased search precision and reduced onboarding time.
***Tech:*** RAG, ChromaDB, LangChain, Document Parsing

---
-->

### 🔄 Customer Churn Prediction

***Problem:*** Retention teams struggled to identify at-risk customers.   
***Solution:*** Built predictive models using behavior and transaction data.   
***Impact:*** Reduced churn by 20% via proactive outreach.   
**Backend Tech:** XGBoost, Scikit-learn, SHAP.   
**Frontend Tech:**  Data Visualization, Google Cloud, MLflow

<!--
***Impact:*** Reduced churn by 20% via proactive outreach.
-->

---

### 🛒 Product Recommendation Engine

***Problem:*** Users struggled to find relevant products in a large portfolio.   
***Solution:*** Developed collaborative and content-based recommendation system for a 55K-product catalog.   
***Impact:*** Boosted sales and improved user engagement.   
**Backend Tech:** FastAPI, Matrix Factorization, Pandas, PySpark   
**DevOps:** Docker, MLflow
<!--
***Impact:*** Boosted sales by 12% and improved user engagement.
-->

<!--

### 🧾 NLP for Invoice & Product Reports

***Problem:*** Reporting workflows were inefficient due to unstructured data.
***Solution:*** Applied NLP to standardize and improve quality of invoice descriptions and product listings.
***Impact:*** Improved reporting clarity and reduced review cycles.
***Tech:*** NLP, SpaCy, Regex, BERT Embeddings
-->


---
---

## 🧠 Generative AI Projects (Personal)

### 🔁**Two-Stage RAG for Document QA** 
`🟢 Production Ready - Backend + Frontend`   

**_Problem_:** Companies using AI for document search often suffer from poor precision or high compute costs. Traditional RAG systems either retrieve irrelevant content or waste resources. 

**_Data_:** Enterprise documents used in QA systems, requiring accurate and scalable semantic search.   

**_Solution_:** Designed a two-stage retrieval pipeline combining fast keyword search with precise semantic reranking, using Sentence Transformers and Cross-Encoders. Built with LangChain, ChromaDB, and Docker.   

**_Impact_:**
- Cut retrieval overhead by 75%
- Boosted precision and reduced latency for real-world document QA use cases
- Live demo deployed with a frontend for stakeholders and clients
  
▶️ [Live App](https://bbkhosseini--two-stage-conrag-run.modal.run/), [Medium Writeup](https://medium.com/@bbkhosseini/two-stage-consecutive-rag-for-document-qa-enhancing-precision-and-scalability-ac2af206babd), [GitHub](https://github.com/bab-git/two-stage-conrag)   
**Backend Tech:** RAG, Sentence Transformers, Cross-Encoder Reranker, LangChain, ChromaDB, Poetry  
**Frontend Tech:** Streamlit  
**DevOps:** Docker, Modal


<!--A scalable Retrieval-Augmented Generation (RAG) pipeline leveraging two-stage retrieval: keyword and semantic search.  
This approach enhances precision and reduces computational costs, achieving over 75% reduction in retrieval overhead for enterprise-scale QA.  
**Read More:** [Two-Stage Consecutive RAG for Document QA](https://medium.com/@bbkhosseini/two-stage-consecutive-rag-for-document-qa-enhancing-precision-and-scalability-ac2af206babd) on Medium  
▶️ [Try the Live App](https://bbkhosseini--two-stage-conrag-run.modal.run/)     
*Tech:* RAG, Sentence Transformers, Cross-Encoder Reranker, LangChain, ChromaDB, Docker, Poetry, Streamlit
-->

---

### 🧬 LLM Agents for Clinical Trials
 `🔵 Development Notebooks` 
 
**_Problem_**: Matching patients to clinical trials is complex, time-consuming, and prone to regulatory risks, often requiring human review of hundreds of eligibility criteria.   

**_Data_**: Clinical trial criteria and patient profiles, with structured and unstructured medical data.   

**_Solution_**: Built an agentic LLM workflow using LangGraph to automate trial eligibility screening, hallucination detection, and compliance checks. Integrated human-in-the-loop review and tool calling.   

**_Impact_**:
- Improved review speed and consistency
- Reduced manual effort in preliminary trial screening
- Framework extensible to other regulated domains like insurance or finance

🔗 [GitHub Repo](https://github.com/bab-git/llm_pharma)   
**Backend Tech:** LangGraph, OpenAI, Agentic, Tool-calling, Pydantic  
**Frontend Tech:** Gradio

<!--
### 🧬 [**LLM Agents for Clinical Trials**](https://github.com/bab-git/llm_pharma) `🔵 Development Notebooks`  
Agentic LLM pipeline automating clinical trial eligibility and patient matching.  
Includes data analysis, compliance verification, hallucination grading, and human-in-the-loop workflows.  
**Tech:** LangGraph, OpenAI, Agentic, Tool-calling, Pydantic, Gradio
-->

---

### **LLM Tutorials & Applications**
`🔵 Development Notebooks - Educational`  

A collection of practical LLM architectures and end-to-end notebooks featuring carefully selected case studies across domains like: 
  [**healthcare**](https://github.com/bab-git/llm-tutorials/blob/master/notebooks/Fundamentals/QA_chatbot_memory.ipynb),
  [**customer support**](https://github.com/bab-git/llm-tutorials/blob/master/notebooks/Fundamentals/QA_chatbot.ipynb),
  [**product search**](https://github.com/bab-git/llm-tutorials/blob/master/notebooks/Retrieval_Augmented_Generation/RAG_evaluation.ipynb).  
Includes RAG, tool-using agents, clinical trial retrieval, chatbot workflows, and document QA with real-world data sources.  
🔗 [GitHub Repo](https://github.com/bab-git/llm-tutorials)   
**Backend Tech:** OpenAI, RAG, LangChain, ChromaDB, Pinecone  
**Frontend Tech:** Streamlit


---
---

## 📈 Machine Learning & Data Science Projects (Personal)


### 📊 Social Sphere: Student Behavior Analytics ([SuperDataScience community project](https://community.superdatascience.com/feed))
`🟢 Production Ready - Backend + Frontend` 

**_Problem_**: Educators and psychologists seek to understand how digital behavior affects students' mental health, relationships, and academic performance.   

**_Data_**: Survey of ~700 students aged 16–25 across multiple countries ([Kaggle Q1 2025 dataset](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships)). Features include screen time, platform usage, conflicts, sleep, and well-being.    

**_Solution_**: Led this [**SuperDataScience**](https://community.superdatascience.com/feed) community project to predict social-media addiction scores and relationship conflicts.
Conducted comprehensive data exploration to uncover key behavioral patterns and insights. 
<!-- Performed clustering to segment students into behavioral groups. Used SHAP to explain key influencing factors.    -->

**_Impact_**:
- Accurately predicted student addiction levels with 1% error
- Flagged at-risk relationship conflicts with 99% sensitivity (Recall)
- Revealed critical insights into student behavior, such as the impact of daily screen time and platform usage on mental health and relationships
<!-- - Revealed behavior-based student groups to inform support strategies -->

▶️ [Live App](https://bbkhosseini--social-sphere-analytics-run.modal.run/) • 
🔗 [GitHub Repo](https://github.com/bab-git/SDS-social-sphere/tree/main/submissions/team-members/bob-hosseini) • [Live MLflow Dashboard](https://dagshub.com/bab-git/SDS-social-sphere.mlflow/#/experiments/2)   
**Backend Tech:** Python, Scikit-Learn, XGBoost, Regression, Data Visualization, MLflow, SHAP  
**Frontend Tech:** Streamlit  
**DevOps:** Modal, MLflow, Dagshub

<!-- **_Tech_:** Python, Scikit-Learn, XGBoost, Regression, Clustering, Data Visualization, MLflow, SHAP -->

<!-- 
- [**Social Sphere: Student Social-Media Analytics**](https://github.com/bab-git/SDS-social-sphere/tree/main/submissions/team-members/bob-hosseini) `🟡 Ongoing`  
As the team lead for this [**SuperDataScience**](https://community.superdatascience.com/feed) community project, I am spearheading efforts to predict relationship conflicts and self-reported addiction levels from digital behavior, segment students into behavior-based clusters, and visualize trends in usage intensity, platform preference, and mental well-being.      
🗂️ [**Data Source**](https://www.kaggle.com/datasets/adilshamim8/social-media-addiction-vs-relationships): Utilizing a fresh dataset of nearly 700 students aged 16–25 from high school to graduate programs across multiple countries, collected in Q1 2025, from Kaggle.      
🖥️ [**MLflow Dashboard**](https://dagshub.com/bab-git/SDS-social-sphere.mlflow/#/experiments/2) on Dagshub      
**Tech:** Python, Scikit-Learn, XGBoost, Regression, Clustering, Data Visualization, MLflow, SHAP
-->

---

### 🔋**Energy Forecasting with SARIMAX** ([SuperDataScience community project](https://community.superdatascience.com/feed))
`🟢 Production Ready - Backend + Frontend`  

**_Problem_**: Facility managers and sustainability teams need reliable short-term energy forecasts to optimize planning and reduce costs. However, real-world energy consumption is volatile and only weakly correlated with exogenous drivers like temperature.

**_Data_**: Synthetic building energy dataset ([Kaggle](https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction)) with hourly and daily electricity usage, temperature, humidity, and occupancy variables.

**_Solution_**: 
- Built a time-series forecasting pipeline using SARIMAX, including:
- Time-series CV, ADF tests, and outlier detection for robust preprocessing
- Simulation of noisy exogenous inputs via random walks to mimic real-world uncertainty
- SARIMAX trained and benchmarked against ARIMA, achieving R² ≈ 0.33 despite injected noise
  
▶️ [Live App](https://bbkhosseini--wattwise-energy-forecast-run.modal.run/) 
🔗 [GitHub Repo](https://github.com/bab-git/SDS-CP027-watt-wise/tree/main/submissions/team/bob-hosseini)      
**Backend Tech:** Python, pandas, statsmodels, SARIMAX  
**Frontend Tech:** Streamlit  
**DevOps:** Modal

<!--
Community project with [**SuperDataScience**](https://community.superdatascience.com/feed) to forecast building energy consumption using a synthetic [Kaggle dataset](https://www.kaggle.com/datasets/mrsimple07/energy-consumption-prediction).  
Built a **SARIMAX pipeline** with **uncertainty-injected exogenous inputs** (random walks) and **time-series CV**.  
App delivers **EDA**, **forecast accuracy**, and **feature relevance** visualizations.  
▶️ [Test the Live App](https://bbkhosseini--wattwise-energy-forecast-run.modal.run/)     
**Tech:** Python, pandas, statsmodels, SARIMAX, Streamlit
-->

---

### **Data Science & ML Mini Tasks**
`🔵 Development Notebooks`  

Single-notebook projects showcasing applied machine learning and data science, including: 
  - [Ad Response Prediction](https://github.com/bab-git/data-science-and-ml-mini-projects/blob/master/tasks/Predict_Advertisement_Response),  
  - [Material Strength Prediction](https://github.com/bab-git/data-science-and-ml-mini-projects/tree/master/tasks/Predictive_Modeling_for_Material_Strength),
  - [Recipe Recommender](https://github.com/bab-git/data-science-and-ml-mini-projects/tree/master/tasks/Recommendation_System_Food_Recipes),
  - [Customer Satisfaction Classification](https://github.com/bab-git/data-science-and-ml-mini-projects/tree/master/tasks/Customer_Satisfaction_Prediction),
  - [Hotel Staff Size Prediction](https://github.com/bab-git/data-science-and-ml-mini-projects/tree/master/tasks/Hotel_Staff_Size_Estimation_via_Regression).  

**Backend Tech:** Python, scikit-learn, XGBoost, pandas, matplotlib, Jupyter  
**Frontend Tech:** Streamlit

---
---

## ✍️ Writing

- **[Guardrails in LLM Apps](https://www.linkedin.com/feed/update/urn:li:ugcPost:7275192025069621248/)** – *Strategies for implementing ethical safeguards, ensuring compliance, and enhancing security in Large Language Model applications.*
- **[LLM Model Selection and Updates](https://medium.com/@bbkhosseini/llm-model-selection-and-updates-c6448b23eb36)** – *Guidelines for selecting appropriate Large Language Models and managing their updates to balance quality, cost, and scalability in AI applications.*
- **[Two-Stage RAG for Document QA](https://medium.com/@bbkhosseini/two-stage-consecutive-rag-for-document-qa-enhancing-precision-and-scalability-ac2af206babd)** – *An innovative approach to document-based question answering using a two-stage retrieval strategy to enhance precision and scalability in Retrieval-Augmented Generation systems.*
- **[Data Engineers: The Unsung Heroes Behind AI](https://www.linkedin.com/feed/update/urn:li:ugcPost:7209355924925202432/)** – *An exploration of the pivotal role data engineers play in AI development, emphasizing their contributions to data quality, infrastructure, and the overall success of data science teams.*



---

## 💬 Let’s Connect

Feel free to reach out for collaboration, professional opportunities, or just to swap ideas on building better GenAI systems.


📫 [Email](mailto:bbkhosseini@gmail.com) • [LinkedIn](https://www.linkedin.com/in/bhosseini)

---

> “Build AI that works — and teams that last.”


<!--
**bab-git/bab-git** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



