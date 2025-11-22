---
title: "Contact Us"
permalink: /contact/
layout: single
author_profile: false
---

<h2>Get In Touch</h2>

<p>We'd love to hear from you. Fill out the form below or contact us directly using the information provided.</p>

<h3>Contact Information</h3>
<div class="contact-info">
  <p><strong>Email:</strong> <a href="mailto:brigesh@clearmapusa.com">brigesh@clearmapusa.com</a></p>
  <p><strong>Phone:</strong> <a href="tel:1-2015159970">(201) 515-9970</a></p>
</div>

<h3>Send us a message</h3>
<form id="contact-form">
  <div class="form-group">
    <label for="name">Name *</label>
    <input type="text" id="name" name="name" required>
  </div>

  <div class="form-group">
    <label for="email">Email *</label>
    <input type="email" id="email" name="email" required>
  </div>

  <div class="form-group">
    <label for="subject">Subject</label>
    <input type="text" id="subject" name="subject">
  </div>

  <div class="form-group">
    <label for="message">Message *</label>
    <textarea id="message" name="message" rows="6" required></textarea>
  </div>

  <button type="submit" class="btn btn-primary">Send Message</button>
</form>

<style>
.contact-info {
  background: #f8f9fa;
  padding: 20px;
  border-radius: 5px;
  margin: 20px 0;
}

.form-group {
  margin-bottom: 15px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
  font-weight: bold;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 16px;
}

.form-group textarea {
  resize: vertical;
}

.btn {
  background-color: #007bff;
  color: white;
  padding: 12px 24px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 16px;
}

.btn:hover {
  background-color: #0056b3;
}
</style>

<script>
// Basic form handling (you can customize this)
document.getElementById('contact-form').addEventListener('submit', function(e) {
  e.preventDefault();
  alert('Thank you for your message! We will get back to you soon.');
  this.reset();
});
</script>
