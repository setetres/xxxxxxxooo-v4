<template>
    <Bar title="v1" />
    <CardImage class="col-span-2 p-12">
        <img src="~assets/images/v1.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardImage class="p-12">
        <img src="~assets/images/v1.png" width="2560" height="1440" alt="" />
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
        <img src="~assets/images/v1.png" width="2560" height="1440" alt="" />
    </CardImage>
    <CardDetail class="col-span-2">
        <Detail name="Project">
            v1
        </Detail>
        <Detail name="Description">
            👻 v1.0 of my website.
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
    description="github.com/setetres/v1"
    url="github.com/setetres/v1"
    class="rounded-bl-lg"
    />
    <CardExternal
    label="Live"
    title="View Project"
    description="v1.setetres.st"
    url="v1.setetres.st"
    class="rounded-br-lg pattern"
    />
</template>