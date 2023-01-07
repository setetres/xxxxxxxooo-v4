<template>
  <Bar
    id="back"
    title="VINGT-VINGT"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/vingt-vingt.png" width="1080" height="1080" alt="VINGT-VINGT Cover" />
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
    <Detail name="#05">
      <div class="flex flex-1 justify-between">
        <span>TRICERACOUGH</span>
        <span>3:33</span>
      </div>
    </Detail>
    <Detail name="#06">
      <div class="flex flex-1 justify-between">
        <span>MOSHAXÉ</span>
        <span>3:33</span>
      </div>
    </Detail>
    <Detail name="#07">
      <div class="flex flex-1 justify-between">
        <span>DISPLAYNONE</span>
        <span>3:07</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/zfEtdrSOpNs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/82A_sMmKGGI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardImage class="col-span-2">
    <img src="~assets/images/vingt-vingt-image.jpg" width="1920" height="1080" alt="VINGT-VINGT Vinyl Pack" class="w-full" />
  </CardImage>
  <CardText>
    <HeadingSans>Only 10 Available!</HeadingSans><br />
    <HeadingSerif class="text-5xl">
      VINGT-VINGT Vynil Limited Edition
    </HeadingSerif>
  </CardText>
  <CardText>
    <div class="space-y-8 text-white uppercase">
      <div>
        <HeadingSerif class="text-2xl">
          Vinyl 12''
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Translucent black vinyl, lathe cutted with soft cover
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Poster A1
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Black and white print with protective case
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Postcards A6
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Black and white with UV print
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Patches
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Black and white embroidery
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Tote Bag
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Black and white embroidery.
          100% cotton
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Sticker Sheet A4
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Collection of colored stickers
        </p>
      </div>
      <div>
        <HeadingSerif class="text-2xl">
          Diskettes
        </HeadingSerif>
        <p class="text-zinc-400 uppercase">
          Digital version to share with friends
        </p>
      </div>
    </div>
  </CardText>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      VINGT-VINGT
    </Detail>
    <Detail name="Description">
      VINGT-VINGT (LP), by XXXXXXXOOO. Recorded in FL Studio 20 during the COVID-19 quarantine. Prints at Aster Graf, vinyl at Vinyl-Lab and embroideries at Borda Laser.
    </Detail>
    <Detail name="Type">
      LP
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
        id="instagram-vingt-vingt"
        to="https://instagram.com/ar/965617350568430"
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
    id="applemusic-vingt-vingt"
    label="Listen on"
    title="Apple Music"
    url="music.apple.com/br/album/vingt-vingt/1525239686"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-vingt-vingt"
    label="Listen on"
    title="Bandcamp"
    url="xxxxxxxooo.bandcamp.com/album/vingt-vingt"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-vingt-vingt"
    label="Listen on"
    title="Deezer"
    url="deezer.com/br/album/163383462"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-vingt-vingt"
    label="Listen on"
    title="Spotify"
    url="open.spotify.com/album/6NgLlnVG9HTJA8U0TcRj4Z"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-vingt-vingt"
    label="Listen on"
    title="Tidal"
    url="tidal.com/browse/album/150081917"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-vingt-vingt"
    label="Watch on"
    title="Youtube"
    url="youtube.com/watch?v=zfEtdrSOpNs"
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
