<!DOCTYPE html>
<html>
<head>
  <title>Richill - Ruhák Diavetítő</title>
  <style>
    /* CSS stílusok a diavetítőhöz */
    .header {
      text-align: center;
    }

    .slogan {
      font-style: inherit;
      text: size adjust 100px;;
    }

    .slideshow-container {
      display: flex;
      justify-content: space-between;
    }

    .mySlides {
      flex: 1;
      text-align: center;
    }

    .mySlides img {
      max-width: 100%;
      height: auto;
    }

    

/* Előző gomb pozíciója az alulon */
.prev {
  left: 0;
  bottom: 0;
}

/* Következő és előző gombok stílusai */
.prev, .next {
  cursor: pointer;
  position:absolute;
  top: 50%;
  width: auto;
  padding: 20px;
  margin-top: 0px;
  color: black;
  font-weight: lighter;
  font-size: 24px;
  transition: 1s ease;
  border-radius: 0 0px 0px 0;
  user-select: inherit;
}

/* Előző gomb pozíciója a bal oldalon */
.prev {
  left: 0;
  bottom: 0;
  border-radius: 3px 0 0 3px;
}

/* Következő gomb pozíciója a jobb oldalon */
.next {
  right: 0;
  bottom: 0;
  border-radius: 0 3px 3px 0;
}

    /* Következő és előző gombok hover stílusai */
    .prev:hover, .next:hover {
      background-color: rgba(0, 0, 0, 0.8);
    }

    /* Felirat konténer stílusa */
    .caption-container {
      text-align: center;
      background-color: #f2f2f2;
      padding: 8px 16px;
    }

    /* Felirat szöveg stílusa */
    #caption {
      color: #333;
      font-size: 18px;
    }
  </style>
</head>
<body style="background-image:https://cdn.wallpapersafari.com/88/28/zrps1V.jpg;">
  <div class="header">
    <h1>Richill</h1> <!-- Főcím -->
    <p class="slogan">jus chill</p> <!-- Szlogen -->
  </div>
  <div class="slideshow-container">
    <!-- Képek diavetítője -->
    <div class="mySlides">
      <img src="https://sep.yimg.com/ay/yhst-25212677457636/hoodies-21.jpg" alt="Pulcsik" width="50%" height="50%">
      <div class="caption">Pulcsik</div>
    </div>

    <div class="mySlides">
        <img src="https://www.soloepis.com/9554-large_default/camiseta-tcnica-transpirable.jpg" alt="Pólók" width="50%" height="50%">
        <div class="caption">Pólók</div>
      </div>
      
      <div class="mySlides">
        <img src="https://lamchutaichinh.vn/wp-content/uploads/2021/05/dang-ky-internet-banking-vpbank-chi-tiet.jpg" alt="Kiegészítők" width="80%" height="80%">
        <div class="caption">Kiegészítők</div>
      </div>
      
      <!-- Következő és előző gombok -->
      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
      
     

<!-- Facebook, Instagram és Email gombok -->
<div style="text-align:center; position: absolute; bottom: 0; left: 50%; transform: translateX(-50%);">
    <a href="https://www.facebook.com/profile.php?id=100006154549008" target="_blank" style="margin-right: 10px;">
      <img src="https://logodix.com/logo/938964.png" alt="Facebook" style="width:60px;height:60px;">
    </a>
    <a href="https://www.instagram.com/kaszaricsi16/" target="_blank" style="margin-right: 10px;">
      <img src="https://icon-library.com/images/instagram-small-icon/instagram-small-icon-12.jpg" alt="Instagram" style="width:50px;height:50px;">
    </a>
    <a href="mailto:kaszaricsi17@gmail.com">
      <img src="https://th.bing.com/th/id/R.acd4841303a1144ed825b9eae4a7c9e2?rik=uoEWp0tjSOAS%2fg&pid=ImgRaw&r=0" alt="Email" style="width:60px;height:60px;">
    </a>
  </div>

  
