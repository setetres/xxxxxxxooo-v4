<template>
  <Bar
    id="back"
    title="FEIN"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/fein.png" width="1080" height="1080" alt="FEIN Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>QUATRE-VINGT-DIX-NEUF</span>
        <span>2:38</span>
      </div>
    </Detail>
    <Detail name="#02">
      <div class="flex flex-1 justify-between">
        <span>COWEED-19</span>
        <span>2:18</span>
      </div>
    </Detail>
    <Detail name="#03">
      <div class="flex flex-1 justify-between">
        <span>XD</span>
        <span>2:33</span>
      </div>
    </Detail>
    <Detail name="#04">
      <div class="flex flex-1 justify-between">
        <span>BANJO</span>
        <span>2:45</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/JtOb7rY6024" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/F4jxM04IStM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/1qnuYMpv5T0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/ECpvHjLvvDE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      FEIN
    </Detail>
    <Detail name="Description">
      FEIN (EP), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      EP
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2020
      </Tag>
    </Detail>
    <Detail name="Extra">
      <NavigationLink
        class="underline"
        color="hover:text-fuchsia-500"
        external="true"
        id="instagram-fein"
        to="https://instagram.com/ar/929622894133566"
      >
        Instagram Filter
      </NavigationLink>
    </Detail>
  </CardDetail>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-fein"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/fein-ep/1513768644"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-fein"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/album/fein"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-fein"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/148877002"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-fein"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/album/0nN10kpHYXrOmIKOr36Ggx"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-fein"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/141839510"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-fein"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=JtOb7rY6024&list=PLWjcKkvgds-9TuK2urpOPMtvwxTU23zmO"
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
