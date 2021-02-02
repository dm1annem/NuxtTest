<template>
    <form>
        <h1>Вход</h1>


        <div class="form-group">
            <input type="text" class="form-control">
        </div>

        <div class="form-group">
            <input type="password" class="form-control">
        </div>

        <button class="btn btn-primery">Войти</button>

        <P>
            <nuxt-link to="/">На главную</nuxt-link>
        </P>
        
    </form>
</template>

<script>
export default {
    layout: 'empty'
}
</script>

<style scoped>

form {
    width: 600px;
}

</style>