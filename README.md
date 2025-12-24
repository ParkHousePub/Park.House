 # Park-House
theme: Park House Pub
Discover the Park House menu, check out our current discounts, and see which beers are coming next!
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Rusty Barrel – Drinks Menu</title>
  <style>
    body {
      margin: 0;
      font-family: "Georgia", "Times New Roman", serif;
      background-color: #f4efe6;
      color: #2e2a24;
    }

    .menu {
      max-width: 700px;
      margin: 40px auto;
      padding: 30px;
      background: #fbf7f0;
      border: 3px solid #5c4a2c;
      box-shadow: 0 0 0 6px #e2d6c2;
    }

    h1 {
      text-align: center;
      font-size: 2.8rem;
      margin-bottom: 10px;
      letter-spacing: 2px;
    }

    h2 {
      margin-top: 35px;
      border-bottom: 2px solid #5c4a2c;
      padding-bottom: 5px;
      font-size: 1.6rem;
    }

    .subtitle {
      text-align: center;
      font-style: italic;
      margin-bottom: 30px;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      display: flex;
      justify-content: space-between;
      padding: 8px 0;
      border-bottom: 1px dotted #b8a98c;
    }

    .item {
      font-weight: bold;
    }

    .price {
      margin-left: 20px;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #6b5e48;
    }
  </style>
</head>
<body>
  <div class="menu">
    <h1>Park House</h1>
    <div class="subtitle">Est. 1892</div>

    <h2>Beers</h2>
    <ul>
      <li><span class="item">House Bitter</span><span class="price">£4.50</span></li>
      <li><span class="item">Golden Ale</span><span class="price">£4.80</span></li>
      <li><span class="item">Stout</span><span class="price">£5.00</span></li>
      <li><span class="item">Lager</span><span class="price">£4.60</span></li>
    </ul>

    <h2>Beers & Ales</h2>

    <h2>Wines</h2>
    <ul>
      <li><span class="item">House Red</span><span class="price">£5.50</span></li>
      <li><span class="item">House White</span><span class="price">£5.50</span></li>
      <li><span class="item">Rosé</span><span class="price">£5.80</span></li>
    </ul>

    <h2>Spirits</h2>
    <ul>
      <li><span class="item">Whisky</span><span class="price">£4.00</span></li>
      <li><span class="item">Gin</span><span class="price">£4.00</span></li>
      <li><span class="item">Vodka</span><span class="price">£3.80</span></li>
      <li><span class="item">Rum</span><span class="price">£3.80</span></li>
    </ul>

    <h2>Non‑Alcoholic</h2>
    <ul>
      <li><span class="item">Lemonade</span><span class="price">£2.50</span></li>
      <li><span class="item">Ginger Beer</span><span class="price">£2.80</span></li>
      <li><span class="item">Soda Water</span><span class="price">£2.00</span></li>
    </ul>

    <footer>
      Please drink responsibly • No credit given
    </footer>
  </div>
</body>
</html>
