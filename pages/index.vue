<template>
    
</template>

<script>
    export default{
        middleware: "authenticated",
        mounted(){
            $nuxt.$router.push("/dashboard");
        }
    }
</script>