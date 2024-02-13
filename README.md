<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
        max-width: 400px;
      }
      .product-card {
        background-color: #f1eded;
        border-radius: 10px;
        padding: 20px;
        margin: 10px;
      }
      .product-image {
        width: 100;
        height: 200px;
        border-radius: 5px;
      }
      .product-name {
        font-weight: bold;
        margin-top: 10px;
      }
      .product-price {
        color: #007bff;
        font-size: 18px;
      }
      .best-seller {
        color: #28a745;
        font-size: 14px;
      }
      header {
        background-color: #ffffdd;
        height: 200px;
        text-align: center;
        padding-top: 50px;
        color: #016a70;
      }
      h1 {
        padding-bottom: 68px;
      }

      ul {
        list-style-type: none;
        background-color: #d2de32;
        overflow: hidden;
        padding: 0;
      }
      ul a {
        display: inline-block;
        text-decoration: none;
        padding: 20px 20px;
        font-size: large;
        font-weight: bold;
        color: #004f53;
        width: 150px;
      }
      ul a:hover {
        background-color: #016a70;
        color: white;
      }
      li {
        float: left;
      }
      .active {
        background-color: #a2c579;
      }
      img {
        width: 155px;
        float: lef;
        padding: 5px;
      }
      footer {
        background-color: #eaead1;
        text-align: center;
        overflow: auto;
      }
      body {
        text-align: center;
      }
      .label {
        background-color: #007bff;
      }
    </style>
  </head>
  <body>
    <img src="./12.jpeg" alt="" />
    <ul>
      <li><a class="active" href="./index.html">Home</a></li>
      <li><a href="">Orders</a></li>
      <li><a href="">Contact us</a></li>
      <li><a href="">About</a></li>
    </ul>
    <input type="text" id="nameInput" placeholder="Search" />

    <div><h1>Recommended for You</h1></div>

    <div class="product-card">
      <img
        src="./download (1).jpeg"
        alt="Apple iPhone 13 Pro Max"
        class="product-image"
      />
      <div class="product-name">
        Apple iPhone 15 Pro Max 512GB Gray Titanium 5G With FaceTime - Middle
        East Vertion
        <button>+</button><button>0</button><button>-</button><button>Put It In The Cart</button>
      </div>
      <div class="product-price">5,149 SAR</div>
    </div>

    <div class="product-card">
      <img
        src="./download.jpeg"
        alt="Sony PlayStation 5 Console"
        class="product-image"
      />
      <div class="product-name">
        Galaxy S24 Ultra 5G Dual SIM Phantom Purple 12GB RAM 256GB - Middle East
        Version
        <button>+</button><button>0</button><button>-</button><button>Put It In The Cart</button>
      </div>
      <div class="product-price">3,376 SAR</div>
      <div class="best-seller">Best Seller</div>
    </div>

    <div class="product-card">
      <img
        src="./download (3).jpeg"
        alt="Sony PlayStation 5 Console"
        class="product-image"
      />
      <div class="product-name">
        Sony PlayStation 5 Slim Console - New Model 2023 (International version)
        <button>+</button><button>0</button><button>-</button><button>Put It In The Cart</button>
      </div>
      <div class="product-price">2,079 SAR</div>
      <div class="best-seller">Best Seller</div>
    </div>
    <div class="product-card">
      <img
        src="./download (4).jpeg"
        alt="Sony PlayStation 5 Console"
        class="product-image"
      />
      <div class="product-name">
        AirPods (3rd generation) with MagSafe Charging Case White
        <button>+</button><button>0</button><button>-</button><button>Put It In The Cart</button>

      </div>
      <div class="product-price">739 SAR</div>
      <div class="best-seller">Best Seller</div>
    </div>

    <footer>&copy; 2023 Your Website Name. All rights reserved.</footer>

  </body>
</html>
