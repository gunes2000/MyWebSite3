# MyWebSite2
 <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Nisanur GÜNEŞ</title>
        <link rel="stylesheet" href="Site.css">
    </head>

    <body>
        <header id="header">
            <div class="header">
                <div class="header-navbar">
                    <h2>Blog</h2>
                </div>
                <div class="header-menu">
                    <ul>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Özgeçmiş</a></li>
                        <li><a href="#">Yetenekler</a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div>
                <h1><span class="first-letter">B</span></h1>
            </div>
            
            </div>
        </header>
    </body>
</html>
//CSS----------------------------------------------------------

@import url('https://fonts.googleapis.com/css2?family=Kalam&family=Poppins:ital,wght@1,400;1,500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kalam:wght@400;700&family=Poppins:ital,wght@1,400;1,500&display=swap');
.container{
    max-width: 1170px;
    margin: 0 auto;
    padding:0 15px;



}

.header{
    background-image: url(cicek.jpg);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    height: 105vh;
}
.header-navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0px 0;
}

ul{
    display: flex;
}
li{
    margin-left: 27px;

}
li:first-child{
    margin-right: 70px;
}
a{
    color:black;
    font-weight: bold;
    font-size: 20px;
}