<template>
  <Bar title="Untitled" />
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
      <Tag>
        2021
      </Tag>
    </Detail>
  </CardDetail>
  <CardExternal
    label="Listen on"
    title="Apple Music"
    description="Available now!"
    url="music.apple.com/br/album/untitled-single/1561012200"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Bandcamp"
    description="Available now!"
    url="xxxxxxxooo.bandcamp.com/track/untitled"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Deezer"
    description="Available now!"
    url="deezer.com/br/album/219148382"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Spotify"
    description="Available now!"
    url="open.spotify.com/album/4rGuP76giFpYMfbzn730PW"
    class="pattern"
  />
  <CardExternal
    label="Listen on"
    title="Tidal"
    description="Available now!"
    url="tidal.com/browse/album/179082981"
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
  />
  <CardExternal
    label="Watch on"
    title="Youtube"
    description="Available now!"
    url="youtube.com/watch?v=NTZcILhcNa8"
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
  />
</template>
