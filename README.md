<div align="center">

# 🖥️ DB88

**An honest browser that only opens what can be opened.**

</div>

---

## 👋 Welcome

Every modern browser promises the same thing: the entire internet, at your fingertips. It's a beautiful promise — and it's a lie. Half the web doesn't want to be opened in a small window. Google, Facebook, Instagram, Amazon, and most of the sites you visit every day actively block being embedded inside a frame. Your browser pretends this is fine. It isn't.

DB88 doesn't pretend anything. It calls itself **Dumb** on purpose — because it knows its limits, and it tells you the truth about them. If a site refuses to be opened inside a frame, DB88 says so plainly and points you home. If a site works, you get it clean, fast, and with nothing watching you in the background.

There is no tracking here. No ads. No analytics. No account to create. No data leaving your device. Just a small, warm, slightly retro window that opens a specific set of things very well — and is honest about everything else.

Open it, and you'll see: a boot sequence, a khaki-green palette borrowed from an old terminal, chunky pixel buttons, and a tiny set of hand-picked sites that actually work inside a frame. That's the whole product. That's the whole point.

---

## 📸 Look Inside

<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/DB88-MC88/raw/main/images/preview-1.png" alt="The DB88 boot sequence" width="100%" />
  <br />
  <sub><b>① The boot sequence</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/DB88-MC88/raw/main/images/preview-2.png" alt="The home screen with folders" width="100%" />
  <br />
  <sub><b>② The home screen</b></sub>
</div>

<br />
<br />

<div align="center">
  <img src="https://github.com/mohamed005cheikh-rgb/DB88-MC88/raw/main/images/preview-3.png" alt="A site opened inside DB88" width="100%" />
  <br />
  <sub><b>③ A site, opened clean</b></sub>
</div>

---

## ✨ What you'll find

**A boot sequence, every time.**  
Six seconds of pixel font, scanlines, a progress bar, and a fake log streaming lines like an old computer waking up. It's pure theater — and it sets the tone for everything that follows. You can tap or press any key to skip it, and DB88 will remember not to slow you down again.

**Two themes built into the design.**  
The default is *khaki* — a warm, paper-green that looks like a monitor from 1988. The alternative is *dark* — the same aesthetic, but at night. One button in the header flips between them, and your choice is saved the next time you open it.

**Folders, not bookmarks.**  
Every saved site lives inside a folder — *News*, *Photos*, *Games*, *Encyclopedia*, or any folder you create. Tap a folder to see its sites. Tap a site to open it. That's it. No tags, no smart suggestions, no algorithmic feed. Just folders, the way we used to organize things.

**Add and remove sites, freely.**  
Tap **⚙ Edit** and the whole interface changes. You can add a new site (name, URL, emoji icon, folder), add a new folder, or delete anything you don't want. Everything is stored in your browser — nothing is sent anywhere. When you close Edit, the interface returns to its clean form.

**A history that actually belongs to you.**  
Every site you open is recorded in a local history log — with a timestamp, a short URL, and a small delete button for each entry. You can clear the whole thing with one tap. There is no cloud sync, no account, no server that knows what you've been looking at.

**Back, forward, home, URL bar.**  
Real navigation. A back button, a forward button, a home button, a URL input for when you want to jump somewhere directly, and a history button that opens your log. Nothing more, nothing less.

**A retro aesthetic that commits all the way.**  
VT323 pixel font. Hard 2-pixel borders. Chunky shadow buttons that press down when you tap them. A grid background behind the splash. CRT scanlines. Every detail follows the same rule: it should feel like a piece of software that knows exactly what it is.

**Local, private, offline-friendly.**  
Everything DB88 stores — your folders, your custom sites, your history, your theme — lives in your own browser. There is no backend, no API, no analytics. You can install it as a PWA, use it offline, and it will keep working exactly the same.

**Honest about what it can't do.**  
If a site refuses to be embedded inside a frame, DB88 shows a page that says — in plain language — *"This site can't be displayed. The website refuses to be embedded in a frame. That's the site's decision — not a bug in DB88."* No error code, no confusing browser message. Just the truth.

---

## 🧭 How it works

**1. Open it.**  
One HTML file, plus a `manifest.json` and a service worker for PWA install. Open it in any browser and the boot sequence starts.

**2. Watch it boot — or skip it.**  
Tap the screen or press any key to skip the six-second intro.

**3. Pick a folder.**  
*News*, *Photos*, *Games*, *Encyclopedia* — or anything you've created yourself.

**4. Tap a site.**  
It opens in a frame inside DB88. If it works, you get it clean. If it doesn't, you get an honest message.

**5. Go back, forward, or home.**  
Standard navigation. No surprises.

**6. Customize it — if you want to.**  
Tap **⚙ Edit** to add your own sites, create folders, or reset everything back to defaults.

**7. Switch themes whenever.**  
One button in the header. Your choice is remembered.

That's the entire browser. Nothing hidden, nothing waiting to surprise you.

---

## 🛠️ A few small helps

**"Why doesn't Google open in DB88?"**  
Because Google blocks being embedded inside a frame. So do Facebook, Instagram, X, Reddit, Amazon, YouTube, and most large commercial platforms. This is their choice, not a limitation of DB88. The whole point of DB88 is that it works with sites that *permit* being embedded — Wikipedia, Internet Archive, OpenStreetMap, small independent sites, embed players, educational tools. Try one of those and it works beautifully.

**"What does 'Dumb' mean in the name?"**  
It's not an insult — it's a design philosophy. Most browsers pretend they can do everything and fail confusingly. DB88 knows what it can do, does it well, and tells you the truth when a site refuses. Honesty over false promises.

**"Can I install it as an app?"**  
Yes. Open it in Chrome or Safari and use **Add to Home Screen** (or the install icon in the address bar). DB88 becomes a real app on your device — same interface, same behavior, works offline.

**"Is anything sent to a server?"**  
No. Everything — folders, sites, history, theme — is stored locally in your browser's `localStorage`. There is no backend. You can turn off your internet and DB88 will keep working exactly the same. The only time the network is used is when *you* open a site, because the site itself is loaded from its own server.

**"How do I add a site that isn't in the defaults?"**  
Tap **⚙ Edit** in the header → **+ Site** → enter the name, the URL (must start with `https://`), pick an emoji icon, choose a folder, then Save. It appears immediately, and it's saved for next time.

**"My history disappeared."**  
If you're in a private or incognito window, your browser wipes local storage the moment you close it. Use a normal window — everything persists across sessions.

**"How do I reset everything?"**  
Tap **⚙ Edit** → **Reset**. You'll get your original folders and sites back. Your history is kept separately, so it stays unless you clear it from the History screen.

**"The boot animation is long."**  
Six seconds on purpose — it's meant to feel like a real machine coming to life. If it bothers you, tap the screen or press any key and it disappears immediately.

**"Why does it look like 1988?"**  
Because that's the point. VT323 font, khaki palette, hard borders, pixel-perfect buttons — DB88 isn't trying to look modern. It's trying to look like software that respects its own aesthetic. If you like it, you like it. If you don't, that's fine too.

---

<div align="center">

### 📞 A question, an idea, a bug?

[![Email](https://img.shields.io/badge/Email-mohamed005cheikh@gmail.com-d14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mohamed005cheikh@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-+222_30_73_64_75-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/22230736475)
[![GitHub](https://img.shields.io/badge/GitHub-mohamed005cheikh--rgb-181717?style=flat-square&logo=github)](https://github.com/mohamed005cheikh-rgb)

<br />

*Dumb on purpose. Honest by design.*

<sub>© 2026 Mohamed Cheikh — MC88</sub>

<br />
<br />

    ███    ███    ████████    ████████    ████████
    ████  ████   ███    ███  ███    ███  ███    ███
    ██ ████ ██   ███         ███    ███  ███    ███
    ██  ██  ██   ███          ████████    ████████
    ██      ██   ███         ███    ███  ███    ███
    ██      ██   ███    ███  ███    ███  ███    ███
    ██      ██    ████████    ████████    ████████

</div>
