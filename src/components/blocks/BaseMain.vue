<template>
  <main>
    <SectionWorldClass />
    <SectionSignUp />
    <SectionWorkOut />
    <SectionResults />
    <SectionPerformance />
    <SectionBruceLee />
    <SectionTrainers />
    <SectionNews />
    <SectionJoin />
  </main>
</template>

<script>
import SectionBruceLee from "../sections/SectionBruceLee.vue"
import SectionJoin from "../sections/SectionJoin.vue"
import SectionNews from "../sections/SectionNews.vue"
import SectionPerformance from "../sections/SectionPerformance.vue"
import SectionResults from "../sections/SectionResults.vue"
import SectionSignUp from "../sections/SectionSignUp.vue"
import SectionTrainers from "../sections/SectionTrainers.vue"
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
    SectionTrainers,
    SectionNews,
    SectionJoin,
  },
}
</script>

<style></style>
