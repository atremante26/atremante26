# Hi, I'm Andrew. Nice to meet you! 👋

🎓 **CS @ Amherst College '26**   
🚀 **Incoming Data Scientist @ IBM**  
🔬 **Honors Thesis Research on Text-to-SQL Evaluation | Published at ICLR 2026**    
🏢 **Previously — Machine Learning Engineer Intern @ TrueData | Data Science Intern @ Philadelphia Union**

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andrewtremante@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&cacheSeconds=0&v=2)](https://www.linkedin.com/in/andrew-tremante-71253a238/)
[![Website](https://img.shields.io/badge/Website-6E6E6E?style=for-the-badge&logo=googlechrome&logoColor=white)](https://andrewtremante.com)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-1A73E8?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=EXRKa94AAAAJ&hl)


---

## 🔬 Research

**Text-to-SQL Evaluation with Formal Verification** @ Amherst College, VMware Research by Broadcom  
Developing formal verification methods to evaluate Text-to-SQL systems using logical equivalence. Work independently requested by Amazon for evaluation of their production Text-to-SQL quality assurance system.

📄 **[SpotIt: Evaluating Text-to-SQL Evaluation with Formal Verification](https://arxiv.org/abs/2510.26840)** — *ICLR 2026*  
&nbsp;&nbsp;&nbsp;&nbsp;→ Evaluation pipeline that applies bounded equivalence verification to search for differentiating database instances between generated and gold queries.
 
📄 **[SpotIt+: Verification-based Text-to-SQL Evaluation with Database Constraints](https://arxiv.org/abs/2603.04334)** — *Under Review*  
&nbsp;&nbsp;&nbsp;&nbsp;→ Extends the verification framework with an automatic constraint-mining pipeline that combines rule-based specification mining over example databases with LLM validation.
 
🔧 **[SpotIt+ (GitHub)](https://github.com/ai-ar-research/SpotIt-plus)**  
&nbsp;&nbsp;&nbsp;&nbsp;→ Open-source tool for constraint-augmented SQL equivalence checking.

---

## 🚀 Featured Projects

### **[UnifySQL](https://github.com/atremante26/UnifySQL)**
Open-source, model-agnostic Text-to-SQL infrastructure layer addressing core reliability gaps in enterprise natural language querying systems.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Automatically constructs and maintains semantic layers from database schemas using LLMs, with SQLGlot-based dialect compilation across Snowflake, BigQuery, and PostgreSQL.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Implements clean LLM adapter interfaces for seamless model swaps and a feedback loop that persists analyst corrections, decoupling the model problem from the infrastructure problem.
 
#### Tech Stack
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="35" height="35" title="Python"/>
<img src="https://assets.streamlinehq.com/image/private/w_300,h_300,ar_1/f_auto/v1/icons/logos/flask-qvsfwhwywucb6zv0d7ce.png/flask-1byb2jlw6nwim4nx2248xg.png?_a=DATAg1AAZAA0" alt="flask" width="35" height="35" title="Flask"/>
<img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/langchain-color.png" alt="langchain" width="35" height="35" title="LangChain"/>
<img src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" alt="snowflake" width="35" height="35" title="Snowflake"/>
<img src="https://www.vectorlogo.zone/logos/google_bigquery/google_bigquery-icon.svg" alt="bigquery" width="35" height="35" title="BigQuery"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="35" height="35" title="PostgreSQL"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="35" height="35" title="Docker"/>
</p>

### [**MindPulseAI**](https://github.com/atremante26/MindPulseAI)
Full-stack analytics platform tracking population mental health trends with automated data pipelines and ML-powered insights.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Engineered serverless pipeline with Airflow on AWS ECS Fargate, Snowflake, and S3, featuring Great Expectations validation and CI/CD via GitHub Actions.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Implemented Prophet 30-day forecasting, HDBSCAN clustering, Claude 3.5 Haiku LLM insights, and a content-based recommender system served through a FastAPI backend and React frontend.
 
#### Tech Stack
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="35" height="35" title="Python"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="35" height="35" title="AWS"/>
<img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/apache-airflow.png" alt="airflow" width="35" height="35" title="Apache Airflow"/>
<img src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" alt="snowflake" width="35" height="35" title="Snowflake"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="35" height="35" title="React"/>
<img src="https://cdn.worldvectorlogo.com/logos/fastapi.svg" alt="fastapi" width="35" height="35" title="FastAPI"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="35" height="35" title="Docker"/>
</p>

**[🌐 LIVE SITE](https://mindpulseai.io/)**

---

### [**SafetyLens**](https://github.com/atremante26/SafetyLens)
Research project evaluating model architecture impact on hate speech detection across multi-dimensional datasets.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Compared logistic regression, single-task RoBERTa, and multi-task RoBERTa on DICES-350 dataset, achieving 29% F1 improvement over baseline.  
&nbsp;&nbsp;&nbsp;&nbsp;→ Analyzed explainability differences using LIME, SHAP, and Integrated Gradients with results visualized in an interactive web application.
 
#### Tech Stack
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="35" height="35" title="Python"/>
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="35" height="35" title="PyTorch"/>
<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="35" height="35" title="Hugging Face"/>
<img src="https://cdn.worldvectorlogo.com/logos/fastapi.svg" alt="fastapi" width="35" height="35" title="FastAPI"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="35" height="35" title="React"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="35" height="35" title="Docker"/>
</p>

**[🌐 LIVE SITE](https://atremante26.github.io/SafetyLens/)**

---

### [**Match Prediction Model**](https://github.com/atremante26/Match_Prediction_Model)
Convolutional Neural Network (CNN) built using PyTorch to predict professional soccer matches based on historical betting data.        
&nbsp;&nbsp;&nbsp;&nbsp;→ 50% return on investment (ROI) in simulated weekly betting performance on 20+ years of data (2002-2023).

#### Tech Stack
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="35" height="35" title="Python"/>
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="35" height="35" title="PyTorch"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="35" height="35" title="scikit-learn"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="35" height="35" title="pandas"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/numpy/numpy-original.svg" alt="numpy" width="35" height="35" title="NumPy"/>
</p>

**[📹 VIDEO DEMO](https://www.youtube.com/watch?v=_78TkQ1djPI)**

---

## 🛠️ Technologies & Tools
 
### Languages
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40" title="Python"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40" title="Java"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="sql" width="40" height="40" title="SQL"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40" title="TypeScript"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40" title="JavaScript"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/r/r-original.svg" alt="r" width="40" height="40" title="R"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/scala/scala-original.svg" alt="scala" width="40" height="40" title="Scala"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40" title="C"/>
</p>
 
### AI/ML & Data
<p align="left">
<img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40" title="PyTorch"/>
<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="huggingface" width="40" height="40" title="Hugging Face"/>
<img src="https://registry.npmmirror.com/@lobehub/icons-static-png/latest/files/dark/langchain-color.png" alt="langchain" width="40" height="40" title="LangChain"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40" title="scikit-learn"/>
<img src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" alt="snowflake" width="40" height="40" title="Snowflake"/>
<img src="https://cdn.jsdelivr.net/gh/homarr-labs/dashboard-icons/png/apache-airflow.png" alt="airflow" width="40" height="40" title="Apache Airflow"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40" title="pandas"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/numpy/numpy-original.svg" alt="numpy" width="40" height="40" title="NumPy"/>
<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40" title="TensorFlow"/>
</p>
 
### Cloud & Infrastructure
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40" title="AWS"/>
<img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" alt="gcp" width="40" height="40" title="Google Cloud"/>
<img src="https://www.vectorlogo.zone/logos/google_bigquery/google_bigquery-icon.svg" alt="bigquery" width="40" height="40" title="BigQuery"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="docker" width="40" height="40" title="Docker"/>
<img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" width="40" height="40" title="Kubernetes"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="postgresql" width="40" height="40" title="PostgreSQL"/>
</p>
 
### Development
<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="react" width="40" height="40" title="React"/>
<img src="https://cdn.worldvectorlogo.com/logos/fastapi.svg" alt="fastapi" width="40" height="40" title="FastAPI"/>
<img src="https://assets.streamlinehq.com/image/private/w_300,h_300,ar_1/f_auto/v1/icons/logos/flask-qvsfwhwywucb6zv0d7ce.png/flask-1byb2jlw6nwim4nx2248xg.png?_a=DATAg1AAZAA0" alt="flask" width="40" height="40" title="Flask"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" alt="nodejs" width="40" height="40" title="Node.js"/>
<img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40" title="Git"/>
</p>

---

*Always looking to learn, build, and collaborate. Feel free to reach out!*
