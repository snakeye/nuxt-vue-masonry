<template>
  <div class="container mx-auto">
    <div v-masonry>
      <div v-masonry-tile v-for="item, index in items" :key="index" class="w-1/3">
        {{ item }}
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data: () => ({
    items: [
      1, 2, 3, 4, 5, 6, 7, 8
    ]
  })
}
</script>
