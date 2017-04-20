<html>
<meta charset="utf-8">
<head>
<title>ife百度前端学院</title>
<link rel="stylesheet" type="text/css" href="work5.css">
<style type="text/css">
   body{
	font-family: 'microsoft yahei';
margin: 0;
padding: 0;
width: 85%;
display: block;
background: black;
margin: 0 auto;
}
.beijing1{

	display: block;
	width: 85%;
	margin: 0 auto;
	margin-top: 2em;
background: rgb(222,222,222);
margin-bottom: 2em;
position: absolute;
}
h3{
	color:grey;
	line-height: 0.5em;
}
 p label#zuozhe{
	font-size: 0.8em;
	color:grey;
	opacity: 70%;
	font-weight: bold;
}
ul{
	text-decoration: none;
	
}
ul li{
 list-style: none;
	padding-left: -1.5em;
    
}
 .first-part{
 	
    float: left;
    width: 50%;
 	margin: 1em 1.5em;
	background:white;
	border-radius: 0.1em;
	padding: 1em 2em;
	margin-top: 2em;
	box-shadow:  1px 1px 1px #888888;

}
#lastpart{
	transform: scale(0.86);
	position:fixed;    /*距顶部位置*/
	max-width: 30%; 
	margin-left: 50%;
	top:-1em;   /*距顶部位置*/
	float: right;
	margin-bottom: 2em;
	  /*ie6下样式，加下划线表示只针对ie6 的hack */
  _position:absolute;/* 把导航栏位置定义为绝对位置  关键*/
  _top:expression(documentElement.scrollTop + "px"); /* 把导航栏位置放在浏览器垂直滚动条的顶端  关键 */
  z-index:9999; /* 让导航栏浮在网页的高层位置，遇到flash和图片时候也能始终保持最外层 */
  text-align:left;
}
.lefttop{
	display: block;
    background: #ccc;
    width: 5px;
    float: left;
    height: 45px;
    z-index: 9999;


}
#tupian{
color:black;}
.HaoKan{
	margin: 0;
	padding: 0;
	border:1px solid rgb(222,222,222);
	display: table;
	width: 12%;
	margin: 0 auto 1em 2em;
}
.HaoKan img{
  display: table;
  margin: 0 auto 1em;
	width: 80%;
}

.haokan p{
	padding: -0.5em 0 0 0;
 text-align: center;
	font-size: 0.8em;
}
#button{
	color:white;
	background: rgb(51,85,208);
	width: 80%;
	text-align: center;
	border-radius: 0.6em;
	padding: 0.5em;
	margin: auto;
	margin-left: 9%;

}
#break{
	text-indent: 2em;
}
.buttom{
	background: rgb(204,204,204);
}
a:hover,a:linked,a:visited{
	color:black;
}
.lastpart{
	display: table;
	margin: 0 auto;
}
table{
	border:1px;
	width: 98%;
border-collapse: collapse;
line-height: 2em;
height: 2em;


}
table th,td{
	padding-left: 0.5em;
}
i{

}
.wenben{

	margin: 0;
	padding: 0;
	display: inline-block;
	width: 20em;
	height: 30px;

}
.wenan{
margin: 0 auto;

	text-align: right;
	overflow: hidden;

}
.left{
	text-align: right;
	width: 9em;
	font-size:1em;
  margin-right: 1em;

}
  .choice{
  	display: inline-block;
    margin-left: 1em; 
  }
.choice .radio{  
    position: relative;  
    display: inline-block;   
    padding-left: 2em;
    padding-top: -6.5em;
    font-size: 0.8em;
    cursor: pointer;  
}  
.choice .radio input{  
    position: absolute;  
    left: -9999px;  
}  
.choice .radio i{  

    display: block;  
    position: absolute;  
    top: 6px;  
    left: 0;  
    width: 15px;  
    height: 15px;  
    outline: 0;  
    border: 1px solid #379CFA;  
    background: white;  
    border-radius: 50%;  
    transition: border-color .3s  
    -webkit-transition: border-color .3s;  
}  
.choice .radio input:checked+i{  
    background:#379CFA;;   /*i标签被选中时*/

}  
.choice .radio input+i:after{  
    position: absolute;  
    content: '';  
    top: 5.5px;     /*i标签之后的内容*/
    left: 5.5px;  
    width: 4px;  
    height: 4px;  
    border-radius: 50%;  
    background-color: white;  /*圆心*/
    opacity: 0;  
    transition: opacity .1s;  
    -webkit-transition: opacity .1s;  
}  
.choice .radio input:checked+i:after{  
    opacity: 1;  
    background: white;
}  
.teshu{
	text-align: right;
	
}
.title{
	
	background: black;
	text-align: left;
	color:white;
	border-collapse: none;

}
textarea{
	float: right;
	display: inline-block;
	width: 40%;
	overflow: hidden;
	height: 300px;
	margin-left: -5em;
	border: 1px solid #ccc;

}
.celan{
	position: absolute;
	top: 2.5em;
   margin-left: 1em;
	color: black;
	margin-bottom: 1em;
}
.tishi{
	margin-left: 35%;
	font-size: 11px;
	color:rgb(222,222,222);
}
input{
	border: 1px solid #ccc;
	display: inline-block;
	margin-bottom: 2.5em;

}
select{
	text-align: center;
}
.aihao{
	display: block;
	margin-top: 1.5em;
}
option{
	display: block;
	width:2.5em;
	text-align: center;
}
.right{
	text-align:left;
}
 p>span{
 	display: inline-block;
 	  text-align: right;
            margin-right: 10px;
 }
.danxuan{
	text-align: left;
	width: 70em;

}
textarea{
	display:block;
	width: 100%;
	height: 10em;
	  resize: vertical;
	margin-bottom: 2em;

}
.lastpart .topleft{
	margin-top: 4em;
	text-align: right;
	width: 9em;
	font-size:1em;
  margin-right: 1em;
}
.danxuan{
	display:inline;
	float: left;

}
.fuxuan{
	text-align: left;
}
 p input[type='radio'],p input[type='checkbox']{
 	vertical-align: middle;
 	margin-right: 5px;
 }
 .bottom{
    margin-left: 46%;
    margin-bottom: 7%;
 }
</style>
<body>
<div class="beijing1">
       <div class='first-part'>
     <h2>文章一级标题</h2>
     <h3>文章二级标题</h3>
     <p id='zuozhe'>文章作者  文章发表时间</p>

     <p id="break">这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个 很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落<a href="http://ife.baidu.com" color=blue>这有一个段落http://ife.baidu.com</a>这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落</p>
     <img src="C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png">
  
     <p id="break">这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落<a href="http://ife.baidu.com" color=blue>这有一个段落http://ife.baidu.com</a>这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落</p>
   

   </div>
      <div class='first-part'>
     <h2>另一篇文章一级标题</h2>
     <h3>文章二级标题</h3>
     <p id='zuozhe'>文章作者  文章发表时间</p>

     <p id="break">这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落<a href="http://ife.baidu.com" color=blue>这有一个段落http://ife.baidu.com</a>这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落这是一个很长的段落</p>
     <ul>
     <li>列表项目一</li>
     <li>列表项目二</li>
     <li>列表项目三</li>
     </ul>
  <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
  
     
     </div>
       <div class='first-part'>
   
   <h2><label id='tupian'>图片</label></h2>
   <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
  
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
  
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
  
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
  <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
  <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
  
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
       </div>
  

     <div class=HaoKan> 
       <p>好看的图片</p>
        <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
   </div>
     <div class=HaoKan> 
       <p>好看的图片</p>
       <img src=file:///C:/Users/lqagx/Desktop/%E6%88%AA%E5%9B%BE233.png>
 
   </div>
      </div>
       <div class='first-part'>
<h2>最后一篇文章 一级标题</h2>
 
    <h3>文章二级标题</h3>
    <p>文章作者  文章发表时间</p>
    <ol>
    <li>排名1</li>
      <li>排名2</li>
        <li>排名3</li>
          </ol>
         <p>下面是一个表格，给表格加了一个border='1'好让你看出来这是一个表格</p>
         <table>
         	<tr class="title">
         	<th>表头</th>
         	<th>表头</th>
         	<th>表头</th>
         	</tr>
         		<tr>
         		<td>表内容单元格</td>
         		<td>表内容单元格</td>
         		<td><a href="">操作</a></td>
         		</tr>
         		<tr>
         		<td>表内容单元格</td>
         		<td>表内容单元格</td>
         		<td><a href="">操作</a></td>
         		</tr>
         		<tr>
         		<td>表内容单元格</td>
         		<td>表内容单元格</td>
         		<td><a href="">操作</a></td>
         		</tr>
         		<tr>
         		<td>表内容单元格</td>
         		<td>表内容单元格</td>
         		<td><a href="">操作</a></td>
         		</tr>
         		<tr class="buttom">
         		<td>总计</td>
         		<td colspan="2">1000</td>
         	
         		</tr>
         </table>
         </div>
            <div class='first-part' id='lastpart'>
         <h3><i class="lefttop"></i><span class='celan'>这以后是一个侧栏，这是侧栏的标题</span></h3>
     <div  class="lastpart">
         <p>
         <span class="topleft">请输入邮箱地址</span>

         <input type="text" class="wenben" name="文本输入框" placeholder ="这是一个文本输入框" ></input>
       </p>
       <p class="tishi">
         邮箱地址请按格式输入
         </p>
        <p> 
          <span class="left">请输入邮箱密码</span><input type="passport" class="wenben" name="文本输入框" placeholder ="这是一个文本输入框" ></input>
         </p>
         <p>    
          <span class="left">请重复输入邮箱密码</span>
      <input type="passport" class="wenben" name="文本输入框" placeholder="这是一个文本输入框" >
        </p>
      
           <span class='tishi'>密码请为6-18位数字</span>
   <p> 
           <span class="left">性别</span><span class="choice"><label class="radio">男<input type="radio" name="radio" ><i></i></label>
           <label class="radio">女<input type="radio" name="radio" checked><i></i></label>  </span>

           <p>
           <span class="left"> 城市</span>
           
      <select><option>北京</option><option>南京</option>
       </select> 
    
      </p>
      <p>
      <span class="left">爱好</span>
      <label>
       <i class="checkbox"><input type="checkbox" name=""></i>运动</input></label>
      <label>
      <i class="checkbox"><input type="checkbox" name="" ></i>艺术</input></label>
       <i class="checkbox"><input type="checkbox" name=""></i>科学<br/></input>
      </span>
      </p>
      <p>
      <span class="left">个人描述</span>
      <label class="right">
      <textarea>这是一个多行输入框，输入您的个人描述</textarea>
    </label>
 
      <input type="button" name="" value="确认提交" id="button">
      <p class="bottom">版权所有&copy;</p>
 </div>
      </div>
      </div>
      </body>

</html>
