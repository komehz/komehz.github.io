---
layout: single
title: Contact me
permalink: /contact/
---

<!-- modify this form HTML and place wherever you want your form -->

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xrgnjqyk" method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last Name" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="email@domain.com" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="Type Your Message Here" required=""></textarea>
    <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
  </fieldset>
  <input type="submit" value="Submit" class="btn btn--info">
</form>
