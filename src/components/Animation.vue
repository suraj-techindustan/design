<template>
  <div>
    <vue-load-image>
      
      <template v-slot:preloader> 
        <img src="../assets/gifs/giphy.gif" />
      </template>
      <template v-slot:error>Image load fails</template>
    </vue-load-image>
  </div>
</template>

<script>
import VueLoadImage from 'vue-load-image'

export default {
  name:"Animation",
  components: {
    'vue-load-image': VueLoadImage
  }
}
</script>