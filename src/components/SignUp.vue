<template>
<div class="register">
    <form @submit.prevent>
    <div>
    <label>Name</label>
    <input type="text" placeholder="Enter name"/>
    </div>
    <div>
    <label>Phone</label>
    <input type="tel" placeholder="Enter phone number"/>
    </div>
    <div>
    <label>E-Mail</label>
    <input type="email" placeholder="Enter email" />
    </div>
    <div>
    <label>Password</label>
    <input type="password" placeholder="Enter password"/>
    </div>
    <div>
        <button>Sign up </button>
    </div>
</form>
</div>
</template>

<script>
export default{
    name:'SignUp',
    props:[
        'name',
        'phone',
        'email',
        'password'
    ]
}
</script>

<style scoped>

</style>