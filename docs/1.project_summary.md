# Project Summary: Glimpse

## Outcome
Glimpse is a smart notification management app for Android that aggregates, prioritizes, and filters notifications in one place. It uses a lightweight machine learning model to classify notifications as "High Priority" or "Low Priority" and allows users to create custom filtering rules. The goal is to reduce notification clutter and help users focus on what matters most.

## Feasibility Study

### Technical Feasibility
- **Software Stack**: The project will be built using React Native (TypeScript) for the Android frontend, Supabase for the backend (PostgreSQL, Auth, Edge Functions), and a lightweight ML model using spaCy/NLTK for notification prioritization.
- **Development Tools**: VS Code, npm/yarn, Git/GitHub, and Postman will be used for development, collaboration, and testing.
- **Strengths**:
    - Supabase simplifies backend development, saving significant time and effort.
    - TypeScript and React Native provide a modern and robust framework for building the app.
    - Using a pre-trained ML model minimizes the effort required for the ML pipeline.
- **Risks & Mitigations**:
    - The primary risk is the complexity of implementing a native Android Notification Listener in React Native. This will be mitigated by having a dedicated Integration Specialist research and document the process.
    - The ML model's accuracy may be limited initially, but it can be refined post-prototype.

### Financial Feasibility
- **Team Investment**: The project involves a 5-member team working for 8 weeks, with a total estimated effort of 480 hours. The hypothetical team stipend is ₹48,000.
- **Cost Estimation**:
    - **Infrastructure**: ~₹2,100/month for Supabase Pro.
    - **Testing & Monitoring**: ~₹1,250/month for services like Firebase.
    - **Total Operational Cost (2 months)**: ₹6,700.
    - **Total Project Cost**: ₹54,700 (including the team stipend).
- **Benefits**: The project has high ROI potential due to its low initial investment and the possibility of a freemium model post-prototype.

## Result
The project is **feasible**. Both the technical and financial assessments indicate that the project can be successfully completed within the planned 8-week timeline and budget. The risks are well-defined and have clear mitigation strategies, and the overall cost is minimal, making it a low-risk, high-reward.