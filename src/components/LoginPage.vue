<template>
    <div class="login">
    <form @submit.prevent>
    <div>
    <label>Name</label>
    <input type="text" placeholder="Enter name"/>
    </div>
    <div>
    <label>Password</label>
    <input type="password" placeholder="Enter password"/>
    </div>
    <div>
        <button>Login </button>
    </div>
</form>
</div>
</template>

<script>
export default{
    name:'LoginPage',
    props:[
        'name',
        'password'
    ]
}
</script>

<style scoped>


</style>
