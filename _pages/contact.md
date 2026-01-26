---
layout: page
permalink: /contact/
title: contact
description:
nav: true
nav_order: 5
calendar: false
---

Hello! Please reach out to me with any inquiries, comments, or requests. I’ll do my best to get back to you promptly. 

---
layout: page
title: Contact
permalink: /contact/
---

# Contact Me

If you’d like to get in touch, please fill out the form below.

<!-- Contact Form -->
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <label for="name">Name</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="message">Message</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <!-- Optional: Customize email subject and format -->
  <input type="hidden" name="_subject" value="New Contact Message">
  <input type="hidden" name="_template" value="table">

  <button type="submit">Send Message</button>
</form>

---

**Notes for GitHub Preview:**

- The form fields will render correctly in GitHub Markdown preview.  
- Submissions **won’t work in the preview** — they only work when the site is deployed and the Formspree action URL is live.  

---

**Setup Steps:**

1. Sign up at [Formspree](https://formspree.io).  
2. Create a new form and copy your **Form ID**. Replace `YOUR_FORM_ID` in the code above.  
3. Confirm the email address in Formspree after the first submission.  
4. Deploy the site to GitHub Pages — the form will now work.  
