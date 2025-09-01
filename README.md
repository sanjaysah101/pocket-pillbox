# 🩺 Pocket Pillbox

**The medication reminder that just works—for everyone.**  
One ultra-accessible, offline-friendly web app you can trust your grandparents to use.

## 🚀 What is Pocket Pillbox?

Pocket Pillbox is a tiny, single-file web app to help users—especially older adults—remember and track their daily medications.  
It works **entirely in your browser, even offline** after the first load—no installs, no accounts, and zero tech confusion.

- **Big, clear buttons and text** for easy use and reading.
- Add, check off, and clear medication reminders.
- Safely stores your reminders in the browser, not in the cloud.

## 🏆 Hackathon Track Statement

We proudly accepted the hardest challenge!  
Pocket Pillbox is built for these three tracks:

1. **Grandma’s Digital Sage**  
   Fair, inclusive, *truly* easy for older adults.  
   > Large UI, simple words, minimal steps, keyboard accessible.

2. **Single-Request Samurai**  
   Just one browser load—no fetches, no external assets—everything is in a single HTML file.

3. **Offline Survivalist**  
   App is fully usable after the first load, even with the internet disconnected. Data persists via localStorage.

## ✨ Features

- **Add a medication reminder:** Name, dosage, and time.
- **Today’s Meds checklist:** Mark doses as taken.
- **Easy clear/reset:** Start over at any time.
- **Offline guaranteed:** All data is stored in your browser.
- **Pure vanilla code:** No frameworks, no libraries, no build steps.

## 🎨 Accessibility

Pocket Pillbox is designed for:

- **Seniors or anyone with dexterity/vision challenges**
- Bold fonts & high-contrast colors
- Large tap targets and labels
- Plain language and unambiguous controls
- Full keyboard navigation and basic screen reader support (WAI-ARIA + semantic HTML)

## 🌐 How does it work?

- Open the app in any modern web browser.
- Add all your daily medicines in seconds.
- Check each as you take it, every day.
- Your reminders will be right there—even if you’re offline, traveling, or run out of data.

## 🛠️ Technical Approach

- **Everything is in `/index.html`**
- All data is managed with native browser [localStorage].
- No network requests after first load.
- (Optional) Service worker included for robust caching (commented if not allowed)
- 200 lines of plain JS—no frameworks.
- Inline SVG icons and all styles in `<style>`.
- Code is commented for clarity and ease-of-review.

## 📝 Try it out

1. Download/clone or [open the HTML file](./index.html).
2. Double-click: it just works (even without a server).

## 🧪 User Testing & Accessibility

- Manual screen reader and keyboard testing (tab order, focus indication).
- Simulated with 200% zoom and high-contrast mode.
- Feedback from two users aged 60+.

## 🙌 Credits

Built by [Web Warriors '24] for Web Warriors '24.

### Contact / Feedback  

[Discord](https://discord.gg/username)  
[LinkedIn](https://linkedin.com/in/username)

*Judges: Please check our app in Airplane Mode! Thank you for supporting web accessibility for all ages.*
