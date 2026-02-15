# Requirements

## 1. Problem Overview
Current employee well-being strategies in the Indian corporate sector (Bharat) rely on infrequent, subjective surveys that are prone to bias and "survey fatigue." This results in a failure to detect "Micro-Burnout," leading to decreased productivity and high employee turnover.

## 2. Functional Requirements

- **Passive Data Acquisition**: The system must collect non-intrusive digital phenotyping data (e.g., typing rhythm, task-switching frequency) without recording sensitive content.
- **Neurocognitive Scoring**: The AI must process interaction patterns to generate a real-time "Cognitive Health Score" for the user.
- **Threshold-Based Interventions**: The platform must trigger automated suggestions for "Bio-Breaks" or "Linguistic Reframing" exercises when cognitive load exceeds a safe baseline.
- **Administrative Dashboards**: HR managers must have access to aggregated, anonymized heatmaps to identify at-risk departments without compromising individual privacy.

## 3. Non-Functional Requirements

- **Privacy-First Architecture**: Individual raw data must be encrypted and processed locally or in isolated AWS environments to ensure zero data leakage.
- **Latency & Performance**: The background worker must consume less than 1% of CPU resources to ensure it does not interfere with the developer’s or employee’s primary work.
- **Scalability**: The backend must be built using serverless architecture (AWS Lambda) to handle thousands of concurrent users across different startups.

## 4. User Personas

- **The Individual Contributor**: Receives personalized wellness prompts to manage their own mental energy.
- **The HR/Team Lead**: Monitors organizational health trends to adjust deadlines or resources proactively.
