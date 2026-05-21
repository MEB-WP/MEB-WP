<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>

  <title>MEB Authentication</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#111;
      color:white;
      display:flex;
      justify-content:center;
      align-items:center;
      min-height:100vh;
      padding:20px;
    }

    .card{
      width:100%;
      max-width:500px;
      background:#1b1b1b;
      border:2px solid gold;
      border-radius:20px;
      padding:30px;
      text-align:center;
      box-shadow:0 0 25px rgba(255,215,0,0.3);
    }

    .logo{
      font-size:35px;
      font-weight:bold;
      color:gold;
      margin-bottom:10px;
    }

    .subtitle{
      color:#ccc;
      margin-bottom:25px;
    }

    .success{
      background:rgba(0,255,120,0.1);
      border:1px solid #00ff88;
      color:#00ff88;
      padding:15px;
      border-radius:12px;
      margin-bottom:25px;
      font-size:18px;
      font-weight:bold;
    }

    .product-image{
      width:100%;
      border-radius:15px;
      margin-bottom:25px;
      border:2px solid gold;
      background:white;
    }

    .info{
      text-align:left;
      margin-top:20px;
    }

    .info div{
      margin-bottom:12px;
      padding:12px;
      background:#242424;
      border-radius:10px;
    }

    .label{
      color:gold;
      font-weight:bold;
    }

    .sku{
      margin-top:20px;
      background:black;
      padding:15px;
      border-radius:10px;
      color:#00ff88;
      word-break:break-word;
      border:1px solid #333;
    }

    .button{
      display:inline-block;
      margin-top:25px;
      padding:14px 25px;
      background:gold;
      color:black;
      text-decoration:none;
      border-radius:12px;
      font-weight:bold;
      transition:0.3s;
    }

    .button:hover{
      transform:scale(1.05);
    }

    .footer{
      margin-top:25px;
      color:#777;
      font-size:14px;
    }

  </style>
</head>
<body>

  <div class="card">

    <div class="logo">
      MEB WEAR POWER
    </div>

    <div class="subtitle">
      GOLD EDITION AUTHENTICATION
    </div>

    <div class="success">
      ✅ PRODUIT AUTHENTIQUE
    </div>

    <!-- TON IMAGE -->
    <img 
      src="IMG_20260519_233520_717.jpg"
      class="product-image"
      alt="T-shirt MEB WEAR POWER"
    >

    <div class="info">

      <div>
        <span class="label">Collection :</span>
        WEAR POWER
      </div>

      <div>
        <span class="label">Modèle :</span>
        GOLD EDITION
      </div>

      <div>
        <span class="label">Numéro :</span>
        001
      </div>

      <div>
        <span class="label">Couleur :</span>
        Beige
      </div>

      <div>
        <span class="label">Taille :</span>
        2XL
      </div>

      <div>
        <span class="label">Type :</span>
        Tee-shirt
      </div>

    </div>

    <div class="sku">
      SKU : MEB-WP-GE-001-BGE-2XL-TS
    </div>

    <a href="#" class="button">
      VISITER MEB WEAR POWER
    </a>

    <div class="footer">
      © 2026 MEB WEAR POWER — Tous droits réservés
    </div>

  </div>

</body>
</html>
</div>

  </div>

  <!-- PAGE 2 -->
  <div class="card page2" id="mebPage">

    <div class="welcome">
      ✨ BIENVENUE CHEZ MEB ✨
    </div>

    <img 
      src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c?q=80&w=1200&auto=format&fit=crop"
      alt="Fashion"
    >

    <div class="text">
      Découvrez la puissance du style avec la collection 
      <strong>WEAR POWER GOLD EDITION</strong>.
      <br><br>
      Merci de faire confiance à MEB.
    </div>

  </div>

  <script>

    function openMEB(){

      document.getElementById("authPage").style.display = "none";

      document.getElementById("mebPage").style.display = "block";

    }

  </script>

</body>
</html>
