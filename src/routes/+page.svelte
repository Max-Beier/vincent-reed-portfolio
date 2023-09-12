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
      <div class="absolute">
        <h1 class="vhs text-9xl uppercase m-5 mix-blend-difference">
          Vincent Reed
        </h1>
      </div>

      <!-- svelte-ignore a11y-media-has-caption -->
      <video class="h-full w-full" autoplay muted loop>
        <source src={Video} type="video/mp4" />
      </video>
    </div>

    <div class="h-screen w-8/12 flex flex-col items-center">
      <h2 class="vhs text-3xl mt-12">About Me</h2>
      <div class="vhs text-left">
        <p>
          My names Vincent Reed, I'm a Media Production student at London South
          Bank University, I'm studying to become a cameraman for TV, Film,
          Music Videos and Live events like concerts.
        </p>
        <br />

        <h3 class="text-xl">Academic Experience</h3>
        <ul>
          <li>
            Level 3 Media production Merit Merit - BCA (Berkshire College of
            Agriculture)
          </li>
          <li>Media Production - London South Bank University</li>
        </ul>
        <br />

        <h3 class="text-xl">Toolset</h3>
        <p>
          I have a great understanding of Adobe editing softwares like Premiere
          and Photoshop.
        </p>
      </div>

      <h2 class="vhs text-3xl mt-12">Experience</h2>
      <div class="vhs text-left">
        <h3 class="text-xl">July 2019</h3>
        <p>
          Joined award-winning director Jo Southwell as a runner on a
          production, involving early mornings, equipment handling, and working
          with new people. The charity video "Two Hours" was co-produced with
          The Media Trust, Screen South, and Aston, and it was nominated for
          various awards.
        </p>
        <br />

        <h3 class="text-xl">December 2019</h3>
        <p>
          Worked at a local radio station called "Marlow FM" in Berkshire for
          two weeks. Responsibilities included being on air with presenters and
          producing own segments for broadcast.
        </p>

        <br />
        <h3 class="text-xl">September-October 2021</h3>
        <p>
          Started studying Media Production at London South Bank University. As
          part of the course, helped set up and move various equipment for a
          news broadcast that aired every Friday on the JLDN YouTube channel.
          Also created a short documentary and used Adobe Premiere for editing.
        </p>
        <br />

        <h3 class="text-xl">2022</h3>
        <ul>
          <li>Digga D - Noughty by Nature</li>
          <li>Reaction party - Project SNS</li>
          <li>
            Shadowed a live BBC TV gallery during the Women's WSL Arsenal vs
            Tottenham Hotspur match on May 4th
          </li>
        </ul>
      </div>
    </div>
  </div>
</main>
