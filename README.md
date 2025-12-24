<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Park House – Drinks Menu</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 40px;
      font-family: "Playfair Display", serif;
      color: #3b2b1f;

      /* Old paper background */
      background-color: #E2D1BA;
      background-image:
        radial-gradient(circle at 20% 20%, rgba(0,0,0,0.04), transparent 40%),
        radial-gradient(circle at 80% 30%, rgba(0,0,0,0.03), transparent 45%),
        radial-gradient(circle at 50% 80%, rgba(0,0,0,0.04), transparent 50%),
        repeating-linear-gradient(
          0deg,
          rgba(0,0,0,0.015),
          rgba(0,0,0,0.015) 1px,
          transparent 1px,
          transparent 3px
        );
    }

    .menu {
      max-width: 900px;
      margin: auto;
    }

    .section-header {
      display: flex;
      align-items: center;
      gap: 20px;
      margin-top: 40px;
    }

    h1, h2 {
      margin: 0;
      letter-spacing: 2px;
    }

    h1 { font-size: 42px; }
    h2 { font-size: 34px; }

    .icon {
      width: 80px;
      opacity: 0.9;
    }

    .divider {
      border-bottom: 2px solid #3b2b1f;
      margin: 30px 0;
    }

    .price-header,
    .item {
      display: grid;
      grid-template-columns: 1fr 80px 80px 80px;
    }

    .price-header {
      font-size: 18px;
      margin-bottom: 10px;
    }

    .price-header span,
    .prices {
      text-align: right;
    }

    .item {
      margin-bottom: 12px;
      font-size: 20px;
    }

    .name {
      font-weight: 600;
    }

    .desc {
      font-size: 14px;
      font-style: italic;
      color: #6a5745;
    }

    @media (max-width: 600px) {
      .price-header,
      .item {
        grid-template-columns: 1fr 60px 60px 60px;
      }
      .icon {
        width: 60px;
      }
    }
  </style>
</head>

<body>

<div class="menu">

  <!-- DRAUGHT -->
  <div class="section-header">
    <svg class="icon" viewBox="0 0 64 64" fill="none" stroke="#3b2b1f" stroke-width="2">
      <path d="M14 20h28v28a6 6 0 0 1-6 6H20a6 6 0 0 1-6-6V20z"/>
      <path d="M42 24h6a6 6 0 0 1 0 12h-6"/>
      <path d="M14 20c0-6 6-10 18-10s18 4 18 10"/>
    </svg>
    <h1>DRAUGHT</h1>
  </div>

  <div class="price-header">
    <span></span><span>½</span><span>⅔</span><span>Pint</span>
  </div>

  <div class="item">
    <div>
      <div class="name">Show Your Stripes 3.8%</div>
      <div class="desc">GF Lager – Siren</div>
    </div>
    <div class="prices">1.90</div>
    <div class="prices">2.55</div>
    <div class="prices">3.79</div>
  </div>

  <div class="item">
    <div>
      <div class="name">Lumina 4.2%</div>
      <div class="desc">GF IPA – Siren</div>
    </div>
    <div class="prices">2.50</div>
    <div class="prices">3.40</div>
    <div class="prices">4.99</div>
  </div>

  <div class="item">
    <div>
      <div class="name">Weekly Special</div>
      <div class="desc">Ask Bar</div>
    </div>
    <div class="prices">2.15–3.30</div>
    <div class="prices">3.20–4.10</div>
    <div class="prices">4.50–6.20</div>
  </div>

  <div class="divider"></div>

  <!-- CASK -->
  <div class="section-header">
    <svg class="icon" viewBox="0 0 64 64" fill="none" stroke="#3b2b1f" stroke-width="2">
      <ellipse cx="32" cy="12" rx="18" ry="6"/>
      <path d="M14 12v32c0 6 36 6 36 0V12"/>
      <ellipse cx="32" cy="44" rx="18" ry="6"/>
    </svg>
    <h2>CASK</h2>
  </div>

  <div class="item">
    <div>
      <div class="name">Weekly Special</div>
      <div class="desc">Ask Bar</div>
    </div>
    <div class="prices">2.20–2.75</div>
    <div class="prices">3.10–3.70</div>
    <div class="prices">4.20–4.95</div>
  </div>

  <div class="divider"></div>

  <!-- CIDER -->
  <div class="section-header">
    <svg class="icon" viewBox="0 0 64 64" fill="none" stroke="#3b2b1f" stroke-width="2">
      <path d="M32 20c-12-10-28 8-14 22 6 6 22 6 28 0 14-14-2-32-14-22z"/>
    </svg>
    <h2>CIDER</h2>
  </div>

  <div class="item">
    <div>
      <div class="name">Red Fin 4.2%</div>
      <div class="desc">Cider</div>
    </div>
    <div class="prices">2.40</div>
    <div class="prices">3.20</div>
    <div class="prices">4.50</div>
  </div>

</div>

</body>
</html>
