<template>
  <main>
    <SectionWorldClass />
    <SectionSignUp />
    <SectionWorkOut />
    <SectionResults />
    <SectionPerformance />
    <SectionBruceLee />
  </main>
</template>

<script>
import SectionBruceLee from "../sections/SectionBruceLee.vue"
import SectionPerformance from "../sections/SectionPerformance.vue"
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
    SectionPerformance,
    SectionBruceLee,
  },
}
</script>

<style></style>
