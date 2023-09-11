<script lang="ts">
  import Video from "$lib/media/homevideo.mp4";
</script>

<svelte:head>
  <title>Vincent Reed</title>
</svelte:head>

<main class="flex flex-col items-center">
  <div
    class="w-full h-full flex flex-col justify-center items-center text-center"
  >
    <div class="h-screen w-screen flex flex-col justify-center items-center">
      <div class="absolute w-full">
        <h1 class="vhs text-7xl mt-5">Vincent Reed</h1>
        <h3 class="vhs text-4xl">Head of Shredding Scythe Productions</h3>
      </div>

      <!-- svelte-ignore a11y-media-has-caption -->
      <video class="h-full w-full" autoplay loop>
        <source src={Video} type="video/mp4" />
      </video>
    </div>

    <div class="h-screen w-8/12 flex flex-col items-center">
      <h2 class="vhs text-3xl mt-28">About Me</h2>
      <p class="vhs text-lg">-</p>
      <h2 class="vhs text-3xl">Experience</h2>
      <p class="vhs text-lg" />
    </div>
  </div>
</main>
