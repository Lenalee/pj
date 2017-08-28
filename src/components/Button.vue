<template>
<div>
<button class="btn btn-primary" >{{ name }}</button>
</div>
</template>

<script>
export default {
  name: 'button',
  data () {
    return {}
  },
  props: [
    'name'
  ]
}
</script>
