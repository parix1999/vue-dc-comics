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
                    <div class="box-pic"></div>
                    <span>DC MERCHANDISE</span>
                </li>
                <li>
                    <div class="box-pic"></div>
                    <span>SUBSCRIPTION</span>
                </li>
                <li>
                    <div class="box-pic"></div>
                    <span>COMIC SHOP LOCATOR</span>
                </li>
                <li>
                    <div class="box-pic"></div>
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
        justify-content: space-between;

        li{
            display: flex;
            align-items: center;
            span{
            padding-left:5px;
        }
        }

    }
    .box-pic{
        width:50px;
        img{
            width:100%;
        }
        
    }

</style>