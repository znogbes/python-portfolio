---
title: "Exploratory Data Analysis [Under development]"
date: 2025-12-13
---

<iframe
  src="{{ 'assets/intro-and-eda.html' | relative_url}}"
  style="width:100%; border:none"
  id="notebook-iframe"
></iframe>

<script>
function resizeIframe() {
  const iframe = document.getElementById('notebook-iframe');
  if (!iframe) return;
  iframe.onload = () => {
    const doc = iframe.contentDocument || iframe.contentWindow.document;
    iframe.style.height = doc.body.scrollHeight + 'px';
  };
}
window.addEventListener('DOMContentLoaded', resizeIframe);
</script>

[**Back to main page**](https://znogbes.github.io/python-portfolio/)