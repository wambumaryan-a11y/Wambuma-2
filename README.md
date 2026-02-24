# Wambuma-2
<!DOCTYPE html>
<html>
<head>
    <title>Cooking with Wambuma</title>

    <!-- External CSS -->
    <link rel="stylesheet" href="styles.css">

    <!-- Internal CSS -->
    <style>
        body {
            text-align: center;
            background-color: #ffe4b5;
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .container {
            border: 2px solid black;
            padding: 20px;
            margin: 20px auto;
            width: 90%;
            background-color: white;
            border-radius: 10px;
        }

        /* Images side by side */
        .image-row {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        .image-box {
            border: 2px solid black;
            padding: 10px;
            width: 250px;
            background-color: #f8f8f8;
            border-radius: 10px;
        }

        .image-box img {
            width: 100%;
            height: 180px;
            border-radius: 8px;
        }

        /* Videos side by side */
        .video-row {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
        }

        iframe {
            width: 350px;
            height: 200px;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 2px solid black;
            padding: 10px;
        }

        th {
            background-color: lightgray;
        }

        footer {
            background-color: #ddd;
            padding: 15px;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <div class="container">
        <!-- Inline CSS -->
        <h1 style="color: red;">Cooking with Wambuma</h1>
        <p>Welcome to my cooking website where I share delicious homemade meals.</p>
    </div>

    <!-- About Section -->
    <div class="container">
        <h2>About This Website</h2>
        <p>This website is all about sharing my favorite recipes and cooking ideas.</p>
        <!-- Line 2: Italic -->
<p><i>We specialize in fresh, organic, and locally sourced ingredients.</i></p>

<!-- Line 3: Underlined -->
<p><u>Our chefs prepare every dish with passion and creativity.</u></p>

<!-- Line 4: Superscript -->
<p>Our restaurant was established in 2026<sup>th</sup> and has served over 10<sup>3</sup> happy customers.</p>

<!-- Line 5: Subscript -->
<p>Our secret sauce formula includes H<sub>2</sub>O and special spices.</p>

<!-- Line 6: Strike -->
<p><strike>We used to offer frozen meals.</strike> Now we serve only fresh dishes.</p>

<!-- Line 7: Highlight -->
<p><mark>Today’s Special Offer: Get 20% off on all pasta dishes!</mark></p>

<!-- Line 8: Quotation -->
<p><q>Good food is the foundation of genuine happiness.</q></p>

<!-- Line 9: Indented Quotation -->
<blockquote>
    As Wambuma and team, we believe food brings people together.
    Every meal tells a story of culture, flavor, and tradition.
</blockquote>

    </div>

    <!-- Images Section -->
    <div class="container">
    <h2>My Dishes</h2>

    <div class="image-row">
    <!-- FOOD IMAGES -->
<div class="images">
  <img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d" alt="pizza">
    <p>Pizza</p>
</div>
  <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c" alt="salad">
    <p>salad</p>
    </div>
  <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38" alt="burger">
    <p>Burger</p>
</div>
  <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="pasta">
    <p>Pasta</p>
    </div>
  <img src="https://images.unsplash.com/photo-1529042410759-befb1204b468" alt="dessert">
    <p>Dessert</p>
    </div>  
  <img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d" alt="chicken">
  <p>Chicken</p>
  </div>
  

  

        
      
          

   

    <!-- Videos Section -->
    <div class="container">
        <h2>Cooking Videos</h2>

        <div class="video-row">

            <iframe src="https://www.youtube.com/embed/1-SJGQ2HLp8" 
            title="Pilau Recipe" allowfullscreen></iframe>

            <iframe src="https://www.youtube.com/embed/3AAdKl1UYZs" 
            title="Chapati Recipe" allowfullscreen></iframe>

           

        </div>
    </div>

    <!-- Table Section (Before Footer) -->
    <div class="container">
        <h2>Recipe Table</h2>

        <table>
            <tr>
                <th>Dish</th>
                <th>Main Ingredient</th>
                <th>Cooking Time</th>
            </tr>
            <tr>
                <td>Pilau</td>
                <td>Rice</td>
                <td>45 Minutes</td>
            </tr>
            <tr>
                <td>Chapati</td>
                <td>Flour</td>
                <td>30 Minutes</td>
            </tr>
            <tr>
                <td>Ugali</td>
                <td>Maize Flour</td>
                <td>20 Minutes</td>
            </tr>
            <tr>
                <td>Mandazi</td>
                <td>Flour</td>
                <td>25 Minutes</td>
            </tr>
            <tr>
                <td>Fried Rice</td>
                <td>Rice & Vegetables</td>
                <td>35 Minutes</td>
            </tr>
        </table>
    </div>

    <!-- Footer -->
    <footer>
        <p>© 2026 Cooking with Wambuma | All Rights Reserved</p>
    </footer>

</body>
</html>
