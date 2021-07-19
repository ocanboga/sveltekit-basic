<script>
    import Header from "$lib/components/Header.svelte"
</script>
<div class="container">
    <Header></Header>
    <slot></slot>
</div>

<style>
    .container{
        max-width: 700px;
        margin: 50px auto;
     }
</style>