<template>
    <div class="bg-pic">
        <!-- <div class="container prova">
            <div class="bg-logo"></div>
        </div> -->
        <div class="container separazione">
            <ul>
                <li>DC COMICS</li>
                <li><a href="#">Charects</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
                <li class="shop">SHOP</li>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>

            </ul>
            <ul>
                <li>DC</li>
                <li><a href="#">Terms Of Use</a></li>
                <li><a href="#">Privacy(New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscriptions</a></li>
                <li><a href="#">Talent Workshops</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>

            </ul>
            <ul>
                <li>SITES</li>
                <li><a href="#">DC</a></li>
                <li><a href="#">MAD Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Univverse</a></li>
                <li><a href="#">DC Power Visa</a></li>
                
            </ul>
        
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
        .separazione{
            display: flex;
            ul{
                list-style: none;
                padding:0 10px;

                li a {
                    text-decoration: none;
                    color: gray;
                    font-size:12px;

                    
                }
                .shop{
                    color:white;
                    margin:10px 0;
                }
                li{
                    &:first-child{
                        color:white;
                        margin:10px 0;
                    }
                }
            }
        }

    }

</style>