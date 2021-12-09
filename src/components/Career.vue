<template>
    <div class="career-wrapper" id="career">
        
        <div class="career">
            <h1>経歴</h1>
            <h2>2016年3月 神奈川県立湘南高校 卒業</h2>
            <h2>2020年9月 慶應義塾総合政策学部 卒業</h2>
            <h2>2021年3月 東京工業大学情報理工学院情報工学科修士課程 入学</h2>
        </div>
        <div class="career">
            <h1>職務経験</h1>
            <h2>2016年7月〜2017年5月 塾講師</h2>
            <h2>2017年7月〜2018年8月 塾講師</h2>
            <h2>2021年1月〜2021年6月 株式会社リッジアイ インターン 機械学習エンジニア</h2>
        </div>

    </div>

    
</template>

<style scoped>

.career-wrapper {
  padding: 50px 0px;
  background-color: #f7f7f7;
  
}

.career{
    width: 100%;
}

.career h1{
    margin-left: 80px;
    padding: 5px 0px;
}

.career h2{
    margin-left: 150px;
    margin-top: 10px ; 
    margin-bottom: 10px ; 
}

@media screen and (max-width:768px){
    .career-wrapper{
        padding: 25px 35px;
    }

    .career h1 {
        margin-left: 0px;
        font-size: 20px;
    }
    .career h2 {
        margin-left: 0px;
        font-size: 16px;
    }


}


</style>
