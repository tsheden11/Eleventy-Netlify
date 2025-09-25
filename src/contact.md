---
layout: base.html
title: Contact
---

# Contact Us

Get in touch with us using the information below or fill out our contact form.

## Contact Information

- **Email**: your-email@example.com
- **Phone**: (555) 123-4567
- **Address**: Your Address Here

## Contact Form

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" required /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" required /></label>
  </p>
  <p>
    <label>Subject: <input type="text" name="subject" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message" rows="5" required></textarea></label>
  </p>
  <p>
    <button type="submit">Send Message</button>
  </p>
</form>

---

*This form will be automatically handled by Netlify when deployed. All form submissions will be available in your Netlify dashboard.*
