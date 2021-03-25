<template>
    <div>
    <button :class="tailwindbg" class="hover:bg-purple-500 focus:outline-none  p-4 rounded-xl shadow">{{texte}}</button>
    </div>
</template>

<script>
export default {
props:
    {
    'tailwindbg':String,
    'texte': String
    },
}

</script>

<style>

</style>