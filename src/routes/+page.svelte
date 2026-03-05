<script lang="ts">
  import Header from '$lib/components/Header.svelte';
  import Note from '$lib/components/Note.svelte';
  import Project from '$lib/components/Project.svelte';
</script>

<svelte:head>
  <title>naxocist</title>
  <link rel="icon" type="image/x-icon" href="/assets/favicon.ico" />
</svelte:head>

<main
  class="mx-auto w-full max-w-200 space-y-4 bg-white p-5 font-sans leading-relaxed shadow-[0_0_5px_0.25px_grey] sm:p-8"
>
  <Header />

  <a
    class="mb-0 inline-block leading-none"
    href="https://k-on.fandom.com/wiki/Yui_Hirasawa"
    target="_blank"
    rel="noopener noreferrer"
  >
    <img class="block h-auto w-50 max-w-full" src="/assets/yui-guitar.gif" alt="Yui Hirasawa" />
  </a>
  <p>Yui Hirasawa | 平沢唯</p>

  <hr class="my-4 border-0 border-t border-[#eee]" />

  <Project />

  <hr class="my-4 border-0 border-t border-[#eee]" />

  <Note />
</main>
