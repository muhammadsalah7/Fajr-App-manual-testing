# 🕌 Fajr Alarm App QA Documentation

This repository contains the QA testing documentation for the **Fajr Alarm Application**, including feature summaries, executed test plans, test cases, and QA recommendations. The application helps users manage prayer times, alarms, reminders, and Qibla direction with a wide array of customizable options.

---

## 📋 Features Summary

### Prayer Times & Navigation
- Hijri date display with swipe/arrow navigation
- Next prayer countdown with progress ring
- Location-based prayer times display
- Tap-to-configure prayer notifications

### Prayer Notifications
- Azan and alarm sound selection (local and downloadable)
- Pre-prayer & Iqamah reminders with sound and timing options
- Sunrise alarm toggle
- Fajr alarm redirect options

### Alarm System
- Separate Fajr and Suhoor alarms
- Time configuration before/after prayer
- Sound selection, volume settings, gentle wake-up
- Wake-up challenges (math, shake, memory, random, questions)
- Bedtime reminders (exact or relative to Fajr)
- Wake-up check notifications

### Qibla Detection
- Compass-based direction with success confirmation
- Location accuracy and Kaaba distance

### App Settings
- Prayer time calculations (method, angles, mazhab)
- Language, Hijri correction, widget, calendar sync
- App permissions, share/rate/support features

---

## 🧪 Test Execution Summary

### Test Plan
- Comprehensive plan covering alarm behavior, sounds, toggles, challenges, and reminders
- Regression-ready structure with automation and manual checks

### Manual Test Cases
- ✅ **23 total test cases executed successfully** on Android 14 / ONE UI 6.0
- Covered scenarios include:
  - Fajr alarm timing (before/after)
  - Sound management (local, azan, downloadable)
  - Volume configuration and gentle alarm toggle
  - Challenge logic and preview functionality
  - Bedtime and wake-up check reminders
  - Save and discard logic for user selections

---

## 🐞 Bugs & Ambiguities

- Minute-only Fajr alarm time selector (recommend hours:minutes UI)
- Suhoor toggle disables instantly vs. Fajr toggle showing options
- Duplicate share options in Settings tab
- Navigation inconsistency between Prayer Notifications and Prayer Times tabs
- Unclear use of copied User ID
- Prayer times arrows positioned near location, not the date
- Non-linear volume increments (in some ranges)

---



## 📌 Notes

This QA documentation serves as a comprehensive reference for functional testing, regression planning, and future enhancements for the Fajr Alarm application. All test cases and recommendations are derived from hands-on execution and real device validation.

---

**Prepared by:** *Muhammad – QA Automation Engineer*  
**Location:** Alexandria, Egypt  
**Platform:** Android 14 / ONE UI 6.0  
