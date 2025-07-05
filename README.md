# 🌐 Personal Portfolio Website

Responsive Personal Portfolio Website
Developed using HTML, CSS, and JavaScript, this fully responsive portfolio highlights my background, technical skills, and featured projects. The site includes a dynamic contact form integrated with the **EmailJS** API, allowing visitors to easily get in touch with me. It serves as a comprehensive introduction to my work and capabilities in web development.

🚀 **Live Demo:** [https://tech-sahilsh.github.io/MyPortfolio/](https://tech-sahilsh.github.io/MyPortfolio/)

---

## ✨ Features

- ✅ Fully responsive layout optimized for mobile, tablet, and desktop devices
- 🧑‍💻 About Me section detailing skills, education, and professional background
- 💼 Project showcase with an interactive and user-friendly interface
- 📬 ontact form powered by **EmailJS** for seamless message delivery
- 🖼️ Smooth scrolling and modern transition effects for enhanced user experience

---

## 🛠️ Tech Stack

| Category   | Technology            |
| ---------- | --------------------- |
| Frontend   | HTML, CSS, JavaScript |
| Email API  | EmailJS               |
| Deployment | GitHub Pages          |

---

## 📧 Contact Form (EmailJS)

The contact form is powered by **EmailJS**, enabling direct email delivery to my inbox **without the need for a backend server**.

### To set it up:

1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Create a service and template
3. Replace the following in your JavaScript:

```javascript
emailjs.sendForm(
  "YOUR_SERVICE_ID",
  "YOUR_TEMPLATE_ID",
  form,
  "YOUR_PUBLIC_KEY"
);
```
