<!DOCTYPE HTML>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="script.js"></script>
        
    </head>
  <style>
    html, body{
    background-color: #1D1D1D;
    color: #ffffff;
   overflow-x: hidden;
    height:100%;
    margin: 0;
}
.full-height {
    height: 100%;
  
  }
.intro-container{
    padding-top: 100px;
    padding: 50px;
   
    width: 100%;
   
    margin-left: auto;
    
}
.intro{
    width: auto;
    display: inline-block;
    height: auto;
    padding: 5px;
    
}
.namaste-world{
    width: 100%;
}
.h1char{
    font-size: 103px;
    margin-bottom: 1px;
    line-height: 90px;
    
}
.h1char:hover{
    color: #FD2155;
    font-size:110px;
}
.h2char:hover{
    color: #FD2155;
}
.h2char{
    font-size: 102px;
    line-height: 90px;  
    
}

.about-container{
   margin-left:25px;
   margin-top: 1px;
   margin-bottom: 30px;
}  
.intro-heading{
    font-size: 73px;
    color: #FD2155;
}
.about-flex-container{
    display: flex;
    flex-wrap: wrap;
   
}
.about-box{
    width: 60%;
    text-align: justify;
   
}
.about-graphics{
    
}

.projects-container{
    margin:25px;
    border: 1px solid red;
}
.project-heading{

}
.project-flex-container{
    display: flex;
    flex-wrap: wrap;
}
.project-box{
    width: 250px;
    height: 300px;
    margin: auto;
    padding: 5px;
    border: 1px dotted orange;
}

.blog-container{
    border: 1px solid orange;
    margin: 25px;
}
.blog-flex-container{
    border: 1px solid purple;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    
}
.blog-heading{
    width: 40%;
    border: 1px solid white;
}
.blog-square{
    border:1px solid yellow;
    height: 310px;
    
    width: 300px;
}
.blog-rec{
    width:100%;
    border:1px solid yellow;
    height: 310px;
    margin: auto;
}

/* max 760px */
@media only screen and (max-width:750px) {
    .h1char{
        font-size: 80px;
        margin-bottom: 1px;
        line-height: 80px;
    }
    .h2char{
        font-size: 79px;
        line-height: 80px;  
        
    }
    .intro-heading{
        font-size: 55px;
        
    }
    .about-box{
        width: 100%;
    }


    .projects-continer{
       
    }
    .project-heading{
    
    }
    .project-flex-container{
        width: 100%;
        border: 1px solid blue;
    }
    .project-box{
        width: 300px;
        border: 1px solid green;
    }
    .blog-container{
        justify-content:center;
    }
    .blog-heading{
        width: 100%;
        display: none;
    }
    .blog-square{
       margin: auto;
    }
    .blog-rec{
        width:80%;
    }


}

/*  max 570px */
@media only screen and (max-width:570px) {
    .h1char{
        font-size: 50px;
        margin-bottom: 1px;
        line-height: 55px;
    }
    .h2char{
        font-size: 49px;
        line-height: 55px;  
        
    }
    .intro-container{
        padding: 1px;
    }
    .intro{
       
        margin-top:50%;
        padding-left:1px;
    }
    .intro-heading{
        font-size: 35px;
    }

    .projects-container{

    }
    .project-heading{
    
    }
    .project-flex-container{
    
    }
    .project-box{
        margin-top: 20px;
        width: 250px;
        height: 300px;
    }


}
/* max 359 */
@media only screen and (max-width:370px) {
    .h1char{
        font-size: 40px;
        margin-bottom: 1px;
        line-height: 44px;
        
    }
    .h2char{
        font-size: 39px;
        line-height: 44px;  
        
    }
    .intro-container{
        padding: 1px;
    }
    .intro{
       
        margin-top:50%;
        padding-left:1px;
    }

    .projects-container{

    }
    .project-heading{
    
    }
    .project-flex-container{
    
    }
    .project-box{
       
    }

}



  </style>
    <body>
        <!-- intro -->
        <div class="full-height intro-container">
            <div class="intro">
                <div class="namaste-world">
                    <span class="h1char">N</span>
                    <span class="h1char">a</span>
                    <span class="h1char">m</span>
                    <span class="h1char">a</span>
                    <span class="h1char">s</span>
                    <span class="h1char">t</span>
                    <span class="h1char">e</span>
                    <span class="h1char">&nbsp;</span>
                    <span class="h1char">W</span>
                    <span class="h1char">o</span>
                    <span class="h1char">r</span>
                    <span class="h1char">l</span>
                    <span class="h1char">d</span>
                </div>
                <div class="name">
                    <span class="h2char">I</span>
                    <span class="h2char">'</span>
                    <span class="h2char">m</span>
                    <span class="h2char">&nbsp;</span>
                    <span class="h2char">S</span>
                    <span class="h2char">a</span>
                    <span class="h2char">g</span>
                    <span class="h2char">a</span>
                    <span class="h2char">r</span>
                    <span class="h2char">,</span>
                </div>
               <div class="title">
                <span class="h2char">W</span>
                <span class="h2char">e</span>
                <span class="h2char">b</span>
                <span class="h2char">&nbsp;</span>
                <span class="h2char">D</span>
                <span class="h2char">e</span>
                <span class="h2char">v</span>
                <span class="h2char">e</span>
                <span class="h2char">l</span>
                <span class="h2char">o</span>
                <span class="h2char">p</span>
                <span class="h2char">e</span>
                <span class="h2char">r</span>
               </div>
                 
                <a href="" class="contact-me">Contact me </a> 
            </div>
        </div>
       
          
            <!-- About -->
        <div class="about-container">
            
            <div class="about-flex-container">
                <div class="about-box">
                    <h2 class="intro-heading"> Me, Myself and I</h2>
                    <p>
                        Growing up in the age of computers and the Internet . I developed an interest in computers and the Internet by playing games and exploring the Internet in my teenage years. I was always curious about how these websites, games  and the Internet work. This is the main reason why I chose this field.</p>
                        <p>I am  currently pursuing Btech in Computer Science  at Graphic Era Deemed To Be University. I had a Diploma in Computer Science and Engineering from Swami Rama Himalayan University.

                    </p>
                </div>
                <div class="about-graphics">

                </div>
            </div>
        </div>



            <!-- Projects -->
        <div class="projects-container">
            <h2 class="intro-heading project-heading">
                My Project
            </h2>
            <p>
                A Small gallery Of recent projects done by me. 
                <a href="" style="float: right;">See More</a>
            </p>
           
            <div class="project-flex-container">
                <div class="project-box">
                    <img src="fullscreen.png" style="width: 100%; height:200px;">
                    <p> <b>Twak</b></p>
                    <p>cvbnmmnb bvzdx nbve nb...</p>
                </div>
                <div class="project-box">
                    <img src="fullscreen.png" style="width: 100%; height:200px;">
                    <p> <b>Twak</b></p>
                    <p>cvbnmmnb bvzdx nbve nb...</p>
                </div>
                <div class="project-box">
                    <img src="fullscreen.png" style="width: 100%; height:200px;">
                    <p> <b>Twak</b></p>
                    <p>cvbnmmnb bvzdx nbve nb...</p>
                </div>
                < <div class="project-box">
                    <img src="fullscreen.png" style="width: 100%; height:200px;">
                    <p> <b>Twak</b></p>
                    <p>cvbnmmnb bvzdx nbve nb...</p>
                </div>
            </div>
        </div>
            <!-- blog -->
            <div class="blog-container">
                <div class="blog-flex-container">
                    <div class="blog-heading">
                        <h2> Blogs</h2>
                    </div>
                    <div class="blog-square">
                            Block Slider
                    </div>

                    

                </div>
                <div class="  blog-rec">
                    blog List
                 </div>
            </div>
            
            <!-- Contact -->
            <!-- Footer -->
           
    </body>
</html>
