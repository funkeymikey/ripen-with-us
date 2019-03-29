---
layout: page #used everywhere except the homepage
title: Contact Us #the page title
permalink: /contact #the url that this page should show in the browser
toc: true #include a table of contents at the top of this page
---

### Address

500 Kenmore Ave
Buffalo, NY 14223

### Phone Number

(716) 836-1014

### Fax Number

(716) xxx-xxxx

### Get in touch
<form action="https://formspree.io/mike.kozelsky@gmail.com" method="POST">
  <div class="form-element">
    <label for="name">Your name <span class="required">*</span></label>
    <input type="text" placeholder="Your name" id="name" name="name" required>
  </div>

  <div class="form-element">
    <label for="email">Your email address</label>
    <input type="email" placeholder="Your email address" name="_replyto">
  </div>
   
  <div class="form-element">
    <label for="name">Your message <span class="required">*</span></label>
    <textarea type="text" placeholder="Your message" name="message" id="message" rows="5" required></textarea>
  </div>
  
  <div class="form-element">
    <input type="submit" value="Send Message">
  </div>
</form>
