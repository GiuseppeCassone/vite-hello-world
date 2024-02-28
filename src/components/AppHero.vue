<script>
export default{
    jumbo: 'AppHero',
}
</script>

<template>
    <div class="jumbotron">
        <h2>Jumbotron</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae non commodi rem modi distinctio illum. Aperiam, sapiente id nemo iure totam quaerat quasi saepe velit. Accusantium temporibus pariatur voluptas blanditiis!</p>       
    </div>
</template>

<style>
    .jumbotron{
        width: 60%;
        margin-left: auto;
        margin-right: auto;
        margin-top: 25px;
        padding: 100px;
        border: 1px solid rgba(255, 255, 255, 0.1);
        border-radius: 20px;
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        background-image: url(../assets/img/dark-theme.jpg);
        box-shadow: 4px 4px 6px rgba(0, 0, 0, 0.3);

    }

    h2{
        font-size: 30px;
    }
</style>