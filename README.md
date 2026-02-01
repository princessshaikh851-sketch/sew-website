# sew-website<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>SEW | Shaikh Edits World</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#0e0e0e;
    color:#fff;
}


header{
    position:fixed;
    top:0;
    width:100%;
    padding:15px 40px;
    background:rgba(0,0,0,0.7);
    display:flex;
    justify-content:space-between;
    align-items:center;
    z-index:1000;
}


.logo{
    display:flex;
    align-items:center;
    gap:10px;
}

.logo img{
    width:45px;
    animation:spin 6s linear infinite;
}

.logo h1{
    color:#ff004f;
    letter-spacing:2px;
}


@keyframes spin{
    0%{transform:rotate(0deg);}
    100%{transform:rotate(360deg);}
}

nav a{
    color:#fff;
    margin:0 15px;
    text-decoration:none;
}

nav a:hover{
    color:#ff004f;
}

section{
    min-height:100vh;
    padding:120px 60px;
    position:relative;
    overflow:hidden;
}

.brand-bg{
    position:absolute;
    font-size:110px;
    font-weight:700;
    color:rgba(255,255,255,0.05);
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
    letter-spacing:12px;
}


.content{
    max-width:900px;
    animation:fadeUp 1.2s ease;
}

@keyframes fadeUp{
    from{opacity:0; transform:translateY(40px);}
    to{opacity:1; transform:translateY(0);}
}

h2{
    font-size:42px;
    color:#ff004f;
    margin-bottom:20px;
}

p{
    font-size:18px;
    line-height:1.7;
}

.home-img{
    margin-top:30px;
    width:100%;
    max-width:500px;
    border-radius:15px;
    box-shadow:0 0 20px rgba(255,0,79,0.5);
    animation:float 4s ease-in-out infinite;
}

@keyframes float{
    0%,100%{transform:translateY(0);}
    50%{transform:translateY(-15px);}
}


.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:40px;
}

.card{
    background:#1a1a1a;
    padding:25px;
    border-radius:12px;
    text-align:center;
    transition:0.4s;
}

.card img{
    width:60px;
    margin-bottom:15px;
}

.card:hover{
    background:#ff004f;
    transform:translateY(-12px) scale(1.05);
}

.social a{
    display:inline-block;
    margin:10px 15px 0 0;
    color:#ff004f;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.social a:hover{
    color:#fff;
    transform:scale(1.2);
}

footer{
    text-align:center;
    padding:20px;
    background:#000;
    font-size:14px;
}
</style>
</head>

<body>

<header>
    <div class="logo">
        
        <img src="logo.png">
        <h1>SEW</h1>
    </div>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>


<section id="home">
    <div class="brand-bg">SEW</div>
    <div class="content">
        <h2>Shaikh Edits World</h2>
        <p>
            Professional video editing brand creating cinematic edits,
            viral reels, thumbnails & motion graphics.
        </p>

        
        <img class="home-img"
        src="back.png">
    </div>
</section>


<section id="about">
    <div class="brand-bg">ABOUT</div>
    <div class="content">
        <h2>About Us</h2>
        <p>
            SEW is a creative editing studio focused on modern visuals,
            storytelling and next-level digital content.
        </p>
    </div>
</section>

<section id="services">
    <div class="brand-bg">SERVICES</div>
    <div class="content">
        <h2>Our Services</h2>

        <div class="services">
            <div class="card">
                <img src="video.jpeg">
                <h3>Video Editing</h3>
            </div>
            <div class="card">
                <img src="reels.jpeg">
                <h3>Instagram Reels</h3>
            </div>
            <div class="card">
                <img src="ce.jpeg">
                <h3>Cinematic Edits</h3>
            </div>
            <div class="card">
                <img src="thumbnail.jpeg">
                <h3>Thumbnails</h3>
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <div class="brand-bg">CONTACT</div>
    <div class="content">
        <h2>Contact</h2>
        <p>Email: shaikheditsworld@gmail.com</p>
        <p>Phone: +91 XXXXX XXXXX</p>

        <div class="social">
            <a href="#">Instagram</a>
            <a href="#">YouTube</a>
            <a href="#">WhatsApp</a>
        </div>
    </div>
</section>

<footer>
© 2026 Shaikh Edits World | Designed by SEW
</footer>

</body>
</html>
