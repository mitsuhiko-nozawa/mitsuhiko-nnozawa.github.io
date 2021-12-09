<template>
    <div class="contact-wrapper">
        <div class="contact" id="contact">
            <h1>連絡先</h1>
            <h2>mnozawa.shiningstars@[gmail]</h2>
            <h2 class="sp"><a href="https://twitter.com/ShiningStars_2"><span class="fa fa-twitter"></span>Twitter</a></h2>
            <h2 class="sp"><a href="https://github.com/mitsuhiko-nozawa"><span class="fa fa-github"></span>Github</a></h2>
        </div>
    </div>

    
</template>

<style scoped>


.contact-wrapper {
  padding: 50px 0px;
  background-color: #f7f7f7;
  
}

.contact{
    width: 100%;
}

.contact h1{
    margin-left: 80px;
}

.contact h2{
    margin-left: 150px;
    margin-top: 10px ; 
    margin-bottom: 10px ; 
}

.sp{
    display: none;
}
.sp a{
    color: black;
}

@media screen and (max-width:768px){
    .contact-wrapper{
        padding: 25px 35px;
    }

    .contact h1 {
        margin-left: 0px;
        font-size: 20px;
    }
    .contact h2 {
        margin-left: 0px;
        font-size: 16px;
    }
    .sp{
        display: block;
    }


}


</style>
