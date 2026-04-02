# Predictive Intelligence for Geriatric Healthcare Access & Patient Stratification

📌 **Executive Summary**  
This project delivers an end-to-end AI-driven clinical decision-support system designed to predict healthcare utilization (frequency of doctor visits) among geriatric patients. By integrating Mathematical Statistics with Deep Learning (MLP), the system identifies high-risk patient segments. This enables healthcare providers to optimize resource allocation, improve prognostic accuracy, and ensure timely interventions for elderly populations.

## 🛠️ Tech Stack & Architecture
- **Deep Learning**: PyTorch (Multi-Layer Perceptron).
- **Machine Learning**: Random Forest, LightGBM, Logistic Regression (Scikit-Learn).
- **Statistical Validation**: SciPy (Chi-Square Analysis, Hypothesis Testing).
- **Data Engineering**: Pandas, NumPy, SQL-based logic for clinical data optimization.
- **Workflow**: Automated AI Pipelines for production-ready inference.

## 🧬 Methodology: The Clinical Data Science Lifecycle

### 1. Clinical Data Modeling & Feature Engineering
- Developed a custom Clinical Risk Index by synthesizing multifaceted health metrics including physical, mental, and dental health status.
- **Data Refinement**: Handled complex survey categories (Refused/Not Asked) to ensure high-fidelity model inputs.
- **Scaling**: Implemented a robust StandardScaler within an automated pipeline to maintain feature consistency and prevent data leakage.

### 2. Statistical Validation (The Mathematical Foundation)
Consistent with my background in Mathematical Statistics, I performed rigorous Chi-Square Hypothesis Testing to validate correlations between socio-demographic factors and healthcare access.  
**Outcome**: Confirmed statistically significant relationships (\(p < 0.05\)), providing a formal basis for the neural network's feature selection.

### 3. Patient Stratification (Risk-Based Triage)
Patients were segmented into Low, Medium, and High-risk tiers. This stratification logic serves as the engine for the Decision-Support Tool, allowing clinicians to prioritize patients requiring urgent care.

### 4. Deep Learning Implementation (MLP)
- Implemented a 3-layer Multi-Layer Perceptron (MLP) using PyTorch.
- **Architecture**: Optimized with Adam Optimizer and Cross-Entropy Loss.
- **Class Balancing**: Integrated `class_weight='balanced'` to address inherent skewness in clinical datasets, ensuring the model identifies high-need patients accurately.

## 📊 Key Performance Insights (Clinical Evaluation)
The system was evaluated using medical-grade metrics, focusing on Recall for high-utilization classes to minimize false negatives in patient care.

| Metric     | Category 2 (Average Care) | Category 3 (High-Need) |
|------------|---------------------------|-------------------------|
| **Precision** | 0.56                     | 0.48                   |
| **Recall**    | 0.85                     | 0.33                   |
| **F1-Score**  | 0.68                     | 0.39                   |

**Technical Insight**: The high recall (85%) in Category 2 demonstrates model stability, while the lower recall in Category 3 reflects the "Volatile Patient" challenge common in geriatric emergency analytics—a primary area for further RAG-based augmentation.

## 🚀 Scalability & Future Roadmap
- **SQL & Neo4j Integration**: Migrating data to a Knowledge Graph to capture multi-hop reasoning between chronic conditions.
- **AWS Deployment**: Utilizing Amazon SageMaker for real-time model monitoring and automated CI/CD for healthcare workflows.
- **RAG & LangChain**: Developing a Retrieval-Augmented Generation pipeline to allow clinicians to query patient summaries via Natural Language.

## 📬 Contact & Collaboration
**Nastaran Nikpour** – Junior Data Scientist | AI in Healthcare Specialist  
- **Education**: Dual Master's in Data Science and Mathematical Statistics.  
- **Location**: Naples, Italy (Open to Relocation).  
- [LinkedIn: nastaran-nikpour](https://linkedin.com/in/nastaran-nikpour)  
- [GitHub: nikpournastaran](https://github.com/nikpournastaran)  
- Email: [nastaran_nik74@yahoo.com](mailto:nastaran_nik74@yahoo.com)  

Developed with a focus on translating complex clinical data into actionable life-saving insights.
