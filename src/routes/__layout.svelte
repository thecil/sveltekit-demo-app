<script>
    import Title from "$lib/title.svelte"
    import "../routes/styles/global.css"
</script>

<header>
    <Title title="Ninja Gaming Guides" />
</header>

<main>
    <slot></slot>
</main>

<footer>
    <p>Copyright 2022 Ninja Gaming Guides</p>
</footer>

<style>
    header {
        display: flex;
        justify-content: center;
    }

    main {
        max-width: 950px;
        margin: 20px auto;
    }

    footer {
        text-align: center;
    }

</style>
