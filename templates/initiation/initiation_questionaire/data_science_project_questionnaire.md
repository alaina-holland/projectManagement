# Questionnaire for Preparing Proposals for Data Science Projects

### Inspired by Umesh Menon’s article: [Ask These Questions While Preparing a Proposal for Data Science Projects](https://www.linkedin.com/pulse/ask-questions-while-preparing-proposal-data-science-project-menon/)

---

## Business Understanding

### Business Problem Definition
1. What is the business problem we are trying to solve? (Exact definition needed)
2. Is it a prediction problem? (e.g., predicting company’s profit in the next quarter)
3. Are we doing segmentation? (e.g., customer segmentation for targeted marketing)
4. Are we going to recommend something? (e.g., product recommendation to users)
5. Is it an anomaly detection or fraud detection problem?
6. Is it an optimization problem? (e.g., optimizing company revenue)

### Problem Categorization
1. Does the problem fall into any of these categories?
   - Prediction
     - Classification
     - Regression/Time Series Forecasting
     - Scoring or Class Probability Estimation
     - Survival Analysis/Churn Analysis
   - Segmentation/Clustering
   - Similarity Matching/Recommendation
   - Profiling/Anomaly Detection/Fraud Detection/Look-alike Modeling
   - Causal Modelling/Root Cause Analysis
   - Co-occurrence Grouping/Association Rule Discovery/Frequent Itemset Mining/Market Basket Analysis
   - Data Reduction
   - Optimization

### Specific Problem Type Questions
1. Prediction
   - Do we know what variable (target) to be predicted?
   - Is that target variable defined precisely?
   - What values or ranges of values can this variable take?
   - Will modeling this target variable address all the problems defined in the scope or only a sub-problem?
2. Clustering
   - Do we know the end objective? Is an EDA (Exploratory Data Analysis) path clearly defined?
   - Are we addressing a specific problem or a generic problem across all business?
   - Who are the targeted audience?
   - How do you evaluate your solution outcome? Are there any evaluation metrics available?
   - What is the acceptance criteria for the solution? (e.g., for a classification task accuracy should be above 65%)

---

## Solution Approach

### Analytical Solution Formulation
1. Is the proposed analytical solution formulated appropriately to solve the business problem OR is it an approximation?
2. Will the proposed solution address all the problems defined in the scope or only a sub-problem?
3. What will be the benefits of the proposed solution? Benefit vs. Cost.
4. What will be the specific end objectives to be met by the proposed solution?
5. What should be the anticipated outcomes of the proposed solution?

---

## Data Preparation

### Variables and Data Types
1. What are the important variables that we should collect?
2. Are these variables readily available? Or is there additional effort needed to collect these variables?
3. What are the types of data? (e.g., sensor data, ERP, e-commerce, SAP CRM data)

### Data Locations and Acquisition
1. Where are the locations of data in the system? (e.g., ERP SQL RDBMS database, OLAP data in SQL server, text data from social media)
2. Where are the data coming from? (e.g., data from sensors, sales data from ERP, online store)
3. Who are the current consumers of the data? (e.g., visualization tools, BI application)
4. What are the methods to acquire data? (e.g., data lake ingestion, access control for internal data, API for social data)
5. What are the problems in acquiring the data? What are the solutions in case of problems?
6. What are the integration points? (e.g., database access, API services)

### Data Practicality
1. Will it be practical to get all the relevant variables and load them into our workspace?
2. For prediction problems, is sufficient amount of labeled examples available? Or is there a cost involved in getting these values?
3. Are the training data drawn from a similar population on which the model will be applied? If not, are the selection biases noted? What are the plans to compensate for this?

---

## Modelling

### Model Choice and Requirements
1. Is the choice of model appropriate for the business problem? Is it in line with our prior knowledge of the problem?
2. Does the modeling technique meet all the other requirements (functional and non-functional) of the problem?
3. Should various modeling techniques be tried and compared using appropriate evaluation metrics?
4. Check these points:
   - Amount of data required
   - Generalization performance
   - Learning time

---

## Evaluation

### Domain Expert Validation
1. Is there a plan for domain expert validation?
2. Will the model be in a form that they can understand?

### Evaluation Metrics
1. Is there an evaluation metric set up by the business? (e.g., for a classification problem, there should be less than x% of false positives)
2. Is there a hold-out data available for validation?
3. Against what baseline or benchmark will the results be compared? 
4. Are the business costs and benefits considered?
5. For a classification problem, is there a threshold defined?
6. For a regression problem, how will we evaluate the quality of prediction in the business context?
7. For a clustering problem, how is the clustering interpreted in the context of the business problem?
8. How will we measure the business impact of the final model? How will we justify the project expense against the benefits?

---

## Project Management

### Timeline and Milestones
1. What is the project timeline with key milestones?
2. What are the deadlines for deliverables?

### Resource Allocation
1. Who are the team members and what are their roles?
2. What resources are needed? (e.g., computational power, software tools)

### Risk Management
1. What are the potential risks and mitigation strategies?
2. What are the contingency plans for project delays or data issues?

---

## Stakeholder Engagement

### Stakeholder Identification
1. Who are all the stakeholders and what are their roles?
2. What is the involvement and communication plan for each stakeholder?

### Communication Plan
1. What are the regular meetings and updates with stakeholders?
2. What are the communication methods and frequency? (e.g., weekly reports, monthly presentations)

---

## Ethical and Legal Considerations

### Data Privacy
1. Are we compliant with data privacy laws? (e.g., GDPR, CCPA)
2. What are the data anonymization and protection methods?

### Bias and Fairness
1. Are there potential biases in data and modeling?
2. What steps are taken to ensure fairness and mitigate bias?

### Regulatory Compliance
1. What industry-specific regulations apply?
2. What compliance measures are documented?

---

## Technical Feasibility

### Software and Tools
1. What software, tools, and libraries will be used?
2. Are they compatible with existing systems?

### Technical Challenges
1. What are the technical challenges and proposed solutions?
2. Is the feasibility of proposed technical solutions evaluated?

---

## Data Strategy

### Data Collection
1. What is the data collection strategy and data sources?
2. What are the methods for data acquisition and integration points?

### Data Quality
1. How is data quality assessed? (e.g., completeness, accuracy, consistency)
2. What are the data cleaning and preprocessing steps?

### Data Storage and Management
1. What are the data storage solutions? (e.g., databases, data lakes)
2. What are the data management practices? (e.g., version control, data lineage)

---

## Performance Metrics

### Model Evaluation Metrics
1. What specific metrics will be used to evaluate model performance? (e.g., accuracy, precision, recall, F1 score)

### Business Impact Metrics
1. What key performance indicators (KPIs) will measure business impact? (e.g., ROI, customer satisfaction)

### Monitoring and Maintenance
1. What is the plan for monitoring model performance post-deployment?
2. What is the maintenance schedule for model updates and retraining?

---

## Budget and Cost Management

### Cost Estimation
1. What is the detailed cost estimate for the project?
2. What are the costs for data acquisition, software licenses, hardware, personnel?

### Budget Tracking
1. What is the system for tracking project expenses?
2. How will budget adherence be ensured and deviations reported?

---

## Documentation

### Project Documentation
1. What comprehensive documentation will be maintained throughout the project lifecycle?
2. What project plans, data dictionaries, model documentation, and final reports will be included?

### User Documentation
1. What documentation will be prepared for end-users? (e.g., user manuals, training materials)

### Technical Documentation
1. What detailed technical documentation will be ensured for developers and maintainers?

---

## Existing Systems/Requirements

### Related Requirements
1. Are there any related requirements? (e.g., price elasticity, demand forecasting)
2. What are the existing/related systems within the capability that capture/use related information?
3. What are the gaps?
4. Who are the stakeholders?
5. Who will be affected by this implementation?

---

## Assumptions/Dependencies/Challenges

### Assumptions
1. What are the assumptions? (e.g., availability of necessary data, access to the infrastructure, licenses)

### Dependencies
1. What are the dependencies? (e.g., infrastructure/tools access, access rights)
2. Are there any other dependencies?
3. Do you see any other problems/challenges?

---

## Implementation

### Technology Preference
1. Does the client have a technology preference?
