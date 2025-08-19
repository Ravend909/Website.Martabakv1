<!DOCTYPE html>
<html lang="id">
<head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Teks Tengah</title>
        <style>
            * {
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }
            
            body {
                font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                background-color: #f8f9fa;
                color: #212529;
                min-height: 20vh;
                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                text-align: center;
                padding: 20px;
            }
            
            .centered-content {
                max-width: 800px;
                margin: 0 auto;
            }

            h1 {
                font-size: 2.5rem;
                margin-bottom: 1rem;
                color: #2c3e50;
            }

            p {
                font-size: 1.2rem;
                line-height: 1.6;
                margin-bottom: 2rem;
                color: #495057;
            }

            .divider {
                height: 3px;
                width: 100px;
                background: linear-gradient(90deg, #3498db, #9b59b6);
                margin: 1.5rem auto;
                border-radius: 3px;
            }

            @media (max-width: 768px) {
                h1 {
                    font-size: 2rem;
                }

                p {
                    font-size: 1rem;
                }
                nav {
                    background-color: #f8f9fa;
                    padding: 10px 0;
                    text-align: center;
                }

                nav a {
                    color: #;
                    text-decoration: none;
                    margin: 0 15px;
                    font-weight: bold;
                }
                footer {
                    background-color: #333;
                    color: #333;
                    text-align: center;
                    padding: 20px 0;
                    margin-top: 30px;
                }

            }
            
        </style>

<body>

    <div class="centered-content">
        <img src="erasebg-transformed.png" height="150"/>
        <h1 style="border-bottom: ;">MARTABAK TERANG BULAN BONKISS</h1>
        <div class="divider"></div>
        <nav>
            <a href="Japt.html">Beranda</a>
            <a href="latihan2.html">Kategori Produk</a>
            <a href="latihan3.html">Tentang</a>
            <a href="latihan4.html">Panduan</a>
            <a href="latihan5.html">Kontak</a>
        </nav>
  
    </style>
        <body>
            <div class="centered-content">
                <br><h1>Sejarah Martabak & Terang Bulan</h1>
            <div class="divider"></div>
                <p>Menyelami perjalanan dua kuliner legendaris Indonesia yang telah memikat lidah selama puluhan tahun
                </p>

    <div class="food-history-section">
        <h2>Asal Usul Martabak</h2>
        <img src="mtbkcc.jpeg" height="300p" height="300p" alt="Martabak telur                   asin khas Indonesia" class="history-img">
                <p>Martabak berasal dari Timur Tengah, dibawa oleh pedagang India dan Arab ke Nusantara. Di Indonesia berkembang                                  menjadi dua jenis: martabak telur gurih dan martabak manis.
                </p>
    </div>

    <div class="food-history-section">
        <h2>Legenda Terang Bulan</h2>
        <img src="Kue Terang Bulan.jpeg" height="300p" alt="Terang bulan dengan berbagai topping" class="history-img">
                <p>Terang bulan atau martabak manis mulai populer tahun 1950-an di Bandung. Nama "terang bulan" konon berasal dari                                bentuknya yang bulat seperti bulan purnama.
                </p>
    </div>

    <div class="food-history-section">
        <h2>Perkembangan Modern</h2>
        <img src="Martabak also.jpeg" height="300p" alt="Martabak modern dengan berbagai varian" class="history-img">
                <p>Sekarang martabak berkembang dengan berbagai kreasi seperti green tea, red velvet, dan beragam toping inovatif yang disukai                    generasi muda.
                </p>
    </div>
    </div>
    </div>
/* CSS untuk semua halaman */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f9fa;
    color: #333;
}

header {
    background-color: #f8f9fa;
    color: #333;
    text-align: center;
    padding: 20px 0;
}

.logo {
    font-size: 2em;
    font-weight: bold;
    margin-bottom: 10px;
}

.tagline {
    font-style: italic;
}

nav {
    background-color: #f8f9fa;
    padding: 10px 0;
    text-align: center;
}

nav a {
    color: #;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

.container {
    max-width: 1000px;
    margin: 20px auto;
    padding: 0 20px;
}

.page-title {
    text-align: center;
    color: #49505;
}

.hero {
    text-align: center;
    margin-bottom: 30px;
}

.hero img {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}

.menu-section {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 30px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.menu-item {
    display: flex;
    margin-bottom: 20px;
    align-items: center;
}

.menu-item img, .promo-item img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 10px;
    margin-right: 20px;
}

.promo-item {
    text-align: center;
}

.promo-item img {
    width: 200px;
    height: 200px;
    margin: 0 auto 15px;
}

.price {
    color: #e67e00;
    font-weight: bold;
    font-size: 1.2em;
}

.old-price {
    text-decoration: line-through;
    color: #999;
    font-size: 0.9em;
    margin-left: 10px;
}

footer {
    background-color: #333;
    color: #333;
    text-align: center;
    padding: 20px 0;
    margin-top: 30px;
}

.btn-Success {
    background-color: #49505;
    color: #333;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-weight: bold;
    cursor: pointer;
    text-decoration: none;
    display: inline-block;
    margin-top: 10px;
}

.btn-Success:hover {
    background-color: #49505;
    
}

.contact-methods {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

.contact-method {
    flex-basis: 30%;
    text-align: center;
    margin-bottom: 20px;
}

.map img {
    width: 100%;
    border-radius: 10px;
}

/* Responsive Design */
@media (max-width: 768px) {
    .menu-item {
        flex-direction: column;
        text-align: center;
    }

    .menu-item img {
        margin-right: 0;
        margin-bottom: 15px;
    }

    .contact-method {
        flex-basis: 100%;
    }
    /* STYLE PANDUAN */
    .page-title {
        text-align: center;
        color: #333;
        margin-bottom: 30px;
    }

    .guide-section {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
        margin-bottom: 40px;
    }

    .guide-card {
        background-color: white;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }

    .guide-card h2 {
        color: #333;
        border-bottom: 2px dashed #333;
        padding-bottom: 10px;
        margin-top: 0;
    }

    .guide-card ol, 
    .guide-card ul {
        padding-left: 20px;
    }

    .guide-card li {
        margin-bottom: 8px;
    }

    .note {
        font-style: italic;
        color: #666;
        font-size: 0.9em;
    }

    .payment-methods {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }

    .payment-method {
        flex: 1;
        min-width: 150px;
    }

    /* Responsive */
    @media (max-width: 600px) {
        .guide-section {
            grid-template-columns: 1fr;
        }

        .payment-methods {
            flex-direction: column;
     
        }
    }
}
</body>
</html>
