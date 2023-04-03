<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<script>
export default 
{
    props: ['title']
};
</script>

<style scoped>
    header 
    {
        background-color: purple;
        width: 100%;
        height: 5rem;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    header h1 
    {
        color: white;
    }


</style>