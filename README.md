# RandoTone
**Offline-first ringtone personalization for iOS**

RandoTone is a concept iOS app that explores how personalization can extend into system-adjacent experiences like ringtones, while respecting iOS platform constraints and user privacy.

This project is designed as a **portfolio and learning project**, not a production app.

---

## Why This Project

Most people listen to thousands of songs but keep the same ringtone for years.

RandoTone explores:
- How music taste could influence ringtones
- How to design within iOS limitations
- How to prioritize clarity, privacy, and user intent

---

## Key Principles

- ✅ Offline-first after setup  
- ✅ Apple Music only (read-only access)  
- ✅ No analytics, ads, or accounts  
- ✅ On-device logic after setup  
- ✅ User-initiated actions only  

---

## App Flow

1. Connect Apple Music during setup  
2. Receive a suggested ringtone based on liked songs  
3. Preview a 30-second clip  
4. Follow iOS guidance to set the ringtone  

---

## Platform Constraints (Intentional)

iOS does not allow:
- Automatic ringtone switching
- Programmatic system ringtone changes
- Direct use of Apple Music tracks as ringtones

This project intentionally designs **within** those limits instead of working around them.

---

## Tech (Concept)

- SwiftUI  
- MusicKit (read-only)  
- AVFoundation (local preview, conceptual)  

---

## Status

✅ UI mock complete  
✅ App Store preview assets complete  
✅ Portfolio-ready  

---

## Author

Built by **[alistorfalls]**
