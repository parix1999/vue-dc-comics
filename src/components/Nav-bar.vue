<template>
    <div class="container">
        <nav>
            <div class="box-logo">
                <img src="../assets/dc-logo.png" alt="logoDC">

            </div>

            <div class="text-nav">
                <ul>
                    <li><a href="#">CHARATERS</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIBLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                    
                </ul> 

            </div> 


        </nav>
        
    </div>
</template>

<script>
export default {
    name: 'Nav-bar',
}
</script>


<style lang="scss" scoped>

    .box-logo{
        width:80px;
        img{
            width:100%;
        }

    }

    nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top:20px;
        
    }
    ul {
        display: flex;
        list-style: none;

        li{
            padding: 0 10px;
            height: 80px;
            line-height: 80px;
            
            &:hover{
                border-bottom:4px solid #2d83f9;

            }

        }

        a{
            color:black;
            text-decoration: none;
            &:hover{
                color:#2d83f9;
            }
        }
    }
</style>




