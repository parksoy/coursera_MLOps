# Soyoung's archive for DeepLearning.AI - Machine Learning Engineering for Production (MLOps) Specialization

## Course 1. Introduction to Machine Learning in Production


### Week 1. Overview of the ML Lifecycle and Deployment  
introduction to machine learning production systems focusing on their requirements and challenges. Next, the week focuses on deploying production systems and what is needed to do so robustly while facing constantly changing data.  

 
Video: Steps of an ML Project  
Video: Case study: speech recognition     
Video: Key challenges  
Video: Deployment patterns  
Video: Monitoring  
Video: Pipeline monitoring    
Reading: Ungraded Lab - Deploying a Deep Learning model (local setup)  
Ungraded Lab: Ungraded Lab - Deploying a Deep Learning model   

Graded: The Machine Learning Project Lifecycle  
Graded: Deployment  



### Week 2. Select and Train a Model  
model strategies and key challenges in model development. It covers error analysis and strategies to work with different data types. It also addresses how to cope with class imbalance and highly skewed data sets.  
 

Video: Modeling overview  
Video: Key challenges  
Video: Why low average error isn't good enough  
Video: Establish a baseline  
Video: Tips for getting started  
Video: Error analysis example  
Video: Prioritizing what to work on  
Video: Skewed datasets  
Video: Performance auditing  
Video: Data-centric AI development  
Video: A useful picture of data augmentation  
Video: Data augmentation  
Video: Can adding data hurt?  
Video: Adding features  
Video: Experiment tracking  
Video: From big data to good data    
Ungraded Lab: A journey through Data  

Graded: Selecting and Training a Model  
Graded: Modeling challenges  



### Week 3. Data Definition and Baseline  
working with different data types and ensuring label consistency for classification problems. This leads to establishing a performance baseline for your model and discussing strategies to improve it given your time and resources constraints.
 
Video: Why is data definition hard?  
Video: More label ambiguity examples  
Video: Major types of data problems  
Video: Small data and label consistency  
Video: Improving label consistency  
Video: Human level performance (HLP)  
Video: Raising HLP  
Video: Obtaining data  
Video: Data pipeline  
Video: Meta-data, data provenance and lineage  
Video: Balanced train/dev/test splits  
Video: What is scoping?  
Video: Scoping process  
Video: Diligence on feasibility and value  
Video: Diligence on value  
Video: Milestones and resourcing  
Reading: Week 3 Optional References  
Practice Quiz: Scoping (optional)   
Ungraded Lab: Data Labeling 

Graded: Data Stage of the ML Production Lifecycle  

## Course 2. Machine Learning Data Life cycle in Production  

### Week 1. Collecting, Labeling and Validating Data   

 
Video: Overview  
Video: ML Pipelines  
Practice Quiz: Intro to MLEP   
Video: Importance of Data  
Video: Example Application: Suggesting Runs  
Video: Responsible Data: Security, Privacy & Fairness  
Practice Quiz: Data Collection  
Video: Case Study: Degraded Model Performance  
Video: Data and Concept Change in Production ML  
Video: Process Feedback and Human Labeling  
Practice Quiz: Data Labeling  
Video: Detecting Data Issues  
Video: TensorFlow Data Validation  
Practice Quiz: Issues in Training Data  
  
Ungraded Lab: TFDV Exercise   

Graded: Data Validation

### Week 2. Feature Engineering, Transformation and Selection  
Implement feature engineering, transformation, and selection with TensorFlow Extended by encoding structured and unstructured data types and addressing class imbalances

Video: Introduction to Preprocessing  
Video: Preprocessing Operations  
Video: Feature Engineering Techniques  
Video: Feature Crosses   
Video: Preprocessing Data at Scale  
Video: TensorFlow Transform  
Video: Hello World with tf.Transform  
Ungraded Lab: Simple Feature Engineering  
Ungraded Lab: Feature Engineering Pipeline  
Practice Quiz: Feature Transformation  
Video: Feature Spaces  
Video: Feature Selection  
Video: Filter Methods  
Video: Wrapper Methods  
Video: Embedded Methods  
Reading: Week 2 Optional References  
Ungraded Lab: Feature Selection  
Practice Quiz: Feature Selection   

### Week 3. Data Journey and Data Storage 
Understand the data journey over a production system’s lifecycle and leverage ML metadata and enterprise schemas to address quickly evolving data.

Video: Data Journey  
Video: Introduction to ML Metadata  
Video: ML Metadata in Action  
Ungraded Lab: ML Metadata  
Practice Quiz: Data Journey  
Video: Schema Development  
Video: Schema Environments  
Ungraded Lab: Iterative Schema  
Practice Quiz: Schema Environments  
Video: Feature Stores  
Video: Data Warehouse  
Video: Data Lakes  
Reading: Week 3 Optional References  
Practice Quiz: Enterprise Data Storage   

Graded: Data Pipeline Components for Production ML



### Week 4. Advanced Labeling, Augmentation and Data Preprocessing
Combine labeled and unlabeled data to improve ML model accuracy and augment data to diversify your training set.

Video: Semi-supervised Learning  
Video: Active Learning  
Video: Weak Supervision  
Practice Quiz: Advanced Labelling  
Video: Data Augmentation  
Practice Quiz: Data Augmentation  
Video: Time Series  
Reading: Feature Engineering with Weather Data  
Video: Sensors and Signals  
Reading: Feature Engineering with Accelerometer Data  
Ungraded Lab: Feature Engineering with Images  
Reading: Week 4 Optional References  
Practice Quiz: Different Data Types  
App Item: Lecture Notes W4  
Reading: Course 2 Optional References   
Reading: Acknowledegements   








## Course 3. Machine Learning Modeling Pipelines in Production
Learn how to effectively search for the best model that will scale for various serving needs while constraining model complexity and hardware requirements.

### Week 1.  Neural Architecture Search  
 
Video: Hyperparameter Tuning  
Video: Keras Autotuner Demo   
Practice Quiz: Hyperparameter Tuning and Neural Architecture Search  
Reading: Ungraded Lab - Intro to Keras Tuner  
Reading: Ungraded Lab - Hyperparameter Tuning and Model Training with TFX  
Video: Intro to AutoML  
Video: Understanding Search Spaces  
Video: Search Strategies  
Reading: Neural Architecture Search  
Video: Measuring AutoML Efficacy  
Video: AutoML on the Cloud  
Reading: AutoML  
Practice Quiz: AutoML  
Video: Assignment Setup  
App Item: A Tour of Qwiklabs and Google Cloud    

Graded: Classify Images of Clouds in the Cloud with AutoML Vision  

### Week 2.  Model Resource Management Techniques  
Learn how to optimize and manage the compute, storage, and I/O resources your model needs in production environments during its entire lifecycle.  


Video: Dimensionality Effect on Performance  
Video: Curse of Dimensionality  
Video: Curse of Dimensionality: an Example  
Video: Manual Dimensionality Reduction  
Video: Manual Dimensionality Reduction: Case Study  
Reading: Ungraded Lab - Manual Feature Engineering  
Video: Algorithmic Dimensionality Reduction  
Video: Principal Components Analysis  
Video: Other Techniques  
Reading: Dimensionality Reduction Techniques  
Practice Quiz: Dimensionality Reduction  
Reading: Ungraded Lab - Algorithmic Dimensionality Reduction  
Video: Mobile, IoT, and Similar Use Cases  
Video: Benefits and Process of Quantization  
Video: Post Training Quantization  
Video: Quantization Aware Training  
Reading: Quantization  
Video: Pruning  
Reading: Pruning  
Practice Quiz: Quantization and Pruning  
Reading: Ungraded Lab - Quantization and Pruning  
App Item: Lecture Notes W2  


### Week 3.  High-Performance Modeling  
Implement distributed processing and parallelism techniques to make the most of your computational resources for training your models efficiently.  


Video: Distributed Training  
Reading: Ungraded Lab - Distributed Strategies with TF and Keras  
Video: High-Performance Ingestion  
Video: Training Large Models - The Rise of Giant Neural Nets and Parallelism  
Reading: High-Performance Modeling  
Practice Quiz: High-Performance Modeling  
Video: Teacher and Student Networks  
Video: Knowledge Distillation Techniques  
Reading: Ungraded Lab - Knowledge Distillation   
Reading: Knowledge Distillation  
Practice Quiz: Knowledge Distillation    

Graded: Distributed Multi-worker TensorFlow Training on Kubernetes  


### Week 4: Model Analysis
Use model performance analysis to debug and remediate your model and measure robustness, fairness, and stability.  



Video: Model Performance Analysis  
Reading: TensorBoard  
Practice Quiz: Model Analysis  
Video: Introduction to TensorFlow Model Analysis  
Video: TFMA in Practice  
Reading: TensorFlow Model Analysis  
Reading: Ungraded Lab - Tensorflow Model Analysis  
Reading: Ungraded Lab - Model Analysis with TFX Evaluator  
Video: Model Debugging Overview  
Video: Benchmark Models  
Video: Sensitivity Analysis and Adversarial Attacks  
Video: Adversarial Attack Demo  
Reading: Sensitivity Analysis and Adversarial Attacks  
Video: Residual Analysis  
Video: Model Remediation  
Video: Fairness  
Video: Measuring Fairness  
Reading: Ungraded Lab - Fairness Indicators  
Reading: Model Remediation and Fairness  
Practice Quiz: Model Analysis and Debugging  
Reading: [IMPORTANT] Information about the Week 4 assignment  
Video: Continuous Evaluation and Monitoring  
Reading: Continuous Evaluation and Monitoring  
Practice Quiz: Continuous Evaluation and Monitoring   


Graded: Machine Learning with TensorFlow in Vertex AI  

### Week 5: Interpretability


Video: Explainable AI  
Reading: Explainable AI  
Practice Quiz: Explainable AI  
Video: Model Interpretation Methods  
Video: Intrinsically Interpretable Models  
Reading: Interpretability  
Practice Quiz: Interpretability  
Video: Model Agnostic Methods  
Video: Partial Dependence Plots  
Video: Permutation Feature Importance  
Reading: Permutation Feature Importance  
Reading: Ungraded Lab - Permutation Feature Importance  
Video: Shapley Values  
Video: SHapley Additive exPlanations (SHAP)  
Reading: Ungraded Lab - Shapley Values  
Reading: Understanding Model Predictions  
Video: Testing Concept Activation Vectors  
Video: LIME  
Reading: TCAV and LIME  
Video: AI Explanations  
Reading: AI Explanations  
Practice Quiz: Understanding Model Predictions   

## Corurse 4. Deploying Machine Learning Models in Production

### Week 1. Model Serving: Introduction 
Learn how to make your ML model available to end-users and optimize the inference process
 
Video: Introduction to Model Serving  
Reading: Ungraded Labs - Best Practices  
Reading: Ungraded Lab - Introduction to Docker  
App Item: Ungraded Lab - Introduction to Docker (Google Cloud)   
Video: Introduction to Model Serving Infrastructure  
Video: Deployment Options  
Video: Improving Prediction Latency and Reducing Resource Costs  
Video: Creating and deploying models to AI Prediction Platform  
Reading: Optional: Build, train, and deploy an XGBoost model on Cloud AI Platform  
App Item: Ungraded Lab - Vertex AI Workbench Notebook: Qwikstart  
Video: Installing TensorFlow Serving  
Reading: Ungraded Lab - Tensorflow Serving with Docker  
Reading: Ungraded Lab - Serve a model with TensorFlow Serving  
 
Ungraded labs
- Introduction to Docker  
* C4_W1_Lab_1_Docker_Intro  
* C4_W1_Lab_2_TFS_Docker  
* C4_W1_Lab_3_TFS  
* C4_W1_Optional_Lab_1: XGBoost_CAIP  
- Introduction to Docker (Google Cloud)  

Graded: Introduction to Model Serving  
Graded: Introduction to Model Serving Infrastructure  
Graded: TensorFlow Serving  


### Week 2. Model Serving: Patterns and Infrastructure

Video: Model Serving Architecture  
Video: Model Servers: TensorFlow Serving  
Video: Model Servers: Other Providers  
Reading: Documentation on model servers  
Practice Quiz: Model serving architecture  
Reading: Ungraded Lab - Deploy a ML model with FastAPI and Docker  
Video: Scaling Infrastructure  
Reading: Learn about scaling with boy bands  
Reading: Explore Kubernetes and KubeFlow  
Practice Quiz: Scaling Infrastructure  
App Item: Ungraded Lab - Orchestrating the Cloud with Kubernetes  
Video: Online Inference  
Practice Quiz: Online Inference  
Reading: Ungraded Lab - Latency testing with Docker Compose and Locust  
Video: Data Preprocessing  
Reading: Data preprocessing  
Practice Quiz: Data Preprocessing  
Video: Batch Inference Scenarios  
Practice Quiz: Batch inference scenarios  
Video: Batch Processing with ETL  
Reading: Ungraded Lab (Optional): Machine Learning with Apache Beam and TensorFlow  
Practice Quiz: Batch Processing with ETL   


Ungraded Labs
* C4_W2_Lab_1_FastAPI_Docker,  
  [Part 1.One prediction per request](https://github.com/https-deeplearning-ai/machine-learning-engineering-for-production-public/blob/main/course4/week2-ungraded-labs/C4_W2_Lab_1_FastAPI_Docker/no-batch/README.md)
  [Part 2. Batch inference](https://github.com/https-deeplearning-ai/machine-learning-engineering-for-production-public/blob/main/course4/week2-ungraded-labs/C4_W2_Lab_1_FastAPI_Docker/with-batch/README.md)  
* C4_W2_Lab_2_Intro_to_Kubernetes: Orchestrating the Cloud with Kubernetes  
* C4_W2_Lab_3_Latency_Test_Compose: Latency testing with Docker Compose and Locust  
* Machine Learning with Apache Beam and Tensorflow  
  
Graded: Autoscaling Tensorflow model deployments with TF Serving and Kubernetes  

 
### Week 3. Model Management and Delivery  
Learn how to implement ML processes, pipelines, and workflow automation that adhere to modern MLOps practices, which will allow you to manage and audit your projects during their entire lifecycle  


Video: Experiment Tracking  
Video: Tools for Experiment Tracking  
Reading: Experiment Tracking  
Video: Introduction to MLOps  
Practice Quiz: ML Experiments Management and Workflow Automation  
Video: MLOps Level 0  
Video: MLOps Levels 1&2  
Reading: MLOps Resources  
Reading: Ungraded Lab: Intro to Kubeflow Pipelines  
Video: Developing Components for an Orchestrated Workflow  
Reading: Architecture for MLOps using TFX, Kubeflow Pipelines, and Cloud Build  
Practice Quiz: MLOps Methodology  
Ungraded Lab: Ungraded Lab: Developing TFX Custom Components  
Video: Managing Model Versions  
Reading: Ungraded Lab - Model Versioning with TF Serving  
Reading: ML Model Management  
Video: Continuous Delivery  
Reading: Ungraded Lab - CI/CD pipelines with GitHub Actions  
Reading: Continuous Delivery  
Video: Progressive Delivery  
Reading: Progressive Delivery  
Practice Quiz: Model Management and Deployment Infrastructure  
 


Ungraded Labs
* Intro to Kubeflow Pipelines  
* Model Versioning with TF Serving  
* CI/CD pipelines with GitHub Actions  
  
Graded:  
* TFX on Google Cloud Vertex Pipelines  
* Implementing Canary Releases of TensorFlow Model Deployments with Kubernetes and Anthos Service Mesh  


### Week 4. Model monitoring and Logging

Video: Why Monitoring Matters  
Video: Observability in ML  
Video: Monitoring Targets in ML  
Video: Logging for ML Monitoring  
Video: Tracing for ML Systems  
Reading: Monitoring Machine Learning Models in Production  
Practice Quiz: Model Monitoring and Logging  
Video: What is Model Decay?  
Video: Model Decay Detection  
Video: Ways to Mitigate Model Decay  
Reading: Addressing Model Decay  
Practice Quiz: Model Decay  
Video: Responsible AI  
Reading: Responsible AI  
Video: Legal Requirements for Secure and Private AI  
Reading: GDPR and CCPA  
Video: Anonymization and Pseudonymisation  
Video: Right to be Forgotten  
Practice Quiz: GDPR and Privacy   

* Graded: Data Loss Prevention