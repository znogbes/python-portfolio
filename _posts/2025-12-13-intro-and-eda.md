---
title: "Exploratory Data Analysis [Under development]"
date: 2025-12-13
---
<div class="iframe-fullscreen" markdown="0">
  <iframe
    src="{{ 'assets/notebooks/intro-and-eda.html' | relative_url}}"
    id="notebook-iframe"
    style="width:100%; border:none"
  ></iframe>
</div>

<script>
function resizeIframe() {
  const iframe = document.getElementById('notebook-iframe');
  if (!iframe) return;

  iframe.onload = () => {
    try {
      const doc = iframe.contentDocument || iframe.contentWindow.document;
      iframe.style.height = doc.body.scrollHeight + 'px';  /* Adjust iframe height */
      iframe.style.overflow = 'hidden';  /* Prevent scrollbars */
    } catch (e) {
      iframe.style.height = '1000px';  /* Fallback height */
    }
  };
}
// Trigger after page content loads
window.addEventListener('DOMContentLoaded', resizeIframe);
</script>

[**Back to main page**](https://znogbes.github.io/python-portfolio/)