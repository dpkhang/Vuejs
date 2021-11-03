<template>
    <div class="title">
        <h1>First Project</h1>
        {{title}}
    </div>
</template>

<script>
    import './Home.scss'
    export default {
        name: 'home',
        data () {
            return {
                title: 'Hello World',
            }
        }
    }
</script>