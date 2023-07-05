# pritanand7.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script src="https://kit.fontawesome.com/dd815888da.js" crossorigin="anonymous"></script>
   
    <!--Add your image link here!-->
    <link rel="icon" href="Prit\assets\Prit.jpg" type="image/icon type">


   
   <!--Add your name here!-->
    <title>Prit Anand</title>


<style>
#head {
    color: rgb(253, 249, 249);
    margin-top: 8%;
    text-align: center;
    font-size: 50px;
}

body {
    background-image: url("assets/Background.png");  
    background-repeat: no-repeat;
    background-size: cover;
    background-blend-mode: lighten;
    background-attachment: fixed;
    font-family: Inter, sans-serif;
}

img {
    border-radius: 50%;
    box-shadow: 3px 3px rgba(56, 56, 56, 0.575);
    margin-top: 9%;
    width: 500px;
}

#profileIMG {
    margin-left: 8%;
}


/* #Content {
    display: flex;
    flex-direction: row;
} */

#Content .links {
    /* margin-left: 8%; */
    margin-top: 2%;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bold;
    height: fit-content;
    width: 100%;
}

.social {
    margin: 50px;
    background-color: white;
    border-radius: 15px;
    box-shadow: 2px 2px rgba(0, 0, 0, 0.581);
    text-decoration: none;
    padding: 2%;
}

.social:hover {
    background-color: rgb(40, 40, 40);
    color: white;
}

a {
    text-decoration: none;
    color: rgb(40, 40, 40);
}

.inline {
    display: flex;
    flex-direction: row;
}

.text {
    margin-left: 40%;
    font-size: 18px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.icon {
    font-size: 30px;
}

.grid-container {
    display: grid;
    grid-template-columns: auto auto;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
}

.grid-container>div {
    text-align: center;
}

@media only screen and (min-width: 600px) {
    img {
        width: 50%;
    }
    #head {
        font-size: 50px;
    }
}

@media only screen and (max-width: 600px) {
    img {
        width: 55%;
    }
    #head {
        font-size: 38px;
    }
}  
</style>

</head>

<body>

      <!--Add your name here!-->
    <h1 id="head">Hey Folks!</h1>

    <div id="Content" class="grid-container">
        <div id="profileIMG">
            <img src="assets\Prit.jpg" alt="
        Prit Anand">      <!--Add your image link here!-->
        <h1>Prit Anand</h1>

        </div>

        <div class="links">

            <a href="https://www.youtube.com/@BurstTech" target="_blank">   <!--Add your YT Channel link here! (If Exists)-->
                <div class="social">
                    <div class="inline">


                        <div class="icon">
                            <i class="fa-brands fa-youtube"></i>
                        </div>
                        <div class="text">YouTube</div>
                    </div>
                </div>
            </a>


            <a href="https://linkedin.com/in/pritanand7" target="_blank">   <!--Add your linkedin link here!-->
                <div class="social">
                    <div class="inline">


                        <div class="icon">
                            <i class="fa-brands fa-linkedin"></i>

                        </div>
                        <div class="text">Linkedin</div>
                    </div>
                </div>
            </a>

            <a href="https://github.com/pritanand7" target="_blank"> <!--Add your github profile link here!-->
                <div class="social">
                    <div class="inline">
                        <div class="icon">
                            <i class="fa-brands fa-github"></i>

                        </div>
                        <div class="text">GitHub</div>
                    </div>
                </div>
            </a>

            
            <a href="https://twitter.com/pritanand7" target="_blank"> <!--Add your twitter link here!-->
                <div class="social">
                    <div class="inline">
                        <div class="icon">
                            <i class="fa-brands fa-twitter"></i>
                            
                        </div>
                        <div class="text">Twitter</div>
                    </div>
                </div>
            </a>
            
            <a href="https://www.instagram.com/pritanand7" target="_blank"> <!--Add your Instagram link here!-->
                <div class="social">
                    <div class="inline">


                        <div class="icon">
                            <i class="fa-brands fa-instagram"></i>

                        </div>
                        <div class="text">Instagram</div>
                    </div>
                </div>
            </a>


        </div>

    </div>





</body>

</html>
