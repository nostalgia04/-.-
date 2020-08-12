
## 1.文件内容为冯思晗同学初学<label style="font-size:40px;color:red">css</label>尝试设计的一些样式。
## 2.主要内容为一种按钮的样式，包括大小颜色边框选择器等等
### 代码具体如下
``` css
.login-button {	width: 200px;
                                                                 height: 65px; 
                                                	border-width: 0px;
                                                   	border-radius: 15px;
                                                  	background: #00BFFF; 
                                                                font-family:SimSun;
                                                                cursor: pointer;	
                                                                outline: none; 
        	                                                
      	                                                color: white;
                                                   	font-size: 45px;  }
.login-button:hover { 	background: #5599FF;}
                         
.footer{                    width:500px;
                                                             height:55px;
                                                             float: middle;
                                                             font-size: 35px;
                                                             font-family:SimSun;
                                                             position:relative;
                                                             top:335px;
                                                             left:260px;                                  }
.button{               width: 500px;
                                                             height: 200px;
                                                             position:relative;
                                                             left:270px;
                                                              display:inline-block;
    width:200;
    padding:0 20px;
    height:40px;line-height:30px;
    background:white;
    border-radius:30px;
    text-align: center;
    color:#00BFFF;
    position:absolute;
    top:2px;
    opacity:0;
    -webkit-transition:all 1s;
    -webkit-transform:translateX(-40px);

 }
.button button:hover + span{-webkit-transform:translateY(80px);
    opacity:1;}
.button span{
   
}
```
### 实现的大致效果如下
![图片加载失败，请重试](https://w.wallhaven.cc/full/n6/wallhaven-n6mkl7.jpg "2333")
##### *如想使用，无需本人授权，可自行使用*。
