<template>
  <div>
    <h1>Пользователь {{$route.params.id}}</h1>
  </div>
</template>

<script>
export default {
  validate({params}) {
    return /^\d+$/.test(params.id)
  }
  
};
</script>

<style lang="scss" scoped></style>