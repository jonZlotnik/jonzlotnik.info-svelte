<script>
    import Navbutton from "../components/NavButton.svelte";
</script>

<div class="container">
    <nav class="columns">
        <div class="column"><Navbutton text="Photos" color='#E86868' /></div>
        <div class="column"><Navbutton text="Projects" color='#71C9E8' /></div>
        <div class="column"><Navbutton text="Notes" color='#4FE185' /></div>
    </nav>
</div>

<style lang="scss">
    @import "bulma/sass/utilities/_all.sass";
    @import "bulma/sass/grid/columns.sass";
</style>