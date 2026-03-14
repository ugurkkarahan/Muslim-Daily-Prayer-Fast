# Muslim Daily: Ramadan & Prayer

iOS app for Ramadan and daily prayer. Displays iftar and sahur times, full prayer times, countdown, daily dua and Quran verse, qibla direction, religious days calendar, dhikr counter, and rich notifications.

## Features

### Ramadan
- **Iftar & Sahur times** — Based on your selected city (Diyanet for Turkey, Aladhan for the rest of the world)
- **Live countdown** — Time remaining until iftar, sahur, or Ramadan start
- **Daily Dua** — A different prayer each day on the Ramadan screen
- **Eid screen** — Completion message when Ramadan ends

### Prayer Times
- **Full prayer times** — Imsak, Sunrise, Dhuhr, Asr, Maghrib, Isha for your location
- **Next prayer countdown** — Time until the next prayer
- **Daily Quran verse** — A different verse each day with translation (locale-based)
- **Nearby mosques** — Find mosques on the map and get directions (Premium)

### Qibla
- **Qibla compass** — Direction to the Kaaba using device location and heading

### Religious Days & Nights
- **Islamic occasions calendar** — Blessed nights (kandils), Eid, and other occasions with dates and countdown to the next

### Dhikr
- **Custom dhikr counter** — Create your own dhikrs with optional target and completion date
- **Session timer** — Tracks time spent on each dhikr
- **Completion tracking** — Mark and review completed goals

### Notifications
- **Ramadan** — 2 hours, 1 hour, and 30 minutes before iftar and sahur; greeting at iftar time; optional Eid greeting
- **Prayer times** — At the start of each prayer (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha)
- **Daily Dua & Verse** — Reminder at 12:00 PM
- **Dhikr reminder** — At 10:00 AM
- **Friday prayer** — 1 hour before Jumu’ah

All notification types can be turned on or off in **Settings → Notifications**.

### Widgets
- **Iftar & Sahur widget** — Countdown to iftar or sahur; small, medium, and lock screen (inline, rectangular, circular)
- **Prayer times widget** — Next prayer countdown plus full prayer times grid; small, medium, large

Widget content requires Premium.

### Other
- **Theme** — Light, dark, or system
- **Multi-language** — English, Turkish, Arabic, and others (Localizable)
- **Premium (IAP)** — Weekly, monthly, yearly subscription or lifetime; removes ads, unlocks widgets and nearby mosques

## Technologies

- **SwiftUI** — iOS 16+
- **StoreKit 2** — Subscriptions and lifetime purchase
- **CocoaPods** — Google Mobile Ads (AdMob)
- **MapKit** — Location search (MKLocalSearchCompleter), nearby mosques
- **Core Location** — Qibla direction, user location for mosque search
- **User Notifications** — Local notifications
- **WidgetKit** — Home and lock screen widgets (App Group for data sharing)
```

## Support

For questions or issues, please open an issue at [GitHub Issues](https://github.com/ugurkkarahan/Muslim-Daily-Ramadan-Prayer/issues).

## Privacy

See [PRIVACY_POLICY.md](PRIVACY_POLICY.md) for our privacy policy.
