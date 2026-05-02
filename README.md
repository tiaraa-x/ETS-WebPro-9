
*{
    margin:0; padding:0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    outline: none; border:none;
    text-decoration: none;
    text-transform: capitalize;
    transition: .2s linear;
}

html{
    font-size: 62.5%;
    scroll-behavior: smooth;
    scroll-padding-top: 6rem;
    overflow-x: hidden;
}

section{
    padding: 2rem 9%;
}

/*header*/
header{
    position: fixed;
    top:0; left:0; right:0;
    background:#EAD4D2;
    padding:2rem 9%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1);
}

header .logo{
    font-size: 3rem;
    color:#D18C76;
    font-weight: bolder;
}

header .logo span{
    color:#D18C76;
}

header .navbar a{
    font-size: 1.5rem;
    padding:0 1.5rem;
    color:#D18C76;
}

header .navbar a:hover{
    color:#DEA2A6;
}

header .icons a{
    font-size: 1.5rem;
    color:#D18C76;
    margin-left: 1.5rem;
}

header .icons a:hover{
    color:#DEA2A6;
}

header #toggler{
    display: none;
}

header .fa-bars{
    font-size: 3rem;
    color:#333;
    border-radius: .5rem;
    padding:.5rem 1.5rem;
    cursor: pointer;
    border:.1rem solid rgba(0,0,0,.3);
    display: none;
}

.heading{
    text-align: center;
    font-size: 4rem;
    color: #F8DC6C;
    padding:1rem;
    margin:2rem 0;
    background:rgba(255, 51, 153,.05);
}

.heading span{
    color: #EAD4D2;
}
/*header end*/



/*home*/
.home{
    display: flex;
    align-items: center;
    min-height: 100vh;
    background:url(pic/goku.jpg) no-repeat;
    background-size: cover;
    background-position: center;
}

.home .content{
    max-width: 50rem;
}

.home .content h3{
    font-size: 6rem;
    color:#F8DC6C;
}

.home .content span{
    font-size: 2rem;
    color:#DEA2A6;
    padding:1rem 0;
    line-height: 1.5;
    font-family: Segoe Script;
}

.home .content p{
    font-size: 1.5rem;
    color:#666;
    padding:0.5rem 0;
    line-height: 1.5;
}

.btn{
    display: inline-block;
    margin-top: 1rem;
    border-radius: 5rem;
    background:#D18C76;
    color:#fff;
    padding:.9rem 3.5rem;
    cursor: pointer;
    font-size: 1.7rem;
}

.btn:hover{
    background:#EAD4D2;
}
/*home end*/



/* about */ 

.about .row{ 
    display: flex; 
    align-items: center; 
    justify-content: space-between; 
    gap: 2rem; 
    flex-wrap: wrap; 
    padding: 2rem 0 3rem; 
} 

.about .row .content{ 
    flex: 1 1 40rem; 
    order: 1; 
} 

.about .row .content h3{ 
    font-size: 3rem; 
    color: #D18C76; 
} 

.about .row .content p{ 
    font-size: 1.5rem; 
    color: #999; 
    padding: .5rem 0; 
    line-height: 1.6;
 } 
 
 .about .row .image-container{ 
    flex: 1 1 40rem; 
    order: 2; 
    position: relative; 
} 

.about .row .image-container img{ 
    width: 100%; 
    height: auto; 
    border: 1.5rem solid #fff; 
    border-radius: .5rem; 
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.1); 
} 
/* about end */

/*about2*/
.about-2{
    background: linear-gradient(135deg, #fff, #fdf3f0);
}

.about-2 .stats{
    display:flex;
    gap:2rem;
    margin:1.5rem 0;
}

.about-2 .stats .box{
    flex:1;
    background:#fff;
    padding:1.5rem;
    border-radius:1rem;
    text-align:center;
    box-shadow:0 .5rem 1rem rgba(0,0,0,.1);
    transition:.3s;
}

.about-2 .stats .box:hover{
    transform:translateY(-5px);
}

.about-2 .stats h2{
    font-size:2.5rem;
    color:#D18C76;
}

.about-2 .stats span{
    font-size:1.2rem;
    color:#777;
}

.about-2 .highlight{
    margin-top:1rem;
    padding:1rem;
    background:#EAD4D2;
    color:#fff;
    border-radius:.5rem;
    font-weight:bold;
}

.about-2 .image-container img{
    border-radius:1rem;
    box-shadow:0 1rem 2rem rgba(0,0,0,.15);
}
/*about 2 end*/

/*about 3*/
.about-3{
    background:#fff;
}

.about-3 .image-container{
    position:relative;
    overflow:hidden;
    border-radius:1rem;
}

.about-3 .image-container img{
    width:100%;
    display:block;
    transition:0.5s;
}

.about-3 .overlay{
    position:absolute;
    bottom:0;
    left:0;
    width:100%;
    background:linear-gradient(to top, rgba(0,0,0,0.7), transparent);
    color:#fff;
    padding:2rem;
    transform:translateY(100%);
    transition:0.5s;
}


.about-3 .image-container:hover img{
    transform:scale(1.1);
}

.about-3 .image-container:hover .overlay{
    transform:translateY(0);
}

.about-3 .content{
    display:flex;
    flex-direction:column;
    gap:1.5rem;
}

.about-3 .feature{
    padding:1.5rem;
    border-radius:1rem;
    background:#fdf3f0;
    transition:.3s;
}

.about-3 .feature:hover{
    background:#D18C76;
    color:#fff;
    transform:translateX(10px);
}

.about-3 .feature h4{
    font-size:1.5rem;
}

.about-3 .feature p{
    font-size:1.2rem;
    color:#555;
}

.about-3 .feature:hover p{
    color:#fff;
}
/*about 3 end*/



/*review*/
.review-section{
    padding:5rem 5%;
    background:linear-gradient(135deg, #fff, #fdf3f0);
}

.review-section .review-container{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
    gap:2rem;
    margin-top:3rem;
}

.review-section .review-card{
    background:#fff;
    padding:2rem;
    border-radius:1rem;
    text-align:center;
    transition:.3s;
    box-shadow:0 .5rem 1rem rgba(0,0,0,.1);
}

.review-section .review-card:hover{
    transform:translateY(-8px);
    background:#D18C76;
    color:#fff;
}

.review-section .stars{
    color:#DEA2A6;
    font-size:1.5rem;
    margin-bottom:1rem;
}

.review-section .review-card p{
    font-size:1.3rem;
    color:#666;
    margin-bottom:1rem;
}

.review-section .review-card h3{
    font-size:1.5rem;
}

.review-section .review-card:hover p{
    color:#fff;
}
/*review end*/


/* products */
.products .box-container{
    display:grid;
    grid-template-columns: repeat(2, 1fr); /* 2 kolom */
    gap:2rem;
}

.products .box-container .box{
    flex:1 1 30rem;
    box-shadow: 0 .5rem 1.5rem rgba(0,0,0,.1);
    border-radius: .5rem;
    border:.1rem solid rgba(0,0,0,.1);
    position: relative;
}

.products .box-container .box .image .icons{
    position: absolute;
    bottom:-7rem;
    left:0;
    right:0;
    display: flex;
}

.products .box-container .box:hover .image .icons{
    bottom:0;
}

.products .box-container .box .image .icons a{
    flex:1; 
    height: 5rem;
    line-height: 5rem;
    font-size: 2rem;
    background:var(--pink);
    color:#fff;
    text-align: center;
}

.products .box-container .box .image .icons .cart-btn{
    border-left: .1rem solid #fff7;
    border-right: .1rem solid #fff7;
}

.products .box-container .box .image .icons a:hover{
    background:#333;
}

.products .box-container .box .content{
    padding:2rem;
    text-align: center;
}

.products .box-container .box .content h3{
    font-size: 2.5rem;
    color:#333;
}

.products .box-container .box .image{
    width:100%;
    height:250px; 
    overflow:hidden;
    position:relative;
}

.products .box-container .box .image img{
    width:100%;
    height:100%;
    object-fit:cover; 
    display:block;
}
/* products end */


/*icons*/
.icons-section{
    background: linear-gradient(135deg, #EAD4D2, #fdf3f0);
    padding:5rem 5%;
}

.icons-section .icons-container{
    display:flex;
    flex-wrap:wrap;
    gap:2rem;
    justify-content:center;
}

.icons-section .icon-card{
    background:#fff;
    border-radius:1rem;
    padding:2rem;
    display:flex;
    align-items:center;
    gap:1.5rem;
    max-width:280px;
    width:100%;
    box-shadow:0 .5rem 1rem rgba(0,0,0,.1);
    transition:.3s;
}

.icons-section .icon-card:hover{
    transform:translateY(-8px);
    background:#D18C76;
    color:#fff;
}

.icons-section .icon-card img{
    width:60px;
    height:60px;
    border-radius:50%;
    object-fit:cover;
    transition:.3s;
}

.icons-section .icon-card:hover img{
    transform:scale(1.1);
}

.icons-section .icon-card h3{
    font-size:1.4rem;
}

.icons-section .icon-card p{
    font-size:1.2rem;
    color:#666;
}

.icons-section .icon-card:hover p{
    color:#fff;
}
/*icons end*/



/*footer*/
.footer .box-container{
    display: flex;
    flex-wrap: wrap;
    gap:1.5rem;
}

.footer .box-container .box{
    flex:1 1 25rem;
}

.footer .box-container .box h3{
    color:#333;
    font-size: 2.5rem;
    padding:1rem 0;
}

.footer .box-container .box a{
    display: block;
    color:#666;
    font-size: 1.5rem;
    padding:1rem 0;
}

.footer .box-container .box a:hover{
    color:var(--pink);
    text-decoration: underline;
}

.footer .box-container .box img{
    margin-top: 1rem;
}

.footer .credit{
    text-align: center;
    padding:1.5rem;
    margin-top: 1.5rem;
    padding-top: 2.5rem;
    font-size: 2rem;
    color:#333;
    border-top: .1rem solid rgba(0,0,0,.1);
}

.footer .credit span{
    color:var(--pink);
}
/*footer end*/



/* media queries  */
@media (max-width:991px){
    html{
        font-size: 55%;
    }
    header{
        padding:2rem;
    }
    section{
        padding:2rem;
    }
}

@media (max-width:768px){
    header .fa-bars{
        display: block;
    }
    header .navbar{
        position: absolute;
        top:100%; left:0; right:0;
        background:#eee;
        border-top: .1rem solid rgba(0,0,0,.1);
        clip-path: polygon(0 0, 100% 0, 100% 0, 0 0);
    }
    header #toggler:checked ~ .navbar{
        clip-path: polygon(0 0, 100% 0, 100% 100%, 0% 100%);
    }
    header .navbar a{
        margin:1.5rem;
        padding:1.5rem;
        background:#fff;
        border:.1rem solid rgba(0,0,0,.1);
        display: block;
    }
    .home .content h3{
        font-size: 5rem;
    }
    .home .content span{
        font-size: 2.5rem;
    }
    .icons-container .icons{
        width:100%;
    }
}

@media (max-width:450px){
    html{
        font-size: 50%;
    }
    .heading{
        font-size: 3rem;
    }
}

/* scroll animation */
section, .box, .icons {
    opacity: 0;
    transform: translateY(40px);
    transition: 0.6s ease;
}

section.show, .box.show, .icons.show {
    opacity: 1;
    transform: translateY(0);
}

/* header scroll effect */
header.active {
    background: #fff;
    box-shadow: 0 .5rem 1rem rgba(0,0,0,.2);
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Ketahanan Pangan (GOKU)</title>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">

    <link rel="stylesheet" href="goku.css">
</head>

<script>
let navbar = document.querySelector('.navbar');
let toggler = document.getElementById('toggler');

document.querySelectorAll('.navbar a').forEach(link => {
    link.onclick = () => {
        toggler.checked = false;
    }
});

window.onscroll = () => {
    if(window.scrollY > 50){
        document.querySelector('header').classList.add('active');
    } else {
        document.querySelector('header').classList.remove('active');
    }

    revealOnScroll();
};

function revealOnScroll(){
    let reveals = document.querySelectorAll('section, .box, .icons');

    reveals.forEach(el => {
        let windowHeight = window.innerHeight;
        let elementTop = el.getBoundingClientRect().top;
        let visible = 100;

        if(elementTop < windowHeight - visible){
            el.classList.add('show');
        }
    });
}

document.querySelectorAll('.cart-btn').forEach(btn => {
    btn.addEventListener('click', (e) => {
        e.preventDefault();
        btn.innerText = "added!";
        btn.style.background = "#333";

        setTimeout(() => {
            btn.innerText = "add to cart";
            btn.style.background = "";
        }, 1500);
    });
});

document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener("click", function(e){
        e.preventDefault();

        document.querySelector(this.getAttribute("href"))
        .scrollIntoView({
            behavior: "smooth"
        });
    });
});

document.querySelector("form").addEventListener("submit", function(e){
    e.preventDefault();
    alert("Pesan berhasil dikirim!");
});
</script>


<body>
<!--header-->
<header>
    <input type="checkbox" name="" id="toggler">
    <label for="toggler" class="fas fa-bars"></label>

    <a href="#" class="logo">GOKU<span>.</span></a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#about">about</a>
        <a href="#review">review</a>
        <a href="#products">products</a>
        <a href="#contact">contact</a>
    </nav>

    <div class="icons">
        <a href="#" class="fas fa-heart"></a>
        <a href="#" class="fas fa-shopping-cart"></a>
        <a href="#" class="fas fa-user"></a>
    </div>
</header>
<!--header end-->



<!--home-->
<section class="home" id="home">
    <div class="content">
        <h3>GOKU</h3>
        <span> Fuel Your Day in Healthy Way </span>
        <p>Snackbar Berbahan Dasar Sorgum untuk Mendukung Ketahanan 
        Pangan melalui Diversifikasi Pangan Lokal</p>
        <a href="#about" class="btn">learn more</a>
    </div>
</section>
<!--home end-->



<!--about 1-->
<section class="about" id="about">
    <h1 class="heading"> <span> about </span> us </h1>

    <div class="row">

        <div class="content">
            <h3>why choose GOKU?</h3>
            <p>
            Dirancang untuk gaya hidup modern, GOKU menghadirkan camilan sehat berbahan dasar 
            sorgum yang kaya nutrisi dan diproses dengan cermat untuk menjaga kualitas rasa dan tekstur. 
            Perpaduan bahan alami pilihan memberikan energi yang stabil tanpa rasa bersalah. GOKU 
            pilihan tepat untuk menemani aktivitas harianmu dengan lebih seimbang.
            </p>
            <p>
            GOKU hadir sebagai langkah kecil menuju konsumsi pangan yang lebih beragam, 
            sehat, dan berkelanjutan melalui pemanfaatan bahan lokal bernilai tinggi.
            </p>
        </div>

        <div class="image-container">
            <img src="pic/proteinbar.jpg.jpeg" alt="GOKU protein bar">
        </div>

    </div>
</section>
<!--about 1 end-->

<!--about 2-->
<section class="about about-2">
    <h1 class="heading"><span>did you</span> know?</h1>

    <div class="row fade-in">

        <div class="content">
            <h3>Indonesia Masih Bergantung pada Beras</h3>
            <p>
            Pola konsumsi masyarakat Indonesia masih didominasi oleh satu sumber pangan utama, 
            yaitu beras. Hal ini berisiko terhadap ketahanan pangan di masa depan.
            </p>

            <div class="stats">
                <div class="box">
                    <h2>91%</h2>
                    <span>Konsumsi Beras</span>
                </div>
                <div class="box">
                    <h2>9%</h2>
                    <span>Pangan Alternatif</span>
                </div>
            </div>

            <p class="highlight">
            Saatnya beralih ke pangan lokal seperti sorgum yang lebih sehat dan berkelanjutan.
            </p>
        </div>

        <div class="image-container">
            <img src="pic/pie.jpeg">
        </div>

    </div>
</section>
<!--about 2 end-->

<!--about 3-->
<section class="about about-3">
    <h1 class="heading"><span>why</span> sorgum?</h1>

    <div class="row fade-in">

        <div class="image-container">
            <img src="pic/bar.jpeg" alt="">
            
            <!-- overlay -->
            <div class="overlay">
                <h3>Sorgum = Superfood Lokal</h3>
                <p>Lebih sehat, lebih tahan, dan lebih berkelanjutan</p>
            </div>
        </div>

        <div class="content">

            <div class="feature">
                <h4>🌾 Tinggi Serat</h4>
                <p>Membantu pencernaan & kenyang lebih lama.</p>
            </div>

            <div class="feature">
                <h4>💪 Kaya Zat Besi</h4>
                <p>Mendukung energi dan mencegah lemas.</p>
            </div>

            <div class="feature">
                <h4>⚡ Energi Stabil</h4>
                <p>Tidak menyebabkan lonjakan gula darah.</p>
            </div>

            <div class="feature">
                <h4>🥗 Nutrisi Seimbang</h4>
                <p>Cocok untuk gaya hidup sehat modern.</p>
            </div>

        </div>

    </div>
</section>
<!--about 3 end-->


<!--review-->
<section class="review-section" id="review">
    <h1 class="heading">Review of <span>Sorghum</span></h1>

    <div class="review-container">

        <div class="review-card">
           <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            </div>
            <p>Sorgum membutuhkan air lebih sedikit ➡️ Cocok untuk daerah kering.</p>
            <h3>Hemat Air 💧</h3>
        </div>

        <div class="review-card">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            </div>
            <p>Mampu tumbuh di kondisi minim air ➡️ Tetap produktif saat kemarau.</p>
            <h3>Tahan Kekeringan 🌤️</h3>
        </div>

        <div class="review-card">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            </div>
            <p>Dapat tumbuh di lahan kurang subur ➡️ Maksimalkan lahan marginal.</p>
            <h3>Lahan Marginal 🌱</h3>
        </div>

        <div class="review-card">
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
            </div>
            <p>Masa panen cepat ➡️ Rotasi tanam lebih fleksibel.</p>
            <h3>Panen Cepat ⏱️</h3>
        </div>
    </div>
</section>

<!--products-->
<section class="products" id="products">
    <h1 class="heading"> latest <span>products</span> </h1>

    <div class="box-container">

        <div class="box">
            <div class="image">
                <img src="pic/ori.jpeg" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">add to cart</a>
                    <a href="#" class="fas fa-share"></a>
                </div>
            </div>
            <div class="content">
                <h3>Original</h3>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img src="pic/chocolate.jpeg" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">add to cart</a>
                    <a href="#" class="fas fa-share"></a>
                </div>
            </div>
            <div class="content">
                <h3>sweet chocolate</h3>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img src="pic/strawberry.jpeg" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">add to cart</a>
                    <a href="#" class="fas fa-share"></a>
                </div>
            </div>
            <div class="content">
                <h3>strawberry</h3>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img src="pic/vanilla.jpeg" alt="">
                <div class="icons">
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="cart-btn">add to cart</a>
                    <a href="#" class="fas fa-share"></a>
                </div>
            </div>
            <div class="content">
                <h3>vanilla</h3>
            </div>
        </div>
    </div>
</section>
<!--products end-->



<!--icons-->
<section class="icons-section">
    <div class="icons-container">

        <div class="icon-card">
            <img src="pic/enegy.jpg.jpeg">
            <div class="info">
                <h3>Energi</h3>
                <p>329 kkal</p>
            </div>
        </div>

        <div class="icon-card">
            <img src="pic/karbo.jpg.jpeg">
            <div class="info">
                <h3>Karbohidrat</h3>
                <p>73 gr</p>
            </div>
        </div>

        <div class="icon-card">
            <img src="pic/protein.jpg.jpeg">
            <div class="info">
                <h3>Protein</h3>
                <p>11 gr</p>
            </div>
        </div>

    </div>
</section>
<!--icons end-->




<!--footer-->
<section class="footer">

    <div class="box-container">

        <div class="box">
            <h3>quick links</h3>
            <a href="#home">home</a>
            <a href="#about">about</a>
            <a href="#review">review</a>
            <a href="#products">products</a>
        </div>

        <div class="box">
            <h3>extra links</h3>
            <a href="#">my account</a>
            <a href="#">my order</a>
            <a href="#">my favorite</a>
        </div>

        <div class="box">
            <h3>contact info</h3>
            <a href="#">+123-456-7890</a>
            <a href="#">example@gmail.com</a>
            <a href="#">Surabaya, Indonesia - 400104</a>
            <img src="images/payment.png" alt="">
        </div>

        <div class="box">
            <h3>member</h3>
            <a href="#">Ivana Dwi Sherlinadia 2043251023</a>
            <a href="#">Tiara Putri Ayu S 2043251030</a>
            <a href="#">Aghnayla Aura Nadinya P 2043252083</a>
            <a href="#">Nyimas Valenci Kesia Azzahra 2043251093</a>
        </div>
    </div>

    <div class="credit"> created by <span> kelompok 9 </span> | all rights reserved </div>
</section>
<!--footer end-->
</body>
</html>
