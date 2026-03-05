<script lang="ts">
  const projects = [
    {
      name: 'Blurp - Anime discord bot',
      url: 'https://github.com/naxocist/Blurp'
    }
  ];
</script>

<section id="projects" class="space-y-1">
  <h2 class="m-0 text-2xl font-semibold">Projects</h2>

  {#each projects as project}
    <a
      class="inline-block hover:underline"
      href={project.url}
      target="_blank"
      rel="noopener noreferrer">{project.name}</a
    >
  {/each}
</section>
