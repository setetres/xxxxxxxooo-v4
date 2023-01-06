<template>
  <Bar
    id="back"
    title="XXXXXXXOOO-v3"
    color="hover:text-fuchsia-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v3.png" width="2560" height="1440" alt="Version Three Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      xxxxxxxooo-v3
    </Detail>
    <Detail name="Description">
      📀 A knife-grinder music endeavor, version 3.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2022
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-fuchsia-500"
    description="github.com/setetres/xxxxxxxooo-v3"
    external="true"
    id="github-xxxxxxxooo-v3"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/xxxxxxxooo-v3"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="v3.xxxxxxx.ooo"
    external="true"
    id="live-xxxxxxxooo-v3"
    label="Live"
    title="View Project"
    url="https://v3.xxxxxxx.ooo"
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
