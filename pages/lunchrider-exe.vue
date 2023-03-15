<template>
  <Bar
    id="back"
    title="LunchRider.exe"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/lunchrider-exe.png" width="1080" height="1080" alt="LunchRider.exe Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>Intro</span>
        <span>1:09</span>
      </div>
    </Detail>
    <Detail name="#02">
      <div class="flex flex-1 justify-between">
        <span>Sleep/Repeat, Part 1</span>
        <span>2:02</span>
      </div>
    </Detail>
    <Detail name="#03">
      <div class="flex flex-1 justify-between">
        <span>Sleep/Repeat, Part 2</span>
        <span>2:27</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/o7GLLbly_6A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      LunchRider.exe
    </Detail>
    <Detail name="Description">
      LunchRider.exe (EP), by XXXXXXXOOO featuring Grupo Porco. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      EP
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2022
      </Tag>
    </Detail>
    <Detail name="Extra">
      <NavigationLink
        class="underline"
        color="hover:text-fuchsia-500"
        external="true"
        id="instagram-lunchrider-exe"
        to="https://instagram.com/ar/430523635205836"
      >
        Instagram Filter
      </NavigationLink>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/b9Lx_5BC2iY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-lunchrider-exe"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/lunchrider-exe-single/1600384926"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-lunchrider-exe"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/album/lunchrider-exe"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-lunchrider-exe"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/280521002"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-lunchrider-exe"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/5llp2E1SNPaZZPT0Fospwi"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-lunchrider-exe"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/209251677"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-lunchrider-exe"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=o7GLLbly_6A"
  />
</template>
<script>
  export default {
    mounted() {
      this.$nextTick(() => {
      })
    },
    beforeRouteLeave(to, from, next) {
      setTimeout(function() {
        next()
      }, 173)
    }
  }
</script>
