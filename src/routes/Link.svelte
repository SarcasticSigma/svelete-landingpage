<script>
    export let href = '/';
    export let myProps = {};
</script>

<!--<style>-->

<!--    a {-->
<!--        color:#9290c3;-->
<!--        text-decoration: none;-->
<!--        background-color: #1b1a55;-->
<!--        padding: 0.25rem 0.5rem;-->
<!--        display: inline-block;-->
<!--        border: 2px solid #535c91;-->
<!--        transform: skew(-5deg);-->
<!--        & :hover {-->
<!--            filter: brightness(1.5);-->
<!--            & span {-->
<!--                filter: brightness(1.2);-->
<!--            }-->
<!--        }-->

<!--        & span {-->
<!--            transform: skew(5deg);-->
<!--        }-->
<!--    }-->

<!--</style>-->



<style>

    a {
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
        text-decoration: none;


        & span {
            transform: skew(5deg);
        }
    }

    a:hover {
        border-top: 3px solid aqua;
        border-bottom: 3px solid aqua;
    }

    a:active {
        background-color: #253179;
    }
</style>

<a {...myProps} {href}><span><slot/></span></a>