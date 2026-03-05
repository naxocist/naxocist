<script lang="ts">
  const notes = [
    {
      topic: 'What is this?',
      url: 'Is something supposed to be here?'
    }
  ];
</script>

<section id="notes" class="space-y-3">
  <h2 class="text-2xl font-semibold">Recent Notes</h2>

  {#each notes as note}
    <article class="space-y-0.5 pb-2">
      <small class="text-[dimgray]">2026-02-17</small>
      <h3 class="text-xl">{note.topic}</h3>
      <p>{note.url}</p>
    </article>
  {/each}
</section>
