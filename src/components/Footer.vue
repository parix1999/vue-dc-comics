<template>
    <div class="bg-pic">
        <div class="container">
            <div class="bg-logo">

            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'Footer',
}

</script>

<style lang="scss" scoped>

    .bg-pic{
        height:400px;
        background-image: url('../assets/footer-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        background-position:top;

        .bg-logo{
            height:400px;
            background-image: url('../assets/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position:center right;


        }

    }

</style>