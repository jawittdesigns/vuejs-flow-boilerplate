<template>
  <section :id="setID" :class="setClass" v-bind="setAttr">
    <slot><p>Main</p></slot>
  </section>
</template>

<script lang="js"> // lang=js needs to be declared to remove VSCode typscript errors
/* @flow */

export default {
  name: 'mainLayoutMain',
  components: {},
  props: {
    setID: {
      type: String,
      default: 'main',
    },
    setClass: {
      type: String,
      default: 'main',
    },
    setAttr: {
      type: Object,
      default: () => {
        return { role: 'main' }
      },
    },
  },
  data() {
    return {}
  },
  methods: {},
  computed: {},
  watch: {},
  // Lifecycle Hooks
  beforeCreate() {},
  created() {},
  beforeMount() {},
  mounted() {},
  beforeUpdate() {},
  updated() {},
  beforeDestroy() {},
  destroyed() {},
}
</script>
