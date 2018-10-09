<template>
    <div>
        <li>{{ book.title }}:{{ book.author }}</li>
    </div>
</template>

<script>
export default {
    name: 'BookItem',
    props: ['books'],
}
</script>

<style>
    li {
        display: block;
        margin: 0 10px;
    }
</style>