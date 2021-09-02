<script>
    export const defaultColor = "rgba(0,0,0,0)";
    export let color = defaultColor;
    export let text = "Lorem";
    export let active = false;
</script>

<button on:click={() => {active = !active;}} style="
    background-color: {active ? color : defaultColor};
">{text}</button>

<style>

    button {
        border-radius: 25px;
        height: 50px;
        min-width: 12px;
        border: none;
        cursor: pointer;
        font-size: 14px;
        padding: 0 25px;
    }
    
</style>