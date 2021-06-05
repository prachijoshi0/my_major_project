<!DOCTYPE html>
<html lang="en">
<head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Major Project</title>
        
          <link rel="preconnect" href="https://fonts.gstatic.com">
          <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,500;0,800;1,600&display=swap" rel="stylesheet">
          <link rel="preconnect" href="https://fonts.gstatic.com">
          <link rel="preconnect" href="https://fonts.gstatic.com">

          <link rel="stylesheet" href="website.css">
          <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="majorProject_2.css">
    <script src="https://kit.fontawesome.com/2ae0ed79c7.js" crossorigin="anonymous"></script>
      
          <style>
     html {
          scroll-behavior: smooth;
      }
      body{
          margin: 0;
          padding: 0;
          font-family:Poppins;
      }
   
       .h{
          font-size: 40px;
          text-align: center;
          text-decoration: underline; 
          display: block;
          font-family: 'Poppins';
          margin-bottom: 3px;
      }
       #prt{
               font-size: 50px;
               font-weight: 900;
                
      }  
      p{
          font-size: 24px;
        font-weight: lighter;
  
      } 
      .navbar{
          position: fixed;
          display: flex;
          justify-content: center;
          align-items: center;
          flex-direction: row;
          flex-wrap: wrap;
          background:transparent;
          width: 100%;
          height: 70px;
          z-index: 1;
          padding-bottom: 20px;
          
      }
      .navbar.scrolled{
          background-color: blue !important;
      }
      .hire{
          padding: 10px 20px;
          border-radius: 5px;
          cursor: pointer;
          margin-left: 82px;
          margin-top: 80px;
          background-color: rgb(252, 4, 4);
          color:whitesmoke;
          border-color:  whitesmoke;
          border-width: 3px;
      }
      .hire:hover{
          background-color: white;
          color: rgb(0, 0, 0);
          border-color: rgb(209, 196, 196);
        border-width: 5px;
      }
      .nav{
          display: flex;
        position: sticky;
          justify-content: right;
          list-style: none;
          margin-right: 5%;
          margin-left: 10%;
      
      }
      .logo {
          flex: 1 1 auto;
          margin-left:7%;
          text-transform: uppercase;
          letter-spacing: 1px;     
      }
      .lm{
          font-size: 15px;
      }
      img{
          width: 20%;
      }
      a{
          margin: 25px;
          color:white;
          text-decoration: none;
          text-transform: uppercase;
      }
      a:hover{
          color: rgb(250, 38, 0);
      }
      .banner-area{
          position: relative;
          background-image: url(https://d2v9y0dukr6mq2.cloudfront.net/video/thumbnail/itCjTBE/dark-blue-tech-circuit-board-technology-animated-background-video-graphic-design-ultra-hd-4k-3840x2160_sgelpuywg_thumbnail-full05.png); 
          width: 100%;
          height: 100vh;
          background-repeat: no-repeat;
          background-size: cover;
          top: 0;
            opacity: 9;
      }
      .spa2{
          padding: 240px;
          display: flex;
             box-sizing: border-box;
          flex-direction: column;
          justify-content: space-around;
          height: 500px;
          padding-top: 280px;
          padding-left: 100px;
          color: white;
      }
      .prtfo{
          color: red;
      }
      
      .u{
      
          font-size: 35px;
          margin: 0;
          font-weight: inherit;
      }
      .josh{
          font-size: 60px;
          font-weight: bold;
      }
 
      .example12{
          color: red;
      }
      .about-area, .port-area, .service-area, .contact-area{
          position: relative;
          display: flex;
          justify-content: space-around;
          align-items: center;
          flex-wrap: wrap;
          flex-direction: row;
          width: 100%;
          height: 700px;
      }
      .text-part{
          width: 80%;
          height: 80%;
      
      }        
      .about-area{
          background-color: #fefefe;
          width: 100%;
          height: 100vh;
          background-repeat: no-repeat;
          background-size: cover;
      }
       
      .service-area{
          background-color: #fefefe;
      }
      
      .down{
                background-color: rgb(237, 41, 41);
                border: 2px solid #8e44ad;
                border-radius: 8px;
                color: #fff;
                display: block;
                font-family: inherit;
                font-size: 18px;
                padding: 13px 45px;
                margin-top: 20px;
                font-weight: bold;
                cursor: pointer;
      }
      .down:hover{
          background-color: white;
          color: black;
          border-color: gainsboro;
          border-width: 10px;
      }
      .image{
          
          display: flex;
          width: 30%;
       
      }
      img{
         width: 500px;
         height: 400px;
         margin-right: 100px;
    
        display: flex;
        justify-content: right;
        border: 5px solid black;
      }
      img:hover{
          border: 20px solid grey;
      }
      #copr{
          font-size: 25px;
          margin-bottom: 0;
      }
      #i{
          font-size: 20px;
          font-weight: lighter;
          justify-content: center;
          line-height: 30px;
          margin-left: 80px;
          text-align: justify;
          
      }
      #flex{
          display:inline-flex;
          margin: 0;
      }
      .example{
          margin: 0;
          font-family: 'Poppins';
          color: rgb(240, 53, 53);
          font-weight: bold;
      }
      .spa{
          display:block;
          color: rgb(0, 0, 0);
          font-weight: 500;
          font-size: 30px;
          padding-bottom: 10px;
          margin-top: 0;
      }
      
      .cig{
            color: rgb(82, 1, 1);
            font-weight: 900;
      }
      .colornavbar {
          background-color: blue;
      }
      #c{
          color: red;
          padding: 25px;
          font-size:35px;
          padding-bottom: 0;
      }
      #n{
          
          color: red;
          padding: 25px;
          font-size:35px;
          padding-bottom: 0;
      }
      #e{
          
          color: red;
          padding:25px;
          font-size:35px;
          padding-bottom: 0;
      }
      .nam{
          font-size: 20px;
          padding-bottom: 0;
      }
      #con{
          padding-left:74px;
         
      }
      #con1{
          padding-left: 72px;
      }
      #con2{
          padding-left: 85px;
      }
      #co{
          float: left;
          width: 55%;
          padding-right: 100px;
      }
      input[type=text], [type=email]{
              padding: 5px 55px 10px 20px;
              margin: 20px;
              margin-bottom: 5px;
              border-radius: 5px;
              border-color: whitesmoke;
            
              
      }
      input:focus{
               outline: 0;
               border-color: rgb(255, 227, 227);
               border-width: 5px;
      }
      textarea{
          margin: 20px;
          margin-top: 8px;
          width: 150px;
          padding-bottom: 100px;
          padding-left: 10px;
          padding-right: 90px;
          border-radius: 5px;
         overflow: hidden;
         border-radius: 5px;
        
      }
      textarea:focus{
  
        outline: 0;
        border-color: rgb(209, 196, 196);
        border-width: 5px;

}
      footer{
          display: block;
          text-align: center;
          margin-top: 80px;
          margin-bottom: 50px;
          background-color: #000;
          color: white;
          padding: 15px;
          width: 100%;
         
      
      }
      #hr1{
          color: red ;
      }
      hr{
          color: red;
      }
      #prachi{
          color: red;
      }
    
    .who {
        display: flex;
        flex-direction: row;
        margin-top: 0;
        color: rgb(213, 11, 11);
      }
      .who:before, .who:after{
        content: "";
        border-bottom: 1px solid; 
        margin: auto;
        border: 3px solid black;
       border-radius: 5px;  
        flex: 0.06;
        
      }
      .who:before {
        margin-right: 4px;
    
      }
      .who:after {
        margin-left: 4px;
      }
      .skills{
           
           display: inline-flex; 
           float: left;
           margin: 0;
         
      }
      .ski{  
          text-align: left; 
      
      }
      .l{
          list-style-type: none;
          padding: 5PX 0;
          position: relative;
      }
      .space1{
          padding:0 184px;
        
      }
      .space2{
        padding:0 190px;
      }
      .space3{

        padding-left: 330px;
      }
      .space4{
        padding-left: 376px;
      }
      .space5{
        padding-left:  354px;
      }
      .space6{
        padding-left:  350px;
      }
      .sky{
          padding-top: 50px;
          padding-left:100px;
      
      }
      .sp{
          padding:100px
      }
      
      #leftBottom{
          bottom: 200px;
          left: 1250px;
    }
      .botom{
                 position: fixed;
                bottom: -80px;
                padding: 20px 20px; 
                background-color: rgb(248, 58, 58);
                color: #fefefe;
                border-radius: 10px;
                border-color: #fefefe;
      }
      .btn{
                padding: 10px 43px;
                margin: 10px 50px;
                border-radius: 5px;
                border-color:#fefefe;
               background-color:#fefefe; 
              color: black;
              box-shadow: 0 0 3px;
              cursor: pointer;
              outline: ghostwhite;
      }
      .btn:hover{
          background-color: rgba(0, 0, 0, 0.248);
          color: whitesmoke;
      }
      .black{
                padding: 12px 18px;
                background-color:  black;
                color: white;
                border-color: 5px solid black;
                cursor: pointer;
                border-radius: 5px;
                font-weight: 900;
                margin: 0;
                left: 0;
      }
      .black:hover{
          background-color: cyan;
          color: black;
          border-color:  whitesmoke;
          border-width: 10px;
      }

    #hr1{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
     #hr1:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
         position: relative;
        top: -2px; 
        width: 60%;
        overflow: hidden;
        /* z-index: 1; */
    } 
 
    #hr2{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
    #hr2:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
        position: absolute;
        top: -2px;
        width: 40%;
        /* z-index: 1; */
    }
    #hr3{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
    #hr3:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
        position: absolute;
        top: -2px;
        width: 70%;
       
    }
    #hr4{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
    #hr4:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
        position: absolute;
        top: -2px;
        width: 50%;

    }
    #hr5{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
    #hr5:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
        position: absolute;
        top: -2px;
        width: 90%;
        
    }
    #hr6{
        background-color:rgba(0, 0, 0, 0.248);
        border: none;
        display: block;
        height: 4px;
        overflow: visible;
        position: relative;
        width: 100%;
    }
    #hr6:before{
        background-color:lightgreen;
        content: '';
        display: block;
        height: 8px;
        left: 0;
        position: absolute;
        top: -2px;
        width: 70%;
        
    }
    #top{
        background-color: red;
        padding: 15px;
     
        color: white;
        position: fixed;
        bottom: 160px;
        right: 15px;
        height: 35px;
        width: 35px;
        line-height: 35px;
        text-align: center;
        cursor: pointer;
        border-radius: 5px; 
        z-index: 5;
        border-width: 5px;
        opacity: 10;
        transition: opacity .3s ease-in-out;
       
    }
    #top:hover{
        background: #0ddaa5;
        border-color:  whitesmoke;
        border-width: 10px;
    }

   </style>
</head>
<body>
    <script
    src="https://code.jquery.com/jquery-3.6.0.min.js"
    integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
    crossorigin="anonymous"></script>

          <nav class="navbar navbar-expand-md navbar-default  bg-dark fixed-top">        

          <div class="navbar">
                    <a class="logo" id="prt" href="#"> Portfo<span class="prtfo">lio</span>.</a>
                    <ul class="nav">
                <li><a href="#home" class="lm">Home</a></li>
                <li><a href="#about" class="lm">About</a></li>
                <li><a href="#portfolio" class="lm">Skills</a></li>
                <li><a href="#contact" class="lm">Contact</a></li>

                <li><a href="signin.html" target="_blank">Logout</a></li>
              
                </ul>
                </div>
          </nav>  
               
          <i id="top" class="fas fa-chevron-up"></i> 
           
       
              
            <section class="banner-area" id="home">
                    <span class="spa2"
                    <span class="spa1"><h1 class="u">                   
    Hello, my name is <br>
    <span class="josh">Prachi Joshi<br></span>
      And I'm a <span class="example12"></span></h1>
    </span>
</span>
<a href="mailto: prachijoshi0610@gmail.com"><button class="hire">HIre me</button></a>
                        
                </section>
                 
                <section class="about-area" id="about">
                    <div class="text-part">
                        <h1 class="h">
                About me</h1>
             <h3 class="who">who I am</h3>
                <div id="flex">

                    <div class="image">
                              <img src="prachi.jpg" alt="image" title="Prachi Joshi">
                    </div>
                <div class="imag" id="i">
                    <span class="spa">I am Prachi Joshi and I'm <span class="example"></span></span>
                    
                     <span class="cig">I am student of B.SC(hons) Computer Science</span> of Mata Sundri College For Women of Delhi University, my hobbies are writing, sketching, art and craft, and listening music, I am an extrovert as well as an introvert type of person, I can adapt accourding to my enviornment, my this ablity somehow makes me an addaptive person, I belive there's is nothing which I can't do and this also makes me optimestic as I always try my best to complete my each and every task and I am also an analytical person, I like to analyse things around me, this gives me a sense of thinking in many different ways.
                       
                <a href="ne2w.html" target="_blank" class="ddd">
                    <button class="down">Download CV</button>
          </a></div>
                </div>
                    </div>
              
                
                </section>
                
                <section class="port-area" id="portfolio">
                    <div class="text-part">
                        <h1 class="h">
                My Skills</h1>
                <h3 class="who">what I know</h3>
                <div class="skills">
                 
                    <div class="ski">
                        <h3>My creative skills and experience</h3>
                        <h4>-->Constatnly learning and improving
                            <br>
                        --> Computer programming and learning
                        
                    <ol>   <li>C++</li>
                            <li>Python</li>
                            <li>CoreJava</li>
                     </ol>
                    -->Database 
                        <ol>
                            <Li>SQL server</Li>
                            <li>MYSQl</li>
                        </ol>
                         <h4>
                           -->Constantly learning and improving
                         <br>
                            -->Problem solving and thinking
                         </h4>
                         <a href="#home"><button type="click" class="black">Read more</button></a>
                    </div>
                    <span class="sp"></span>
                    <div class="sky">
                    <Li class="l">
                        <span class="sli">HTML</span><span class="space1"></span><span class="percn">40%</span>
                        </Li>
                       
                        <hr id="hr1"">
                        <Li class="l">
                            
                            <span class="sli">CSS</span><span class="space2"></span><span class="percn">60%</span>
                        </Li>
                        <hr id="hr2">
                        <li class="l">
                            <span class="sli">Core Java</span><span class="space3"></span><span class="percn">70%</span>
                        </li>
                        <hr id="hr3">
                        <LI class="l">
                            <span class="sli">C++</span><span class="space4"></span><span class="percn">50%</span>
                        </LI>
                        <hr id="hr4">
                        <LI class="l">
                            <span class="sli">Python</span><span class="space5"></span><span class="percn">80%</span>
                        </LI>
                        <hr id="hr5">
                        <LI class="l">
                            <span class="sli">My SQL</span><span class="space6"></span><span class="percn">40%</span>
                        </LI>
                        <hr id="hr6">
                    </div>

                </div>
                    
                </section>
                <section class="contact-area" id="contact">
                    <div class="text-part">
                        <h1 class="h">
                Contact Me</h1>
                <h4 class="who"> get in touch </h4>
                <div >
                    <div id="co">
                        <h3>Get in Touch</h3>
                        <p>If you require any further information/assistance, please feel free to contact me/let me know</p>
                        <br>
                        
                        <i class="fa fa-user" aria-hidden="true" fa-5x id="n"></i><span class="nam">Name</span>
                        <br>
                        <span id="con">Prachi Joshi</span>
                        <br>
                        <i class="fa fa-map-marker" aria-hidden="true" id="c"></i><span class="nam">Address</span>
                        <br>
                        <span id="con1">Sector-36 Noida</span>
                        <br>
                        <i class="fa fa-envelope" aria-hidden="true" id="e"></i><span class="nam">Email</span>
                        <br>
                        <span id="con2">prachijoshi0610@gmail.com</span>
                        <br>
                    </div>
                    <div>
                        <h3>Message me</h3>
                             <form  method="POST" autocomplete="off" name="Submit-to-google-sheet">
                              
                                <input type="text" name="Name" placeholder="Name" required/>
                                
                                <input type="email" name="Email" placeholder="Email" required/>
                                
                                <input type="text" name="Subject" placeholder="Subject" required/>
                                <br>
                                <textarea  name="Message" placeholder="Message.." ></textarea>
                              
                                 <br>
                                 <button type="submit" class="btn">Send message</button>
                        </form>


                    </div>

                </div>

                </div>
                </section>
            </header>
            <footer>
               
                Created by<span id="prachi"> Prachi Joshi </span> <span id="copr"> &copy;</span> | All rights are reserved
            </footer>
          
            
                <script src="typed.min.js"></script>
                <script>
            var typed = new Typed('.example', {
              strings: ['Student', 'Content Creator','Changemaker','Writter','Poet'],
              typeSpeed: 60,
              backSpeed:60,
             loop:true
            });
            
                </script>
                        <script src="typed.min.js"></script>
                <script>
            var typed = new Typed('.example12', {
              strings: ['Student', 'Content Creator','Changemaker','Writter','Poet'],
              typeSpeed: 60,
              backSpeed:60,
             loop:true
            });
            
                </script>
                     <script>
                  
            
    
    
                const header = document.querySelector("nav div");
                const sectionOne = document.querySelector(".banner-area");
    
                const sectionOneOptions = {
                 rootMargin: "-600px 0px 0px 0px"
                };
    
                    const sectionOneObserver = new IntersectionObserver(function(
                    entries,
                    sectionOneObserver
                    ) {
                    entries.forEach(entry => {
                    if (!entry.isIntersecting) {
                    header.classList.add("colornavbar");
                    } else {
                    header.classList.remove("colornavbar");
                    }
                    });
                    },
                    sectionOneOptions);
    
                    sectionOneObserver.observe(sectionOne);
                    </script>
                    <script>
                        
            const scriptURL = 'https://script.google.com/macros/s/AKfycbzRgMUzjKzyPQMPJ3ZF-kg8qfniwfB6-KKLep79yKWaYcsgE8DJ5oAy8Hg_h0EHSAVA/exec'
            const form = document.forms['Submit-to-google-sheet']
          
            form.addEventListener('submit', e => {
              e.preventDefault()
              fetch(scriptURL, { method: 'POST', body: new FormData(form)})
                .then(response => alert("Thanks for Contacting us..! We Will Contact You Soon..."))
                .catch(error => console.error('Error!', error.message))
            })
          
                  </script>    
                  <script>
                       $(document).ready(function(){
              $(window).scroll(function() {
                  if($(window).scrollTop()>900){
                      $('i'.css({
                          "opacity":"0","pointer-event":"auto"
                      }))
                    }
                      else{
                          $('i'.css({
                            "opacity":"0","pointer-event":"none"
                          }))
                        }
                    });
                   $('i').click(function(){
                       $('html').animate({scrollTop:0},500)
                   });   
                  
              });
              
              function topFunction() {
                 document.body.scrollTop = 0;
                     document.documentElement.scrollTop = 0;
               
                     }

                    const toptreverse = document.querySelector("#top");
                    var rootElement = document.documentElement
                     toptreverse.addEventListener("click", topFunction)
             
                $(window).scroll(function () {
                    if ($(this).scrollTop() > 100) {
                        $('#top').fadeIn();
                    } else {
                        $('#top').fadeOut();
                    }
                });
                  </script> 

</body>
</html>
