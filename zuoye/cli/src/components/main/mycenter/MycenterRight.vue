<template>

    <div class="MycentertRight">
        <div class="headimage">
            <div class="peopleimg"><img src="../../../assets/2.jpg" alt=""></div>
            <div class="message">
                <span>罗密欧</span>
                <img src="" alt="">
                <p>信息完整度</p>

            </div>

        </div>
        <div class="surplus"></div>
        <div class="attestation"></div>

    </div>
</template>
<script>

export default {
    name:'MycentertRight'
    
}
</script>
<style scoped>
*{
    padding: 0;
    margin: 0;
}
.MycentertRight{
    width: 900px;
    height: 500px;
    /* margin: 0 auto; */
    background-color: #ffffff;
    float: right;
    margin-left: 20px;
    
}

.peopleimg img{
    width: 80px;
    height: 80px;
    display: block;
}
.message span{
    color: hsl(0, 0%, 40%);
}


</style>