# code<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Food Blog</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css"
        integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />

    <style>
        body {
             margin: 0%;
        }

        .logo-img {
             margin-right: 35%;
        }

        .header {
             height: 90 vh;
        }

        .list {
                display: flex;
                list-style: none;
        }

        .list li {
                margin-left: 50px;
                font-size: 21px;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
     
        }

        .navbar {
                display: flex;
                align-items: center;
                justify-content: space-evenly;
                color: rgb(31, 35, 41);
        }


        .about {
                margin: 10%;
                display: flex;
                background-color: rgb(241, 226, 236);
        }

        .left-div {
                height: 300px;
                width: 40%;
                background-color: red;

        }

        .left-div img {
                width: 100%;
                height: 100%;
        }

        .about .right-div {
                margin-left: 50px;
                width: 60%;
        }

        .right-div p {
                font-family: Arial, Helvetica, sans-serif;
                font-size: smaller;
        }

        .list li {
                list-style: none;
                display: flex;
                margin-top: 8px;
        }

        .list li i {
                background-color: rgb(176, 176, 238);
                border-radius: 30%;
                padding: 5px;
                margin-right: 5%;
        }

        /* products */

        .cards {
                display: flex;
                justify-content: space-evenly;
                background-color: white;
                padding: 3%;
        }

        .products-div h1 {
                text-align: center;
                color: rgb(26, 26, 27);
        }

        .card-div {
                border: 2px rgb(210, 243, 191) solid;
                width: 250px;
                box-shadow: 5px 1px 0px 1px rgb(140, 140, 141);
        }

        .card-div:hover {
                background-color: rgb(236, 228, 109);
                cursor: pointer;
        }

        .card-div p {
            margin-left: 10%;
        }

        .card-div h3 {
               margin-left: 5%;
        }


        .card-img img {
                width: 100%;
                height: 200px;

        }

     /* recipes */

        .main-div {
                background-color: white;
                width: 100%;
                height: 100%;
                display: flex;
        }

        .recipes {
            margin: 2%;
            width: 60%;
            height: 100%;


        }


        .recip1 {
                width: 90%;
                height: 30%;
                background-color: rgb(224, 237, 240);
                display: flex;
                margin: 5%;

        }

        .ul-div {
                height: 40%;
                width: 30%;
                margin-left: 5%;
        }

        main-div li {
                font-size: medium;
        }

        /* right*/

        .right-sidediv {

                        background-color: rgb(241, 235, 231);
                        width: 61%;
                        height: 5%;

                        margin: 5%;
                        display: flex;
                        box-shadow: 5px 1px 0px 1px rgb(235, 113, 109);
                    }


        .right-one {
                    margin: 2%;
                    background-color: white;
                    width: 40%;
                    height: 100%

        }

        .right-one img {
                 height: auto;
        }

        .right-one li {
                list-style: none;
        }

        .recipes li {
                 list-style: none;
        }

        .order-button {
                    background-color: rgb(233, 229, 14);
                    width: 40%;
                    margin-left: 100%;
                    border-radius: 10px;


        }

        .right-one h3 {
                    margin-left: 100%;
                    color: rgb(241, 24, 24);
                    font-size: 30px;
        }



        /* footer */

        .footer {
                width: 100%;
                height: 70vh;
                background-color: rgb(78, 85, 85);
                display: flex;

        }

        .div-one {
                width: 20%;
                height: 60%;
                background-color: rgb(78, 85, 85);
                margin: 5%;

        }

        .footer li {
                    list-style: none;
                    font-size: larger;
                    padding: 3%;
                    color: aliceblue;
        }


        .text-form input {
                    margin: 5%;
                    padding: 5px;
                    border-radius: 10%;
                }

        .text-form button {
                    background-color: rgb(248, 79, 79);
                    padding: 10px;
                    margin-left: 25%;
                    border-radius: 10px;
                    width: 50%;

        }

        .footer i {
               padding: 4%;
        }

        .footer h4 {
              color: aliceblue;
        }

        .footer h3 {
            color: aliceblue;
        }

        .footer p{
               color: aliceblue;
               font-size:large;
        }

    </style>
</head>

<body>

    <div class="header">
        <div class="navbar">
            <div class="logo-img">
                <img width="60px" src="./images/logo.png">
            </div>
            <div>
                <ul class="list">
                    <li>HOME</li>
                    <li>ABOUT</li>
                    <li>PRODUCTS</li>
                    <li>SERVICE</li>
                    <li>CONTACT</li>
                </ul>
            </div>
        </div>
        <img width="100%" src="./images/next.jpeg">
    </div>


    <!-- about -->
    <div class="about">
        <div class="left-div">
            <img src="./images/aboutt.jpg">
        </div>

        <div class="right-div">
            <h1>About</h1>
            <p>Food is any substance consumed by an organism for nutritional support.Different species of animals have
                different feeding behaviours that satisfy the needs of their metabolisms and have evolved to fill a
                specific ecological niche within specific geographical contexts.</p>




            <div class="list">
                <ul class="first-list">
                    <li><i class="fa-solid fa-check"></i>Product</li>
                    <li><i class="fa-solid fa-check"></i>service</li>
                    <li><i class="fa-solid fa-check"></i>Good</li>
                </ul>

                <ul class="second-list">

                    <li><i class="fa-solid fa-check"></i>Food</li>
                    <li><i class="fa-solid fa-check"></i>Testy</li>
                    <li><i class="fa-solid fa-check"></i>Healthy</li>
                </ul>

            </div>
        </div>

    </div>

    </div>

    <!-- <------product----->

    <div class="products-div">
        <h1>Product</h1>
        <div class="cards">
            <div class="card-div">
                <div class="card-img">
                    <img src="./images/burgur.jpg">

                </div>
                     <h3>Burger</h3>
                        <p>Test of food is very good and delicious also service is very prompt.
                            I will advise to people visit such place with family for and spend quality time.
                        </p>

                <p>150/-</p>

            </div>


            <div class="card-div">
                <div class="card-img">
                    <img src="./images/fries.jpg">

                </div>
                    <h3> French Fries</h3>
                      <p>All the one who love french fries must ones have a visit here.They serve french fries with n no of
                        styles and n number of sauces.
                      </p>
                <p>180/-</p>
            </div>


            <div class="card-div">
                <div class="card-img">
                    <img
                        src="https://images.pexels.com/photos/1352270/pexels-photo-1352270.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1">

                </div>
                   <h3>Fried Chicken</h3>
                      <p>KFC was one of the first American fast-food chains to expand internationally,
                          as it went through a series of changes in corporate.
                       </p>

                      <p>499/-</p>
               </div>


            <div class="card-div">
                <div class="card-img">
                    <img src="./pizza.avif">

                </div>
                <h3>Pizza</h3>
                <p>Pizza is an Italian dish typically consisting of a flat base of leavened wheat-based dough topped
                    with tomato, cheese,
                    and other ingredients.
                </p>
                <p>495/-</p>
        
            </div>

        </div>
    </div>


    <!-- <-----recipes---->

 <h1 style="text-align: center;">Recipes</h1>
    <div class="main-div">
        <div class="recipes">
            <div class="recip1">
                <img src="./images/burgur.jpg">

                   <div class="ul-div">
                        <h2>Burger</h2>
                        <ul class="list-re">
                           <li>Bun</li>
                           <li>Beef</li>
                           <li>chees</li>
                        </ul>
                          <button class="order-button">Order</button>
                </div>
            </div>

            <div class="recip1">
                <img src="./images/fries.jpg">
                <div class="ul-div">
                    <h2>French Fries</h2>
                       <ul class="list-re">
                           <li>Potatoes</li>
                           <li>oil</li>
                           <li>Salt</li>
                        </ul>
                        <button class="order-button">Order</button>
                </div>

            </div>


            <div class="recip1">
                <img src="./images/fdf.jpg">
                   <div class="ul-div">
                      <h2>Fride Chicken</h2>
                            <ul class="list-re">
                                <li>Chicken</li>
                                <li>Buttermilk</li>
                                <li>Seasonings</li>

                            </ul>

                       <button class="order-button">Order</button>
                    </div>
            </div>

            <div class="recip1">
                <img src="./pizzaa.jpg">
                    <div class="ul-div">
                        <h2>Pizza</h2>
                          <ul class="list-re">
                                <li>Ingredients</li>
                                <li>Flour</li>
                                <li>Pizza sauce</li>
                                <li>Yeast</li>
                           </ul>
                        <button class="order-button">Order</button>
                    </div>
            </div>
        </div>

 <!-- right side -->

        <div class="right-one">
            <div class="right-sidediv">
                <div class="right-1">
                    <img src="./images/offers kfc.jpg">
                    <div class="ul-div">
                        <h2>OFFER</h2>
                        <h3>399/- Only-</h3>
                    </div>
                </div>
            </div>

         <div class="right-sidediv">
                <div class="right-1">
                    <img src="./images/OFF.jpg">
                       <div class="ul-div">
                          <h1>COMBO offer</h1>
                         <h3>Just 499/- Only</h3>
                    </div>
                </div>
            </div>

            <div class="right-sidediv">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQTulkLAjajU9QmV7wA1pbhq7CyDHfA6N78Ow&s">
            </div>
        </div>
    </div>

<!-- footer -->

    <div class="footer">
                <div class="div-one">
                    <h3>ABOUT </h3>
                    <p>We share delicious recipes, top-quality products, 
                        and a passion for food. Stay connected for more tasty ideas!
                    </p>
                </div>

        <div class="div-one">
                <ul>
                    <h3>SERVICE</h3>
                    <li><i class="fa-solid fa-paper-plane"></i>HOME</li>
                    <li><i class="fa-solid fa-paper-plane"></i>ABOUT</li>
                    <li><i class="fa-solid fa-paper-plane"></i>PRODUCTS</li>
                    <li><i class="fa-solid fa-paper-plane"></i>SERVICE</li>
                    <li><i class="fa-solid fa-paper-plane"></i>CONTACT</li>
                </ul>
        </div>

        <div class="div-one">
             <h3>FOOD COMPANY</h3>
                <ul>
                    <li><i><i class="fa-solid fa-location-dot"></i></i>kozhicode,</li>
                    <li><i><i class="fa-solid fa-phone"></i></i>75684937397</li>

                </ul>
        </div>

        <div class="div-one">
            <form class="text-form">
                <input type="text" placeholder="Name">
                <input type="number" placeholder="Phone Number">
                <input type="text" placeholder="email">
                <input type="text" placeholder="Message">
                <button type="button">sumit</button>
            </form>

        </div>

    </div>





</body>

   </html>-hubb
