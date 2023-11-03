- 👋 Hi, I’m @malik759
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bmw Car</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <section class="main">
        <header>
            <img src="Logo.png" alt="Logo" height=".." width="100px" />
            <ul class="navigation">
                <li><a href="#">Top Features</a></li>
                <li><a href="#">Gallery</a></li>
                <li><a href="#">Store</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </header>
        <div class="content">
            <h2>Ready To <span>Race</span></h2>
            <a href="#" class="btn">Ride Now</a>
            <img src="m340i.png" alt="Car" width="1000px">
        </div>

        <!-- Slider Content -->
         <div class="slider">
            <div class="slides active">
                <h2><span>Engine</span><br> 2998cc</h2>
                <h2><span>Max Speed</span><br> 269kmph</h2>
            </div>
            <div class="slides">
                <h2><span>Mileage</span><br> 14 kmpl</h2>
                <h2><span>0-60 kmph</span><br> 4 seconds</h2>
            </div>
            <div class="slides">
                <h2><span>Wheels</span><br> 19 inch F30 442</h2>
                <h2><span>Tyre Type</span><br> Tubelese</h2>
            </div>
         </div>  

        <div class="footer">
            <ul class="sci">
                <li><a href="#"><ion-icon name="logo-facebook"></ion-icon></a></li>
                <li><a href="#"><ion-icon name="logo-twitter"></ion-icon></a></li>
                <li><a href="#"><ion-icon name="logo-instagram"></ion-icon></a></li>
            </ul>
            <div class="dots">
                <span class="dot active"></span>
                <span class="dot"></span>
                <span class="dot"></span>
            </div>
        </div>
    </section>

    <script type="module" src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"></script>

<script>
    const slides = document.querySelectorAll('.slides');
    const dots = document.querySelectorAll('.dot');

    function setActive(i){
        for(slide of slides)
        slide.classList.remove('active');
        slides[i].classList.add('active');
        for(dot of dots)
        dot.classList.remove('active');
        dots[i].classList.add('active');
        
    }

     for(let j =0; j<dots.length; j++){
        dots[j].addEventListener('click', function(){
            setActive(j)
        })
        
     }
</script>
</body>
</html>

<!---
malik759/malik759 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
