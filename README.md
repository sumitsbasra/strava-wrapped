# 🏃 recap.fit — Your Year in Motion

A beautiful, privacy-focused fitness year-in-review that transforms your Strava data into a stunning visual story.
![IMG_0850](https://github.com/user-attachments/assets/fe6840dd-d964-4d08-a794-c5a8afc04e4f)


## ✨ Features

- **15 Animated Story Cards** — Distance, time, elevation, heart rate, streaks, PRs, and more
- **Beautiful Design** — Gradient backgrounds, smooth animations, mobile-friendly
- **100% Private** — Fully client-side; your data never leaves your device
- **No Approval Needed** — Uses your own Strava API credentials

## 🚀 How to Use

### First-Time Setup (2 minutes)

**Step 1: Create a Strava API App**

1. Go to [strava.com/settings/api](https://www.strava.com/settings/api)
2. Fill in the form:
   - **Application Name:** `My Recap` (or anything you like)
   - **Category:** `Social`
   - **Club:** (leave blank)
   - **Website:** `recap.fit`
   - **Authorization Callback Domain:** `recap.fit`
3. Click **Create**

**Step 2: Get Your Credentials**

After creating your app, you'll see:
- **Client ID** — A 5-6 digit number
- **Client Secret** — A long alphanumeric string

**Step 3: Connect**

1. Visit [recap.fit](https://recap.fit)
2. Follow the onboarding flow
3. Paste your Client ID and Client Secret
4. Click "Save & Connect"
5. **You'll be redirected to Strava's authorization page** — This is part of OAuth 2.0 security. Even though you created the API app, you still need to authorize it to access your data. This happens every time you connect (or when your session expires).
6. Click **Authorize** on Strava's page
7. You'll be redirected back to recap.fit
8. Enjoy your personalized 2025 Wrapped! 🎉

**Why the Strava redirect?**
This is OAuth 2.0 working as designed. Creating a Strava API app gives you credentials, but you still need to explicitly authorize those credentials to access your data. This security measure ensures no app can access your Strava data without your explicit permission—even your own app!

### Returning Users

Your credentials are saved in your browser. Just visit [recap.fit](https://recap.fit) and your Wrapped loads automatically.

## 🔒 Privacy & Security

**Your data stays yours.**

- ✅ Credentials stored only in your browser's localStorage
- ✅ Fitness data fetched directly from Strava to your browser
- ✅ No server, no database, no tracking
- ✅ Fully open source — check out the code yourself

We never see your Strava data or API credentials, everything runs locally in your browser!

## 📊 What's Included

| Card | Stats Shown |
|------|-------------|
| Intro | Personalized welcome |
| Distance | Total km, weekly avg, longest run |
| Time | Hours moving, avg per activity |
| Elevation | Total climb, biggest climb |
| Heart Rate | Max, avg, resting change |
| Calories | Total burned, daily avg |
| Activities | Breakdown by type |
| Streak | Longest streak, activity heatmap |
| Pace & PRs | Best times across distances |
| Kudos | Given and received |
| Segments | Local legends, top efforts |
| Start Time | Favorite workout time |
| Records | Personal records achieved |
| Best Month | Your peak month |
| Summary | Year overview with all key stats |

## 🤝 Contributing

Contributions welcome! Feel free to:
- Report bugs
- Suggest features
- Submit PRs

---

**Built with ❤️ for athletes who want to celebrate their year.**
