# Glimpse Project Timeline

## Overview
8-week timeline for a team of 5 to deliver a functional Glimpse prototype. The plan is structured into two-week phases to allow for deeper focus on planning, development, integration, and testing.

---

### Phase 1: Foundation & Planning (Weeks 1-2)

**Week 1: Detailed Planning & Research**
- **Goal**: Solidify project scope and technical approach.
- **Tasks**: Finalize user stories, define success metrics, conduct in-depth research on the Android Notification Listener service, and compare lightweight NLP models.
- **Deliverable**: A comprehensive project plan and a detailed task backlog.

**Week 2: Environment & Schema Setup**
- **Goal**: Establish a complete development and deployment foundation.
- **Tasks**: Scaffold React Native project, configure Supabase (Auth, DB schema), set up GitHub repository with CI/CD pipeline.
- **Deliverable**: All development environments are set up; initial codebase is committed.

---

### Phase 2: Core Logic Implementation (Weeks 3-4)

**Week 3: Backend & ML Model Development**
- **Goal**: Build the server-side logic and the initial ML model.
- **Tasks**: Backend developer implements Edge Functions for rule processing. ML Engineer develops the first version of the classification model locally.
- **Deliverable**: Functional Supabase Edge Functions for rules; a working Python script for the ML model.

**Week 4: ML Deployment & API Creation**
- **Goal**: Make the ML model accessible to the application.
- **Tasks**: ML Engineer deploys the model to a Supabase Edge Function. Backend Developer creates the API endpoint for classification. QA writes unit tests.
- **Deliverable**: A deployed ML model that can be called via an API endpoint.

---

### Phase 3: Frontend & Integration (Weeks 5-6)

**Week 5: Frontend UI & Native Module**
- **Goal**: Build the user-facing components and the core notification capture mechanism.
- **Tasks**: Frontend Developer builds all UI screens (notification list, settings) and implements the Android Notification Listener service.
- **Deliverable**: A mobile app that successfully captures device notifications and has a complete (but not yet connected) UI.

**Week 6: End-to-End Integration**
- **Goal**: Connect all parts of the system.
- **Tasks**: Frontend connects the UI to the Supabase backend, calls the ML function, and displays the results. Backend enables real-time sync. QA performs initial integration tests.
- **Deliverable**: A fully integrated prototype where notifications flow from the device to the UI, classified by the ML model.

---

### Phase 4: Testing, Refinement & Deployment (Weeks 7-8)

**Week 7: Rigorous Testing & Optimization**
- **Goal**: Ensure the application is stable, performant, and accurate.
- **Tasks**: QA leads usability and performance testing. The team focuses on fixing bugs and optimizing database queries and model accuracy based on feedback.
- **Deliverable**: A stable, beta-quality prototype that meets performance and accuracy targets.

**Week 8: Final Polish & Project Delivery**
- **Goal**: Finalize and deliver the project.
- **Tasks**: Apply final UI polish, deploy the application (APK for testing), complete all documentation, and prepare the final presentation.
- **Deliverable**: A deployed prototype, comprehensive documentation, and presentation materials.

---

## Key Milestones
- **End of Week 2**: Project foundation and environments are fully set up.
- **End of Week 4**: Core backend and ML model are built and deployed.
- **End of Week 6**: A fully integrated prototype with end-to-end functionality is complete.
- **End of Week 8**: The final, tested, and documented prototype is delivered.