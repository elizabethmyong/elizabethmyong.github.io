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
<style>
form {
  max-width: 775px;
  margin: auto;
}
input, textarea {
  width: 100%;
  padding: 10px;
  margin-top: 6px;
  margin-bottom: 16px;
  border: 1px solid #ccc;
  border-radius: 4px;
}
button {
  background: #0366d6;
  color: white;
  padding: 10px 16px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
button:hover {
  background: #024ea2;
}
</style>

<form action="https://formspree.io/f/xbdokkrb" method="POST">
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
