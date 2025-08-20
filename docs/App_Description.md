# Glimpse App: Complete Description

## Overview
Glimpse is a smart notification management app that aggregates, prioritizes, and filters notifications directly from the user's device using machine learning (ML). The prototype targets the **Android** platform, capturing notifications directly from the system's notification panel.

## Key Features
1. **Notification Aggregation**
   - Captures all incoming notifications directly from the Android system's notification panel.
   - Requires the user to grant "Notification Access" permission to the app.
   - Benefit: Centralizes *all* of the user's notifications in one place for unified management.

2. **ML-Driven Notification Prioritization**
   - Classifies notifications as "High Priority" or "Low Priority" using a lightweight ML model (e.g., logistic regression with spaCy for keyword-based NLP).
   - Considers content (e.g., “urgent,” “meeting”) and user behavior (e.g., opened or dismissed notifications).
   - Model hosted on Supabase Edge Functions; feedback stored for retraining.
   - Benefit: Highlights critical notifications, reduces clutter.

3. **Customizable Filtering Rules**
   - Users set rules (e.g., “Prioritize from [contact],” “Mute Slack from 9 PM–7 AM”).
   - Rules stored in Supabase PostgreSQL, processed via Edge Functions.
   - Benefit: Offers manual control over notifications.

4. **Basic Do Not Disturb (DND) Mode**
   - Suppresses low-priority notifications during user-defined time windows.
   - Schedules stored in Supabase; applied server-side.
   - Benefit: Minimizes distractions.
