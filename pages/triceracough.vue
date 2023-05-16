<template>
  <Bar
    id="back"
    title="TRICERACOUGH"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/triceracough.png" width="1080" height="1080" alt="TRICERACOUGH Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>TRICERACOUGH</span>
        <span>3:33</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/CKqnuZBjsZY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/YUyrXiCl5kU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      TRICERACOUGH
    </Detail>
    <Detail name="Description">
      TRICERACOUGH (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
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
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/_mR0GXUrw_Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-triceracough"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/triceracough-single/1514705104"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-triceracough"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/triceracough"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-triceracough"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/149920012"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-triceracough"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/1o0IoOxGycM6IfD7EcYxZ9"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-triceracough"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/142432861"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-triceracough"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=CKqnuZBjsZY"
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
