<template>
    <div id="main">
        <Header />
        <div class="container my-4">
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
import Header from './Header'

export default {
    name: 'MainApp',
    components: { Header }
}
</script>
