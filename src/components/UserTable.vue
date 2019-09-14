<template>
  <div id="user-table">
    <tbody>
        <tr v-for="user in users" :key="user.id">
          <td>{{ user.name }}</td>
          <td>{{ user.email }}</td>
        </tr>
    </tbody>
  </div>
</template>

<script>
  export default {
    name: 'user-table',
    props: {
        users: Array,
    },
  }
</script>

<style scoped></style>