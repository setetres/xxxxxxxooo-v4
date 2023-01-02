<template>
  <Bar title="56kbps" />
  <CardImage>
    <img src="~assets/images/56kbps.png" width="1080" height="1080" alt="56kbps Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>56kbps</span>
        <span>2:36</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/EcJp45_onTo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <img src="~assets/images/56kbps-image.jpg" width="1920" height="1080" alt="28kbps Diskette Pack" class="w-full" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      56kbps
    </Detail>
    <Detail name="Description">
      56kbps (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      Single
    </Detail>
    <Detail name="Year">
      <Tag>
        2021
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Listen on"
    title="Apple Music"
    description="Available now!"
    url="music.apple.com/br/album/56kbps-single/1565410700"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Bandcamp"
    description="Available now!"
    url="xxxxxxxooo.bandcamp.com/track/56kbps"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Deezer"
    description="Available now!"
    url="deezer.com/br/album/226743122"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Spotify"
    description="Available now!"
    url="open.spotify.com/album/6evGL1ZGOjGBJKWdQzN7yT"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Tidal"
    description="Available now!"
    url="tidal.com/browse/album/182404878"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
  />
  <CardExternal
    label="Watch on"
    title="Youtube"
    description="Available now!"
    url="youtube.com/watch?v=EcJp45_onTo"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
