<script lang="ts">
  import DownArrow from "$lib/icons/Down Arrow Group.svg";
  import BackgroundMedia from "$lib/media/background-test.gif";
</script>

<svelte:head>
  <title>Vincent Reed</title>
</svelte:head>

<main class="flex flex-col items-center mt-5">
  <div
    class="w-full h-full flex flex-col justify-center items-center text-center"
  >
    <div class="h-screen w-8/12 flex flex-col items-center">
      <h1 class="vhs text-3xl">Vincent Reed</h1>
      <h3 class="vhs text-lg">Head of Shredding Scythe Productions</h3>

      <img
        draggable="false"
        class="vhs-box sm:w-96 md:w-8/12 mt-40 select-none pointer-events-none border-solid border-white border-4"
        src={BackgroundMedia}
        alt="Background media"
      />
    </div>

    <div class="h-screen w-8/12 flex flex-col items-center">
      <h2 class="vhs text-3xl mt-5">About Me</h2>
      <p class="vhs text-lg">-</p>
      <h2 class="vhs text-3xl">Experience</h2>
      <p class="vhs text-lg">-</p>
    </div>
  </div>
</main>
