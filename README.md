# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
<p><strong>Deployed by:</strong> DMI Cohort 2 | Nuthan S | Group 3 | Week 4 | 13-02-2026</p>
<span id="deployDate"></span>

<script>
  const today = new Date();
  const options = { day: '2-digit', month: 'short', year: 'numeric' };
  const formattedDate = today.toLocaleDateString('en-GB', options);
  document.getElementById('deployDate').textContent = formattedDate;
</script>

## UI & Accessibility Improvements

- Improved footer spacing and padding
- Increased contrast for better readability
- Adjusted font size for desktop and mobile
- Tested responsive layout using Chrome DevTools

Responsive validation performed on:
- Desktop view
- Mobile view (iPhone viewport simulation)

✅ This proof must be visible in your browser screenshot submission.