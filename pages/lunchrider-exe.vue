<template>
  <Bar title="LunchRider.exe" />
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
      <Tag>
        2022
      </Tag>
    </Detail>
    <Detail name="Extra">
      <NavigationLink to="https://instagram.com/ar/430523635205836" class="underline" target="_blank">
        Instagram Filter
      </NavigationLink>
    </Detail>
  </CardDetail>
  <CardExternal
  label="Listen on"
  title="Apple Music"
  description="Available now!"
  url="music.apple.com/br/album/lunchrider-exe-single/1600384926"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Bandcamp"
  description="Available now!"
  url="xxxxxxxooo.bandcamp.com/album/lunchrider-exe"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Deezer"
  description="Available now!"
  url="deezer.com/br/album/280521002"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Spotify"
  description="Available now!"
  url="open.spotify.com/album/5llp2E1SNPaZZPT0Fospwi"
  class="pattern"
  />
  <CardExternal
  label="Listen on"
  title="Tidal"
  description="Available now!"
  url="tidal.com/browse/album/209251677"
  class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
  />
  <CardExternal
  label="Watch on"
  title="Youtube"
  description="Available now!"
  url="youtube.com/watch?v=o7GLLbly_6A"
  class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
