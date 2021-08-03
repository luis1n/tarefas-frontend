<template>
  <main class="container index">
    <front />
  </main>
</template>

<script>
export default {
  name: "Index",
  components: {
    Front: () => import("../components/Front.vue"),
  },
};
</script>
