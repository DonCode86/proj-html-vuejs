<template>
  <main>
    <SectionWorldClass />
    <SectionSignUp />
    <SectionWorkOut />
  </main>
</template>

<script>
import SectionSignUp from "../sections/SectionSignUp.vue"
import SectionWorkOut from "../sections/SectionWorkOut.vue"
import SectionWorldClass from "../sections/SectionWorldClass.vue"
export default {
  components: { SectionWorldClass, SectionSignUp, SectionWorkOut },
}
</script>

<style></style>
