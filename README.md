# Coffee-and-Tea-
<!DOCTYPE html>
<html>

<head>
    <title>LA TV Shows | Home</title>
    <meta name="description" content="A Catalog of Shows Set in Los Angeles">
    <link rel="stylesheet" href="style.css" />
    <script type="text/javascript" src="scripts.js"></script>
</head>

<body>
    <header class="main-header">
        <h1 class="title">LA TV Shows</h1>
    </header>
    <div id="card-container">
        
    </div>
    <div class="card" style="display: none;">
        <div class="card-content">
            <h2>TV Show Title</h2>
            <img src="" alt="TV Show Poster">
            <ul>
                <li>Bullet Point 1</li>
                <li>Bullet Point 2</li>
                <li>Bullet Point 3</li>
            </ul>
        </div>
    </div>
    <div class="footer">
        <button onclick="quoteAlert();">
            Get A Quote!
        </button>
        <button onclick="removeLastCard();">
            Remove A Card!
        </button>
    </div>
</body>

</html>
html,
body {
    margin: 0;
    padding: 0;
}

.main-header {
    background-color: rgba(0, 0, 0, .3);
    padding-bottom: 10px;
}

.title {
    text-align: center;
    margin: 0;
    font-size: 8em;
    font-family: "Helvetica";
    font-weight: normal;
    color: white;
}

#card-container {
    display: flex;
    justify-content: center;
    margin: 20px;
}

.card {
    width: 300px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin: 5px;
}

.card-content {
    padding: 20px;
    font-family: "Verdana";
    color: #777;
}

.card-content h2 {
    margin-top: 0;
    font-size: 20px;
}

.card img {
    width: 100%;
    height: auto;
}

.footer {
    display: flex;
    justify-content: center;
    background-color: rgba(0, 0, 0, .3);
    padding: 10px;
}

button {
    text-align: center;
    background-color: #666;
    border: none;
    padding-left: 10px;
    padding-right: 10px;
    height: 40px;
    border-radius: 10px;
    color: white;
    font-size: 22px;
    cursor: pointer;
    margin: 5px;
}
