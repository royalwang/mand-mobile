<template>
  <div class="md-example-child md-example-child-icon md-example-child-icon-2">
    <div class="md-example-item-s">
      <md-icon name="circle-right" color="#333"></md-icon>
      <p>xs</p>
    </div>
    <div class="md-example-item-s">
      <md-icon name="circle-right" color="orange"></md-icon>
      <p>sm</p>
    </div>
    <div class="md-example-item-s">
      <md-icon name="circle-right" color="blue"></md-icon>
      <p>md</p>
    </div>
    <div class="md-example-item-s">
      <md-icon name="circle-right" color="purple"></md-icon>
      <p>lg</p>
    </div>
  </div>
</template>

<script>import {Icon} from 'mand-mobile'

export default {
  name: 'icon-demo',
  title: '颜色',
  components: {
    [Icon.name]: Icon,
  },
}
</script>
