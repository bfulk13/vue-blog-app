<template>
    <div>
        <p>{{postObj.author}}</p>
        <p>{{postObj.post}}</p>
        <hr>
    </div>
</template>

<script>
export default {
    props: ['postObj']
}
</script>

<style>

</style>
