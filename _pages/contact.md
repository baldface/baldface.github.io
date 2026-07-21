---
layout: page
permalink: /contact/
title: Contact
nav: false
nav_order: 6
---
<style>
  form {
    display: grid;
    grid-template-columns: max-content 1fr;
    grid-gap: 1rem;
    text-align: left;
    padding: 2rem 0;
    margin: 0;
  }
  form label {
    display: contents;
  }
  form input[type="email"],
  form textarea,
  form button {
    grid-column: 2;
    font-family: inherit;
    font-size: inherit;
    border: 1px solid currentColor;
    backgound: none;
    padding: 0.4rem 0.5rem;
  }
  form textarea {
    resize: vertical;
  }
  form button {
    justify-self: start;
  }

  header.post-header {
    margin-bottom: 0 !important;
    margin-block-end: 0 !important;
  }
  
  /* Target the description if it exists */
  .post-description {
    margin-bottom: 0 !important;
    margin-block-end: 0 !important;
  }

  /* Target the content container */
  article.post-content {
    margin-top: 0 !important;
    margin-block-start: 0 !important;
  }
</style>

Feel free to reach out using the form below:
<form
  action="https://formspree.io/f/meeyodjz"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="email" />
  </label>

  <label>
    Your message:
    <textarea name="message" rows="8"></textarea>
  </label>

  <button type="submit">Send</button>
</form>
