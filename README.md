# 🌐 Personal Portfolio Website

This is my **responsive personal portfolio website** built using **HTML, CSS, JavaScript**, and integrated with **EmailJS API** to enable contact form functionality. It showcases my background, skills, and projects — offering a direct way for visitors to connect with me.

🚀 **Live Demo:** [https://tech-sahilsh.github.io/MyPortfolio/](https://tech-sahilsh.github.io/MyPortfolio/)

---

## ✨ Features

- ✅ Fully responsive design for mobile, tablet, and desktop
- 🧑‍💻 About Me section with skills and education
- 💼 Project showcase with interactive layout
- 📬 Contact form integrated with **EmailJS**
- 🖼️ Smooth scrolling and modern transitions

---

## 🛠️ Tech Stack

| Category     | Technology           |
|--------------|----------------------|
| Frontend     | HTML, CSS, JavaScript |
| Email API    | EmailJS              |
| Deployment   | GitHub Pages         |

---

## 📧 Contact Form (EmailJS)

The contact form uses **EmailJS** to send emails directly to my inbox — no backend required!

### To set it up:
1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create a service and template
3. Replace the following in your JavaScript:
```javascript
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form, 'YOUR_PUBLIC_KEY')
