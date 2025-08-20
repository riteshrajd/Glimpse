
# Software Requirements Specification (SRS) for Glimpse

## 1. Functional Requirements

- **FR-1: Notification Capture:** The application must be able to capture all incoming notifications from the Android Notification Listener service.
- **FR-2: Notification Classification:** A machine learning model (TensorFlow Lite) will be used to classify notifications into "High Priority" and "Low Priority" categories.
- **FR-3: Custom Filtering:** Users will be able to create, edit, and delete custom filtering rules based on keywords, applications, and contacts.
- **FR-4: Notification History:** The application will maintain a history of all received notifications, which can be reviewed by the user.
- **FR-5: DND Mode:** A "Do Not Disturb" mode will be available to suppress low-priority notifications during user-defined schedules.

- **FR-6: Android SDK:** The application will be developed using Android SDK version 26 (Oreo) or higher.
- **FR-7: Programming Language:** The application will be written in Kotlin, following modern Android development best practices.
- **FR-8: Local Database:** A local SQLite database will be used to store notification history, user preferences, and custom filtering rules.
- **FR-9: Backend API:** A RESTful API, developed with Node.js and Express.js, will handle user authentication, account management, and data synchronization across devices.
- **FR-10: Cloud Infrastructure:** The backend services will be deployed on a scalable cloud platform, such as AWS or Google Cloud.

## 2. Non-Functional Requirements

### 2.1. Performance
- **NFR-1: Notification Processing:** The time between a notification arriving and it being classified and displayed to the user shall not exceed 2 seconds.
- **NFR-2: UI Responsiveness:** The user interface must respond to user interactions within 500 milliseconds.
- **NFR-3: Battery Consumption:** The application's background services should consume no more than 5% of the device's battery over a 24-hour period.
- **NFR-4: Memory Usage:** The application's memory footprint should not exceed 100MB of RAM on the user's device.

### 2.3. Reliability
- **NFR-8: Service Availability:** The backend services will have a minimum uptime of 99.5%.
- **NFR-9: Data Integrity:** The system will ensure that no notifications are lost or duplicated during processing.
- **NFR-10: Fault Tolerance:** The application will gracefully handle network outages and other potential errors without crashing.

### 2.4. Security
- **NFR-11: Data Encryption:** All user data, both in transit and at rest, will be encrypted using industry-standard encryption algorithms.
- **NFR-12: Secure Authentication:** User authentication will be handled through secure protocols, and session management will be implemented to prevent unauthorized access.
- **NFR-13: Data Deletion:** Users will have the ability to permanently delete their account and all associated data from the application.

### 2.5. Scalability
- **NFR-14: Backend Scalability:** The backend architecture will be designed to handle a growing number of users and a high volume of notifications without any degradation in performance.


## 3. Goal of Implementation

The goal of implementation is to build a robust and scalable Android application based on the defined functional and non-functional requirements. This involves setting up a clean architecture, implementing the core features, and ensuring a high-quality user experience.
