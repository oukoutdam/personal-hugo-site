+++
date = '2026-05-03T03:06:10+09:00'
draft = false
title = 'Contact'
+++

# Contact

Feel free to reach out, I'll get back to you as soon as I can.

<style>
.dark .form-control {
  background-color: var(--bg-variant);
  color: var(--font-color);
  border-color: #444;
}
.dark .form-control:focus {
  background-color: var(--bg-variant);
  color: var(--font-color);
  border-color: #888;
  box-shadow: none;
}
.dark .form-control::placeholder {
  color: #666;
}
</style>

<form action="https://api.web3forms.com/submit" method="POST" class="mt-4" style="max-width: 600px;">
  <input type="hidden" name="access_key" value="ff634914-42f2-494c-a152-3386f135d9b0">
  <input type="hidden" name="redirect" value="false">

  <div class="mb-3">
    <label for="name" class="form-label">Name</label>
    <input type="text" id="name" name="name" class="form-control" placeholder="Your name" required>
  </div>

  <div class="mb-3">
    <label for="email" class="form-label">Email</label>
    <input type="email" id="email" name="email" class="form-control" placeholder="your@email.com" required>
  </div>

  <div class="mb-3">
    <label for="message" class="form-label">Message</label>
    <textarea id="message" name="message" class="form-control" rows="5" placeholder="Your message..." required></textarea>
  </div>

  <div class="h-captcha" data-captcha="true"></div>

  <button type="submit" class="btn btn-dark">Send Message</button>
</form>

<script src="https://web3forms.com/client/script.js" async defer></script>
