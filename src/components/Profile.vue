<template>
    <div class="profile-wrapper" id="profile">
        
        <div class="profile">
            <h1>プロフィール</h1>
            <h2>氏名:<br /> <span class="content">野沢充彦</span></h2>
            <h2>所属:<br /> <span class="content">東京工業大学情報理工学院情報工学科 修士1年</span></h2>
            <h2>研究テーマ:<br /> <span class="content">情報検索における検索アルゴリズムに関する研究</span></h2>
            <h2>趣味:<br /> <span class="content">ランニング、猫、漫画・アニメ</span></h2>
        </div>
        <div class="profile-image">
            <img src="../assets/my_pic.jpg">
        </div>
        <div class="clear">

        </div>
    </div>

    
</template>

<style scoped>
.profile-wrapper .clear{
    float: clear;
    height: 360px;
}

.profile-wrapper {
  height: auto;
  padding: 50px 0px;
  background-color: #f7f7f7;
  
}

.profile{
    float: left;
    width: 50%;
}

.profile h1{
    margin-left: 80px;
}

.profile h2{
    margin-left: 150px;
    margin-top: 10px ; 
    margin-bottom: 10px ; 
}

.profile-image{
    float: left;
    width: 50%;
    display: block;
    text-align: center;
    
}
.profile-image img{
    width: 45%;
    margin: 10px;
    
}


@media screen and (max-width:768px){
    .profile-wrapper{
        
        padding: 25px 0px;
    }

    .profile h1 {
        margin-left: 30px;
        font-size: 20px;
    }
    .profile h2 {
        margin-left: 30px;
        font-size: 16px;
    }
    .profile-image img{
        padding-top: 50px;
        width: 80%;
    }
    .profile h2 .content {
        font-size: 14px;
    }

}
</style>
