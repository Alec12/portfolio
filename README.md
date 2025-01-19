# Data Science Portfolio

## Education
### **University of California, Berkeley | Berkeley, CA**
  
  - **Degree**: Master's of Information and Data Science _(May 2025)_
  - **Related Coursework**: Natural Language Processing with Deep Learning, Machine Learning Data Systems, Machine Learning at Scale, Applied Machine Learning, Python Programming, Statistics for Data Science, Data Visualization
  
### **University of California, Berkeley | Berkeley, CA**
  - **Degree**: B.A. Economics, Minor Industrial Engineering and Operations Research _(December 2018)_
  - **Related Coursework**: Econometrics, Machine Learning and Data Analysis, Forecasting Statistics, Innovation and Design, Rapid Prototyping, Probability and Risk Analysis for Engineers, Industrial Data Systems, Linear Programming and Network Flows

## Work Experience

### **Pubmatic, Inc. | Redwood City, CA**
&nbsp;_Senior Data Analyst (October 2021 - January 2024)_
  
   - Led 18 product rollouts, contributing $27M in additional annual revenue through cross-functional and regional team coordination.
   - Boosted A/B experiment efficiency by 300% by leading the development of a multi-cluster framework and UI, collaborating with AdServer and Analytics leadership.
   - Designed and implemented 70+ A/B experiments for machine learning and AdTech real-time bidding features, driving results across North America, Europe, and Asia.
   - Identified and evaluated short- and long-term opportunities to enhance auction and machine learning algorithm efficiency, impacting 4,000+ publishers and 140+ demand portfolios.
  - Served as the primary stakeholder for product experimentation, delivering actionable insights and findings to C-suite executives and teams in Product, Marketplace, Engineering, Sales, and Customer Success.
  
### **Paramount Plus | San Francisco, CA**
&nbsp;_Senior Revenue Optimization Analyst (March 2019 - October 2021)_
  
  - Designed and implemented an unsupervised K-Means Algorithm to classify 5000+ portfolio advertisers by buying patterns and budgets for the Private Marketplace Sales Team, enabling more targeted and effective sales outreach by identifying high-value prospects within similar deal categories.
  - Conducted ad-hoc analyses for 31 brands, including CBS News, CBS Sports, MTV, and CNET, to assess the impact of new AdTech integrations on viewer behavior, traffic, programmatic pricing, and multi-million-dollar revenue goals.
  - Created 14 KPI dashboards for brands and partners using Tableau, Data Studio, and Google Sheets; automated backend data pipelines with SQL, Python, and Google API integrations to streamline performance evaluations.
  - Built a Python-based tool to detect data anomalies and pipeline breakages in seconds, empowering Operations and AdTech teams to troubleshoot issues efficiently; utilized Tableau subscription emails to share insights.
  - Migrated seven MS Excel and MS Access databases to BigQuery, automating workflows for six departments, including Partnerships, Yield, AdTech, Brand Developers, Sales, and Finance.
  - Established bi-weekly data validation processes, ensuring revenue accuracy and pipeline quality across 30+ partner portfolios.
  - Led weekly partnership meetings, presenting in-depth performance analyses to Programmatic Partnership Directors, VPs, and SVPs, driving actionable insights.
  - Analyzed datasets with over 1M data points to enhance data mining, feature engineering, and communication skills, delivering insights to executives, sales teams, and AdTech engineers.
  
### **MetaRail | San Francisco, CA**
&nbsp;_Commerce-based Advertising AdTech company specializing in publisher-side monetization_

&nbsp;_E-Commerce and Operations Analyst (May 2018 - March 2019)_
  
  - Performed real-time revenue and CTR performance analysis using R and Excel for 14 content publishers and advertisers.
  - Oversaw daily programmatic advertising traffic management and optimization across desktop, mobile web, and applications.
  - Developed predictive models for e-commerce conversion rates using data from AdTech platforms (LKQD and Beachfront), and designed Tableau dashboards to visualize optimizations and forecasts.

## Projects

  - **Bechdel Test Automation with Deep Learning Co-Reference Resolution**
    - Built a pipeline to automate the Bechdel Test; leveraged recent research in transformer-based chunking techniques and co-reference resolution to identify character interactions and conversation topics, effectively analyzing movie scripts with token counts 55x higher than standard limits.
    - Enhanced text classification with deep learning models, achieving a 14% improvement in F1 score over baseline methods across 400+ scripts.
    - [More details in repository](https://github.com/Alec12/Automating-the-Bechdel-Test)
      
  - **New York Times Front-Page Article Detection**
    - Developed a binary classification model to predict whether articles will make the front page of the New York Times, leveraging models such as RNNs and Gradient Boosting.
    - Optimized for F1 performance: baseline models achieved 5% F1, logistic regression improved to 73.7% F1, and RNN models delivered the highest performance with 94% F1.
    - (In-Progress) Fine-tuning BERT embeddings to classify article headlines, aiming for further improvements in accuracy and robustness.
    - &nbsp;[More details in repository](https://github.com/Alec12/NYT-Front-Page-Headline-Detection)

  - **Predicting Flight Delays with Parallelized Training**
    - Analyzed over 31 million rows of flight and weather data using SparkML and a distributed framework, enabling scalable feature engineering and model training.
    - Leveraged the PageRank algorithm to compute airport centrality as a graph-based feature, capturing traffic flow dynamics and its impact on delay likelihood.
    - Implemented a blocking time series split for cross-validation, ensuring robust evaluation by training and validating on temporally ordered data to mimic real-world conditions.
    - Developed a binary classification model to predict delayed arrivals, experimenting with Logistic Regression, Random Forest, and Neural Network models, achieving a 7% improvement in F1 score over the best baseline.
    - &nbsp;[More details in repository](https://github.com/Alec12/Predicting-Flight-Delays-with-Distributed-ML)
      
  - **End-to-End Machine Learning API for Scalable Sentiment Analysis**
    - Built a scalable machine learning API by developing a prediction service using FastAPI with HuggingFace’s DistilBERT model for CPU-efficient sentiment analysis. Containerized the application with Docker and deployed it on Azure Kubernetes Service (AKS).  
    - Optimized performance by implementing Redis caching to reduce latency and integrating Grafana for monitoring system performance and resource utilization during load testing with k6.
    - Tackled large-scale deployment challenges by pre-baking the 1GB model into the container image, minimizing pod startup latency and enabling seamless scaling during high-traffic events.
    - &nbsp;[More details in repository](https://github.com/Alec12/scalable-DistilBERT-API)

  - **Recreated a Second-Price Auction Marketplace**
    - Designed and implemented a second-price auction system in Python to simulate competitive online advertising environments.
    - Secured a top 10 placement out of 130 classmates with a strategic, heuristic-based bidding algorithm balancing exploration and exploitation while barred from the use of machine learning techniques.
    - [More details in repository]([https://github.com/Alec12/Automating-the-Bechdel-Test](https://github.com/Alec12/AdTech-Second-Price-Auction-Model-Baseline))
      
  - **Capstone: Deepfake Audio Detection** _(In Progress)_
    - Developing a convolutional neural network (CNN) model to detect deepfake audio by analyzing spectrogram features from thousands of labeled audio samples, with a focus on identifying noisy deepfakes.
    - Exploring the use of generative adversarial networks (GANs) to create and test watermarking solutions that identify AI-generated audio without compromising sound quality.
    - Potential applications include combating misinformation in media, aiding companies like Meta in protecting users, and supporting the music industry in distinguishing AI-generated works to align with copyright regulations.
      
  - **Data Visualization Project** _(In Progress)_
    - Designing a web-based interactive dashboard to explore trends in housing prices datasets, integrating D3.js and Plotly for dynamic visualizations.
    - 	Focusing on user-centric insights by combining data storytelling techniques with predictive analytics, enabling better decision-making for non-technical stakeholders.
   
  - **Predictive Analysis for Kickstarter Campaigns, Machine Learning & Data Analytics**
    - In a team of five engineers, collected and evaluated 300,000+ Kickstarter projects using NLP to extract and process campaign descriptions for predictive modeling.
    - Built an ensemble classification model using Random Forests, Boosting, Stepwise Regression, Logistic Regression, and Neural Network techniques, achieving actionable insights for campaign success prediction and marketing guidance for creators.
  
  - **Business Planning for Startups (BPS) | Sonoma, CA (Co-Founder) | April 2016 – August 2018**
    &nbsp;_*BPS is a pro-bono consulting organization specializing in launch and growth strategies for startups in the Bay Area_
    - Designed comprehensive startup launch plans that include long-term objectives, implementation strategies, and industry/competitor analysis for key stakeholders in companies like River Rock Casino and Lucas Marketing & Media
    - Analyzed current and forecasted startup growth patterns to set revenue milestones, marketing strategies, and pro-forma income statements based on current company assets


### Technical Skills
  - **Languages:** Python, R, SQL, D3, JavaScript
  - **Developer Tools:** Kubernetes, Docker, Git, CI/CD
  - **Technologies/Frameworks:** TensorFlow, PyTorch, Scikit-learn, Keras, Hugging Face Transformers, NLTK, spaCy, LightGBM
  - **Cloud Platforms:** AWS(SageMaker, Lambda, EC2), GCP (Vertex AI, BigQuery), Microsoft Azure, Databricks, Snowflake
