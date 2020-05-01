<template>
    <div class="nav">
       <div class="nav_list">
            <ul>
                <li class="my">Mycenter</li>
                <li>基本信息</li>
                <li>课程管理</li>
                <li>我的问答</li>
            </ul>
       </div>
       <div class="add_class">
           <!-- <img src="../../assets/add.png" alt=""> -->
           <span>+添加课程</span>
       </div>
    </div>
    
</template>
<script>
export default {
    name:"Nav"
    
}
</script>
<style scoped>
*{
    padding: 0;
    margin: 0;
}
.nav{
    background-color:#ffffff;
    /* width: 1366px; */
    height: 80px;
    box-shadow: 2px 2px 4px #e7e7e7;
}

.nav_list li{
    float: left;
    color: hsl(0, 0%, 40%);
    line-height: 80px;
    padding-left: 100px;
    font-size: 14px;

}
.nav_list .my{
    color: #00aaff;
    font-size:20px;
}
.nav_list li:hover{
    color: #00aaff;
}
.add_class{
    width: 155px;
    height: 30px;
    border: 1px solid #eeeeee;
    border-radius: 15px;
    text-align: center;
    float: right;
    margin-top:25px;
    line-height: 30px;
    margin-right: 120px;
    /* cursor: pointer; */
}
/* .add_class img{
    width: 20px;
    height: 20px;
    
} */
.add_class span{
    color: #00aaff;
}


</style>