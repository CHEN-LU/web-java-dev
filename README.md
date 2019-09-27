# web-java-dev
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PAGE</title>
</head>
<body>
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <title></title>
    <style type="text/css">
        *{
            margin:0;
            padding:0;
        }
        body{
            color: rgb(135, 72, 91);
        }
        header{
            height:60px;
            background-color: rgb(146, 74, 94);
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding-left: 10px;
            padding-right: 10px;
        }
        .nav{
            flex: 0 1 50%;
            list-style: none;
            display: flex;
        }
        .nav li{
            margin-left: 120px;
            margin-right: 120px;
            width:50px;
        }
        .user-info{
            padding-right: 20px;
        }
        .nav li a{
            text-decoration: none;
            color: #000000;
        }
        .nav li a:hover{
            color: rgb(181, 135, 161);
        }
        .search-wrap{
            height:60px;
            background-color:rgb(181, 135, 161);
            display: flex;
            align-items: center;
            padding-left: 2%;
            margin-bottom: 10px;
        }
        .input-box{
            width:400px;
            height: 40px;
            border:1px solid rgb(181, 135, 161);
            border-radius: 25px;
            margin-left:10px;
        }
        .container{
            width: 90%;
            margin: 0 auto;
            height: 100%;
            background-color: rgb(186, 105, 112);
            display: flex;
            padding: 5px 5px 5px 5px;
        }
        .left{
            flex:0 0 66%;
            height: 90%;
            background-color: rgb(192, 135, 154);
            padding: 10px 10px 10px 10px;
        }
        .right{
            flex: 0 0 30%;
            height: 100%;
            margin-left: 5px;
            background-color: rgb(249, 185, 158);
        }
        .row{
            display: flex;
            flex-wrap: wrap;
            padding: 5px 5px 5px 5px;
        }
        .column{
            flex: 0 0 18%;
            height:200px;
            background-color: rgb(192, 135, 154);
            border: 1px solid #333333;
            border-radius: 10px;
            margin: 5px 5px 5px 5px;
        }
        .column img{
            width:100%;height:100%;
            border-top-left-radius:5%;
            border-top-right-radius:5%;

        }
        .footer{
            height: 200px;
            background-color: #aaa;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .avatar{
            width:120px;
            height:150px;
            border-radius: 10px;
        }
        body{
            background-color: rgb(253, 200, 155);
        }
    </style>
</head>
<body>
<!--
    作者：1094508449@qq.com
    时间：2019-09-24
    描述：顶部导航
-->
<header>
    <div>
        <ul class="nav">
            <li>
                <a href="#">
                    首页
                </a>
            </li>
            <li>
                <a href="#">
                    小说
                </a>
            </li>
            <li>
                <a href="#">
                    新闻
                </a>
            </li>
            <li>
                <a href="#">
                    娱乐
                </a>
            </li>
            <li>
                <a href="#">
                    热点
                </a>
            </li>
        </ul>
    </div>

    <!--搜索区-->
    </div>
    <div class="user-info">
        <h3>READER</h3>
    </div>
</header>
<div class="search-wrap">
    <h2>阅读时光</h2>
    <input type="text" placeholder="输入要搜索的内容" class="input-box">
</div>
<div class="container">
    <div class="left">
        <h2>今日优选</h2>
        <hr>
        <div class="row">
            <div class="column"><img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1569343866414&di=4ca25eef475124b584d2d43fb51f4da9&imgtype=0&src=http%3A%2F%2Fhbimg.b0.upaiyun.com%2Ff1df8d8852166508799e47e0e2db16d7f90aa67810330-A67Y8R_fw658" class="avatar"></div>
            <div class="column"><img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1569343811284&di=c52ce7c67d711ef2a11eaaeb1f225826&imgtype=0&src=http%3A%2F%2Fwww.dzwww.com%2Fyule%2Fyy%2F201402%2FW020140224512486922134.jpg" class="avatar"></div>
            <div class="column"><img src="https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1569344377609&di=85b79ab3363664e3edd852eec8f4f5c4&imgtype=0&src=http%3A%2F%2Fimg3.doubanio.com%2Fview%2Fnote%2Fl%2Fpublic%2Fp53886093.jpg" class=".avatar"></div>
            <div class="column"><img src="https://cdn.motieimg.com/book/0001/14408/1.jpg" class=".avatar"></div>
            <div class="column"><img src="http://www.gxpprft.gov.cn/uploadfile/2018/0319/20180319095500462.jpg" class=".avatar"></div>
            <div class="column"><img src="http://img3.jarhu.com/goodimages/201206/23/di1340423765379.jpg" class=".avatar"></div>
            <div class="column"><img src="https://pic.pimg.tw/serenity/5d51cc94782365ab4f62c79969c9556f_n.jpg" class=".avatar"></div>
            <div class="column"><img src="https://gss0.baidu.com/9vo3dSag_xI4khGko9WTAnF6hhy/zhidao/pic/item/a8ec8a13632762d0762e3be5a1ec08fa513dc65c.jpg" class=".avatar"></div>
            <div class="column"><img src="http://www.kaiwind.com/whsy/201301/W020130130388025930054.jpg" class=".avatar"></div>
            <div class="column"><img src="https://i02piccdn.sogoucdn.com/54ca7f15aab3e3c8" class=".avatar"></div>

        </div>
    </div>
    <div class="right">
        <div class="conBigTitle">
            <h2>出版图书</h2>
            <p>
                <li ><h5><span>学习文献</span></h5></li>
                <li ><h5><span>励志成功</span></h5></li>
                <li ><h5><span>文学</span></h5></li>
                <li ><h5><span>经济管理</span></h5></li>
                <li ><h5><span>更多</span></h5></li>
            <li ><h5><span>古典小说推荐</span></h5></li>
            <li ><h5><span>现代小说推荐</span></h5></li>
            <li ><h5><span>出版书籍</span></h5></li>
            <li ><h5><span>今日限免</span></h5></li>
            <li ><h5><span>小说推荐排行榜</span></h5></li>
            </p>
        </div>
    </div>
</div>
<footer>
    <p></p>
</footer>
</body>
</html>

</body>
</html>
