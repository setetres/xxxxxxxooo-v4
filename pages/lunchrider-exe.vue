<template>
    <Bar title="v14" />
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/v14.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v14.png" width="2560" height="1440" alt="" />
    </CardImage>
    <div class="aspect-w-16 aspect-h-9">
                <iframe class="w-full" width="560" height="315" src="https://www.youtube.com/embed/o7GLLbly_6A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
    <CardText>
        <HeadingSans>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSans>
        <HeadingSerif class="text-5xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSerif>
    </CardText>
    <CardImage class="sm:col-span-2 p-12">
        <img src="~assets/images/v14.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail>
        <Detail name="Project">
            v14
        </Detail>
        <Detail name="Description">
            ✏️ v14.0 of my website.
        </Detail>
        <Detail name="Framework">
            Vue / NuxtJS
        </Detail>
        <Detail name="Year">
            <Tag>
                2022
            </Tag>
        </Detail>
    </CardDetail>
    <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v14"
    url="github.com/setetres/v14"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v14.setetres.st"
    url="v14.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>