<template>
  <main>
    <SectionWorldClass />
    <SectionSignUp />
    <SectionWorkOut />
    <SectionResults />
  </main>
</template>

<script>
import SectionResults from "../sections/SectionResults.vue"
import SectionSignUp from "../sections/SectionSignUp.vue"
import SectionWorkOut from "../sections/SectionWorkOut.vue"
import SectionWorldClass from "../sections/SectionWorldClass.vue"
export default {
  components: {
    SectionWorldClass,
    SectionSignUp,
    SectionWorkOut,
    SectionResults,
  },
}
</script>

<style></style>
