<template>
<div class="mycenter">
    <MycenterLeft></MycenterLeft>
    <MycenterRight></MycenterRight>

</div>

    
</template>
<script>
import MycenterLeft from'./MycenterLeft.vue'
import MycenterRight from'./MycenterRight.vue'

export default {
    neme:'mycenter',
    components: {
        MycenterLeft,
        MycenterRight
         
    }
    
}
</script>
<style  scoped>
*{
    padding: 0;
    margin: 0;
}

.mycenter{
    margin: 0px auto;
    width: 1125px;
    padding-top: 30px;
    display: flex;
}

</style>