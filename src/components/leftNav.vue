<template>
    <div class="left-nav">
        <ul>
            <li>
            <i  class="icon iconfont icon-rectangle390" ></i>
            <p>购物车</p>
            </li>
            <li>
            <i  class="icon iconfont icon-xiaoyuanyiqiatong" ></i>
            <p>阿萨德</p>
            </li>
            <li>
            <i  class="icon iconfont icon-qianbaopengyou" ></i>
            <p>多个发</p>
            </li>
            <li>
            <i  class="icon iconfont icon-kuaidi" ></i>
            <p>更好发</p>
            </li>
            <li>
            <i  class="icon iconfont icon-zhuanzhang" ></i>
            <p>去玩儿</p>
            </li>
        </ul>
    </div>
</template>
<script>
    export default {
       methods:{

       }
    }
</script>
<style scoped>
*{
    margin: 0;
    padding: 0;
}
.left-nav{
    width: 5%;
    height: 100%;
    background: #f5d5c3;
    float: left;
}
.left-nav ul{
    list-style: none;
    /* height: 100%; */
}
.left-nav ul li {
    width: 100%;
    height: 60px;
    text-align: center;
    border-bottom: 2px solid #fff;
    padding-bottom: 25px;
}
.iconfont{
    font-size: 30px;
}
</style>

