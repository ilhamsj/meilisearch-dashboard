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
