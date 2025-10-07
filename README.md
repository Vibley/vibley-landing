# 🌟 Vibley — Meet People Who Match Your Vibe

**Vibley** is a new kind of social experience — no swiping, no pressure, just genuine people who share your energy.  
This landing page introduces the concept and collects early sign-ups from people interested in trying it first.

---

## 🚀 Live Site
👉(https://vibley.github.io/vibley-landing/)



---

## 🧩 Project Overview
This project includes:
- A modern **responsive landing page** built in pure HTML/CSS/JS  
- A **waitlist form** connected to **Google Sheets** via an **Apps Script endpoint**
- Scroll reveal animations and a gradient hero section for visual impact  
- Lightweight and **mobile-friendly** layout

---

## 🧠 How It Works
1. Visitors fill in their name, email, age range, and ZIP code.
2. Submissions go directly to your Google Sheet using your published Google Apps Script endpoint.
3. They see a friendly success message on the page — no page reload needed.

---

## 🛠 How to Update

### Edit the Content
- Modify `index.html` directly in the GitHub web editor.
- Update text, colors, or copy under `<section>` blocks (Hero, How It Works, Waitlist).

### Update Your Google Apps Script
1. Open your script in [Google Apps Script](https://script.google.com/).  
2. Deploy as **Web App** with these settings:
   - Execute as: **Me**
   - Who has access: **Anyone**
3. Replace your endpoint URL inside the form’s `action` in `index.html` if it ever changes.

### Enable GitHub Pages
1. Go to your repo **Settings → Pages**.  
2. Under “Build and deployment,” select:
   - **Source:** Deploy from a branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`
3. Wait ~30 seconds — your site will go live.

---

## 📬 Optional Enhancements
- **Privacy line:** Add “Your email is safe with us — no spam ever.” under the submit button.  
- **Analytics:** Add [Plausible.io](https://plausible.io) for privacy-friendly tracking.  
- **Custom domain:** Link your own domain (e.g., `vibley.com`) under GitHub Pages → Custom Domain.

---

## 🧑‍💻 Author
**Hintsa H. (NathSpire)**  
Founder & Developer of Vibley  
🔗 [LinkedIn](https://www.linkedin.com/in/hintsa-h-050a96aa)  
📧 Reach out:Nathspire25@gmail.com 

---

## 🪪 License
This project is open-source for personal and educational use.  
Feel free to clone or fork, but please credit **Vibley** if you share or modify it.
