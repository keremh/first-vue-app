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
          name: 'Kerem Hallaç',
          email: 'hallackerem@gmail.com',
        },
        {
          id: 2,
          name: 'Kerem Gilfoyle',
          email: 'gilfoyle@piedpiper.com',
        },
        {
          id: 3,
          name: 'Test Chugtai',
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


