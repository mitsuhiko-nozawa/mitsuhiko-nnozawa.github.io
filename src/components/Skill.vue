<template>
    <div class="skill-wrapper" id="skill">
        
        <div class="skill">
            <h1>スキル</h1>
            <h2>Python, C++, Docker, Linux</h2>
        </div>


    </div>

    
</template>

<style scoped>

.skill-wrapper {
  padding: 50px 0px;
  background-color: #f7f7f7;
  
}

.skill{
    width: 100%;
}

.skill h1{
    margin-left: 80px;
}

.skill h2{
    margin-left: 150px;
    margin-top: 10px ; 
    margin-bottom: 10px ; 
}

@media screen and (max-width:768px){
    .skill-wrapper{
        padding: 25px 35px;
    }

    .skill h1 {
        margin-left: 0px;
        font-size: 20px;
        padding: 5px 0px;
    }
    .skill h2 {
        margin-left: 0px;
        font-size: 16px;
    }


}



</style>
