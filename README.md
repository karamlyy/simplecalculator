<html>
    <head>
        <style>
            .container{margin:auto;}
            #answer{width:300px;
                    border-radius:10px;}
            input{font-size:30px;
                width:65px;
                height:55px;
                margin:5px;
                border:0px solid;
                border-radius:8px;
            background:rgb(230,230,230);
                outline:none;
            }
            .calc{background:rgb(109, 130, 197);
                padding:10px;
                border-radius:20px; display:inline-block ;}                
                input{
                box-shadow:5px 5px 5px rgb(138, 11, 11), -5px -5px 5px white;
            }
            input:hover{
                box-shadow:inset 5px 5px 5px rgb(138, 11, 11),inset -5px -5px 5px white;
            }
            #answer{
                box-shadow:inset 5px 5px 5px rgb(37, 4, 99),inset -5px -5px 5px white;
            }
            .calc{
                box-shadow:5px 5px 5px grey, -5px -5px 5px grey;
            }        
        </style>    
        <meta name="viewport" content="width=device-width" initial-scale="1.0">    
        <title>Karam's Calculator</title>        
    </head>
    <body style="background-image: url(back1.jpg);">
      <div calss="container" align="center">        
        <h1>CALCULATOR</h1>
            <form name="forms">
                    <div class="calc">
                        <input type="text" id="answer" name="screen">
                        <br>
                        <input type="button" value=" 1 " onclick="forms.screen.value+='1'">
                        <input type="button" value=" 2 " onclick="forms.screen.value+='2'">
                        <input type="button" value=" 3 " onclick="forms.screen.value+='3'">
                        <input type="button" value=" AC " onclick="forms.screen.value =''">
                                            <br>
                        <input type="button" value=" 4 " onclick="forms.screen.value+='4'">
                        <input type="button" value=" 5 " onclick="forms.screen.value+='5'">
                        <input type="button" value=" 6 " onclick="forms.screen.value+='6'">
                        <input type="button" value=" + " onclick="forms.screen.value+='+'">
                                            <br>
                        <input type="button" value=" 7 " onclick="forms.screen.value+='7'">
                        <input type="button" value=" 8 " onclick="forms.screen.value+='8'">
                        <input type="button" value=" 9 " onclick="forms.screen.value+='9'">
                        <input type="button" value=" - " onclick="forms.screen.value+='-'">
                                            <br>                                            
                        <input type="button" value=" . " onclick="forms.screen.value+='.'">
                        <input type="button" value=" 0 " onclick="forms.screen.value+='0'">
                        <input type="button" value=" = " onclick="forms.screen.value = eval(forms.screen.value)">
                        <input type="button" value=" * " onclick="forms.screen.value+='*'">
                                            <br>                                            
                        <input type="button" value=" ( " onclick="forms.screen.value+='('">
                        <input type="button" value=" ) " onclick="forms.screen.value+=')'">
                        <input type="button" value=" % " onclick="forms.screen.value+='%'">
                        <input type="button" value=" / " onclick="forms.screen.value+='/'">
                   <br>                   
                     </div>                
            </form>            
        </div><br><br><br><br><br><br><br><br><br><br><br>
        <div style="font-size: 20px; color:rgb(0, 0, 0); font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif; font-weight: bold;">Created by Karam Afandi</div>
    <script async src="https://drv.tw/inc/wd.js"></script></body> 
