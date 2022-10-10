<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="../node_modules/bootstrap/dist/css/bootstrap.css">
    <link rel="stylesheet" href="../node_modules/bootstrap-icons/font/bootstrap-icons.css">
</head>
<style type="text/css">
    * {
        padding: 0;
        margin: 0;
        box-sizing: 0;
        font-family: serif;
    }

    @media(max-width:1200px) {
        h1 {
            font-size: 50px;
        }
    }

    @media(min-width:300px) {
        #butt {
            font-size: 20px;
            margin-top: 10px;
            margin-left: 150px;
            
        }
    }

    @media(min-width:300px) {
        h2 h1 {
            font-size: 20px;
        }
    }

    #dribbble {
        font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif
    }

    @media screen and (max-width: 500px) and (orientation:portrait) {
                h1 {
                    height: 250px;
                    width: 500px;
    
                    color: blue;  
                }
                #app{
                    margin-right: 100px;
                }
                #first{
                    width: 500px;
                }
                #projet{
                    color: rebeccapurple;
                    direction: row;
                    padding: 100px;
                }
                #pic{
                    width: 200px;
                    height: 200px;
                }
                #img{
                    display: block;
                    margin-top: 400px;
                }
              
            }
</style>

<body class="">
    <div class="container-fluid nav nav-bar bg-secondary d-flex justify-content-lg-between p-2">
        <div class="nav-item d-flex " style="font-size: 18px;">
            <img src="../ex-vpn.jpeg" alt="" height="30px" width="30px" class="mx-4 mt-2 rounded rounded-circle">
            <div class="mx-4 mt-2">Tour</div>
            <div class="mx-4 mt-2">About</div>
            <div class="mx-4 mt-2">Support</div>
            <div class="mx-4 mt-2">Pricing</div>
        </div>
        <div class="me-5">
            <Button class="btn text-black border border-dark " id="butt"
                style="font-size: 15px; border-radius: 20px; width: 150px; height: 40px;">SIGN UP</Button>
        </div>
    </div>
    <section class=" d-flex text-center my-5 justify-content-center align-items-center ">
        <div class="">
            <div class="my-5">
                <h1 style="font-size: 50px; font-weight: 700;" class="p-4">Impress Your Clients, <br> Surprise Your Team
                </h1>
            </div>
            <div class="my-5">
                <Button class="btn btn-sm btn-primary p-2 text-white" style="border-radius: 20px; width: 200px;">LIVE
                    PREVIEW</Button>
            </div>
            <div class="my-4 ">
                <img src="../12.jpg" alt="" class="img-fluid w-50">
            </div>
        </div>
    </section>
    <div style="margin-top:40px" ; class="text-center">
        <div class="mt-5">
            <h2 style="font-size: 50px; font-weight: 700;" class="p-4">Showreel Will Show You Real</h2>
        </div>
        <div>
            <img src="../13.jpg" alt="" class="image-fluid w-50 mt-5 p-4 mb-lg-5">
        </div>
    </div>
    <div class="row p-lg-5 mt-4">
        <div class="col p-4 ms-4">
            <h3>CREATE</h3>
            Leave the technical stuff to us and focus on whtat you do best, making awesome work.
        </div>
        <div class="col p-4">
            <h3>UPLOAD</h3>
            Update and personalise your creative protfolio quicker and easier thean ever befor.
        </div>
        <div class="col p-4">
            <h3>IMPRESS</h3>
            Baikal's intelligent themes adapt to your works so your portfolio shines, on any of your daring devices.
        </div>
        <div class="col p-4 me-4">
            <h3>A NEW WAY</h3>
            Working with Baikal is a pleasure. Form now on update your site is something you'll want to do.
        </div>
    </div>
    <div class="bg-primary text-center p-4">
        <div class="mt-5">
            <h3 style="font-size: 50px; font-weight: 700;" class="p-4">Online portfolio. Infinite <br> possibilities.
            </h3>
        </div>
        <div class="">
            <p style="font-size: 20px;" class="p-5">Portfolio websites for creative professionals. Try it <br> free with
                a 14-day trial.</p>
        </div>
        <div>
            <img src="../14.jpg" alt="" class="image-fluid w-50 mt-lg-5 p-3">
        </div>

    </div>
    <div class="row" style="margin-top: 70px;" id="projet">
        <div class="col text-center p-lg-5">
            <div class="bi bi-search" style="font-size: 40px;"></div>
            <div style="font-size: 20px; font-weight: bold;" class="mb-3">PROJEXT RESEARCH</div>
            <div>
                <p>Use thie UI kit to boost up your great ideas and make your startup</p>
            </div>
        </div>
        <div class="col text-center p-lg-5">
            <div class="bi bi-search" style="font-size: 40px;"></div>
            <div style="font-size: 20px; font-weight: bold;" class="mb-3">WIREFRAMES</div>
            <div>
                <p>Russian expansion into the Buryat area around Lake Baikal in 1628.</p>
            </div>
        </div>
        <div class="col text-center p-lg-5">
            <div class="bi bi-search" style="font-size: 40px;"></div>
            <div style="font-size: 20px; font-weight: bold;" class="mb-3">DESIGN</div>
            <div>
                <p>Russian expansion into the Buryat area around Lake Baikal in 1628.</p>
            </div>
        </div>
        <div class="col text-center p-lg-5">
            <div class="bi bi-search" style="font-size: 40px;"></div>
            <div style="font-size: 20px; font-weight: bold;" class="mb-3">DEVELOPMENT</div>
            <div>
                <p>Lake Baikal in 1628-1658 was part of the Russian conquest</p>
            </div>
        </div>
    </div>
    <div class="row bg-dark p-5 text-white ">
        <div class="col-3 p-5 ms-4 mt-2 " id="app">
            <div class="" style="font-weight: bold;">
                APPLICATION
            </div>
            <div class=" mt-4 ">
                <li class="mt-2"> Intro</li>
                <li class="mt-2"> Sliders</li>
                <li class="mt-2"> Sliders</li>
            </div>
        </div>
        <div class="col-8 p-4  flex-wrap" id="first">
            <div class=" text-white w-50 mb-2" style="font-size: 40px; font-weight: bold;">
                The First Responsive Airline Website
            </div>
            <p class="mb-5">Who says airline website are too complex to be responsive? The Work & Co technology team
                built a site that works
                wherever you are, so you have a great experience at any point of your trip, from a laptop to a
                mobile device.
            </p>
            <div class="d-flex justify-content-lg-start ">
                <div class="mt-5   ">
                    <img src="../15.jpg" alt="" height="500px" class="" width="300px" id="pic" >
                </div>

                <div class="p-5 " style="margin-top: 50px;" id="img">
                    <div class="">
                        <span class="bi bi-search  mt-5  p-2" style="font-size: 25px; width: 10px;"></span>
                        <span class="" style="font-weight: bold;"> SMART SEARCH</span>
                        <div class=" text-secondary" style="margin-left:42px;"> A set of 130 elements, perfectly fitting
                            each other</div>
                    </div>

                    <div style="margin-top: 90px;"><span class="bi bi-search   mt-5  p-2"
                            style="font-size: 25px; width: 10px;"></span>
                        <span class="" style="font-weight: bold;"> FAVOURITES</span>
                        <div class=" text-secondary" style="margin-left:44px;">TCO technology team built a site that works</div>
                    </div>

                    <div style="margin-top: 90px;"><span class="bi bi-search   mt-5  p-2"
                            style="font-size: 25px; width: 10px;"></span>
                        <span class="" style="font-weight: bold;">FAVOURITES</span>
                        <div class=" text-secondary" style="margin-left:44px;">TCO technology team built a site that works</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div style="margin-top:-50px;">
    <div class="my-lg-5 mb-lg-5 p-4"  style="background-color: rgb(199, 243, 222);">
        <div class="text-center" style="margin-top: 50px;">PROUD TO WORK WITH</div>
        <div class="d-flex text-secondary justify-content-center my-lg-5" style="font-size: 40px;font-weight: bold; ">
            <div class="mx-5" id="wired"><span class="bg-secondary text-white"> W</span> I <span
                    class="bg-secondary text-white"> R</span> E <span class="bg-secondary text-white"> D </span> </div>
            <div class="mx-5" style="font-family: Arial;">tumblr.</div>
            <div class="mx-5" id="dribbble">dribbble</div>
            <div class="mx-5" style="font-family:calibri;">Vans off The WALL</div>
        </div>
    </div>
</div>
    <div class="row p-5 " style="background-color: rgb(164, 164, 196); margin-top: -60px;">
        <div class="col-3  d-flex justify-content-center">
            <img src="../n2.jfif" alt="" class="img-fulid w-50 rounded rounded-circle">
        </div>
        <div class="col-9  p-4">
            <p style="font-size: 18px;">"Just started using awesome Baikal UI Kit. Great way to boost the designing or
                prototyping pricess. Also a perfect tool for creative studios."</p>
            <div>
                <span class="bi bi-search bg-white p-2 rounded rounded-circle mx-2"></span>
                <span>KOGI MOTOFUMI</span>
                <div class="mx-lg-5 text-secondary">Lead Designer at Dropbox</div>
            </div>
        </div>
    </div>
    <div class=" d-flex justify-content-center p-lg-5 " style="background-color: rgb(112, 204, 247);">
        <div>
       <h1 class="mt-lg-5" style="font-weight: bold;"> Free Trial for 30 Days</h1>
       <p class="text-secondary my-4 text-center" style="font-size: 18px; width: 380px;">Hurry up and get a limited time freeble. Comes only for OS X</p>
       <div class="input-group my-5">
        <input type="text" placeholder="Enter You mail" class="p-1 form-control input-group-text">
        <button class="btn btn-primary btn-lg p-2 input-group-text" style="font-size: 15px;">SIGN UP</button>

       </div>
        </div>
    </div>
    
    <div class="d-flex justify-content-center   align-item-center p-2" style="margin-top: 100px;">
        <div class=" text-center">
            <img src="../ex-vpn.jpeg" alt=""  class="  centered  rounded rounded-circle my-lg-5" height="180px" width="180px" style="margin-left: px;">
            <h1 class="my-lg-1  text-center" style="font-weight: bold;">Get an App</h1>
            <p class="my-lg-5 text-center text-secondary" style="width:380px ;">Hurry up and get a limited time freeble. Comes only for OS X.</p>
            <button class="text-white p-1 bg-dark btn-lg" style="width: 180px; height: 70px;"><span class="bi bi-apple me-4" style="font-size: 20px;"></span><span style="font-size: 12px;">Download on the <span style="font-size: 20px; margin-left: 40px;">Apps Store</span></span>
            </button>
        </div>
    </div>
    <footer class="bg-secondary my-lg-5 p-4" style="height:300px ;" >
        <div class="row mt-lg-5">
            <div class="col-3 text-center mt-4">
                <img src="../ex-vpn.jpeg" alt="" width="50px" height="50px" class="rounded rounded-circle">
            </div>
            <div class="col text-white">
                <div class="mb-3">TOUR</div>
                <div class="mb-3">SERVICE</div>
                <div class="mb-3">APPS</div>
            </div>
            <div class="col text-white">
                <div class="mb-3">SIGN UP</div>
                <div class="mb-3">CONTACTS</div>
                <div class="mb-3">ABOUT</div>
            </div>    
            <div class="col">
                <div class="mb-3" style="color: rgb(13, 187, 50);">Terms & Condition</div>
                <div  style="color: rgb(13, 187, 50);">Privacy Policy</div>
            </div>
            <div class="col p-4 ">
                <div style="font-size: 30px;">
                    <span class="bi bi-facebook bg-primary text-white p-1 mx-1  "></span>
                    <span class="bi bi-twitter bg-secondary text-primary p-1 mx-1"></span>
                    <span class="bi bi-instagram bg-danger text-white p-1 mx-1"></span>
                    <span class="bi bi-google bg-secondary text-danger p-1 mx-1"></span>
                </div>
            </div>       
        </div>
    </footer>
       <script src="../node_modules/jquery/dist/jquery.js"></script>
    <script src="../node_modules/bootstrap/dist/js/bootstrap.bundle.js"></script>
</body>

</html>
