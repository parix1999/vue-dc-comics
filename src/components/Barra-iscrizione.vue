<template>
    <div class="bg-barra-sotto">
        <div class="container spaziatura">
            <div class="box-1">
                SIGN-UP NOW!
            </div>

            <div>
                <ul class="icon-social">
                    <li>FOLLOW US</li>
                    <li>
                        <div class="box-social">
                            <img src="../assets/footer-facebook.png" alt="social-logo">
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Barra-Iscrizione',
}

</script>

<style lang="scss" scoped>
    
    .bg-barra-sotto{
        background-color:#2c2c2c;
        padding:20px 0;
    }

    .spaziatura{
        display:flex;
        justify-content:space-between;
        align-items: center;

        .box-1{
            color:white;
            border: 2px solid #2465b1;
            padding: 10px;
        }
    }
    ul{
        list-style-type: none;
        li{
            padding:0 10px;
            &:first-child{
                color:#2e76f9;
            }
        }
    }
    .icon-social{
        display: flex;
        align-items: center;;
    }


</style>