<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https: //fonts.googleapis.com/css2? family= Roboto:wght@400;500 & display=swap" rel="stylesheet">

    <title>Bonsai</title>
</head>
<body>
    <div class="navbar">
        <div class="logo-container">
          <img src="logo.png" alt="Logo">
          <div class="company-name">Bonsai</div>
        </div>
        <div class="navbar-items-container">
          <div class="navbar-item">Product</div>
          <div class="navbar-item">Templates</div>
          <div class="navbar-item">Pricing</div>
          <div class="navbar-item">Reviews</div>
        </div>
        <div class="navbar-buttons-container">
          <button class="white-button">LOG IN</button>
          <button class="green-button">START FREE</button>
        </div>
      </div>
      
</body>
</html>





body{
    font-family: 'Roboto', sans-serif;;
}


.navbar {
    display: flex; /* Per allineare orizzontalmente gli elementi all'interno della navbar */
    justify-content: space-between; /* Per distribuire gli elementi all'interno della navbar */
    align-items: center; /* Per allineare verticalmente gli elementi all'interno della navbar */
  }
  .logo-container {
    display: flex; /* per allineare gli elementi all'interno del contenitore */
    align-items: center; /* per allineare verticalmente gli elementi all'interno del contenitore */
  }
  
  .company-name {
    margin-left: 10px; /* per separare il nome dell'azienda dal logo */
    font-size: 30px;
    color:green;
  }
  
  .navbar-items-container {
    display: flex; /* Per allineare orizzontalmente gli elementi all'interno del contenitore */
    align-items: center; /* Per allineare verticalmente gli elementi all'interno del contenitore */
  }
  
  .navbar-item {
    margin: 0 10px; /* Margine per separare gli elementi */
    cursor: pointer;
    font-size: 20px;
  }
  
  .navbar-buttons-container {
    display: flex; /* Per allineare orizzontalmente gli elementi all'interno del contenitore */
  }
  
  .green-button, .white-button {
    border-radius: 20px; /* Smussatura dei bordi */
    padding: 10px 20px; /* Spaziatura interna */
    margin-left: 10px; /* Margine per separare i bottoni */
  }
  
  .green-button {
    background-color: green; /* Colore di sfondo */
    color: white; /* Colore del testo */
    cursor: pointer;
  }
  
  .white-button {
    background-color: white; /* Colore di sfondo */
    color: black; /* Colore del testo */
    border: 1px solid green; /* Bordo */
    cursor: pointer;
  }
  
