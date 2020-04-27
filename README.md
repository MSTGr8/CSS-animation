
<!doctype html>
<html>
 <head> 
  <style>
    body{
      background-color:black;
      }
     #value{
      text-align:center;
      position:absolute;
      width :100%;
      height : 100px;
      }
      
       .anim1{
           text-align:center;
           font-size:100px;
           letter-spacing:3px;
           animation-name : text;
           animation-duration:10s;
           animation-iteration-count:infinite;
           animation-direction:alternate;
           animation-timing-function:linear;
           position:relative;
           animation-delay:12s;
           }
           @keyframes text{
             0%{
               color:#06F232;
               letter-spacing:20px;
               font-size:90px;
               text-shadow : 0 0 10px #00FF2F,
                             0 0 20px #00FF2F,
                             0 0 30px #00FF2F;
               }
             50%{
               text-shadow:0 0 40px #7107F4,
                           0 0 50px #7107F4,
                           0 0 60px #7107F4;
               color:#532A85; 
               letter-spacing:5px;
               font-size:75px;
               }
               100%{
                 text-shadow: 0 0 70px #0285F0,
                              0 0 80px #0285F0
                              0 0 90px #0285F0;
                 color: #3472A5;
                 letter-spacing:10px;
                 font-size:100px;
                 } 
                 }
                 #mm{
                   padding:425px;
                   text-align:center;
                   align-content:center;
                   }
                 .loader{
  color: #ffffff;
  font-size: 90px;
  text-indent: -9999em;
  overflow: hidden;
  width: 1em;
  height: 1em;
  border-radius: 50%;
  margin: 72px auto;
  position: relative;
  -webkit-transform: translateZ(0);
  -ms-transform: translateZ(0);
  transform: translateZ(0);
  -webkit-animation: load6 2s infinite ease, round 2s infinite ease;
  animation: load6 2s 3.5 ease, round 2s 3.5 ease;
}
@-webkit-keyframes load6 {
  0% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
  5%,
  95% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
  10%,
  59% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.087em -0.825em 0 -0.42em, -0.173em -0.812em 0 -0.44em, -0.256em -0.789em 0 -0.46em, -0.297em -0.775em 0 -0.477em;
  }
  20% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.338em -0.758em 0 -0.42em, -0.555em -0.617em 0 -0.44em, -0.671em -0.488em 0 -0.46em, -0.749em -0.34em 0 -0.477em;
  }
  38% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.377em -0.74em 0 -0.42em, -0.645em -0.522em 0 -0.44em, -0.775em -0.297em 0 -0.46em, -0.82em -0.09em 0 -0.477em;
  }
  100% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
}
@keyframes load6 {
  0% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
  5%,
  95% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
  10%,
  59% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.087em -0.825em 0 -0.42em, -0.173em -0.812em 0 -0.44em, -0.256em -0.789em 0 -0.46em, -0.297em -0.775em 0 -0.477em;
  }
  20% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.338em -0.758em 0 -0.42em, -0.555em -0.617em 0 -0.44em, -0.671em -0.488em 0 -0.46em, -0.749em -0.34em 0 -0.477em;
  }
  38% {
    box-shadow: 0 -0.83em 0 -0.4em, -0.377em -0.74em 0 -0.42em, -0.645em -0.522em 0 -0.44em, -0.775em -0.297em 0 -0.46em, -0.82em -0.09em 0 -0.477em;
  }
  100% {
    box-shadow: 0 -0.83em 0 -0.4em, 0 -0.83em 0 -0.42em, 0 -0.83em 0 -0.44em, 0 -0.83em 0 -0.46em, 0 -0.83em 0 -0.477em;
  }
}
@-webkit-keyframes round {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}
@keyframes round {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(360deg);
    transform: rotate(360deg);
  }
}


        .loader2 {
  border: 16px solid black; /* Light grey */
  border-top: 16px solid white;
  border-bottom: 16px solid white;
  border-radius: 50%;
  width: 150px;
  height: 150px;
  animation: spin2 0.5s linear 10;
  animation-delay:7s ;
  margin:25px;
  transform:translate(-50px,-50px);
}
        .mess{
          animation:l 7s linear 1;
          animation-delay:0s;
          }
          .aa{
            animation:l 5s linear 1;
            animation-delay:7s;
            }  
          @keyframes spin2{
          0% {
             box-shadow:0 0 50px #FFFFFF;
             transform : rotate(-360deg);}
          100% { 
            box-shadow:0 0 50px #FFFFFF;
            transform : rotate(0deg);}
          }
         @keyframes l{
           100%{
             color:white}
             }            
       </style> 
 </head> 
 <body> 
  <div id="value"> 
   <span class="anim1" id="e">first animation in css plzz give star</span> 
  </div> 
  <div id="mm"> 
   <div class="loader"></div> 
   <h1 class="mess">loading plz wait....</h1> 
   <h1 class="aa">checking system compatibility plz wait....</h1> 
   <div class="loader2"></div> 
   <div> 
   </div> 
  </div> 
 </body>
</html>
