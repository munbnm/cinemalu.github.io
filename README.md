
<html lang="en">
    <style>
        div{
            width: 500px;
            height: 500px;
            background-repeat: no-repeat;
            border: 2px solid blue;
            background-size: 500px 500px; 
        }
    </style>

   
<body  >
    <a href="str.htm">html</a>
    <div > 
        <button onclick="q()"> click </button></div>
    <script>
       a=[];
       a[0]='./avengers.jfif'
       a[1]='./i mano.jfif'
       a[2]='./robo 2.0.jfif'
       document.write(a);
       function q() {
        
        c=Math.trunc(Math.random()*3);
        
        if(c==0){
        document.querySelector("div").style.backgroundImage="url('./avengers.jfif')";
          }

       
       else if(c==1){
        document.querySelector("div").style.backgroundImage="url('./i mano.jfif')";
        }
        
       
       else if(c==2){
        document.querySelector("div").style.backgroundImage="url('./robo 2.0.jfif')";
       }
        
       }
      
    </script>
    
</body>
</html>
