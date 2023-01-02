<template>
  <Bar title="VAZIØ" />
  <CardImage>
    <img src="~assets/images/vazio.png" width="1080" height="1080" alt="VAZIØ Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>VAZIØ</span>
        <span>7:03</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/Bv3jI_nFQEw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      VAZIØ
    </Detail>
    <Detail name="Description">
      VAZIØ (Single), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      Single
    </Detail>
    <Detail name="Year">
      <Tag>
        2020
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
  label="Listen on"
  title="Apple Music"
  description="Available now!"
  url="music.apple.com/br/album/vazi%C3%B8-single/1534502526"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Bandcamp"
  description="Available now!"
  url="xxxxxxxooo.bandcamp.com/track/vazi"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Deezer"
  description="Available now!"
  url="deezer.com/br/album/177544912"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Spotify"
  description="Available now!"
  url="open.spotify.com/album/2ooPMxZyHDTq8ltMm6UdqB"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Tidal"
  description="Available now!"
  url="tidal.com/browse/album/157442782"
  class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
  />
  <CardExternal
  label="Watch on"
  title="Youtube"
  description="Available now!"
  url="youtube.com/watch?v=Bv3jI_nFQEw"
  class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
