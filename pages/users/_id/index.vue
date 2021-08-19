<template>
    <div class="mt-4 mb-4">
   <h2>Users Id is {{ $route.params.id }}</h2>

  
    </div>
</template>

<script>
export default {
    // Validate integer id
    validate(params) {
       return /^\d+$/.test(params.id)
    }
  
}
</script>