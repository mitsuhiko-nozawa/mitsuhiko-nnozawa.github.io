<template>
    <div class="profile-wrapper" id="profile">
        
        <div class="profile">
            <h1>プロフィール</h1>
            <h2>氏名: 野沢充彦</h2>
            <h2>所属: 東京工業大学情報理工学院情報工学科 修士1年</h2>
            <h2>研究テーマ: 情報検索における検索アルゴリズムに関する研究</h2>
            <h2>趣味: ランニング、猫、漫画・アニメ</h2>
        </div>
        <div class="profile-image">
            <img src="../assets/my_pic.jpg">
        </div>
    </div>

    
</template>

<style scoped>

.profile-wrapper {
  height: 600px;
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
</style>
