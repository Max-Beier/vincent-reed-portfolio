<script lang="ts">
  import DownArrow from "$lib/icons/Down Arrow Group.svg";
  import BackgroundMedia from "$lib/media/background-test.gif";
</script>

<svelte:head>
  <title>Vincent Reed</title>
</svelte:head>

<main class="flex justify-center items-center flex-col">
  <div class="h-screen w-screen flex justify-center items-center flex-col">
    <h1 class="vhs text-9xl">Vincent Reed</h1>
    <h2 class="vhs text-4xl">Head of Shredding Scythe Productions</h2>
    <img class="w-8/12" src={BackgroundMedia} alt="Background media" />
  </div>
  <div class="h-screen w-screen flex justify-center items-center flex-col">
    <h1 class="vhs text-4xl">About Me</h1>
    <h1 class="vhs text-4xl">Contact</h1>
  </div>
</main>
