<template>
  <nav id="header__nav" class="header__nav nav" role="navigation">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
</template>

<script lang="js"> // lang=js needs to be declared to remove VSCode typscript errors
/* @flow */

export default {
  name: 'mainNav',
  components: {},
  props: {},
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
