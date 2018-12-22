# siteLv0
<!DOCTYPE html>
<html>
  
<head >
        <link rel="shortcut icon " href="../Images/FondMunDurf2.PNG" type="image/x-icon"/>
        <meta charset="utf-8" />
        <link rel="stylesheet" href="steelsheet.css"> 
        <title>Démarage</title>
</head>
<body >




	<div class="centrage"></div>

	<div class="initalisation">

      <section class="section" onemouseover="loader()">

        <span class="loader loader-quart"></span>
        Demarage Lv0

      </section>


        <div id="loader">
          
          <div id="loaderFull" ></div>
          <p id="accesLv0"> <a href="home.php"> Accedez au site</a></p>

        </div>  
     
    </div>



	<div class="centrage"></div>
 <script>
        window.onload=function loader() {
            var elem = document.getElementById("loaderFull"); 
            var width = 1;
            var id = setInterval(frame, 10);
            function frame() {
                if (width >= 100) {
                    clearInterval(id);
                } else {
                    width++; 
                    elem.style.width = width + '%'; 
                }
            }

        }
</script>

<script >
  
       alerte("hey")

           
        }

</script>
</body>
</html>

 
