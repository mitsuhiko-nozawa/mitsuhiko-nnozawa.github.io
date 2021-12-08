<template>
    <header>
        <div class="header-list">
            
                <li><a href="#">Home</a></li>
                <li><a href="#profile">プロフィール</a></li>
                <li><a href="#career">経歴</a></li>
                <li><a href="#skill">スキル</a></li>
                <li><a href="#contact">連絡先</a></li>
                <li class="fa fa-twitter"> <a href="https://twitter.com/ShiningStars_2">Twitter</a></li>
                <li class="fa fa-github"> <a href="https://github.com/mitsuhiko-nozawa">Github</a></li>
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
    vertical-align: middle;
}



.header-list li{
    list-style: none;
    float: left;
    height:20px;
    padding: 20px 30px;
    display: inline-block;
    vertical-align: middle;
    background-color: rgba(129, 232, 255, 0.824);
    box-align: center; 
    transition: all 0.2s;
}
.header-list a{
    color: black;
}


.header-list li:hover{
    opacity: 0.3;
}

</style>