<template>
  <div class="home reuse">
    <stripe />
    <index name="Website Down" dqoute="Undergoing Temporary Maintenance" qq=""/>
    <stripe />
  </div>
</template>

<style lang="scss" scoped>
@import '../themes/light.scss';
@import '../themes/master.scss';
</style>

<script>
// @ is an alias to /src
import index from '@/components/index.vue';
import navbar from '@/components/navbar.vue';
import stripe from '@/components/stripe.vue';
import foot from '@/components/foot.vue';
import * as presc from '../assets/presc.js';


export default {
  name: 'home',
  components: {
    index,
    navbar,
    stripe,
    foot,
  }
}
</script>
