<script>
    import Navigation from "./Navigation.svelte";
    import Pallete from './Pallete.svelte';
    import Button from "./Button.svelte";
    import Link from "./Link.svelte";
</script>

<style>

    .navigation-wrapper, .content-wrapper {
        margin: 0 15%;
        display: block;
    }

    .content-wrapper {
        margin-top: 5%;
        margin-bottom: 2rem;
    }

    section {
        margin-top: 2rem;
        background-color: rgba(27, 26, 85, 1);
        box-shadow: 10px 5px 5px #1794bd;
        padding: 0.5rem 2rem 2rem;
    }

    img {
        height: 100%;
        width: 100%;
        position: absolute;
        top: 0;
        left: 0;
        z-index: 1;
        object-fit: cover;
    }

    .page-wrapper {
        z-index: 3;
        position: absolute;
        left: 0;
        top: 0;
    }

</style>

<img src="/hero.jpg" alt="Abstract art">
<div class="page-wrapper">

    <div class="navigation-wrapper">
        <!--        <Navigation/>-->


    </div>
    <div class="content-wrapper">
        <section>
            <h1>Why Sigmaplex?</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque culpa earum enim, error explicabo maiores
                necessitatibus perferendis perspiciatis quas, quod, ratione suscipit. Accusantium at commodi deleniti
                dolore
                esse, et iste molestiae. Esse ex facere itaque nam numquam odio quas rerum! A doloremque ducimus sed!
                Corporis
                enim libero natus similique. Magni?</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aliquid aspernatur consequatur
                corporis
                deleniti distinctio doloribus excepturi facere facilis ipsum maiores, molestiae nobis nulla numquam quae
                quas
                quasi quidem, quos tempora voluptates. Aperiam architecto eos est ex molestias nisi non placeat quam
                quo,
                quod
                rerum tempore vel, vitae. Facere, iste?</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aliquid aspernatur consequatur
                corporis
                deleniti distinctio doloribus excepturi facere facilis ipsum maiores, molestiae nobis nulla numquam quae
                quas
                quasi quidem, quos tempora voluptates. Aperiam architecto eos est ex molestias nisi non placeat quam
                quo,
                quod
                rerum tempore vel, vitae. Facere, iste?</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci aliquid aspernatur consequatur
                corporis
                deleniti distinctio doloribus excepturi facere facilis ipsum maiores, molestiae nobis nulla numquam quae
                quas
                quasi quidem, quos tempora voluptates. Aperiam architecto eos est ex molestias nisi non placeat quam
                quo,
                quod
                rerum tempore vel, vitae. Facere, iste?</p>
        </section>

        <section>
            <h1>Support Us</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Architecto blanditiis consectetur consequuntur
                doloribus est eveniet odio quia quisquam sit voluptate. Aspernatur culpa placeat quidem reiciendis.</p>
            <Link href="">Support Us</Link>
        </section>

    </div>

<!--    <Pallete/>-->

</div>
