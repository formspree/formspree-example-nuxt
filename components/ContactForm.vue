<template>
  <form
    action="https://formspree.io/p/1615048538327089110/f/contact"
    method="POST"
  >
    <label>
      Your email:
      <input type="email" name="email" />
    </label>

    <label>
      Your message:
      <textarea name="message"></textarea>
    </label>

    <button type="submit">Send</button>
  </form>
</template>

<style>
/* Some nice boilerplate CSS to tidy up your form */
form {
  display: grid;
  grid-template-columns: max-content 1fr;
  grid-gap: 1rem;
  text-align: left;
  padding: 2rem 0;
}
form label {
  display: contents;
}
form input[type="email"],
form textarea,
form button {
  font-family: inherit;
  font-size: inherit;
  border: 1px solid currentColor;
  background: none;
  padding: 0.4rem 0.5rem;
  margin: 0;
}
form textarea {
  resize: vertical;
}
form button {
  justify-self: start;
}
</style>
