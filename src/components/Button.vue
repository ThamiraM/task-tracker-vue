<template>
    <button :class="`btn btn-${type}`">{{text}}</button>
</template>

<script>
 export default {
    name: 'ButtonComponent',
    props: {
        type: String,
        text: String
    }
 }
</script>