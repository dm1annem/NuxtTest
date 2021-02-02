<template>
    <section>
        <h1>{{ pageTitle }}</h1>

        <ul>
          <li v-for="user in users" :key="user">
            <a href="#" @click="goTo(user)" >Пользователь {{user}}</a>
          </li>
        </ul>
    </section>
</template>

<script>
export default {

  asyncData() {
     return new Promise(resolv=>{
       setTimeout(()=>{
         resolv({
           users:[
             1, 2, 3, 4, 5
           ]
         })
       }, 3000)
     })
  },
  
  
  data() {
    return {
      pageTitle: 'Страница пользователей'
    };
  },
  props: {},
  methods: {
    goTo(user){
      this.$router.push('/users/' + user)
    }
  },
};
</script>

<style lang="scss" scoped></style>