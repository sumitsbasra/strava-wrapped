# 🏃 Recap.fit — Your Year in Motion

A beautiful, privacy-focused fitness year-in-review that transforms your Strava data into a stunning visual story.
![IMG_0850](https://github.com/user-attachments/assets/235770ab-16b7-45b1-80b8-588317c6ba16)

## ✨ Features

- **15 Animated Story Cards** — Distance, time, elevation, heart rate, streaks, PRs, and more
- **Beautiful Design** — Gradient backgrounds, smooth animations, mobile-friendly
- **100% Private** — Fully client-side; your data never touches our servers
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
2. Follow the onboarding wizard
3. Paste your Client ID and Client Secret
4. Click "Connect with Strava"
5. Authorize the app
6. Enjoy your personalized 2025 Wrapped! 🎉

### Returning Users

Your credentials are saved in your browser. Just visit [recap.fit](https://recap.fit) and your Wrapped loads automatically.

## 🔒 Privacy & Security

**Your data stays yours.**

- ✅ Credentials stored only in your browser's localStorage
- ✅ Fitness data fetched directly from Strava to your browser
- ✅ No server, no database, no tracking
- ✅ Fully open source — inspect the code yourself

We never see your Strava data or API credentials. Everything runs locally in your browser.

## 🛠 Self-Hosting / Fork Your Own

Want to run your own instance?

1. **Fork this repo**
2. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
3. **Update the CNAME file** with your domain (or delete it to use `yourusername.github.io`)
4. **Update callback domain** — Users will need to set their Strava app's Authorization Callback Domain to match your hosted URL

### Local Development

Just open `index.html` in a browser. For OAuth to work locally, you'd need to:
1. Create a Strava API app with callback domain `localhost`
2. Serve via local server: `python -m http.server 8000`
3. Visit `http://localhost:8000`

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
