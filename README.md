# MGS Foodie Trophy Tracker

A web-based tracker for the Metal Gear Survive "Foodie" trophy/achievement. Track all 159 food items across 7 categories with user authentication and persistent storage.

## Features

- ✅ User authentication (sign up/login)
- ✅ Persistent progress tracking using localStorage
- ✅ 159 food items organized by category
- ✅ Real-time progress tracking
- ✅ Category-specific progress counters
- ✅ Reset progress option
- ✅ Metal Gear themed dark UI

## Deployment Options

### Option 1: Simple Static Hosting (Recommended)

Just upload `index.html` to any static hosting service:

- **GitHub Pages**: Push to a repo and enable Pages
- **Netlify**: Drag and drop the HTML file
- **Vercel**: Import from GitHub or drag and drop
- **Cloudflare Pages**: Connect your repo
- **Any web server**: Upload to your server

### Option 2: Local Testing

1. Download `index.html`
2. Open it directly in your browser
3. No build process required!

## How to Use

1. **Sign Up**: Create an account with a username and password
2. **Track Progress**: Check off food items as you consume them in-game
3. **Auto-Save**: Your progress saves automatically to localStorage
4. **Multi-User**: Each user has their own progress tracking
5. **Reset**: Use the reset button to clear all progress

## Food Categories

- Raw Food (33 items)
- Grilled Food (25 items)
- Stews (19 items)
- Smoked Food (25 items)
- Baked Food (25 items)
- Steamed Food (25 items)
- Special Food (5 items)

**Total: 159 food items**

## Technical Details

- **Frontend**: React 18 (via CDN)
- **Styling**: Tailwind CSS (via CDN)
- **Storage**: Browser localStorage
- **No Build Required**: Pure HTML file with inline React

## Credits

- Original data compiled by u/thanos89
- Inspired by [MGSurvive-TrophyHelper](https://github.com/Ak-0/MGSurvive-TrophyHelper)

## Notes

- Data is stored locally in your browser
- Clearing browser data will reset progress
- Works offline after initial load
- No server-side backend required

## Support

For issues or questions, please refer to the original Metal Gear Survive trophy guides.

---

**Note**: Spoiled food does not count toward the trophy achievement.