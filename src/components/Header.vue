<template>
    <header>
        <div class="header-list">
            
                <li class="logo"><a href="#">Home</a></li>
                <li class="item"><a href="#profile">プロフィール</a></li>
                <li class="item"><a href="#career">経歴</a></li>
                <li class="item"><a href="#skill">スキル</a></li>
                <li class="item"><a href="#contact">連絡先</a></li>
                <li class="item"> <a href="https://twitter.com/ShiningStars_2"><span class="fa fa-twitter"></span>Twitter</a></li>
                <li class="item"> <a href="https://github.com/mitsuhiko-nozawa"><span class="fa fa-github"></span>Github</a></li>
        </div>
        <div class="gnav">
            <a href="#"><span class="fa fa-bars menu-icon"></span></a>
            <ul>
                <li class="item"><a href="#profile">プロフィール</a></li>
                <li class="item"><a href="#career">経歴</a></li>
                <li class="item"><a href="#skill">スキル</a></li>
                <li class="item"><a href="#contact">連絡先</a></li>
                <li class="item"> <a href="https://twitter.com/ShiningStars_2"><span class="fa fa-twitter"></span>Twitter</a></li>
                <li class="item"> <a href="https://github.com/mitsuhiko-nozawa"><span class="fa fa-github"></span>Github</a></li>            
            </ul>
        </div>


    </header>
</template>

<script>

</script>

<style scoped>
header .fa{
    color: black;
}




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

.gnav ul{
    height: 0px;
    width: 0px;
    padding: 0px;
}
.gnav ul li {
    overflow: hidden;
    transition: .5s;
}
.gnav {
    float: right;
    height:20px;
    padding: 20px 30px;
    display: none;
    background-color: rgba(129, 232, 255, 0.824);
}

.gnav:active > ul > li {
    height: 2rem;
    overflow: visible;
}

header .gnav:hover{
    opacity: 0.3;
}


@media screen and (max-width:768px){
    .header-list .item{
        display: none;
    }    
    header .gnav{
        /*display: block;*/
        display: none;
    }
}


</style>

