# 🌐 Tony An's Personal Website

A personal website project for writing and managing diaries and investment records.

## 📸 Preview

A personal webpage consisting of profile, diary, and investment sections.

## ✨ Features

### Profile Section
- Profile image and introduction
- Date of birth display
- Quote (Dancing Script font)

### 📝 Diary
- Create/delete diary entries
- Image attachment (drag & drop supported)
- Sorted by date

### 💰 Investment
- Stock/Crypto category classification
- Filter by category
- Image attachment

### 🔒 Security
- Password protection (for create/delete)

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Frontend | HTML, CSS, JavaScript |
| Database | Firebase Firestore |
| Font | Google Fonts (Dancing Script) |
| Hosting | GitHub Pages |

## 📁 Project Structure

```
📦 my-website
 ┗ 📜 index.html    # Main page (HTML/CSS/JS integrated)
```

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/my-website.git
```

### 2. Firebase Setup
Update the Firebase configuration in `index.html` with your own project:
```javascript
const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    // ...
};
```

### 3. Change Password
```javascript
const ADMIN_PASSWORD = 'your_password';
```

### 4. Run
Open `index.html` in your browser or deploy via GitHub Pages.

## 🔗 Links

- **Website**: [https://minsu-code.github.io/]
- **X (Twitter)**: [@KR_MSU](https://x.com/KR_MSU)

## 📝 Changelog

- **v1.0** - Initial release
  - Profile section
  - Diary/Investment CRUD functionality
  - Image attachment feature
  - Dark top bar + X link

## 📄 License

This project is licensed under the MIT License.

---

Made with ❤️ by Tony An
