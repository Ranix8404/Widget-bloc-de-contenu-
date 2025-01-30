# Widget-bloc-de-contenu-
Content block widget for Google site 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Widget Blog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            padding: 20px;
        }
        .blog-container {
            display: flex;
            flex-direction: column;
            gap: 20px;
            max-width: 800px;
            margin: auto;
        }
        .blog-row {
            display: flex;
            background: linear-gradient(135deg, #ff9966, #ff5e62);
            padding: 15px;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0,0,0,0.2);
        }
        .image-container {
            flex: 1;
            position: relative;
            overflow: hidden;
        }
        .image-slider {
            display: flex;
            overflow-x: auto;
            scroll-snap-type: x mandatory;
            gap: 10px;
        }
        .image-slider img {
            width: 150px;
            height: auto;
            border-radius: 5px;
            scroll-snap-align: start;
        }
        .content {
            flex: 2;
            padding-left: 15px;
        }
        .title {
            font-size: 18px;
            font-weight: bold;
            color: white;
        }
        .description {
            color: white;
            margin: 10px 0;
        }
        .button {
            background-color: white;
            color: #ff5e62;
            padding: 8px 12px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            display: inline-block;
        }
    </style>
</head>
<body>
    <div class="blog-container">
        <div class="blog-row">
            <div class="image-container">
                <div class="image-slider">
                    <img src="https://via.placeholder.com/150" alt="Image 1">
                    <img src="https://via.placeholder.com/151" alt="Image 2">
                </div>
            </div>
            <div class="content">
                <div class="title">Titre du blog</div>
                <div class="description">Description courte du contenu ici...</div>
                <a href="#" class="button">LEARN MORE</a>
            </div>
        </div>
    </div>
</body>
</html>
