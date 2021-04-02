<template>
    <div>
        <form name="loginform">
            <input type="text" name="hello"/>
        </form>
    </div>
</template>


<script>
export default {
    name: 'form',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
