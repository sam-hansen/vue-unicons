<template>
  <svg
    v-bind="$attrs"
    :width="size"
    :height="size"
    xmlns="http://www.w3.org/2000/svg"
    class="ui-svg-inline"
    viewBox="0 0 24 24"
    fill="currentColor"
  >
    <path
      d="M3,7H21a1,1,0,0,0,0-2H3A1,1,0,0,0,3,7ZM21,17H3a1,1,0,0,0,0,2H21a1,1,0,0,0,0-2Zm0-4H3a1,1,0,0,0,0,2H21a1,1,0,0,0,0-2Zm0-4H3a1,1,0,0,0,0,2H21a1,1,0,0,0,0-2Z"
    />
  </svg>
</template>

<script>
import '../utils/style.css'

export default {
  props: {
    size: {
      type: String,
      default: '1em'
    }
  }
}
</script>