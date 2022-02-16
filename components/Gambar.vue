<template>
  <div>
    <img :src="imageSrc" />
  </div>
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 452,
    },
    height: {
      type: Number,
      default: 342,
    },
    imageSrc: {
      type: String,
      required: true,
    },
  },
};
</script>
