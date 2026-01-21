<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Indian Food</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .header {
      text-align: center;
      padding: 32px;
    }

    .row {
      display: flex;
      flex-wrap: wrap;
      padding: 0 4px;
    }

    .column {
      flex: 25%;
      max-width: 25%;
      padding: 0 8px;
    }

    .column img {
      margin-top: 8px;
      vertical-align: middle;
      width: 100%;
      border-radius: 6px;
    }

    .column p {
      text-align: center;
      font-weight: bold;
      margin: 8px 0;
    }

    .section-title {
      flex: 100%;
      max-width: 100%;
      text-align: center;
      margin-top: 30px;
    }

    /* Tablet */
    @media screen and (max-width: 800px) {
      .column {
        flex: 50%;
        max-width: 50%;
      }
    }

    /* Mobile */
    @media screen and (max-width: 600px) {
      .column {
        flex: 100%;
        max-width: 100%;
      }
    }
  </style>
</head>

<body>

  <!-- Header -->
  <div class="header">
    <h1>INDIAN FOOD</h1>
    <p>
      Indian food is a rich blend of flavors, spices, and cooking traditions from across the country.
      It includes rice and wheat-based dishes, lentils, vegetables, and aromatic spices,
      reflecting both North and South Indian cuisines.
    </p>
  </div>

  <!-- NORTH INDIAN FOOD -->
  <div class="row">
    <div class="section-title">
      <h2>NORTH INDIAN FOOD</h2>
    </div>

    <div class="column">
      <img src="https://i.ndtvimg.com/i/2015-01/625-chole-bhature_625x350_41420696838.jpg">
      <p>Chole Bhature</p>
    </div>

    <div class="column">
      <img src="https://i.ndtvimg.com/i/2015-05/roganjosh_625x350_81430903997.jpg">
      <p>Rogan Josh</p>
    </div>

    <div class="column">
      <img src="https://c.ndtvimg.com/2019-01/mp9n6kn8_bati_625x300_03_January_19.jpg">
      <p>Dal Baati</p>
    </div>

    <div class="column">
      <img src="https://cdn.tasteatlas.com/Images/Dishes/68a0b958e4ec47d7bfc0f5554b5bb746.jpg?w=1476&h=830">
      <p>Dal Tadka</p>
    </div>
  </div>

  <!-- SOUTH INDIAN FOOD -->
  <div class="row">
    <div class="section-title">
      <h2>SOUTH INDIAN FOOD</h2>
    </div>

    <div class="column">
      <img src="https://www.chefspencil.com/wp-content/uploads/Dosa-1.jpg.webp">
      <p>Dosa</p>
    </div>

    <div class="column">
      <img src="https://www.chefspencil.com/wp-content/uploads/Idli.jpg.webp">
      <p>Idli</p>
    </div>

    <div class="column">
      <img src="https://www.chefspencil.com/wp-content/uploads/Appam.jpg.webp">
      <p>Appam</p>
    </div>

    <div class="column">
      <img src="https://www.chefspencil.com/wp-content/uploads/Pongal.jpg.webp">
      <p>Pongal</p>
    </div>
  </div>

</body>
</html>

