# 💼 Joby — Remote Job Board

A clean, simple job board displaying **20 current remote job openings** sourced from [ZipRecruiter](https://www.ziprecruiter.com). Search, filter, and apply directly.

## 🚀 Live Demo

**[👉 View Joby Live](https://dkerubo.github.io/Joby/)**

## ✨ Features

- 🔍 **Instant search** — Filter by job title, company, or keyword
- 🏢 **Category filter** — Marketing, Design, Development, Sales & more
- 🌍 **Location filter** — Remote USA vs Remote Worldwide
- ⏰ **Job type filter** — Full-Time, Part-Time, Contract
- 💰 **Salary displayed** — Every listing shows compensation
- 🚀 **Apply Now** — One click takes you directly to ZipRecruiter
- 📱 **Fully responsive** — Works on mobile, tablet & desktop
- ⚡ **No frameworks** — Pure HTML, CSS & vanilla JavaScript

## 📊 Job Categories

| Category | Count |
|----------|-------|
| Marketing | 6 |
| Sales | 4 |
| Customer Service | 3 |
| Design | 2 |
| Data & Analytics | 2 |
| Healthcare | 1 |
| Administrative | 1 |
| Development | 1 |

## 🛠 Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — CSS Grid, Flexbox, Custom Properties
- **JavaScript** — Vanilla JS, no dependencies
- **Google Fonts** — Inter typeface
- **GitHub Pages** — Hosting

## 📁 Project Structure

```
Joby/
├── index.html    # Main page
├── style.css     # All styles
├── jobs.js       # Job data (20 listings)
├── app.js        # Search, filter & render logic
└── README.md     # This file
```

## 📝 Adding New Jobs

Edit `jobs.js` and add a new object to the `JOBS` array:

```js
{
  id: 21,
  title: "Your Job Title",
  company: "Company Name",
  location: "Remote (USA)",
  salary: "$XX,XXX/yr",
  type: "Full-Time",
  category: "Marketing",
  tags: ["Skill1", "Skill2"],
  posted: "1 day ago",
  url: "https://www.ziprecruiter.com/..."
}
```

## 📄 License

MIT — built by **Vero** ☀️

---

*Job data sourced from ZipRecruiter (June 2026). Listings may change — always verify on ZipRecruiter.*