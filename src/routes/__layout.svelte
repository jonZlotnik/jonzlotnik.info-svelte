<style lang="scss">
    @import "../colors.scss";

    @import url('https://fonts.googleapis.com/css2?family=Lato&family=Roboto&display=swap');

    :global(*) {
        color: $app-text-color;
        font-family: 'Roboto', sans-serif;
        font-weight: 400;
        font-style: normal;
    }
    :global(h1) {
        font-family: 'Lato', sans-serif;
        font-weight: 400;
        font-style: normal;
    }
    :global(body) {
        background-color: $app-background-color;
    }
    
</style>

<slot></slot>