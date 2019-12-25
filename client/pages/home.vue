<template>
  <div>
    <div>
      test {{name}}
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator'

@Component({
  components:{ }
})
export default class Home extends Vue {
  name: string = 'hello-next-decorator';
}
</script>
