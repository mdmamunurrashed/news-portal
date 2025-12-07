# 📰 News Portal - Simple CRUD Application (Md. Mamun Ur Rashed, 2506120)

A full-featured news portal built with vanilla JavaScript and JSON-Server, allowing users to create, read, update, and delete news articles with comments.

## ✨ Features

- 🔐 User authentication (simulated)
- 📝 Create, edit, and delete news articles
- 💬 Add comments to news posts
- 👤 Author-based authorization (only authors can edit/delete their posts)
- 📱 Responsive design

## 🚀 Quick Start

### Prerequisites
- [Node.js](https://nodejs.org/) installed

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/mdmamunurrashed/news-portal.git
cd news-portal
```

2. **Install JSON Server globally**
```bash
npm install -g json-server
```

3. **Start JSON Server**
```bash
npx json-server -w db.json --port 3000
```

4. **Open the application**
   - Install [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.vscode-live-server) extension in VS Code
   - Right-click `index.html` and select "Open with Live Server"
   - Or simply open `index.html` in your browser

## 🎮 Usage

1. **Login** - Select a user from the dropdown (Alice, Karim, or Nusrat)
2. **View News** - Browse all news articles on the main page
3. **Create News** - Click "Create News" button and fill in the form
4. **View Details** - Click "View Details" to read full article and comments
5. **Add Comments** - Scroll down on detail page and post a comment
6. **Edit/Delete** - Only available for your own news posts

## 📁 Project Structure

```
news-portal/
├── index.html          # Login page
├── news-list.html      # Main news listing
├── create-news.html    # Create new news
├── news-detail.html    # News details with comments
├── edit-news.html      # Edit existing news
├── db.json             # Database (Mock JSON Server)
└── NewsPortal.pdf      # Assignment Requirements 
```

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** JSON Server (Mock REST API)
- **Storage:** JSON file-based database

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/users` | Get all users |
| GET | `/news` | Get all news |
| GET | `/news/:id` | Get specific news |
| POST | `/news` | Create new news |
| PATCH | `/news/:id` | Update news |
| DELETE | `/news/:id` | Delete news |


## 👨‍💻 Author

Md. Mamun Ur Rashed - [GitHub](https://github.com/mdmamunurrashed)

---

⭐ Star this repo if you find it helpful!
