<template>
  <Bar
    id="back"
    title="Ùntitled"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/untitled.png" width="1080" height="1080" alt="Untitled Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>Untitled</span>
        <span>3:06</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/NTZcILhcNa8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      Untitled
    </Detail>
    <Detail name="Description">
      Untitled (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
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
    id="applemusic-untitled"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/untitled-single/1561012200"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-untitled"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/untitled"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-untitled"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/219148382"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-untitled"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/4rGuP76giFpYMfbzn730PW"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-untitled"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/179082981"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-untitled"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=NTZcILhcNa8"
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
