<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<style>
    body{
        margin:0px;
        padding:0px;    
    }
    .title{
        background-color: #e13228;
        height:45px;
        width:100%;
    }
    .title_left{
        float: left;
    }
    .title_right{
        float:right;
    }
    .title_logo{
        display: block;
        float: left;
        margin-top:8px;
        margin-left: 20px;
    }
    .title_search{
        float: left;
        border: none;
        outline: 0;
        width: 220px;
        height: 24px;
        border-width: 0;
        border-style: solid;
        border-radius: 12px;
        background-color: #d11c11;
        color: #ffffff;
        margin-top:10px;
        margin-left:20px; 
        padding-left:20px;
        padding-right:40px;
    }
    .sousuo_left{
       margin-left: -30px;
       margin-top:10px;  
    }
    
    ul{
        padding: 0px;
        margin: 0px;
        list-style: none;
        float: left;
       margin-left:10px;
    }
    ul>li{
        margin-left:5px; 
        float: left;
        color: #ffffff;
        text-decoration: none;
    }
    ul>li>a{
        text-decoration: none;
        color:#ffffff;
        line-height: 45px;
        font-size: 12px;
    }
    .right_ul{
        padding: 0px;
        margin: 0px;
        list-style: none;
        float: left;
        margin-left:10px;
    }
    .right_ul>li{
        margin-left:12px; 
        float: left;
        color: #ffffff;
        text-decoration: none;
    }
    .right_ul>li>a{
        
        padding-right: 10px; 
    }
    .bottom_radio{
        position: fixed;
        bottom: 0px;
        background-color: #131e1e;
        height:75px;
        width:100%;
    }
    .topmusic{
       float: left;
       margin-top:30px;
       margin-left:15px;
    }
    .musicstop{
        float: left;
       margin-top:0x;
       margin-left:15px;   
    }
    .lastmusic{
        float: left;
        margin-top:30px;
       margin-left:15px;
    }
    .leftbar{
        width: 13%;
        height: 650px;
    }
    .leftbar_list{
        width:100%;
    }
    .leftbar_list>a{
        display: block;
        width:100%;
        height:36px;
        box-sizing: border-box;
        padding: 0 30px 0 20px;
        color:black;   
        text-decoration: none; 
        line-height: 36px;
    }
    .leftbar_list>a>img{
        float: left;
        width:18px;
        height:18px;
        margin-top:8px;
       padding-right: 10px;
    }
    .leftbar_list>a:hover{
        background: #e13228;
        color:#ffffff
    }
    
    </style>
<body>
    <!--
<div class="title">
        <img src="img/yyh_logo.png" alt="" class="title_logo">
        <input type="text" placeholder="输入歌曲，歌手，专辑名" class="title_search" >
        <ul>
            <li><a href="#">生僻字</a></li>
            <li><a href="#">沙漠五子D5</a></li>
            <li><a href="#">公子向北走</a></li>
        </ul>
        <ul style="font-size: 11px;">
            <li><a href="#">薛之谦</a></li>
            <li><a href="#">林俊杰</a></li>
            <li><a href="#">许嵩</a></li>
        </ul>
    </div>
    -->
    


    <div class="title">
        <!--以上是左边div-->
        <div class="title_left">
                <img src="img/yyh_logo.png" alt="" class="title_logo">
                <div class="title_left">
                    <input type="text" placeholder="输入歌曲，歌手，专辑名" class="title_search" >
                    <a href=""><img src="img/yyh_sousuo.png" alt="" class="sousuo_left"></a>   
                </div>
                <ul>
                    <li><a href="#">生僻字</a></li>
                    <li><a href="#">沙漠五子D5</a></li>
                    <li><a href="#">公子向北走</a></li>
                </ul>
                <ul style="font-size: 11px;">
                    <li><a href="#">薛之谦</a></li>
                    <li><a href="#">林俊杰</a></li>
                    <li><a href="#">许嵩</a></li>
                </ul>        
               
        </div>
        <!--以上是右边div-->
        <div class="title_right">
               <ul class="right_ul">
                   <li><a href="#">登录</a>|</li>
                   <li><a href="#">注册</a>|</li>
                   <li><a href="#">开通VIP</a>|</li>
                   <li><a href="#">皮肤</a>|</li>
                   <li><a href="#">反馈</a>|</li>
                   <li><a href="#">首页</a></li>
               </ul>
        </div>
    </div>
    <div>
        <div class="leftbar">
            <div class="leftbar_list">
               <a href="#">
                    <img src="img/liebiao.png" alt=""> 
                    <span>临时列表</span>           
               </a>
               <a href="#">
                    <img src="img/liebiao.png" alt=""> 
                    <span>我最常听</span>           
               </a>
               <a href="#">
                    <img src="img/xiazaijilu.png" alt=""> 
                    <span>下载历史</span>           
               </a>
               <a href="#">
                    <img src="img/yigouyinyue.png" alt=""> 
                    <span>已购音乐</span>           
               </a>
               <a href="#">
                    <img src="img/ziboyinyue.png" alt=""> 
                    <span>音乐直播</span>           
               </a>
            </div>
            <!--以上是临时列表-->
            <div class="my-list">
                <div><span>自建歌单</span><button>+</button></div>
                <hr width=90% height="2">
                <div><img src="img/xihuan.png" alt="">我喜欢的单曲</div>
            </div>
        </div>
        <div></div>
        <div></div>
        <div></div>

    </div>
    <!--以下是底部播放栏-->
    <div class="bottom_radio">
        <!--以上是未完成绑定的播放按钮-->
        <div class="paly">
            <div><img src="img/topmusic.png" alt="" class="topmusic"></div>
            <div><img src="img/musicstop.png" alt="" class="musicstop"></div>
            <div><img src="img/lastmusic.png" alt="" class="lastmusic"></div>        
        </div>
        <div></div>
        <div></div>
    </div>
</body>
</html> 
