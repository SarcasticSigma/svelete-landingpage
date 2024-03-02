<script>
    export let myProps = {};
</script>

<style>

    button {
        font-size: 16px;
        background-color: #535c91;
        color: #070f2b;
        padding: 0.25rem 0.5rem;
        display: inline-block;
        border: 3px solid transparent;
        border-right-color: aqua;
        border-left-color: aqua;

        transition: border 500ms ease-in;

        transform: skew(-5deg);

        & :hover {

        }

        & span {
            transform: skew(5deg);
        }
    }

    button:hover {
        border-top: 3px solid aqua;
        border-bottom: 3px solid aqua;

        /*color: #9290c3;*/

    }

</style>
<button {...myProps}><span><slot/></span></button>