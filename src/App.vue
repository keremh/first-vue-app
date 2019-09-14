<template>
  <div id="app" class="small-container">
    <h1>Users</h1>

    <user-table />
  </div>
</template>

<script>
import UserTable from '@/components/UserTable.vue'

export default {
  name: 'app',
  components: {
    UserTable,
  },
  data() {
    return {
      users: [
        {
          id: 1,
          name: 'Richard Hendricks',
          email: 'richard@piedpiper.com',
        },
        {
          id: 2,
          name: 'Bertram Gilfoyle',
          email: 'gilfoyle@piedpiper.com',
        },
        {
          id: 3,
          name: 'Dinesh Chugtai',
          email: 'dinesh@piedpiper.com',
        },
      ],
    }
  }
}
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>


