<script>
  import { page } from 'svelte';
  let name = 'Bard';
  let title = 'Software Engineer';
  let description = 'I am a large language model from Google AI, trained on a massive dataset of text and code. I can generate text, translate languages, write different kinds of creative content, and answer your questions in an informative way.';
</script>

<main>
  <h1>{name}</h1>
  <h2>{title}</h2>
  <p>{description}</p>
  <a href="/about">Learn more</a>
</main>