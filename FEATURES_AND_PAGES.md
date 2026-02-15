# Ramadan Companion – Features and Pages

| Feature | Page / Screen | Where to find it |
|--------|----------------|-------------------|
| **Iftar countdown** | Home | Home tab → top card: “Time until Iftar” + live countdown |
| **Next prayer** | Home | Home tab → card under Iftar: “Next Prayer: [name]” + time and “in Xh Ym” |
| **Quick stats (Prayers today / Juz)** | Home | Home tab → two tappable cards: “X/5 Prayers Today”, “X/30 Juz Complete” |
| **Home menu (shortcuts)** | Home | Home tab → list: Prayer Times, Quran Plan, Progress, Community, Wellness, Sadaqah |
| **Pull-to-refresh (prayer times)** | Home | Home tab → pull down to refresh prayer times |
| **Prayer times list** | Prayer | Prayer tab → five rows: Fajr, Dhuhr, Asr, Maghrib, Isha with times |
| **Ramadan schedule (Suhoor / Iftar / Taraweeh)** | Prayer | Prayer tab → “Ramadan Schedule” card at top |
| **Log prayer (5 daily)** | Prayer | Prayer tab → tap a prayer row to mark it done (checkmark) |
| **30-day Quran plan** | Quran | Quran tab → title + “X/30 done” |
| **Quran progress bar** | Quran | Quran tab → bar under subtitle |
| **Juz grid (mark complete)** | Quran | Quran tab → grid of Juz 1–30, tap to mark complete |
| **Stats (streak, juz, deeds)** | Progress | Progress tab → row: Prayer Streak, Juz Complete, Good Deeds |
| **Achievements / badges** | Progress | Progress tab → “Achievements” section (e.g. First Prayer, 5 Prayers, 1 Juz, …) |
| **Log good deed (preset chips)** | Progress | Progress tab → “Log Good Deed” → chips (Charity, Dhikr, etc.) |
| **Log good deed (custom)** | Progress | Progress tab → text input + “Add” under chips |
| **Recent good deeds** | Progress | Progress tab → “Recent Good Deeds” list |
| **Community events list** | Community | More tab → Community & Events **or** Home → Community & Iftar Events |
| **Event “View on Map”** | Community | Community screen → “View on Map” on each event card |
| **Community tip** | Community | Community screen → tip card at bottom |
| **Hydration tracker (8 glasses)** | Wellness | More tab → Wellness **or** Home → Wellness & Hydration |
| **Sleep window tips** | Wellness | Wellness screen → “Sleep Window” card |
| **Light movement tips** | Wellness | Wellness screen → “Light Movement” card |
| **Eating tips** | Wellness | Wellness screen → “Eating Tips” card |
| **Sadaqah verse (Quran 2:261)** | Sadaqah | More tab → Sadaqah **or** Home → Sadaqah & Giving |
| **Sadaqah cause cards** | Sadaqah | Sadaqah screen → Feed the Fasting, Water Wells, Orphan Support, Emergency Relief |
| **Sadaqah “give through trusted charities” tip** | Sadaqah | Sadaqah screen → tip card at bottom |

---

## By page (summary)

| Page | File | Features on this page |
|------|------|------------------------|
| **Home** | `src/screens/HomeScreen.js` | Iftar countdown, next prayer, quick stats (prayers/juz), menu shortcuts, pull-to-refresh |
| **Prayer** | `src/screens/PrayerScreen.js` | Prayer times list, Ramadan schedule (Suhoor/Iftar/Taraweeh), log 5 prayers |
| **Quran** | `src/screens/QuranScreen.js` | 30-day plan, progress bar, Juz 1–30 grid (mark complete) |
| **Progress** | `src/screens/ProgressScreen.js` | Stats row, achievements, log good deed (chips + custom), recent good deeds |
| **Community** | `src/screens/CommunityScreen.js` | Events list, “View on Map” per event, community tip |
| **Wellness** | `src/screens/WellnessScreen.js` | Hydration tracker (8 glasses), sleep window, light movement, eating tips |
| **Sadaqah** | `src/screens/SadaqahScreen.js` | Quran verse, cause cards (links), trusted-charity tip |

---

## How to open each page

- **Home** → Home tab (first tab).
- **Prayer** → Prayer tab, or Home → “Prayer Times & Taraweeh”.
- **Quran** → Quran tab, or Home → “30-Day Quran Plan”.
- **Progress** → Progress tab, or Home → “Progress & Achievements”.
- **Community** → More tab → “Community & Events”, or Home → “Community & Iftar Events”.
- **Wellness** → More tab → “Wellness”, or Home → “Wellness & Hydration”.
- **Sadaqah** → More tab → “Sadaqah”, or Home → “Sadaqah & Giving”.
