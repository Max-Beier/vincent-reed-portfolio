<script lang="ts">
  // MEDIA
  import Video from "$lib/media/homevideo.mp4";
</script>

<svelte:head>
  <title>Vincent Reed</title>
</svelte:head>

<main
  class="w-full h-full flex flex-col justify-center items-center text-center snap-y"
>
  <div class="h-screen flex flex-col justify-center items-center snap-center">
    <!-- svelte-ignore a11y-media-has-caption -->
    <video
      class="pointer-events-none h-screen w-screen"
      autoplay
      playsinline
      muted
      loop
      preload="true"
    >
      <source src={Video} type="video/mp4" />
    </video>

    <div class="absolute">
      <h1
        class="vhs md:text-8xl text-6xl uppercase m-5 mix-blend-difference transform-gpu"
      >
        Vincent Reed
      </h1>
    </div>
  </div>

  <div class="h-full w-8/12 flex flex-col items-center snap-center">
    <h2 class="vhs text-3xl mt-12">About Me</h2>

    <div class="vhs text-left">
      <u class="text-xl">Me</u>
      <p>
        My name is Vincent, I graduated with a bachelor's degree in Media
        Production from London South Bank University. I want to pursue a career
        within media like television, movies as well as live events like
        festivals or concerts.
      </p>
      <br />

      <u class="text-xl">Academic Experience</u>
      <ul>
        <li>
          - Media Production Bachelor's Degree 2:1 - London South Bank
          University (2023)
        </li>
        <li>
          - Level 3 B-TEC MM (Double Merit) Media production - BCA (Berkshire -
          College of Agriculture)
        </li>
      </ul>
      <br />

      <u class="text-xl">Toolset</u>
      <p>
        After 5 years of educational experience, I possess a solid grasp of
        Adobe editing software, including Premier and Photoshop.
      </p>

      <br />
      <p>
        During my two-year tenure in the field, I have developed substantial
        expertise in strategically assembling sets for events of diverse scales.
        This includes everything from expansive large- event stages to intimate
        club night setups and dynamic live sets. I've had the privilege of
        contributing to events at prestigious venues such as the Commonwealth
        Games in Birmingham, The ExCeL London, Lapland, Annabel's in Mayfair,
        and many more.
      </p>
    </div>
  </div>

  <div class="h-screen w-8/12 flex flex-col items-center snap-center">
    <h2 class="vhs text-3xl mt-12">Experience</h2>
    <div class="vhs">
      <u class="text-xl">2023</u>
      <ul>
        <li>Big Brother 2023 - Production Runner</li>
      </ul>
      <br />

      <u class="text-xl">2022</u>
      <ul>
        <li>
          Shadowed a live BBC TV gallery during the Women's WSL Arsenal vs
          Tottenham Hotspur match on May 4th
        </li>
        <li>
          <a href="https://www.youtube.com/watch?v=OXGla-Lm2FM" target="_blank"
            ><u>CORD: Digga D - Noughty by Nature Reaction party Project SNS</u
            ></a
          >
        </li>
        <li>
          <a href="https://www.youtube.com/watch?v=ANGHBXy3OPY" target="_blank"
            ><u
              >CORD: Behind The Scenes at The Producer Roundtable + Beat
              Competition</u
            ></a
          >
        </li>
      </ul>
      <br />

      <br />
      <u class="text-xl">September-October 2021</u>
      <p>
        Started studying Media Production at London South Bank University. As
        part of the course, helped set up and move various equipment for a news
        broadcast that aired every Friday on the JLDN YouTube channel. Also
        created a short documentary and used Adobe Premiere for editing.
      </p>
      <br />

      <u class="text-xl">December 2019</u>
      <p>
        Worked at a local radio station called "Marlow FM" in Berkshire for two
        weeks. Responsibilities included being on air with presenters and
        producing own segments for broadcast.
      </p>
      <br />

      <u class="text-xl">July 2019</u>
      <p>
        Joined award-winning director Jo Southwell as a runner on a production,
        involving early mornings, equipment handling, and working with new
        people. The charity video "Two Hours" was co-produced with The Media
        Trust, Screen South, and Aston, and it was nominated for various awards.
      </p>
      <br />
    </div>

    <h2 class="vhs text-3xl mt-12">Contact</h2>
    <div
      class="w-full vhs flex flex-col gap-5 min-[0px]:text-lg min-[0px]:gap-1 md:text-2xl md:gap-2 sm:text-1xl"
    >
      <a
        href="https://www.youtube.com/@shreddingscytheproductions5987/videos"
        target="_blank"
      >
        <u>YouTube</u>
      </a>
      <a
        href="https://www.instagram.com/shreddingscythe.productions"
        target="_blank"
      >
        <u>Instagram</u>
      </a>
      <a
        href="https://www.linkedin.com/in/vincent-reed-613b26168/"
        target="_blank"
      >
        <u>LinkedIn</u>
      </a>
      <a href="mailto:shreddingscytheproductions@yahoo.com">
        <u>Mail</u>
      </a>
    </div>

    <div class="flex flex-col vhs bottom-0 mt-32">
      <p>
        Copyright (c) {new Date().getFullYear()} - Website by
        <a href="https://maxbeier.dev" target="_blank"><u>Max Beier</u></a>
      </p>
    </div>
  </div>
</main>

<style>
  a {
    text-align: left;
  }
  a:hover {
    color: yellow;
  }
</style>
