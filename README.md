# supreme
My first repository
<html>    
<head>
    <meta charset-"UTF-8">
    
    <title>Login Simple</title>
    
    
    <style>
              .body{
                background-image: url("https://wanzi.image.alimmdn.com/images/583e4180066ed.jpg");
                positition: fixed;
                pverflow-y: scroll
                width: 100%
                top: -20px;
                right: -40px;
                bottom: -40px;
                width: auto;
                height: auto;
                background-size: cover;
                -webkit-filter: blur(0px);
        
                
        }
        
        /*body{text-align: center;}*/
        
        .head{
            position: absolute;
            top: calc(50% - 35px);
            left: calc(50% - 255px);
            
            
            
        }
        
        
        .header div{
            
            
            float: left;
            color: #fff;
            font-family: 'Exo',sans-serif;
            font-size: 40px;
            font-weight: 200;
            
        }
          
        .header div{
             position: absolute;
            top: calc(25% - 75px);
            left: calc(46.5% - 50px);
            height: 150px;
            width: 350px;
            padding: 10px;
            color: #fff !important;
        }
        
        

        .login{
            position: absolute;
            top: calc(50% - 75px);
            left: calc(47.5% - 50px);
            height: 150px;
            width: 350px;
            padding: 10px;
            
        }

        
        .login input [type=text]{
            width: 250px;
            height: 30px;
            background: transparent;
            border: 1px solid rgba(255,255,255,0.6);
            border-radius: 2px;
            color: #fff;
            font-family: 'Exo',sans-serif;
            font-size: 16px;
            font-weight: 400;
            padding: 4px;
        }
        
        .login input [type=password]{
            width: 250px;
            height: 30px;
            background: transparent;
            border: 1px solid #fff;
            border-radius: 2px;
            color: #767171;
            font-family: 'Exo', sans-serif;
            font-size: 16px;
            font-weight: 400;
            padding: 4px;
        }
    
        .login input[type=button]{
            width: 172.5px;
            height: 35px;
            background: transparent;/*#f42626*/;
            border: 1px solid #fff;
            cursor: pointer;
            border-radius: 2px;
            color: #fff;
            font-family: 'Exo',sans-serif;
            font-size: 16px;
            font-weight: 400;
            padding: 6px;
            margin-top: 10px;
        }
        
        .login input [type=button]:hover{
            opacity: 0.8;
        }
       
        .login input [type=button]:active{
            opacity: 0.6;
        }
       
       
        
        
        
        
          .login input [type=text]:focus{
            cutline: none;
            border: 1px.solid #f4ae26;
        }
        
        
        .login input [type=password]:focus{
            outline: none;
            border: 1px solid #f4ae26;
        }
        
        .login input [type=button]:focus{
            outline: none;
        }
       
        ::-webkit-input-placeholder{
            color: #f4ae26;
        }
        
         ::-moz-input-placeholder{
            color: #f4ae26;
        }
        
        
        </style>
    
    
    
    
</head>
    <body oncontextmenu="return true"  class="body">
    
    <div>
        <div class="grad"></div>
        <div class="header">
            
            <div>Hello<span>world!</span></div>
        </div>
        <br>
        <form name="login">
        <div class="login">
            <input type="text"placeholder="username" name="userid"><br>
            <input type="password" placeholder="password" name="pswrd"><br>
            <input type="button" onclick="check(this.form)" value="login"/>
            </div>
            </form>
            </div>
        <script language="javascript">
        function check(form)
            {
                if(form.userid.value=="hello"&& form.pswrd.value =="world")
                    {
                        window.open('http://www.w3school.com.cn/html/html_attributes.asp')
                    }
                else
                {
                     alert("The username and password you entered don't match");
                     form.reset();   
                }
            }
        </script>
    </body>
</html>
