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

<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <label for="first-name">First Name (required)</label><br>
  <input type="text" id="first-name" name="first-name" required><br><br>

  <label for="last-name">Last Name (required)</label><br>
  <input type="text" id="last-name" name="last-name" required><br><br>

  <label for="email">Email (required)</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="message">Message (required)</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <!-- Optional: Customize email subject and format -->
  <input type="hidden" name="_subject" value="New Contact Message">
  <input type="hidden" name="_template" value="table">

  <button type="submit">Submit</button>
</form>
