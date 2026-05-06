# 🎌 AniTrack

<div align="center">

```
 █████╗ ███╗   ██╗██╗    ████████╗██████╗  █████╗  ██████╗██╗  ██╗
██╔══██╗████╗  ██║██║    ╚══██╔══╝██╔══██╗██╔══██╗██╔════╝██║ ██╔╝
███████║██╔██╗ ██║██║       ██║   ██████╔╝███████║██║     █████╔╝ 
██╔══██║██║╚██╗██║██║       ██║   ██╔══██╗██╔══██║██║     ██╔═██╗ 
██║  ██║██║ ╚████║███████╗  ██║   ██║  ██║██║  ██║╚██████╗██║  ██╗
╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝  ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

**your personal anime universe. no cap. 🔥**

[![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-anilist01.netlify.app-7c3aed?style=for-the-badge&logo=netlify&logoColor=white)](https://anilist01.netlify.app)
[![MAL Import](https://img.shields.io/badge/MAL-IMPORT%20READY-2e51a2?style=for-the-badge&logo=myanimelist&logoColor=white)](https://myanimelist.net)
[![Built with](https://img.shields.io/badge/BUILT%20WITH-vibes%20%2B%20html-a855f7?style=for-the-badge&logo=html5&logoColor=white)]()
[![Status](https://img.shields.io/badge/STATUS-BUSSIN%20FR-22c55e?style=for-the-badge)]()

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDd4NHRzaGN6dGZ0aGN6dGZ0aGN6dGZ0/giphy.gif" width="600"/>

</div>

---

## ✨ what even is this

bro if you're tired of MyAnimeList looking like it was built in 2003 and forgot to update... **AniTrack said not today bestie** 💅

this is a **full anime tracking app** that slaps harder than your favorite opening theme. dark purple aesthetic, smooth animations, and it actually works on mobile (insane concept ik)

---

## 🚀 features that go crazy

| feature | vibe check |
|---|---|
| 🔍 **Smart Search** | type one letter and it already knows the anime fr |
| 🖼️ **Anime Posters** | pretty pictures go brr via Jikan API |
| 📊 **Status Tracking** | watching / completed / on hold / dropped / ptw |
| ⭐ **Star Ratings** | rate your anime 1-10 like a proper critic |
| 📤 **MAL Export** | export to XML and flex your list on MAL |
| 📥 **MAL Import** | import your existing MAL list using real anime IDs (no cap 100% match rate) |
| 🧠 **For You** | AI powered recommendations based on YOUR list |
| 📱 **Mobile Ready** | works on your phone unlike some other apps 💀 |
| 💾 **Local Storage** | your data stays yours, no login needed |
| 🔐 **Auth Ready** | Google login coming soon bestie |

---

## 🎨 the aesthetic

```
background: #0a0a0f  ← blacker than your ex's soul
primary:    #7c3aed  ← purple like royalty
accent:     #a855f7  ← lighter purple go brrr
cards:      glassmorphism ← fancy glass effect
animations: smooth af ← no jank allowed
```

no light mode. we don't do that here. 🌑

---

## 🛠️ tech stack (lowkey impressive)

```
Frontend    →  Pure HTML + CSS + Vanilla JS
              (no framework needed when you're built different)

Anime Data  →  Jikan API v4 (free MAL API, no key needed)
              https://api.jikan.moe/v4

Storage     →  localStorage (your browser got you)

Hosting     →  Netlify (free tier because we're smart)

Auth        →  Supabase (coming soon, it's giving backend)
```

---

## 📦 how to run (it's literally this easy)

```bash
# step 1: clone it
git clone https://github.com/01Whitedevil/AniTrack.git

# step 2: open it
open anime-list.html

# step 3: that's it. you're done.
# no npm install. no node_modules hell. just vibes.
```

> no build step. no dependencies. just open the html file and go crazy 🎉

---

## 📥 importing your MAL list

1. go to **myanimelist.net/panel.php?go=export**
2. export your list as XML
3. open AniTrack → click **⬆ Import MAL XML**
4. select your file
5. watch all your anime appear with posters like magic ✨

> uses real MAL IDs for 100% match rate. no "not found" L's here

---

## 📤 exporting to MAL

1. add your anime in AniTrack
2. click **⬇ Export MAL XML**
3. go to **myanimelist.net/import.php**
4. select **MyAnimeList Import**
5. upload the file
6. flex your completed list 💪

---

## 🧠 for you — recommendation system

> *"bro how did it know i'd like that anime"*

AniTrack analyzes your entire list and hits the Jikan API for recommendations based on every anime you've ever watched/completed/dropped (yes even the ones you dropped at ep 3 😭)

- filters by genre
- sorts by how many times it got recommended
- shows WHY it was recommended
- one click add to Plan to Watch
- "not interested" button for the ones that ain't it

---

## 📁 project structure

```
AniTrack/
│
├── anime-list.html      ← the whole app (yes just one file)
├── README.md            ← you are here
└── myanimelist.xml      ← sample MAL export (304 anime btw)
```

---

## 🗺️ roadmap (stuff we cookin)

- [x] anime search with auto suggest
- [x] MAL XML import/export
- [x] poster images
- [x] status tracking
- [x] star ratings
- [x] filter & sort
- [x] stats dashboard
- [ ] 🔐 google login
- [ ] ☁️ supabase backend (cross device sync)
- [ ] 🧠 recommendation system (for you tab)
- [ ] 📌 pinterest poster export
- [ ] 📱 PWA (install on phone like an app)
- [ ] 🌐 public profile pages

---

## 🤝 contributing

found a bug? got a fire feature idea? drop a PR bestie

```bash
git checkout -b feature/your-idea-goes-here
git commit -m "feat: added something that actually slaps"
git push origin feature/your-idea-goes-here
```

open a PR and we'll vibe check it together 🫡

---

## 📊 stats (real ones)

```
Total Anime in Sample List  →  304
Completed                   →  304 (yeah we don't mess around)
Lines of Code               →  actually a lot ngl
Cups of coffee consumed     →  yes
Times MAL import failed     →  used to be many, now zero 💀
```

---

## 🙏 credits

- **Jikan API** — the real MVP, free MAL data for everyone
- **MyAnimeList** — for existing so we could make something better
- **Antigravity** — built this thing with actual skill
- **You** — for having good taste in anime tracker apps

---

<div align="center">

**made with 💜 and way too much free time**

*if this helped you, drop a ⭐ on the repo. it's free and it means a lot fr*

```
    /\_/\  
   ( o.o ) 
    > ^ <  
```

**01Whitedevil** | [MAL Profile](https://myanimelist.net/profile/01Whitedevil) | [Live App](https://anilist01.netlify.app)

</div>
