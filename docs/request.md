# Request Media

Can't find a movie or show you want to watch? Use the form below to request it, and I'll add it to the server as soon as I can.

<form action="https://formspree.io/f/YOUR_ENDPOINT" method="POST" class="request-form">
  <label>
    Your Name:
    <input type="text" name="name" required placeholder="So I know who to tell when it's ready!">
  </label>
  
  <label>
    Content Type:
    <select name="type">
      <option value="movie">Movie</option>
      <option value="tv">TV Show</option>
      <option value="music">Music / Album</option>
      <option value="book">Book / AudioBook</option>
    </select>
  </label>

  <label>
    Title:
    <input type="text" name="title" required placeholder="Enter the title here...">
  </label>

  <label>
    Extra Details (Optional):
    <textarea name="message" placeholder="Year of release, specific season, or link to IMDB..."></textarea>
  </label>

  <button type="submit" class="btn-primary">Send Request</button>
</form>

!!! info "Note on Formspree"
    To make this form work, you'll need to create a free account at [Formspree.io](https://formspree.io/), create a new form, and replace `YOUR_ENDPOINT` in the code with your unique form ID.

<style>
.request-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    max-width: 500px;
    margin-top: 20px;
}

.request-form label {
    display: flex;
    flex-direction: column;
    font-weight: bold;
}

.request-form input, .request-form select, .request-form textarea {
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-family: inherit;
}

.request-form button {
    cursor: pointer;
    border: none;
    align-self: flex-start;
}
</style>
