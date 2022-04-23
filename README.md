# Export-Company-Web-Project
==================================
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com"> 
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Oswald&display=swap" rel="stylesheet">
    <title>Ambara Export - Karur</title>
    <script src="https://kit.fontawesome.com/607329fa87.js" crossorigin="anonymous"></script>
    <style>
    * {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }
    header {
        text-align: center;
    }
    img {
        width: 100%;
        height: 150vh;
    }
    .title h1 {
        margin: 15px;        
        font-family: 'Oswald', sans-serif;
        background: linear-gradient(
            to bottom, #ff9c08, #fffffff8);
            -webkit-text-fill-color: transparent;
            -webkit-background-clip: text;
    }
    address {
        font-size: 20px;
        color: rgba(0, 0, 0, 0.5);
        margin-bottom: 15px;
    }
    .nav-bar {
        display: flex;
        width: 100%;
        background-color: #f3c175e3;
        text-align: center;
    }
    .nav-bar ul {
        display: flex;
        width: 100%;
        justify-content: space-evenly;
        margin: 25px;
    }
    .nav-list li {
        list-style-type: none;
    }
    .nav-list li a {
        text-decoration: none;
        color: rgba(0, 0, 0, 0.418);
        font-size: 25px;
    }
    #black{
        color: black;
    }
    .nav-list li a:hover {
        color: black;
    }
    .nav-list li::after {
        content: '';
        display: block;
        background-color: black;
        height: 1px;
        margin: auto;
        width: 75%;
        transform: scaleX(0);
        transition: transform 700ms;
    }
    .home{
        display: none;
        color: rgb(0, 0, 0);
        font-size: 25px;
        margin: auto;
    }
    .nav-list li:hover::after {
        transform: scaleX(1);
    }
    .fa-bars{
        background: #070707;
            -webkit-text-fill-color: transparent;
            -webkit-background-clip: text;
        margin: 0;
        padding: 0%;
        cursor: pointer;
        display: none;
    }
    .icon h1 {
        font-size: 25px;
        display: none;
        font-family: 'Pacifico', cursive;
        background: linear-gradient(
            to bottom, #000000, #ffffff86);
            -webkit-text-fill-color: transparent;
            -webkit-background-clip: text;
    }
    .main {
        background-color: rgba(221, 215, 215, 0.822);
        width: 100%;
        height: 50vh;
        margin: 0%;
        padding: 0;
        text-align: center;
    }
    @media only screen and (max-width:500px){
        .nav-list { 
            display: none;
            position: absolute;
            flex-direction: column;
            background-color: rgba(0, 0, 0, 0.274);
            top: 12vh;
            right: -10vh;
            width: 0%;
            height: 50vh;
            transition: width 600ms;
        }
        .icon {
            display: flex;
        }
        .fa-bars {
            display: block;
            position: relative;
            font-size: 38px;
            /* left: -170px; */
            /* left: 0%; */
            bottom: 2px;
            margin: auto;
            /* justify-content: space-between; */
            display: flex;
            text-align: center;
            align-items: center;
            justify-content: center;
        }

        .icon h1{
        display: block;        
        }
        .fa-bars::after {
            content: 'Home';
            display: block;
            font-size: 25px;
            margin-left:150px;        
            font-family: 'Pacifico', cursive;
            background: linear-gradient(
            to bottom, #000000, #ffffff86);
            -webkit-text-fill-color: transparent;
            -webkit-background-clip: text;
        }
        img {
        width: 100%;
        height: 80vh;
    }
    }
    .container-list {
        width: 42%;
        margin-left: 16%;
        /* word-wrap: break-word; */
    }
    .container-list li{
       font-size: 16px;
       width: 100%;
       font-weight: 50;
       font-family: 'Montserrat', sans-serif;
       line-height: 33px;
       margin: 0;
       padding: 0;
    }
    .main-container {
        width: 100%;
        background-color: rgb(233, 231, 231);
        height: 100vh;
        display: flex;
        margin: auto;
    }
    .main-container h1 {
        font-family: 'Montserrat', sans-serif;
        margin-left: 10%;
        font-weight: 100;
        color: rgb(250, 164, 4);
    }
    .about-content  {
        width: 60%;
        margin-top: 5%;
        /* background-color: rebeccapurple;  */
    }

    .aside-content-list li {
        font-size: 16px;
       width: 100%;
       font-weight: 50;
       font-family: 'Montserrat', sans-serif;
       line-height: 33px;
    }
    .aside-content h1 {
        margin-left: -11%;
    }
    .footer-3-flex {
        display: flex;
        justify-content: space-between;
        width: 100%;
        text-align: center;
        line-height: 33px;
    }
    .footer-1st-flex {
        margin-left: 50px;
    }
    .fotter-main h1 {
        text-align: center;
        font-family: 'Montserrat', sans-serif;
        margin: auto;
        width: 100%;
        font-weight: 100;
        color: white;
    }
    .footer-3-flex ul li {
        list-style-type: none;
        font-size: 16px;
        width: 100%;
        font-weight: 50;
        font-family: 'Montserrat', sans-serif;
    }
    .fotter-main {
        background-color: #ff9c08a8;
        width: 100%;
        height: 100vh;
    }
    </style>
</head>
<body>
    <header>
        <div class="title"> 
            <h1>
                AMBARA EXPORT
            </h1>
          <address>
                7/4-A Gandhipuram West,
                Senguthapuram(Po),
                Karur-639002,
                Tamilnadu,
                India.
          </address>          
        </div> 
        <hr>
    </header>
    <div class="nav-bar">
        <div class="icon">
            <i class="fa-solid fa-bars"></i>
        </div>
        <ul class="nav-list"> 
        <li><a href="#" id="black">Home</a></li>
        <li><a href="#">Products</a></li>
        <li><a href="#">Certificates</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
    </div>
    <div class="image">
        <img src="https://atlas.in/files/2020/01/slider2-min.jpg" alt="Textile Pic">
    </div>
    <div class="main-container">
        <br> <br>
        <div class="about-content">
        <h1>ABOUT US</h1> <br>
        <ul class="container-list">
            <li>Into Home textiles for about 42 years</li>
            <li>Working space 500,000 sq.ft / 50,000 sq.m</li>
            <li>100% Cotton, Linen, Polyester Blend, Flex...</li>
            <li>Table Linens, Kitchen Linens, Cushion, Curtain, Nursery...</li>
            <li>Huge warehouse with vertical racking storage using hydraulic stackers 1 Million meter capacity per month</li>
            <li>Serve renowned Global Retailers</li>
        </ul>
    </div>
    <div class="main-aside-content">
        <br> <br> <br>
        <div class="aside-content"> 
            <h1>IN-HOUSE FACILITIES</h1> <br>
            <ul class="aside-content-list">
                <li>In-house Printing, Dyeing, Weaving, Embroidery, Sewing, Quilting with sophisticated machineries.</li>
                <li>12 Million meter Capacity/Annum.</li>
                <li>Printing Capacity of 12 Million mtrs/Annum.</li>
                <li>Dyeing Capacity of 12 Million mtrs/Annum.</li>
                <li>Fabric Coating of 12 Million mtrs/Annum.</li>
                <li>Prewashing of 12 Million mtrs/Annum.</li>
                <li>Sewing Machines with Capacity of 50 Million Pcs./Annum.</li>
                <li>Automatic Spreader & Cutting Machine(Bullmer) with Capacity of 6 Million mtrs/Annum</li>
                <li>Quilting Machine(Richpiece) Capacity of 1 Million mtrs/Annum.</li>
                <li>40 Looms including Vamatex Leonardo, Sulzer, European looms with Staubli Dobbies (20 Shafts).</li>
                <li>8 Terry Looms with Capacity of 10,000 towels/day.</li>
                <li>We can weave complicated designs in high speed and producing 10 Million mtrs/Annum.</li>
            </ul>
        </div>
    </div>
    </div>
   <footer>
       <div class="fotter-main">
           <br> <br>
           <h1>
               AMBARA GROUP OF COMPANIES
           </h1> <br>
           <br>
        <div class="footer-3-flex">
            <ul class="footer-1st-flex">
                <li>Ambara Export Enterprises</li>
                <li>Ambara Processing Mills</li>
                <li>Ambara Financial Services Private Limited</li>
            </ul>
            <ul class="footer-2nd-flex">
                <li>Ambara Textiles Export Private Limited</li>
                <li>Ambara Mills Private Limited</li>
            </ul>
            <ul class="footer-3rd-flex">
                <li>Ambara Fuel Station (Reliance Petroleum Dealer</li>
                <li>Ambara Wind Farms Private Limited</li>
            </ul>
        </div>   

       </div>
   </footer>
</body>
</html>
