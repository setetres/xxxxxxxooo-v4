<template>
  <Bar
    id="back"
    title="Against Filet"
    color="hover:text-fuchsia-500"
  />
  <CardImage>
    <img src="~assets/images/against-filet.png" width="1080" height="1080" alt="Against Filet Cover" />
  </CardImage>
  <CardDetail>
    <Detail name="#01">
      <div class="flex flex-1 justify-between">
        <span>Against Filet</span>
        <span>1:51</span>
      </div>
    </Detail>
  </CardDetail>
  <CardImage class="col-span-2">
    <div class="w-full aspect-w-16 aspect-h-9">
      <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/agflnPX22cQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </CardImage>
  <CardText>
    <HeadingSans>Lyrics</HeadingSans>
    <HeadingSerif class="text-5xl">
      Against Filet
    </HeadingSerif>
  </CardText>
  <CardText>
    <div class="space-y-8 text-white uppercase">
      <p>
        Você não é um patriota<br />
        é apenas idiota<br />
        parado<br />
        na frente de um quartel<br />
      </p>
      <p>
        O inferno vai ser pouco<br />
        pra você que levou<br />
        pai<br />
        mãe<br />
        tio<br />
        esposa<br />
        e até um bebê
      </p>
      <p>
        Fascista<br />
        de merda<br />
        pendurado<br />
        pelas pernas<br />
        morto
      </p>
    </div>
  </CardText>
  <CardDetail class="col-span-2">
    <Detail name="Title">
      Against Filet
    </Detail>
    <Detail name="Description">
      Against Filet (Single), by XXXXXXXOOO featuring Grupo Porco. Recorded in FL Studio 20 during the COVID-19 quarantine.
    </Detail>
    <Detail name="Type">
      Single
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2023
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="applemusic-against-filet"
    label="Listen on"
    title="Apple Music"
    url="https://music.apple.com/br/album/against-filet-feat-grupo-porco-single/1657179996"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="bandcamp-against-filet"
    label="Listen on"
    title="Bandcamp"
    url="https://xxxxxxxooo.bandcamp.com/track/against-filet-feat-grupo-porco"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="deezer-against-filet"
    label="Listen on"
    title="Deezer"
    url="https://deezer.com/br/album/382102277"
  />
  <CardMain
    class="pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="spotify-against-filet"
    label="Listen on"
    title="Spotify"
    url="https://open.spotify.com/track/1SN0NipEOXhXCj82GlLrpG?si=b0671b9c14d74cc0"
  />
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="tidal-against-filet"
    label="Listen on"
    title="Tidal"
    url="https://tidal.com/browse/album/263564575"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="Available now!"
    external="true"
    id="youtube-against-filet"
    label="Watch on"
    title="Youtube"
    url="https://youtube.com/watch?v=agflnPX22cQ"
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

