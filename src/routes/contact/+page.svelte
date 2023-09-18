<svelte:head>
  <title>Contact Us</title>
  <meta name="description" content="Contact Us" />
</svelte:head>

<div class="text-column">
  <h1>Get in Touch</h1>

  <h3>
    We'd love to hear from you—whether you're a fan, a venue owner, or a fellow
    musician. Drop us a line!
  </h3>

  <div class="contact-form">
    <form
      name="contact"
      method="POST"
      data-netlify="true"
      data-netlify-honeypot="bot-field"
    >
      <input type="hidden" name="form-name" value="contact" />

      <label for="name">Name</label>
      <input type="text" name="name" id="name" required />

      <label for="email">Email</label>
      <input type="email" name="email" id="email" required />

      <label for="message">Message</label>
      <textarea name="message" id="message" rows="5" required />

      <button type="submit">Send</button>
    </form>
  </div>
</div>

<style>
  .contact-form {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  form {
    display: flex;
    flex-direction: column;
    gap: 1em;
    width: 100%;
    max-width: 500px;
  }

  label {
    font-weight: bold;
  }

  input,
  textarea {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 0.5em;
  }

  button {
    border: 1px solid #ccc;
    border-radius: 4px;
    padding: 0.5em;
    background-color: #fff;
    cursor: pointer;
  }

  button:hover {
    background-color: #ccc;
  }
</style>
