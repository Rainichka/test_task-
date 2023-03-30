Кароч.

<!DOCTYPE html>
<html lang="ru">
<head>
    <!-- Это кодировка, забейте, всегда пишем UTF-8 -->
    <meta charset="UTF-8">
    <!--  
        Internet Explorer настолько "классный" что нам надо указывать эту директиву,
        чтобы он норм работал с нашим сайтом, забейте и все пишите это: http-equiv="X-UA-Compatible" content="IE=edge"
    -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- Это чтобы масштаб подогнался под экран -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Описание сайта, для SEO нужно -->
    <meta name="description" content="Start your development with Meyawo landing page.">
    <!-- Название сайта, выводится в названии владки браузера -->
    <title>Hi_Me</title>
    <!-- Подключаем стили -->
    <link rel="stylesheet" href="css/main.css">
    <link rel="stylesheet" href="css/nav.css">
    <link rel="stylesheet" href="css/header.css">
    <link rel="stylesheet" href="css/about.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="container">
            <a class="logo" href="#">Hi_Me</a>         
            <ul class="nav">
                <li class="item">
                    <a class="link" href="#home">Home</a>
                </li>
                <li class="item">
                    <a class="link" href="#about">About</a>
                </li>
                <li class="item">
                    <a class="link" href="#portfolio">Portfolio</a>
                </li>
            </ul>
            <a href="javascript:void(0)" id="nav-toggle" class="hamburger hamburger--elastic">
                <div class="hamburger-box">
                  <div class="hamburger-inner"></div>
                </div>
            </a>
        </div>          
    </nav><!-- End of Navbar -->

    <!-- Header -->
    <header id="home" class="header">
        <div class="overlay"></div>
        <div class="header-content container">

        </div>              
    </header><!-- End of Header -->

    <!-- About section -->
    <section class="section" id="about">
        
    </section> <!-- End of About section -->


    <script src="plugins/jquery-3.4.1.min.js"></script>

    <script src="js/main.js"></script>

</body>
</html>