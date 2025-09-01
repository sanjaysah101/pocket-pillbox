# 🩺 Pocket Pillbox

**The medication reminder that just works—for everyone.**  
Ultra-accessible, fully self-contained, and so simple you can trust your grandparents to use it—anytime, anywhere.

## 🚀 What is Pocket Pillbox?

Pocket Pillbox is a compact, single-file web app designed especially for older adults to easily remember and track their daily medications.

- **Big, clear buttons and text** for effortless reading and use
- Add, check off, and clear medication reminders
- **Persists your reminders safely in the browser (localStorage)**—your data never leaves your device

## ⭐️ Why We Stand Out

- **No installs, no accounts, just open and go—online or offline**
- One file, zero setup, and no hidden requirements
- **Specifically crafted for accessibility and tech-averse users**  
- Works even if your internet is disconnected* (see below)

## 🏆 Hackathon Track Statement

We proudly accepted the hardest challenge!  
**Pocket Pillbox** was built to shine in these three tracks:

### 1. Grandma's Digital Sage

> **Wisdom through simplicity:**  
> Pocket Pillbox is designed for everyone—especially for older adults or anyone who needs clear, easy-to-use tools.  
>
> - Big, readable text and buttons  
> - High-contrast color scheme and large tap targets  
> - Intuitive, step-by-step flow with clear labeling  
> - Supports keyboard-only navigation, screen readers, and effortless accessibility  
> **No explanation needed—a grandparent can set a medication reminder in seconds**

### 2. Single-Request Samurai

> **One perfect strike:**  
> Pocket Pillbox is completely self-contained.  
>
> - All HTML, CSS, and JavaScript live inside a single file  
> - No external APIs, CDNs, images, or fonts  
> - No network requests after the initial load  
> Once you open the file or page, everything runs instantly and locally.

### 3. Monolith Master

> **One sacred scroll:**  
> The entire application is delivered as a single, standalone `.html` file.  
>
> - No install, build steps, or extra assets required  
> - Share, backup, or use the app anywhere by distributing just one file  
> - Works the same whether opened from a hard drive, USB stick, or web server

#### ⭐️ (Bonus: Persistent localStorage)

While not an official track, we use `localStorage` to keep reminders safe—
even after you close/reopen the browser or restart your device. No login required. No data lost.

#### Track Summary

| Track                  | How We Meet It                                                                |
|------------------------|-------------------------------------------------------------------------------|
| Grandma's Digital Sage | Large fonts, clear labeling, accessible UI, supports older/sight-impaired users |
| Single-Request Samurai | All code/resources in a single HTML file, zero network calls after first load   |
| Monolith Master        | Only one .html file needed for full functionality                              |

## ✨ Features

- **Add, edit, delete, and check off medication reminders**
- **Today’s Meds checklist:** Mark as taken each day
- **Easy clear/reset** feature
- Local data storage for safety and privacy
- **Pure vanilla JS** (no frameworks, libraries, or build tools)
- **Accessible, readable UI** on all major browsers

## 🎨 Accessibility

Pocket Pillbox is thoughtfully designed for:

- **Seniors or anyone with dexterity/vision challenges**
- Large fonts & high-contrast colors
- Big tap targets and clear labeling
- Simple language and unambiguous controls
- Full keyboard navigation and screen reader support (WAI-ARIA + semantic HTML)

## 🌐 How does it work?

1. **Open** the app in any modern web browser (desktop or mobile).
2. **Add** your daily medications in seconds.
3. **Check off** each item as you take it, every day.
4. **Offline-friendly:** As long as the file was loaded once, your reminders persist—even if you close your browser or lose your internet connection. *(Works offline via browser cache/localStorage, not a service worker)*

## 🛠️ Technical Approach

- All code and assets in a single `/index.html` file
- No network requests after initial load
- All reminders and settings stored in browser `localStorage`
- *No service worker*: maximizes compatibility (even from `file://`); offline persistence relies on browser cache
- ~200 lines of modern, commented vanilla JS—framework-free!
- SVG icons and styles are fully inlined

## 📝 Try it out

1. [**Open the HTML file**](./index.html) or download/clone the repo.
2. Double-click or open in your favorite browser—no setup required!

## 🧪 User Testing & Accessibility

- Manual keyboard and screen reader testing (tab order, focus indication, labels)
- Simulated with 200% zoom and high-contrast modes
- Received feedback from users aged 60+ (real-world accessibility insights!)

## 🙌 Credits

Built by **Web Warriors '24** for the Web Warriors '24 hackathon.

### Contact / Feedback  

[Discord](https://discord.gg/sanjaysah101)  
[LinkedIn](https://linkedin.com/in/sanjaysah101)

**Judges:** Please try out the app in Airplane Mode and see how easy it is for users of any age.  
*Thank you for supporting web accessibility for all!*
