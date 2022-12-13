<template>
  <div class="router"></div>
  TEST {{ id }}
</template>

<script>
export default {
  name: "RouterView",
  computed: {
    id() {
      return this.$route.params.id;
    },
  },
};
</script>
