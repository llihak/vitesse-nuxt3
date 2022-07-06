<template>
  <div
    class="MediaObject flex gap-4 flex-col  "
    :class="reverse ? 'md:flex-row-reverse' : 'md:flex-row'"
  >
    <div class="primary md:max-w-3/5 flex-1 p-4">
      <slot name="primary">
        TODO: put primary content here
      </slot>
    </div>
    <div class="secondary md:max-w-2/5 p-4">
      <slot name="secondary">
        TODO: put secondary content here
      </slot>
    </div>

  </div>
</template>

<script>
import { booleanLiteral } from '@babel/types';

export default {
  props: {
    reverse: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style  scoped>
</style>