<template>
    <Bar title="VINGT-VINGT" />
    <CardImage class="p-12">
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
    <CardImage class="col-span-2 p-12">
        <div class="w-full aspect-w-16 aspect-h-9">
            <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/zfEtdrSOpNs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </CardImage>
    <CardImage class="col-span-2 p-12">
        <div class="w-full aspect-w-16 aspect-h-9">
            <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/82A_sMmKGGI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </CardImage>
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/vingt-vingt-image.jpg" width="1920" height="1080" alt="VINGT-VINGT Vinyl Pack" class="w-full" />
    </CardImage>
    <CardText>
        <HeadingSerif class="text-5xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSerif>
    </CardText>
    <CardText>
        <div class="space-y-8 text-white uppercase">
            <p>
                Tu viens de la terre, sorti dans l’espace<br />
                Parcourir galaxie, avec ton grand vaisseau<br />
                Voir les colonies, en jouant du banjo<br />
                Un voyage en musique, des notes en do
            </p>
            <p>
                Un astronaute, dans les colonies spatiales qui joue du
                banjo
            </p>
            <p>
                Tu navigues dans l’espace, avec ton grand vaisseau<br />
                Tu vas parfois loin, tu ne l’oublie jamais<br />
                Tu le prend ou tu vas, c’est ton banjo fétiche<br />
                Meme dans les colonies, il t’accompagne partout
            </p>
            <p>
                Un astronaute, dans les colonies spatiales qui joue du
                banjo
            </p>
            <p>
                Banjo, Banjo, Banjo, Banjo<br />
                Un, deux, trois, quatre, cinq, six, sept, huit
            </p>
            <p>
                You play the Banjo, on the right tempo<br />
                You are a hero, like a great maestro<br />
                You play in space colonies, this is your priority<br />
                Banjo maestro, banjo, banjo
            </p>
            <p>
                Colonies spatiales, tu as mis ta combinaison<br />
                Aventure, un astronaute<br />
                Des notes en sanglot<br />
                Colonies spatiales
            </p>
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
            <Tag>
                2020
            </Tag>
        </Detail>
        <Detail name="Extra">
            <NavigationLink to="https://instagram.com/ar/965617350568430" target="_blank">
                Instagram Filter
            </NavigationLink>
        </Detail>
    </CardDetail>
    <CardExternal
    label="Listen on"
    title="Apple Music"
    description="Available now!"
    url="music.apple.com/br/album/vingt-vingt/1525239686"
    class="rounded-bl-lg pattern"
    />
    <CardExternal
    label="Listen on"
    title="Bandcamp"
    description="Available now!"
    url="xxxxxxxooo.bandcamp.com/album/vingt-vingt"
    class="rounded-br-lg pattern"
    />
    <CardExternal
    label="Listen on"
    title="Deezer"
    description="Available now!"
    url="deezer.com/br/album/163383462"
    class="rounded-bl-lg pattern"
    />
    <CardExternal
    label="Listen on"
    title="Spotify"
    description="Available now!"
    url="open.spotify.com/album/6NgLlnVG9HTJA8U0TcRj4Z"
    class="rounded-br-lg pattern"
    />
    <CardExternal
    label="Listen on"
    title="Tidal"
    description="Available now!"
    url="tidal.com/browse/album/150081917"
    class="rounded-bl-lg pattern"
    />
    <CardExternal
    label="Watch on"
    title="Youtube"
    description="Available now!"
    url="youtube.com/watch?v=zfEtdrSOpNs"
    class="rounded-br-lg pattern"
    />
</template>