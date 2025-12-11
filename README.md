# 🚀 MeiliBoard — The Open Source Dashboard for Meilisearch

MeiliBoard is a **beautiful, modern, fully open-source dashboard** for **self-hosted Meilisearch**.  
It fills the biggest gap in the Meilisearch ecosystem:  
there is *no good dashboard* unless you pay for Meilisearch Cloud.

This project gives everyone — developers, startups, hobbyists —  
a **free and powerful UI** to manage indexes, documents, settings, tasks, and API keys.

---

## ✨ Features

### 📁 Index Management
- List all indexes  
- Create / delete indexes  
- View index metadata  
- Document count, storage stats  

### 🔍 Document Explorer
- Query documents inside the dashboard  
- View JSON with syntax highlighting  
- Edit, update, or delete documents  
- Upload JSON/CSV bulk documents  

### ⚙️ Settings Editor
Configure each index visually:
- Ranking rules  
- Filterable attributes  
- Sortable attributes  
- Faceting  
- Stop words  
- Synonyms  
- Distinct attribute  
- Searchable attributes  

### 🧩 API Keys Manager
- List all keys  
- Create new keys  
- Set permissions (read/search/write/admin)  
- Expiry dates  
- Delete keys  

### 📊 Stats & Monitoring
- Total indexes  
- Total documents  
- Task history  
- Failed tasks  
- Processing queue  
- Real-time stats (if enabled)  

### 🔐 Secure
- No backend required  
- API keys stored locally  
- Self-host only (you control everything)  

---

## 🖥 Tech Stack

- ⚡ **React / Next.js**
- 🎨 **TailwindCSS + shadcn/ui**
- 🧠 **Zustand for state**
- 📊 **Recharts for charts**
- 🔎 **Official Meilisearch JavaScript SDK**

---

## 🚀 Quick Start

### 1. Clone the project

```bash
git clone https://github.com/YOUR_USERNAME/meiliboard.git
cd meiliboard
````

### 2. Install dependencies

```bash
npm install
```

### 3. Create `.env.local`

```env
NEXT_PUBLIC_MEILI_URL=http://localhost:7700
NEXT_PUBLIC_MEILI_API_KEY=MASTER_OR_ADMIN_KEY
```

> Only stored locally. Never uploaded.

### 4. Run the app

```bash
npm run dev
```

Go to:

```
http://localhost:3000
```

Enjoy your **Meilisearch Dashboard** 🎉

---

## 📦 Deployment

Deploy anywhere:

* Vercel
* Netlify
* Docker
* Fly.io
* Render

Just set:

```
NEXT_PUBLIC_MEILI_URL
NEXT_PUBLIC_MEILI_API_KEY
```

---

## 🗺 Roadmap

* [ ] Query logs viewer
* [ ] Dark mode
* [ ] CSV export
* [ ] Import Meilisearch snapshots
* [ ] Multi-host support
* [ ] Plugin system
* [ ] Webhook tester
* [ ] Custom dashboards (widgets)

Have ideas? Open an issue!

---

## 🤝 Contributing

Pull Requests are welcome! ❤️
If you want to add a feature, improve UI, fix bugs, or refactor — jump in.

### Steps

1. Fork the repo
2. Create feature branch
3. Commit changes
4. Open PR

We are friendly — don’t hesitate to ask for help.

---

## ⭐ Support the Project

If this dashboard helps you, please:

* ⭐ Star the repo
* 🐦 Share it on X/Twitter
* 🧩 Contribute a feature
* 💬 Give suggestions

Your support keeps this project alive.

---

## 📄 License

MIT License — do whatever you want, just keep the copyright.

---

## ❤️ Built Because the Community Needed It

Meilisearch is a great search engine —
but for years, the community has had **no proper dashboard** for self-hosting.

This project exists to fix that.

> Free, open-source, and made for developers.
