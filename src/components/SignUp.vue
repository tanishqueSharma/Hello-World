<template>
    <!-- <h1>Sign Up</h1> -->
    <div class="register">
            <h1>Sign Up</h1>

    <input type="text" placeholder="Enter name"/>
    <input type="password" placeholder="Enter password"/>
    <input type="text" placeholder="Enter email"/>
    <button>Sign Up</button>
    </div>
</template>

<script>
export default{
    name:'SignUp'
}
</script>

<style scoped>
.register input{
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