# The Solution: Subscription Tracker

> 💡 A privacy-first, mobile-first app that helps users manage and reduce their monthly subscription expenses with a clean, modern experience.

## Core Features

1. **Manual Subscription Management**
   - What: Add, edit, or delete subscriptions with name, cost, billing cycle, and renewal date
   - How: Simple forms and intuitive UI for fast entry
   - Why: Empowers users to track all recurring expenses without privacy risks

2. **Overview Dashboard**
   - What: See total monthly spending, active and past subscriptions at a glance
   - How: Minimalist dashboard with clear summaries and visual cues
   - Why: Helps users understand and control their recurring expenses

3. **Renewal Reminders**
   - What: Push notifications before renewal dates
   - How: Opt-in reminders, customizable timing
   - Why: Prevents surprise charges and forgotten renewals

4. **Calendar/Timeline View**
   - What: Visualize upcoming renewals in a calendar or timeline
   - How: Interactive calendar/timeline component
   - Why: Makes it easy to plan and avoid overlapping charges

5. **Privacy-First Data Handling**
   - What: No bank/email access required for core features, local storage by default
   - How: All data stays on device unless user opts in to sync
   - Why: Builds trust and protects user privacy

6. **Light/Dark Theme Support**
   - What: Seamless switching between light and dark modes
   - How: System theme detection and manual toggle
   - Why: Improves usability and accessibility

7. **Freemium Model**
   - What: Basic tracking is free, premium features include bank/email sync and insights
   - How: In-app upgrade to unlock advanced features
   - Why: Lowers barrier to entry and supports sustainable growth

## Technology Stack

### Frontend
- **Flutter**: Cross-platform mobile development for iOS and Android
- **Dart**: For fast, expressive UI code

### Backend
- **Supabase**: Authentication, database, and push notifications
- **PostgreSQL**: Reliable, scalable data storage (via Supabase)

### Data & Privacy
- **Local Storage**: All data stored on device by default
- **End-to-End Encryption**: For any cloud-synced data
- **GDPR Compliance**: User consent and data export/delete options

### Notifications
- **Supabase Push**: For renewal reminders and alerts

## Key Differentiators

1. **Privacy-First by Design**
   - No sensitive data leaves the device without explicit consent
   - No bank or email access required for core features

2. **Minimal, Modern UI**
   - Inspired by Notion and Minimalist apps
   - Fast onboarding and easy manual entry

3. **Actionable Reminders**
   - Reliable, customizable notifications
   - Visual calendar/timeline for planning

4. **Cross-Platform & Scalable**
   - Built with Flutter for iOS and Android
   - Supabase backend for easy scaling and feature expansion

## Terminology

- **Subscription**: Any recurring payment (monthly, yearly, etc.)
- **Renewal Reminder**: Notification sent before a subscription renews
- **Privacy-first**: No sensitive data leaves device without user consent
- **Freemium**: Basic features are free, advanced features require payment
- **Recurring Expense**: Any payment that repeats on a schedule
- **Onboarding**: The process of introducing new users to the app’s features and value
