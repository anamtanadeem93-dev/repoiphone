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
