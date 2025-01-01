/* code pour coder la page presentnant les monstres */

<!DOCTYPE html>
<html lang="fr">
<head>
    <link rel="stylesheet" href="">
    <title> Lethal Company </title>


  <title>Fond rouge foncé</title>

  <style>
  body {
  background-color: black; 
  }
  header {
  background: linear-gradient(darkred); 
  color: white; / Texte en blanc /
  text-align: center; / Centrer le contenu /
  padding: 20px; / Espacement interne /
            font-size: 1.5rem; / Taille du texte /
            width: 115%; / Occupe toute la largeur /
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .content {
            padding: 20px; / Contenu principal en dessous de la bannière */
        }

           
            .image {
              position: absolute;
              top: 100px; 
              left: 140px; 
            }
             .image1 {
              position: absolute;
              top: 350px;
              left: 425px; 
            }

            .text {
            position: absolute;
            top: 650px; 
            left: 325px;
            background-color: whitesmoke; 
            
        }

             .text1 {
            position: absolute;
            top: 100px; 
            left: 675px;
            background-color: whitesmoke; 
        }

        /* commande pour faire des encadres */



            .encadre-rouge {
            position: relative;
            border: 2px solid black; 
            background-color: darkred;  
            color: white;           
            padding: 20px;          
            width: 700px;           
            margin: 20px;           
            border-radius: 10px;    
            text-align: center;     
        }
        .encadre-rouge {
        position: absolute;
        top: 0px; 
        left:-75px; 

    }

    .image4 {
              position: absolute;
              top: 110px; 
              left: 1225px; 
              z-index: 2;
    }

        .encadre {
            position: absolute; 
            top: 250px;        
            left: -660px;         
            width: 1340px;      
            height: 340px;      
            border-radius: 20px; 
            border: 6px solid darkred; 
            padding: 25px;      
        }
    .image5 {
         position: absolute;
         top: 900px; 
         left: 425px; 
         z-index: 2;
    }

    .image6 {
         position: absolute;
         top: 1400px; 
         left: 425px; 
         z-index: 2;
    }

    .text6 {
            position: absolute;
            top: 1100px; 
            left: -50px; 
            background-color: whitesmoke;
        }

    .text7 {
            position: absolute;
            top: 1600px; 
            left: 0px; 
            background-color: whitesmoke;
        }
       /*le texte des mosntre juste en dessous l imge avec pelins de monstres*/

        .text5 {
            position: absolute;
            top: 1700px; 
            left: 0px;
            background-color: whitesmoke; 
        }


    .menu-container {
      position: relative;
      width: 200px;
    }

    .menu-button {
              position: absolute;
              top: 30px; 
              left: 400px; 
            }

    
    .menu-button {
      width: 50%;
      padding: 15px;
      font-size: 16px;
      background-color: darkgrey;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-align: left;
    }

    .menu-button:hover {
      background-color: red;
    }

    .menu-list {
              position: absolute;
              top: 50px; 
              left: 400px; 
            }

    .menu-list {
      position: absolute;
      top: 85px;
      width: 100%;
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      overflow-y: auto;
      max-height: 150px;
      display: none;
    }

    .menu-list button {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      background-color: white;
      color: black;
      border: none;
      text-align: left;
      cursor: pointer;
    }

    .menu-list button:hover {
      background-color: red;
    }
    .encadre {
            position: absolute; 
            top: 1075px;         
            left: -100px;         
            width: 150px;       
            height: 15px;      
            border-radius: 20px; 
            border: 6px solid white; 
            padding: 25px;      
        }
    .encadre2 {
            position: absolute; 
            top: 225px;         
            left: -660px;        
            width:  1340px;       
height: 348px;      
  border-radius: 20px; 
  border: 6px solid darkred; 
  padding: 25px;      
  }

  .encadre3 {
  position: absolute; 
  top: 750px;        
  left: -660px;         
  width:  1340px;       
  height: 348px;      
  border-radius: 20px; 
  border: 6px solid darkred; 
  padding: 25px;      
  }
  .encadre4 {
  position: absolute; 
  top: 1250px;         
  left: -660px;         
  width:  1340px;       
  height: 348px;      
  border-radius: 20px; 
  border: 6px solid darkred; 
  padding: 25px;      
  }
  .encadre5 {
  position: absolute; 
  top: 1575px;         
  left: -95px;         
  width:  225px;       
  height: 15px;      
   border-radius: 20px; 
   border: 6px solid white; 
padding: 25px;      
  }

        

 </style>

  <body>
  <header>
  <img src="banniere.jpg" alt="image of the group" width="1500" height="300" >    </center>

  </header>


  <div class="image"></div>
  <img src="logo.png" alt="Image superposée" class="image">
            
  <div class="image1"></div>
  <img src="imagemonstres.png" alt="image of the group" width="525" height="275" class="image1" >



  <div class="image4"></div>
  <img src="loupe.png" alt="image of the group" width="80" height="" class="image4" >

  <div class="image5"></div>
  <img src="trainabandonne.png" alt="image of the group" width="525" height="250" class="image5" >

  <div class="image6"></div>
  <img src="imagesoleil.png" alt="image of the group" width="525" height="250" class="image6" >

  <div class="text">Il existe 2 types distinct de monstres: premièrement, les monstres d’intérieur, c’est-à-dire qu’ils ne pourront être aperçu qu’à l’intérieur de l'usine. <br> Puis, les monstres d'extérieur qui ne seront visible qu'à l'extérieur, souvent lors des fins de journée. <br> Il existe également un troisième type: les hybrides. ils peuvent être à la fois à l’extérieur et à l’intérieur. <br>Il y’a au total 27 monstres en comptant les hybrides, ceux d'intérieur et d'extérieur.</div>

  <center/>

    

  <div3 
  class="text1"> 


  <div class="encadre-rouge">
  <p>LES MONSTRES </p>
  </div>

  <div class="encadre-rouge2">        </div>

  <div class="encadre">
  </div>

  <div class="text5">By Magueye, Alexandre and Gheorghe</div>


  <div class="text6"> LE BUT DU JEUX </div>
  <div class="text7"> LE LORE DU JEUX  </div>

   <div class="menu-container">
    <button class="menu-button" onclick="toggleMenu()">Menu ▼</button>
    <div class="menu-list" id="menuList">
      <button onclick="navigateTo('projetsaetest.html')">Page D'ACCUEIL</button>
      <button onclick="navigateTo('page1.html')">Page 1 LES PLANETES</button>
      <button onclick="navigateTo('page2.html')">Page 2 OBJECTS DU JEUX</button>
      <button onclick="navigateTo('page3.html')">Page 3 LE BUT DU JEUX</button>
      <button onclick="navigateTo('leloredujeuxpage4.html')">Page 4 LE LORE DU JEUX</button>
      <button onclick="navigateTo('page1.html')">Page 5 LES MONSTRES</button>
      <button onclick="navigateTo('page1.html')">Page 6 LES OJECTS DU JEUX</button>
    </div>
  </div>

  <script>
    function toggleMenu() {
      const menuList = document.getElementById('menuList');
      menuList.style.display = menuList.style.display === 'block' ? 'none' : 'block';
    }

    function navigateTo(page) {
      window.location.href = page;
    }

    // Fermer le menu si on clique ailleurs
    window.addEventListener('click', function (e) {
      const menuContainer = document.querySelector('.menu-container');
      if (!menuContainer.contains(e.target)) {
        document.getElementById('menuList').style.display = 'none';
      }
    });
  </script>

  <div class="encadre2">
  </div>
  <div class="encadre3">
    </div>
  <div class="encadre4">
    </div>
  <div class="encadre5">
    </div>

  </html>
