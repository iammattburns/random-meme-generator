<script>
    let imageId = Math.floor(Math.random() * 14 + 1);
</script>
<div class="image">
    <button on:click={()=> imageId = Math.floor(Math.random() * 37 + 1)}>Refresh</button>
    <img src="/images/{imageId}.jpeg" alt="">
</div>
<style>
    .image {
        width: 500px;
        max-width: 100%;
        margin: 0 auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    img {
        width: 100%;
        height: auto;
        border-radius: 10px;
        border: 10px solid aquamarine;
    }
    button {
        font-family: 'Roboto Mono', monospace;
        background-color: aquamarine;
        border: none;
        font-size: 26px;
        font-weight: 700;
        padding: 20px 50px;
        margin-bottom: 40px;
        border-radius: 10px;
        cursor: pointer;
    }
</style>