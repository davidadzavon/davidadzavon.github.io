---
layout: page
title: Contact Me
permalink: /contact/
description: Get in touch and subscribe to research updates.
nav: true
nav_order: 8
---

<!-- # Get in touch -->

Have a question, a research idea, or a collaboration proposal?
I would be happy to hear from you.

## Send me a message

<form action="https://formspree.io/f/mbgdqwpn"
      method="POST">

  <p>
    <label for="contact-name">Name</label><br>
    <input id="contact-name" type="text" name="name"
           placeholder="Your name" required>
  </p>

  <p>
    <label for="contact-email">Email address</label><br>
    <input id="contact-email" type="email" name="email"
           placeholder="you@example.com" required>
  </p>

  <p>
    <label for="contact-subject">Subject</label><br>
    <input id="contact-subject" type="text" name="subject"
           placeholder="Subject" required>
  </p>

  <p>
    <label for="contact-message">Message</label><br>
    <textarea id="contact-message" name="message" rows="6"
              placeholder="Write your message here..."
              required></textarea>
  </p>

  <button type="submit">Send message</button>
</form>

---

## Stay updated

Subscribe to receive occasional updates about my research,
publications, blog posts, and academic activities.

<form action="https://123278c9.sibforms.com/serve/MUIFAOfGI9s_KhxT2WY-L03ce2ZLI1OzF023wpAMmOzjFkrZbSDTDTFMg-ZFYSiWSuWyFDkis9XShEBzLvqZfo-qJKkoToQh8GNoXEhau9VTrdZT5UxCozOZgohDYFRco-4aV5796nD5ttAEhOBK5g0mJXm7tqeDUnRjuuXBtyKc-DE1U8AkX4sfZ5BjwPAS0x8SpCYetuNx7yHDyw=="
      method="POST">

  <p>
    <label for="newsletter-email">Email address</label><br>
    <input id="newsletter-email" type="email" name="EMAIL"
           placeholder="you@example.com" required>
  </p>

  <input type="text" name="email_address_check"
         value="" style="display:none">

  <input type="hidden" name="locale" value="fr">

  <button type="submit">Subscribe to newsletter</button>
</form>

<p><small>You can unsubscribe from the newsletter at any time.</small></p>


<style>
/* Contact and newsletter forms */
#contact-name,
#contact-email,
#contact-subject,
#contact-message,
#newsletter-email {
  display: block;
  width: 100%;
  max-width: 700px;
  padding: 14px 16px;
  font-size: 17px;
  line-height: 1.5;
  box-sizing: border-box;
  border: 1px solid #cbd5e1;
  border-radius: 8px;
  margin-top: 6px;
  background: transparent;
}

/* Larger message area */
#contact-message {
  min-height: 220px;
  resize: vertical;
}

/* Space between fields */
#contact-name,
#contact-email,
#contact-subject,
#contact-message,
#newsletter-email {
  margin-bottom: 12px;
}

/* Labels */
#contact-name + label,
#contact-email + label {
  font-weight: 500;
}
</style>
