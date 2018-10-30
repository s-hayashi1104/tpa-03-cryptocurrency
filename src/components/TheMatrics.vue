<template>
  <div :class="classNames">
    <Matric></Matric>
  </div>
</template>

<script>
import Matric from './TheMatric';

export default {
  name: 'Matric',
  components: {
    Matric,
  },
};
</script>
