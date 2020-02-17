<template>
  <div class="details">
    <Sidebar />
    <h1>This is a page for the bank details of the sender</h1>
  </div>
</template>

<script>
// @ is an alias to /src
import Sidebar from '@/components/layout/Sidebar';


export default {
  name: 'Details',
  components: {
    Sidebar
  }
}
</script>
