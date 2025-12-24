/* ======= BASE STYLES ======= */
body{
    background:#000;
    margin:0;
    font-family: Arial, Helvetica, sans-serif;
    color:#fff;
}

img{
    display:block;
    max-width:100%;
    height:auto;
}

/* ======= HEADER ======= */
.header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px;
    flex-wrap:wrap;
    gap:10px;
}

.header img{
    width:100px;
}

/* ======= NAV ======= */
nav{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}

nav a{
    color:#fff;
    text-decoration:none;
    font-size:18px;
    transition: color 0.3s;
}

nav a:hover{
    color:rgb(32,121,121);
}

/* ======= HERO ======= */
.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:50px;
    flex-wrap:wrap;
    gap:20px;
}

.text{
    max-width:500px;
}

.text h1{
    font-size:60px;
}

.text h1 span{
    color:rgb(32,121,121);
}

.text h2{
    font-size:40px;
    margin-top:20px;
}

.text p{
    font-size:15px;
    line-height:1.6;
    margin-top:15px;
}

.buttons{
    margin-top:30px;
    display:flex;
    flex-wrap:wrap;
    gap:15px;
    justify-content:flex-start;
}

button{
    background:rgb(32,121,121);
    color:#fff;
    border:none;
    border-radius:20px;
    min-width:160px;
    height:45px;
    cursor:pointer;
    transition: 0.3s;
}

button:hover{
    opacity:0.8;
}

.button2{
    background:#000;
    border:1px solid #fff;
}

/* HERO IMAGE */
.hero img{
    width:100%;
    max-width:450px;
}

/* ======= MOBILE RESPONSIVE ======= */
@media (max-width:768px){
    .hero{
        flex-direction:column;
        text-align:center;
        padding:20px;
        gap:20px;
    }

    .text h1{
        font-size:40px;
    }

    .text h2{
        font-size:28px;
    }

    nav{
        margin-top:10px;
        gap:15px;
    }

    nav a{
        font-size:14px;
    }

    .header{
        flex-direction:column;
        align-items:center;
        gap:15px;
    }

    .buttons{
        justify-content:center;
    }
}
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>iPhone 13 Pro</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<!-- ======= HEADER ======= -->
<div class="header">
    <img src="images/Apple.jpg" alt="Apple Logo">
    <nav>
        <a href="iphone.html">iPhone 13 Pro</a>
        <a href="">iPhone 13</a>
        <a href="iWatch.html">iWatch 7</a>
        <a href="">iPad</a>
        <a href="">iTV+</a>
        <a href="">iArcade</a>
    </nav>
</div>

<!-- ======= HERO ======= -->
<div class="hero">
    <div class="text">
        <h1>iPhone 13 <span>PRO</span></h1>
        <h2>PRO CAMERAS <br> PRO PERFORMANCE</h2>
        <p>
            The iPhone 13 Pro is a powerful smartphone featuring
            Apple’s A15 Bionic chip, a bright 120Hz ProMotion display,
            and a versatile triple-camera system with improved low-light
            performance.
        </p>

        <div class="buttons">
            <button>Buy now</button>
            <button class="button2">Learn more</button>
        </div>
    </div>

    <img src="images/iphone13.jpg" alt="iPhone 13 Pro">
</div>

</body>
</html>

