<template>
  <div class="home">
    <EditPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import EditPage from '@/components/EditPage.vue'

export default {
  name: 'Home',
  components: {
    EditPage
  }
}
</script>
