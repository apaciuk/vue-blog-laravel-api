<template>
    <div class="mt-4 mb-4">
   <h2>Enter a Users Id</h2>

   <input type="text" v-model="id">
   <button class="btn btn-primary" @click="loadUser">Load User</button>
    </div>
</template>

<script>
export default {
    data () {
        return {
            id: ''
        }
    },
    methods: {
        loadUser() {
            this.$router.push(`/users/${this.id}`)
        }
    }
}
</script>