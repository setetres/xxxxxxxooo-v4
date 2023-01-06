<template>
  <Bar
    id="back"
    title="28kbps"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/28kbps.png" width="1080" height="1080" alt="28kbps Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>28kbps</span>
        <span>2:50</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/2fzg-qhXrEc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <img src="~assets/images/28kbps-image.jpg" width="1920" height="1080" alt="28kbps Diskette Pack" class="w-full" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      28kbps
    </Detail>
    <Detail name="Description">
      28kbps (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
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
    id="applemusic-28kbps"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/28kbps-single/1565684474"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-28kbps"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/28kbps"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-28kbps"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/227209982"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-28kbps"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/5IFg2JaeMZRPz6jEG98DdM"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-28kbps"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/182667703"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-28kbps"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=2fzg-qhXrEc"
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
