<template>
    <Bar title="v2" />
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/v2.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v2.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardText>
        <HeadingSans>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSans>
        <HeadingSerif class="text-5xl">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </HeadingSerif>
    </CardText>
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/v2.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail class="col-span-2">
        <Detail name="Project">
            v2
        </Detail>
        <Detail name="Description">
            👻 v2.0 of my website.
        </Detail>
        <Detail name="Framework">
            Vue / NuxtJS
        </Detail>
        <Detail name="Year">
            <Tag>
                2008
            </Tag>
        </Detail>
    </CardDetail>
    <CardExternal
    label="Source Code"
    title="View on GitHub"
    description="github.com/setetres/v2"
    url="github.com/setetres/v2"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v2.setetres.st"
    url="v2.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>