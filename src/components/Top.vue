<template>
    <div class="top-wrapper">
        <div class="container">
            <h1>THIS IS MITSUHIKO NOZAWA'S <span class="sp"><br></span>HOME PAGE</h1>    
        </div>
    </div>
</template>

<script>

</script>
<style scoped>

.top-wrapper{
    padding-top: 60px;
    
    background-image: url(../assets/bg1.jpg);
    background-size: cover;
    
    height: 200px;
}
.top-wrapper .container{
    text-align:center;
    color: white;
    padding-top: 40px;
    
    opacity: 0.8;
}
span.sp{
    display: none;
}


@media screen and (max-width:768px){
    .top-wrapper{
        height: 140px;
    }
    .top-wrapper .container {
        font-size:10px;
        padding-top: 15px;
        margin: 0px 0px;
    }
    span.sp{
        display: block;
        height: 0px;
    }
}
</style>