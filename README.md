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
    </div>

    <!-- Images Section -->
    <div class="container">
    <h2>My Dishes</h2>

    <div class="image-row">

        <div class="image-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/5b/Pilau_Kenya.jpg" alt="Pilau">
            <p>Spicy Pilau</p>
        </div>

        <div class="image-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Chapati_Kenya.jpg" alt="Chapati">
            <p>Soft Chapati</p>
        </div>

        <div class="image-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Ugali_with_sukuma_wiki.jpg" alt="Ugali">
            <p>Ugali with Sukuma</p>
        </div>

        <div class="image-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Mandazi.jpg" alt="Mandazi">
            <p>Sweet Mandazi</p>
        </div>

        <div class="image-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Fried_rice_2.jpg" alt="Fried Rice">
            <p>Vegetable Fried Rice</p>
        </div>

    </div>
</div>

    <!-- Videos Section -->
    <div class="container">
        <h2>Cooking Videos</h2>

        <div class="video-row">

            <iframe src="https://www.youtube.com/embed/1-SJGQ2HLp8" 
            title="Pilau Recipe" allowfullscreen></iframe>

            <iframe src="https://www.youtube.com/embed/3AAdKl1UYZs" 
            title="Chapati Recipe" allowfullscreen></iframe>

            <iframe src="https://www.youtube.com/embed/k3uW1YvVvH4" 
            title="Fried Rice Recipe" allowfullscreen></iframe>

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
