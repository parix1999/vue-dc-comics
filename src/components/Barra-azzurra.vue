<template>
    <div class="bg-blue">
        <div class="container">
            <ul>
                <li>
                    <div class="box-pic">
                        <img src="../assets/buy-comics-digital-comics.png" alt="fotoDC">
                    </div>
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <div class="box-pic">
                        <img src="../assets/buy-comics-merchandise.png" alt="fotoDC">
                    </div>
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <div class="box-pic">
                        <img src="../assets/buy-comics-subscriptions.png" alt="fotoDC">
                    </div>
                    <span>SUBSCRIPTION</span>
                </li>
                <li>
                    <div class="box-pic adjustment">
                        <img src="../assets/buy-comics-shop-locator.png" alt="fotoDC">
                    </div>
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <div class="box-pic">
                        <img src="../assets/buy-dc-power-visa.svg" alt="fotoDC">
                    </div>
                    <span>DC POWER VISA</span>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Barra-Azzurra',
}

</script>

<style lang="scss" scoped>

    .bg-blue{
        background-color:#2d83f9;
        padding: 80px 0;
    }
    
    ul {
        display:flex;
        list-style-type: none;

        li{
            display: flex;
            align-items: center;
            font-size:12px;
            color:white;
            padding-left:20px;
            span{
            margin-left:10px;
        }
        }

    }
    .box-pic{
        width:50px;
        img{
            width:100%;
        }
        
    }
    .adjustment{
        width:40px;
    }

</style>