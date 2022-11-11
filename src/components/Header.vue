<template>
    <div class="container d-flex align-items-center justify-content-between bg-light p-4">
    <h2>{{title}}</h2>
    <Button type="primary py-2" text="Add Task"/>
    </div>
</template>

<script>
import Button  from './Button.vue';
export default {
    name: 'HeaderComponent',
    props: {
        title: String
    },
    components: {
        Button
    }
}
</script>