# WP-Mini-Project

<!Doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content=""width=device-width, initial-scale="1.0">
    <!--Bootstrap link for css-->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" rel="stylesheet"/>
    <link href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet"/>
    <title>ZOMATO | HOME </title>
    <style>
        html,body{
            margin:0;
            padding:0;
            box-sizing:border-box;
            overflow-x:hidden;
        }
        #header-img{
            position:relative;
            width:100vw;
            height:400px;
            background-image:linear-gradient(to right, rgba(0,0,0,0.4), rgba(0,0,0,0.6)),url('https://c4.wallpaperflare.com/wallpaper/495/760/53/cuisine-food-india-indian-wallpaper-preview.jpg');
            background-position:center;
            background-repeat:no-repeat;
            background-size:cover;
        }
        header{
            width:100vw;
            height:60px;
        }
        .nav-menu{
            width: 80vw;
            height: 100px;
        }
        .zomato{
            display:block;
            font-weight:bolder;
            color:white;
            text-align:center;
            font-size:60px;
            margin:0;
            font-family:Verdana, Geneva, Tahoma, sans-serif;
        }
        .header-flex
        {
            margin-top:100px;
        }
        .nav-link{
            border-bottom:0px solid black;
            transition: border-bottom 0.3s;
            cursor:pointer;
        }
        .nav-link:hover{
            border-bottom:5px solid white;
        }
        .search-box{
            width:30vw;
            height:60px;
            background-color:white;
            border:none;
            border-top-left-radius:20px;
            border-bottom-left-radius:20px;
            padding-left:20px;
            outline:none;
            font-weight:bold;
            font-size:18px;
        }
        .search-btn{
            width:130px;
            background-color:red;
            color:white;
            border:none;
            border-top-right-radius:20px;
            border-bottom-right-radius:20px;
            font-weight:bold;
            font-size:20px;
        }
        #second-section{
            margin-top: 50px;
            margin-bottom: 50px;
        }
        .card{
            height: 200px;
            width: 200px;
            border: none;
            background-color: white;
            border-radius: 10px;
            box-shadow: 1px 1px 10px #ccc;
            overflow: hidden;
            transition: box-shadow 0.3s;
            margin-bottom: 10px;
        }
        .card:hover{
            box-shadow: 1px 1px 10px #000;
            cursor: pointer;
        }
        .card-bottom{
            position: absolute;
            background-color: white;
            height: 50px;
            width: 100%;
            margin-top: 150px;
        }
        #locations{
            margin-top: 50px;
            margin-bottom: 50px;
        }
        .popular-heading{
            font-size: 40px;
            color: black;
        }
        .locations-div{
            width: 100%;
            height: 60px;
            background-color: white;
            border: 2px solid #ccc;
            border-radius: 10px;
        }
        #get-app{
            margin-top: 50px;
            margin-bottom: 50px;
            padding-top: 30px;
            padding-bottom: 30px;
            background-color: rgba(234,241,130,0.1);
        }
        .e-mail{
            width:250px;
            height: 40px;
            padding-left: 10px;
            border: 1px solid #ccc;
            border-radius: 10px;
            outline: none;
            background-color: white;
        }
    </style>
</head>
<body>
        <div id="header-img">
            <header>
                <!--We are using a flex box and justifying content to center-->
                <div class="d-flex justify-content-center">
                     <!--Navigation menu-->
                    <div class="nav-menu">
                        <p class="float-left text-white m-0 mt-3 nav-link"> Get the app</p>
                        <p class="float-right text-white m-0 mt-3 h4 nav-link"> Sign up</p>
                        <p class="float-right text-white m-0 mt-3 h4 nav-link"> Login</p>
                    </div>
                 </div>
            </header>
            <div class="container">
                <div class="d-flex justify-content-center header-flex">
                <p class="zomato">Zomato</p>
                </div>
                <div class ="d-flex justify-content-center mt-4">
                    <input type ="text" placeholder="Search for dishes or restaurants.." class="search-box"/>
                    <button class ="search-btn">Search</button>
                </div>
            </div>
        </div>
        <section id="second-section">
            <div class="container">
                <div class="d-flex justify-content-center">
                <div class="row">
                    <div class="col-md-3">
                        <div class="card">
                            <img src="https://media.istockphoto.com/photos/hamburger-with-cheese-and-french-fries-picture-id1188412964?k=20&m=1188412964&s=612x612&w=0&h=Ow-uMeygg90_1sxoCz-vh60SQDssmjP06uGXcZ2MzPY=" height="100%" width="100%"/>
                            <div class="card-bottom">
                                <p class="h5 m-0 mt-1 text-center">Order Online</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card">
                            <img src="https://zestysouthindiankitchen.com/wp-content/uploads/2021/05/Facebook-Post_-Samosa-1.jpg" height="100%" width="100%"/>
                            <div class="card-bottom">
                                <p class="h5 m-0 mt-1 text-center">Go Out for a Meal</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card">
                            <img src="https://media-cdn.tripadvisor.com/media/photo-s/03/3f/c9/3c/the-gathering.jpg" height="100%" width="100%"/>
                            <div class="card-bottom">
                                <p class="h5 m-0 mt-1 text-center">Night Life</p>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card">
                            <img src="https://st.hzcdn.com/simgs/4f51c97103a00df7_4-0326/shabby-chic-style-garden.jpg" height="100%" width="100%"/>
                            <div class="card-bottom">
                                <p class="h5 m-0 mt-1 text-center">Zomato Gold</p>
                            </div>
                        </div>
                    </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="locations">
            <div class="container">
                <div class="d-flex justify-content-center">
                    <p class="popular-heading">Popular Locations in and around <span class="font-weight-bold">Mumbai</span></p>
                </div>
                <div class="row mt-4">
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                </div>
                <div class="row mt-4">
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                    <div class="col-md-4">
                        <div class="d-flex align-items-center locations-div">
                            <p class="m-0 ml-3 h5">Park Street Area</p>
                            <i class="fa fa-arrow-right ml-auto mr-4"></i>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="get-app">
            <div class="container">
                <div class="d-flex justify-content-center">
                <div class="row">
                    <div class="col-md-4 d-none d-md-flex">
                        <img src="https://b.zmtcdn.com/web/home/dining/2c17b1c302656ee6d434bff811442f8c1588271130.png" height="500px" width="250px" class="ml:auto"/>
                    </div>
                    <div class="col-md-6">
                        <p class="display-4 font-weight-bold mt-4">Get the Zomato App</p>
                        <p>We will send you a link, click to download the app</p>
                    <div class="d-flex">
                        <input type="text" placeholder="Email" class="e-mail"/>
                        <button class="btn btn-danger ml-2">Get App</button>
                    </div>
                    <p class="mt-3 text-muted">Download App from</p>
                    <div class="d-flex">
                        <img src="https://thumbs.dreamstime.com/z/%D0%BF%D0%B5%D1%87%D0%B0%D1%82%D1%8C-google-play-store-apple-app-store-download-buttons-mobile-app-download-icons-vector-illustration-194272957.jpg" height="150px" width="250px" >
                    </div>
                    </div>
                </div>
                </div>
            </div>
        </section>
</body>
</html>
