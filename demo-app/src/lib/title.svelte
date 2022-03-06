<script>
    export let title = "Ninja Gaming"
</script>

<div class="title">
    <img src="https://cdn-icons-png.flaticon.com/512/2780/2780137.png" alt="site logo">
    <h1>{title}</h1>
</div>

<style>
    .title{
        display: flex;
    }
    .title img {
        display: inline-block;
        filter: 
         invert(88%)
         sepia(18%) 
         saturate(886%) 
         hue-rotate(199deg) 
         brightness(100%)
         contrast(90%);
    }

    .title h1 {
        margin-left: 10px;
    }

    img {
        width: 100px;
        height: 100px;
    }
</style>