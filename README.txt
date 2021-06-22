Dimension by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Dimension, a fun little one-pager with modal-ized (is that a word?) "pages"
and a cool depth effect (click on a menu item to see what I mean). Simple, fully
responsive, and kitted out with all the usual pre-styled elements you'd expect.
Hope you dig it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>用户注册页面</title>
    <style type="textćs">
        .img{
            float:left;
        }
        form{
            width:450px;
            float:left;
        }
        form>:first-child~*{
            margin-left:100px ;
        }
        .img img{
            height:517px;
        }
        .txt,.sure,.sel{
            margin-top: 10px;
            display: block;
            font-size: 18px;
        }
        .txt input,.syre input{
            width:250px;
            height:35px;
        }
        .sure{
            margin-left: -35px;
        }
        .cont>form>div{
            font-size: 18px;
            margin-top: 20px;
        }
        .cont>form>div>label{
            margin-left: 20px;
        }
        .birth select{
            padding:5px 5px 5px 0;
        }
        .addr{
            margin-left: -18px;
        }
        .addr select{
            padding:5px 23px 5px 0;
        }
        p{
            color:#909090;
            font-size: 12px;
            margin:10px 0 0 50px;
        }
        [type="button"]{
            background: #00ff00;
            color:#fff;
            border:none;
            margin:20px 50px;
            font-size: 24px;
            padding:10px 78px;
        }
        .sel input{
            width:15px;
            height:15px;
            margin:auto 10px auto 0;
        }
        <link href="style.css" type="textćs" rel="stylesheet">
        <×yle>
</head>
<body>
       <div class="cont">
       <div class="img">
           <img src="5-1 图片.jpg">
       </div>
         <form>
             <h1>欢迎注册</h1>
             <label class="txt">昵称:<input type="text"></label>
             <label class="txt">密码:<input type="password"></label>
             <label class="sure">确认密码:<input type="password"></label>
             <div>性别:<label><input type="radio"name="sex">男</label>
                        <label><input type="radio"name="sex">女</label></div>
             <div class="birth">生日:
                 <select><option>公历</option><lect>
                 <select><option>1996年</option><lect>
                 <select><option>月</option><lect>
                 <select><option>日</option><lect>
             </div>
             <div class="addr">所在地：
                 <select><option>中国</option><lect>
                 <select><option>吉林</option><lect>
                 <select><option>长春</option><lect>
             </div>
             <label class="sure">手机号码：<input type="text"></label>
             <p>可通过该手机号码快速找回密码</p>
             <input type="button" value="立即注册">
             <label class="sel"><input type="checkbox">我已阅读并同意服务条款和隐私政策</label>
         </form>
   </div>
</body>
<cml>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>申请个人讲师</title>
    <style type="textćs">
        .cont{
            margin:0 auto;
            padding-top: 210px;
            width:1050px;
            background: url("5-2bj.jpg") no-repeat;
        }
        [type="text"]{
            margin-left: 10px;
            height:30px;
            width:230;
        }
        label{
            display:block;
            margin:10px 70px;
        }
        .cont>div>:first-child{
            color:white;
            height:40px;
            line-height: 40px;
            padding-left: 50px;
            background: #6dc5ef;
        }
        <×yle>
</head>
<body>
     <div class="cont">
         <div>
             <p>申请个人讲师</p>
             <label><input type="checkbox">为企业宣传</label>
             <label><input type="checkbox">上传文档至网站</label>
             <label><input type="checkbox">个人需要</label>
             <label><input type="checkbox">团购个人会员</label>
             <label><input type="checkbox">扩充自身网站内容</label>
             <label><input type="checkbox">借助明日科技技术，搭建企业内部平台</label>
         </div>
         <div>
             <p>您所在的单位名称</p>
             <label>请输入你的回答<input type="text"></label>
         </div>
         <div>
             <p>您所在的单位的规模</p>
             <label><input type="radio" name="guimo">100人以内</label>
             <label><input type="radio" name="guimo">100~500人</label>
             <label><input type="radio" name="guimo">501~1000人</label>
             <label><input type="radio" name="guimo">1001~5000人</label>
             <label><input type="radio" name="guimo">5000人以上</label>
         </div>
         <div>
             <p>你是机构的负责任吗？</p>
             <label><input type="radio" name="buy">是</label>
             <label><input type="radio" name="buy">不是</label>
         </div>
     </div>
</body>
<cml>
redits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Responsive Tools (github.com/ajlkn/responsive-tools)
