<template>
    <div class="wrapper">
        Hello, {{name}}!
    </div>
</template>

<script>
export default {
	props: ['name']
}
</script>

<style scoped>
.wrapper {
    padding: 10px;
    margin: 10px 0;
    font-weight: 600;
    background-color: #44e4d6;
}
</style>
