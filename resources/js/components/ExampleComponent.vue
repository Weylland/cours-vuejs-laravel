<template>
    <div class="container">
        <p>
            <input type="text" v-model="name">
            <input type="checkbox" v-model="checkbox">
        </p>
        <p>
            Bonjour {{ name }}
        </p> 
    </div>
</template>

<script>
    export default {
        data() {
            return {
                'name': 'Nicolas',
                'checkbox': true,
            }
        }
    }
</script>
