# 👋 Welcome to My Portfolio

Hey there! I'm **Simmyt3r**, a passionate developer and creative problem-solver dedicated to empowering young Nigerians through tech education. This repository contains my professional portfolio website showcasing my projects, skills, and experience.

## 🌐 Live Portfolio

Visit my live portfolio: **[simmyt3r.github.io/Portfolio](https://simmyt3r.github.io/Portfolio/)**

---

## 🎓 Featured Project: The Builder

**The Builder** is a mobile-first practical learning platform for Nigerian teenagers and young adults. It has grown beyond a flat tutorial page into a small installable learning app that tracks progress locally and guides learners from short lessons into real projects.

### Current learning model

- **6 learning categories**: Tech Skills, Practical Skills, Business, Money, Mindset, and Relationships
- **23-lab Practical Skills Pathway** grouped into Digital Foundations, AI & Productivity, Online Business Skills, and Build for the Web
- **Capstone project** that combines the pathway into one real digital-presence project
- **10-question final assessment** with an 80% pass mark
- **Printable completion certificate** after the pathway, capstone, and assessment are completed
- **Free + premium lessons** with lesson search, category filters, bookmarks, completion tracking, and deep-link sharing
- **Offline/PWA support** using a web manifest and service worker
- **Device-local progress** with JSON backup and restore so learners can move progress between browsers without an account

### Learning experience

The Builder is intentionally simple: open the app, continue the next recommended pathway lesson, complete the practical task, mark it done, and move forward. Learners can still browse the full lesson library when they want a specific topic.

The Practical Skills Pathway currently covers everyday digital work such as cloud files, account security, document scanning, troubleshooting, fact-checking, ChatGPT-assisted work, Google Forms and Sheets, business email, invoices and receipts, social/business profiles, QR codes, customer service, phone product photography, graphic design, simple websites, publishing, portfolios, domains and hosting.

### Product principles

- Mobile first and usable on low-cost Android devices
- Beginner-friendly explanations with practical outputs
- Local progress rather than mandatory accounts
- Offline resilience where possible
- Clear separation between free learning and premium material
- Lessons should produce something the learner can show, use, or earn with

---

## 📁 Repository Structure

```
Portfolio/
├── index.html              # Main portfolio homepage
├── resume.html             # Interactive resume
├── builder.html            # The Builder learning app ⭐
├── builder-ads.html        # Builder variant with ads
├── builder.webmanifest     # Installable app metadata
├── builder-sw.js           # Offline cache/service worker
├── lessons/                # Shareable standalone lesson pages
├── certificates/           # Certificate PDF files
│   └── thumbnails/         # Optional certificate preview images
├── casual.jpg              # Profile photo (casual)
├── formal.jpeg             # Profile photo (formal)
├── sitemap.xml             # SEO sitemap
├── robots.txt              # SEO configuration
└── README.md               # This file
```

---


## 🎓 Certificates

Certificate PDFs are displayed on the main portfolio homepage from the dedicated `certificates/` folder.

### Adding a certificate

1. Save the PDF inside `certificates/`.
2. Use lowercase, URL-safe filenames with this pattern:
   `provider-certificate-topic-year.pdf`
3. Open `index.html` and add a new object to the `CERTIFICATES` JavaScript array.

Required fields:
- `title` - certificate name shown on the card
- `issuer` - issuing organization
- `year` - year earned
- `category` - filter group such as `Web Development`, `Programming`, `AI`, `Cloud`, `Business`, or `Cybersecurity`
- `file` - PDF path, for example `certificates/freecodecamp-responsive-web-design-2025.pdf`

Optional fields:
- `appliedIn` - short note connecting the credential to shipped work
- `thumbnail` - future thumbnail path, preferably under `certificates/thumbnails/`
- `credentialUrl` - external verification link, if the issuer provides one

Example:

```js
{
  title: 'Responsive Web Design',
  issuer: 'freeCodeCamp',
  year: '2025',
  category: 'Web Development',
  file: 'certificates/freecodecamp-responsive-web-design-2025.pdf',
  appliedIn: 'Portfolio, Builder platform, and client landing pages'
}
```

---

## 🚀 Technical Stack

### **Frontend**
- HTML5 semantic markup with proper meta tags
- CSS3 with CSS custom properties (variables)
- Vanilla JavaScript (no external dependencies)
- Responsive design with mobile-first approach
- Smooth scroll behavior enabled

### **Key Technical Features**
- ✨ Zero external JavaScript libraries
- 📱 Fully responsive with breakpoints at 700px and 600px
- 🎨 Interactive collapse/expand with CSS transitions
- 🔒 Client-side password protection for premium content
- 🎯 Tab-based filtering with display none/block
- ⚡ Optimized CSS with custom properties
- ♿ Semantic HTML structure for accessibility

### **Performance Optimizations**
- Preconnected Google Fonts for faster loading
- CSS custom scrollbar styling
- Minimal DOM manipulation
- CSS-based animations instead of JavaScript
- Lightweight inline styles for critical content

---

## 🛠️ Technologies Used

- **HTML5** - Semantic structure, meta tags, viewport optimization
- **CSS3** - Flexbox, Grid, Custom Properties, Animations, Transitions
- **Vanilla JavaScript** - Event listeners, DOM manipulation, password verification
- **Google Fonts** - Syne, Manrope, JetBrains Mono
- **Responsive Web Design** - Mobile-first, breakpoint-based layouts

---

## 🎯 Project Goals

1. **Democratize Tech Education** in Nigeria with free, quality content
2. **Empower Teenagers** to learn skills that lead to income
3. **Bridge Knowledge Gaps** by explaining complex concepts simply
4. **Build Sustainable Revenue** through premium membership model
5. **Create Community** around learning and growth
6. **Provide Practical Skills** applicable to real-world problems

---

## 📞 Connect & Enroll

- **WhatsApp**: [Join The Builder Community](https://wa.me/2349056232366?text=I%20want%20to%20join%20The%20Builder%20community)
- **Phone**: +234 905 623 2366
- **GitHub**: [@Simmyt3r](https://github.com/Simmyt3r)
- **Portfolio**: [simmyt3r.github.io/Portfolio](https://simmyt3r.github.io/Portfolio/)

---

## 💼 About Me

I'm **Simeon Tertese**, founder of **Silabs & Co Technologies**. I'm passionate about:
- 💻 Building real products that solve real problems
- 📚 Teaching practical tech skills in simple language
- 🚀 Helping young Nigerians earn through tech and entrepreneurship
- 🌍 Creating opportunities in the digital economy
- 🎓 Mentoring the next generation of builders

---

## 📄 License

This portfolio and The Builder platform are private projects. All content and code are proprietary.

---

## 🔄 Last Updated

**October 6, 2026**

**Repository**: [github.com/Simmyt3r/Portfolio](https://github.com/Simmyt3r/Portfolio)

---

## 📈 My Mission

> *"To inspire and equip young minds with the knowledge, skills, and mindset needed to succeed in a rapidly evolving digital world."*

**Learn it. Build it. Earn from it.** 🚀

