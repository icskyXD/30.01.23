<script>
export default {
  data() {
    return {
      users: [
        {
          id: 1,
          name: "alisher",
        },
        {
          id: 2,
          name: "temir",
        },
        {
          id: 3,
          name: "Aituar",
        },
        {
          id: 4,
          name: "Dymash",
        },
      ],
    };
  },
};
</script>

<template>
  <p>Контакты</p>
  <ul>
    <li v-for="user of users" :key="user.id">{{ user.name }}</li>
  </ul>
</template>

<style></style>