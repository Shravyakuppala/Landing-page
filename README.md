# Landing-page.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shopping Mall</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Patels Shopping Mall</h1>
            <p>Catch butterflies for some amazing offers.</p>
        </div>
    </header>

    <main>
        <section class="columns">
            <div class="column">
                <h2>Kids</h2>
                <p>Frocks,toys,cute stuff</p>
            </div>
            <div class="column">
                <h2>Men</h2>
                <p>Kurtas,jeans,shirts,T-shirts,shoes,watches etc..</p>
            </div>
            <div class="column">
                <h2>Women</h2>
                <p>Lehangas,Shararas,Sarees,Cosmotics,Frocks etc..</p>
            </div>
        </section>

        <section class="features">
            <h2>Offers</h2>
            <p>Diwali sale starts from this Sunday and earn free gifts on orders above 1999/-</p>
            <ul>
                <li>Rice cooker</li>
                <li>Water bottles</li>
                <li>Watches</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>For more details <a href="#">Click Here</a></p>
        <p>© 2024 Shravya. All rights reserved.</p>
    </footer>
</body>
</html>


#Landing-page.css

body, h1, h2, p, ul, li {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
}

header {
    background-color: #46cfe7;
    color: rgb(255, 255, 255);
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin-bottom: 10px;
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.columns {
    display: flex;
    justify-content: space-between;
    margin: 20px 0;
    padding: 20px;
}

.column {
    background: #fff;
    padding: 20px;
    border: 1px solid #dddddd;
    border-radius: 5px;
    width: 30%;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.features {
    text-align: center;
    margin: 20px 0;
    padding: 20px;
    background: #f0f0f0;
}

footer {
    background: #333;
    color: rgb(255, 255, 255);
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
}

footer a {
    color: #4c4eaf;
    text-decoration: none;
}

footer a:hover {
    text-decoration: underline;
}
