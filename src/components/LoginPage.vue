<template>
    <div class="login">
            <h1>Login</h1>

    <input type="text" placeholder="Enter name"/>
    <input type="password" placeholder="Enter password"/>

    <button>Login</button>
    </div>
</template>

<script>
export default{
    name:'LoginPage'
}
</script>

<style scoped>
.login input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-bottom: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
}

</style>