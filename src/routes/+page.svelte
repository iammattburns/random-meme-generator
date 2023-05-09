<script>
    import Image from "$src/lib/components/Image.svelte"
</script>
<main>
    <h1>Programmers Meme Generator</h1>
    <Image />
</main>
<style>
    h1 {
        font-family: 'Sigmar', cursive;
        color: #c1c1c1;
        text-align: center;
        font-size: 80px;
        line-height: 1.2;
        margin: 50px 0;
        letter-spacing: 5px;
    }
    main {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
</style>