<script setup lang="ts">
</script>

<template>
  <div class="container">
    <img
      src="/image/preview/window.png"
      alt="AutoBangumi WebUI Preview"
      class="webui-preview"
      data-zoomable
    />
  </div>
</template>

<style scoped>

.container {
  display: flex;
  justify-content: center;
  margin: 0 auto;
  padding-inline: 24px;
  padding-block: 60px 20px;
  /**
   * same as VPHero.vue
   * https://github.com/vuejs/vitepress/blob/v1.0.0-beta.5/src/client/theme-default/components/VPHero.vue#L83
   */
  max-width: 1280px;
}

@media (min-width: 640px) {
  .container {
    padding-inline: 48px;
  }
}

@media (min-width: 960px) {
  .container {
    padding-inline: 64px;
  }
}

.webui-preview {
  width: 100%;
  height: auto;
  border-radius: 10px;

  box-shadow: none;
}

</style>