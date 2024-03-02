<script>
    export let href = '/';
    export let myProps = {};
</script>

<style>

    a {
        color:#9290c3;
        text-decoration: none;
        background-color: #1b1a55;
        padding: 0.25rem 0.5rem;
        display: inline-block;
        border: 2px solid #535c91;
        transform: skew(-5deg);
        & :hover {
            filter: brightness(1.5);
            & span {
                filter: brightness(1.2);
            }
        }

        & span {
            transform: skew(5deg);
        }
    }

</style>
<a {...myProps} {href}><span><slot/></span></a>