<template>
  <Bar
    id="back"
    title="I.J.W.G.H"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/ijwgh.png" width="1080" height="1080" alt="I.J.W.G.H Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>I.J.W.G.H</span>
        <span>1:37</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/Kx-yKxgDpaE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      I.J.W.G.H
    </Detail>
    <Detail name="Description">
      I.J.W.G.H (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      Single
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2021
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-ijwgh"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/i-j-w-g-h-single/1577022357"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-ijwgh"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/i-j-w-g-h"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-ijwgh"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/245251512"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-ijwgh"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/4tsB7ObHBi18ggyWmTQKM1"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-ijwgh"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/191341873"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-ijwgh"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=Kx-yKxgDpaE"
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

