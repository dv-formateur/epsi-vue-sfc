<template>
  <div class="router"></div>
  TEST {{ id }}

  {{ $route.query.order }}
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
