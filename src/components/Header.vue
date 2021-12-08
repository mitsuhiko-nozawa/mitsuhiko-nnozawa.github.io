<template>
    <header>
        <div class="header-list">
            
                <li><a href="#">Home</a></li>
                <li><a href="#profile">プロフィール</a></li>
                <li><a href="#career">経歴</a></li>
                <li><a href="#skill">スキル</a></li>
                <li><a href="#contact">連絡先</a></li>
                <li> <a href="https://twitter.com/ShiningStars_2"><span class="fa fa-twitter"></span>Twitter</a></li>
                <li> <a href="https://github.com/mitsuhiko-nozawa"><span class="fa fa-github"></span>Github</a></li>
        </div>
    </header>
</template>

<script>

</script>

<style scoped>
/*.header-list a{
    text-decoration: none;
}*/

header{
    background-color: rgba(129, 232, 255, 0.824);
    height: 60px;
    width: 100%;
    position: fixed;
    top:0px;
    z-index: 10;
}



.header-list li{
    list-style: none;
    float: left;
    background-color: rgba(129, 232, 255, 0.824);
    box-align: center; 
    transition: all 0.3s;
}
.header-list a{
    color: black;
    height:20px;
    padding: 20px 30px;

    display: inline-block;
}


.header-list li:hover{
    opacity: 0.3;
}

</style>