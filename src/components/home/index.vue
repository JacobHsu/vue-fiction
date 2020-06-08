<template>
    <div>
        <Fun />
    </div>
</template>

<script lang='ts'>
import { Component, Vue } from 'vue-property-decorator';
import Fun from './Fun.vue';

@Component({
  components: {
    Fun,
  },
})

export default class Chome extends Vue {
  private newFictionList!: any[];
}
</script>

<style lang="scss" scoped>

</style>