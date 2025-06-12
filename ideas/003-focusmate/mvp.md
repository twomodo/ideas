# Minimum Viable Product

> 💡 Define the smallest set of features that creates value for users and allows for meaningful feedback.

## Must Have Features
- [ ] **User Authentication**
  - Email/password signup
  - Social login (Google, Apple)
- [ ] **Virtual Focus Sessions**
  - Join or create a session (1:1 or group)
  - Push-to-talk audio (walkie-talkie style)
  - Pomodoro timer with notifications
- [ ] **Basic Reporting**
  - End-of-session summary
  - Daily/weekly focus stats
- [ ] **Device Integration (Softphone MVP)**
  - Use phone sensors for haptic feedback
  - Button to toggle mic (simulate hardware)

## Nice to Have Features
- [ ] **Health Reminders**
  - Posture and break suggestions
- [ ] **Desktop Integration**
  - Bluetooth actions (mute/unmute, notifications)
- [ ] **Advanced Matching**
  - Match by interests, profession, or goals

## Out of Scope
- Hardware device manufacturing (for initial MVP)
- AI-based posture detection (for v1.0)
- Cross-platform frameworks (e.g., Flutter)

## Tech Stack for MVP
- Native iOS app (Swift/SwiftUI)
- Supabase backend (auth, database, realtime)
- WebRTC for real-time audio
