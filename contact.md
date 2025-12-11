---
title: Contact
layout: page
---
Email:

<a href="#" id="email-link">Click to show email</a>
<script>
  document.getElementById('email-link').onclick = function(e) {
    e.preventDefault();
    this.href = 'mailto:' + 'robertschank' + '@' + 'gmail.com';
    this.textContent = 'robertschank' + '@' + 'gmail.com';
    this.onclick = null;
  };
</script>

<!-- Fanfund page: -->
<!-- * [https://ko-fi.com/bobschank](https://ko-fi.com/bobschank) -->
