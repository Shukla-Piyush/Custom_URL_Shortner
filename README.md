# 🔗 URL Shortener

A simple and efficient URL Shortener application that allows users to shorten long URLs into compact, shareable links. Useful for cleaner links, better UX, and tracking.

## 🚀 Features

- ✅ Shorten long URLs
- ✅ Redirect short links to the original URL
- ✅ Copy short URL to clipboard
- ✅ Custom or random short codes (if implemented)
- ✅ URL validation and error handling

## 🛠️ Tech Stack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB 

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/url-shortener.git
cd url-shortener

# Install dependencies
npm install

# Run the server
npm start

Project Structure
url-shortener/
├── models/
│   └── Url.js
├── routes/
│   └── urlRoutes.js
├── controllers/
│   └── urlController.js
├── public/
│   └── index.html
├── app.js
└── package.json
