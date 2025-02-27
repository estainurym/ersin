<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Shop</title>
    <style>
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
/*            margin-top: 1;*/
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0); /* Lighter overlay */
            z-index: -1;
        }
        body {
            background-image: url('sigma.jpg');
            background-size: cover;
            background-position: center;
            background-attachment: fixed; /* Fixes the background in place */
        }
        /*body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-image: url('photo_2025-02-26_20-59-37.jpg');
            background: ;
        }*/

        .container {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 items per row */
            gap: 5px; /* Reduce space between items */
            justify-content: center;
            text-align: center;
            max-width: 700px; /* Adjust width */
            margin: auto;
        }
        
        .product {
            padding: 5px; /* Reduce padding */
            margin: 0px; /* Remove margin */
            width: 100%; /* Make items fill available space */
            color: white;
        }




        .product img {
/*            background-image: url('photo_2025-02-26_20-59-37.jpg');*/
            max-width: 100%;
            height: 150px;
            object-fit: cover;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>40000 BILCOIN</p> -->
        </div>
         <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
            <!-- <img src="img/a-whole-lotta-nothing-png-clipart.png" alt=""> -->
            <!-- <p>40000 BILCOIN</p> -->
        </div>
        <div class="product">
            <!-- <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
           <!--  <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p> -->
        </div>
        <div class="product">
           <!--  <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p> -->
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="1t-shirtksblack-189e88918c-a24f9000b8090294a574f50ea61ebce1.jpeg" alt="Pencil">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="asida98sdua8osd.webp" alt="Notebook">
            <p>30000 BILCOIN</p>
        </div>
        <div class="product">
            <img src="images.png" alt="School Bag">
            <p>40000 BILCOIN</p>
        </div>
        

    </div>
</body>
</html>
