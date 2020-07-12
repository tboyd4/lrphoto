<template>
  <div>
    <div class="py-12"></div>
    <Catcher></Catcher>
    <div class="py-12"></div>
    <div class="py-12"></div>
    <recent-work></recent-work>
    <div class="py-12"></div>
  </div>
</template>

<script>
import Catcher from '../components/IndexComps/Catcher.vue'
import RecentWork from '../components/IndexComps/RecentWork.vue'
export default {
  components: {
    Catcher,
    RecentWork
  }
}
</script>
