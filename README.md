<html lang="cs">
<head>
  <meta charset="UTF-8">
  <title>EXPERIMENT</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      padding: 50px;
      background-color: #f5f5f5;
    }
    h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      margin-bottom: 40px;
    }
    a {
      font-size: 20px;
      text-decoration: none;
      color: #3366cc;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
  <script>
    function redirectToRandomVideo() {
      const pages = ["video1.html", "video2.html", "video3.html"];
      const randomIndex = Math.floor(Math.random() * pages.length);
      window.location.href = pages[randomIndex];
    }
  </script>
</head>
<body>

  <h1>EXPERIMENT</h1>
  <p>
    Tohle je pouze test. Video se po spuštění přehraje pouze jednou bez možnosti jej přetáčet nebo zastavit. Nezapomeň si zapnout zvuk ať maximalizuješ příjem smyslových podnětů. Po skončení videa budeš přesměrován na dotazník. :3
  </p>

  <a href="#" onclick="redirectToRandomVideo()">Klikni pro přehrání videa</a>

</body>
</html>
