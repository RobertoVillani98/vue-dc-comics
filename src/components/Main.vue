
<template>
    <main>
        <div class="container">
            <h1> --&gt; Content goes here &lt;-- </h1>
        </div>
    </main>
</template>

<script>
export default {
    name: "Main"
}
</script>

<style lang="scss" scoped>
    @import '../assets/style/partials/variables.scss';
    main {
        background: $black;
        h1 {
            line-height: 100px;
            color: $white;
        }
    }
    
    .container{
        height: 100px;
    }
</style>