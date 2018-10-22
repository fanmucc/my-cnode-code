<template>
    <div class="header">
        <a href="#" class="imgHref"><img src="https://static2.cnodejs.org/public/images/cnodejs_light.svg" alt=""></a>
        <!-- <input type="text"> -->
        <ul>
            <li><a href="#">首页</a> </li>
            <li><a href="#">新手入门</a> </li>
            <li><a href="#">API</a> </li>
            <li><a href="#">关于</a> </li>
            <li><a href="#">注册</a> </li>
            <li><a href="#">登陆</a> </li>
        </ul>
    </div>
</template>
<script>
export default {
    name:'Header'
}
</script>
<style scoped>
    * {
        margin: 0;
        padding: 0;
    }
    .baCkcol {
        background: #fff;
    }
    ul {
        list-style: none;
        display: flex;
        flex-wrap: nowrap;
    }
    
    a {
        text-decoration: none;
        color: #ccc;
    }
    .header {
        display: flex;
        align-items:center;
        justify-content: space-between;
        background: #5a5555;
        height: 50px;
        padding: 0 20px;
    }
    /* .header input {
        background: 4px 4px no-repeat #888;
        padding: 3px 5px 3px 22px;
        color: #666;
        border: 0;
        margin-top: 2px;
        transition: all .5s;
        width: 233px;
        height: 26px;
        margin-left: -200px;
        border-radius: 15px;
        outline: none;
    }
    .header input:hover {
        background: #fff;
    }
    .header input:focus {
        background: #fff;
    } */
    .header .imgHref {
    }
    .header img {
        width: 120px;
        height: 28.19px;
    }
    ul > li {
        line-height: 50px;
        margin: 0 5px;
    }
    ul > li > a {
        font-size: 13px;
    }
    ul > li > a:hover {
        color: #fff;
    }
</style>

