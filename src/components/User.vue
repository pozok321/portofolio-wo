<template>
    <Content :user-data="this.users"/>
  </template>
  <script>
  import Content from "./Content.vue";
  export default {
    components: {
      Content,
    },
    data() {
      return {
        users: [
          {
            id: 1,
            name: "Valeryan Ramadhan",
            email: "Valeryanr18@gmail.com"
          },
          {
            id: 2,
            name: "Achmad Tabrizi",
            email: "achmadtabrizi@gmail.com"
          },
          {
            id: 3,
            name: "Didit Ardiansyah",
            email: "diditardiansyah@gmail.com"
          }
        ]
      };
    }
  };
  </script>