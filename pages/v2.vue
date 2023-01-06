<template>
  <Bar
    id="back"
    title="XXXXXXXOOO-v2"
    color="hover:text-fuchsia-500"
  />
  <CardImage class="col-span-2">
    <img src="~assets/images/v2.png" width="2560" height="1440" alt="Version Two Screenshot" />
  </CardImage>
  <CardDetail class="col-span-2">
    <Detail name="Project">
      xxxxxxxooo-v2
    </Detail>
    <Detail name="Description">
      📀 A knife-grinder music endeavor, version 2.
    </Detail>
    <Detail name="Framework">
      Vue / NuxtJS
    </Detail>
    <Detail name="Year">
      <Tag color="bg-fuchsia-500">
        2021
      </Tag>
    </Detail>
  </CardDetail>
  <CardMain
    class="rounded-b-none sm:rounded-bl-lg sm:rounded-br-none"
    color="group-hover:text-fuchsia-500"
    description="github.com/setetres/xxxxxxxooo-v2"
    external="true"
    id="github-xxxxxxxooo-v2"
    label="Source Code"
    title="View on GitHub"
    url="https://github.com/setetres/xxxxxxxooo-v2"
  />
  <CardMain
    class="rounded-b-lg sm:rounded-bl-none sm:rounded-br-lg pattern"
    color="group-hover:text-fuchsia-500"
    description="v2.xxxxxxx.ooo"
    external="true"
    id="live-xxxxxxxooo-v2"
    label="Live"
    title="View Project"
    url="https://v2.xxxxxxx.ooo"
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
