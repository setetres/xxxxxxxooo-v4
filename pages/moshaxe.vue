<template>
  <Bar
    id="back"
    title="MOSHAXÉ"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/moshaxe.png" width="1080" height="1080" alt="MOSHAXÉ Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>MOSHAXÉ</span>
        <span>2:19</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/Cv9DGU4jOQ8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      MOSHAXÉ
    </Detail>
    <Detail name="Description">
      MOSHAXÉ (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      Single
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2020
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-moshaxe"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/moshax%C3%A9-single/1517796928"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-moshaxe"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/moshax"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-moshaxe"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/153832442"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-moshaxe"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/252g8ZxQ4NWe0SdrW40qoh"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-moshaxe"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/144626772"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-moshaxe"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=Cv9DGU4jOQ8"
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
