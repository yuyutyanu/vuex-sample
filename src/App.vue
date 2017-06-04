<template>
    <div id="app">
        <counter></counter>
        子コンポーネントでインクリメントしたデータをストアから取得：{{$store.state.count}}<br>
    </div>
</template>

<script>
    import Counter from './components/Counter'


    export default {
        components: {
            Counter
        }
    }
</script>

<style>
    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
