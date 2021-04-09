<template>
    <div id="main_top" class="container-fluid">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-md-12 col-lg-12">
                    <h1> Cannabis specialists <strong></strong></h1>
                </div>
                <div class="col-lg-6 col-md-4 col-sm-6 col-xs-12 text-right">

                    <div>
                        <h1>since 1987</h1>
                        <img class="img-fluid" src="/img/logo-main-section.png" alt="">
                    </div>
                
                </div>
                <div class="col-lg-6 col-md-4 col-sm-6 col-xs-12">
                    <div>
                        <p>
                            Dutch Passion was the second European Cannabis Seed Company, established in Amsterdam in 1987. It is our mission to supply the recreational and medical home grower with the highest quality cannabis seeds available in all countries where growing is legally allowed.

                            After many years of dedication Dutch Passion remains a leading supplier of the world’s best cannabis genetics. Our experienced team do their utmost to maintain the quality of our existing varieties and constantly strives to find new ones from an extensive network of worldwide sources.
                            We supply thousands of retailers and seed distributors around the world.
                        </p>
                    
                    </div>
                

                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
<style scooped lang="scss">
    #main_top{
        margin-top:100px;
        background-image: url('/img/bg-image-main.png');
        background-position: center;
        background-size: cover;
        height: 450px;
    }
</style>