<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body class="seven" background="https://img1.goodfon.com/wallpaper/nbig/2/18/minimalism-outside-banka-fon.jpg" >
    <p1 class="one"><b>LOGIN PAGE</b></p1><br>
    <label class="two" ><b>USERNAME:-</b></label>
    <input id="uname" type="text" class="three" placeholder="enter your username"><br>
    <lable class="four" ><b>PASSWORD:-</b></lable>
    <input class="five" type="text" id="pass"placeholder="enter password"><br>
   
</body>

<script>
    function cond(){
        var a=document.getElementById("uname").value;
        var b=document.getElementById("pass").value;
        if (a=="21mis7127" && b=="1234"){
            location.href="https://bonilokesh.github.io/1/"
        }

        else{
            document.write("INVALID USERNAME AND PASSWORD");
        }
    }
</script>
<button class="six" type="button" onclick="cond()" >login</button>
</html>
<style>
    .one{
        position: absolute;
        left: 45%;
        font-size: xx-large;
        bottom: 90%;

    }
</style>
<style>
    .two{
        position: absolute;
        left: 40%;
        font-size: large;
        bottom: 85%;
    }
</style>
<style>
    .three{
        position: absolute;
        left:48%;
        font-size: large;
        bottom: 85%;
        background-color: aliceblue;
    }
</style>
<style>
    .four{
        position: absolute;
        left: 40%;
        font-size: large;
        bottom: 80%;
    }
</style>
<style>
    .five{
        position: absolute;
        left: 48%;
        font-size: large;
        bottom: 80%;
        background-color: aliceblue;
    }
</style>
<style>
    .six{
        position: absolute;
        left: 40%;
        font-size: large;
        bottom: 75%;
    }
</style>
<style>
    .seven{
        background-attachment: fixed;
        background-repeat: no-repeat;
        background-size: 100% 100%;
        

    }
</style>
