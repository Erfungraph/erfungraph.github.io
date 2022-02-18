# erfungraph.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MacBook</title>
  <style>@font-face {
    font-family: ubunto;
    src: url(/project1/src/font/Ubuntu/Ubuntu-Regular.ttf);
}

* {
    margin: 0;
    padding: 0;
}

body {
    font-family: ubunto;
    vertical-align: top;
}

.main {
    position: absolute;
    top: 0;
    width: 100%;
    height: 8000px;
    background-color: rgb(255, 255, 255);
}

#headerphoto {
    width: 100%;
    position: absolute;
    top: 0;
    z-index: 5;
}

.navigation-bar {
    display: inline-block;
    vertical-align: middle;
    list-style: none;
    opacity: 50%;
    position: fixed;
    top: 0;
    z-index: 100;
    background-color: rgb(255, 255, 255);
    width: 100%;
    height: 25px;
    padding: 20px;
}

.navigation-bar ul {
    vertical-align: middle;
    display: inline-block;
}

.navigation-bar a {
    text-decoration: none;
    color: #222;
    font-size: 20px;
    vertical-align: middle;
}

.navigation-bar {
    display: inline-block;
    vertical-align: middle;
}

.navigation-bar ul b li {
    vertical-align: middle;
    list-style: none;
    display: inline-block;
    width: 150px;
}

.navigation-bar a:hover {
    color: rgb(151, 151, 151);
}

.navigation-bar img {
    margin-right: 40px;
    display: inline-block;
    vertical-align: middle;
}

.profile-img {
    z-index: 7;
    position: relative;
    top: 10%;
    margin-left: 42.8%;
    margin-right: auto;
}

.htext {
    font-size: 34px;
    z-index: 8;
    position: relative;
    top: 2%;
    text-align: center;
    color: #fff;
    margin-left: 0;
    margin-right: 0;
    animation-name: htext;
    animation-duration: 1s;
    animation-timing-function: ease;
    animation-delay: 0s;
    animation-direction: alternate;
}

@keyframes htext {
    from {
        top: 2.5%;
        color: rgba(255, 255, 255, 0);
    }
    to {
        top: 2%;
        color: rgba(255, 255, 255, 1);
    }
}

.htext span {
    font-size: 30px;
}

.information {
    position: relative;
    top: 10.5%;
    left: 29.4%;
    text-align: center;
    width: 40%;
    height: auto;
}

.information h2 {
    font-size: 27px;
    margin-bottom: 8px;
}

.information span {
    color: rgb(177, 177, 177);
    font-size: 23px;
}

.afterinfo {
    margin-left: auto;
    margin-right: auto;
    position: relative;
    top: 11.5%;
    border: none;
    background-color: black;
    height: 4px;
    width: 14%;
    margin-top: 3%;
    margin-bottom: 4%;
}</style>
</head>

<body>
    <div class="main">
        <img id="headerphoto" src="/project1/HEADER/header photo.jpg" alt="">
        <nav class="navigation-bar">
            <ul>
                <img src="/project1/HEADER/LOGO.png" width="50px">
                <b><li><a href="https://instagram.com/erfungraph">INSTAGRAM</a></li>
                <li><a href="mailto:/efungraph@gmail.com">EMAIL</a></li>
                <li><a href="https://t.me/erfungraph">TELEGRAM</a></li>
                <li><a href="https://wa.me/+989162630612">WHATSAPP</a></li></b>

            </ul>
        </nav>
        <img class="profile-img" src="/project1/HEADER/profile image.png" width="15%">
        <div class="htext">
            <h1>HI, I'M ERFUNGRAPH</h1>
            <span>Graphic designer & Fron end developer</span>
        </div>
        <div class="information">
            <h2>
                <b>MOHAMMAD ERFAN GHODOOSI</b>
            </h2>
            <span>Visual Artist , Front End Developer , Video Creator</span>
        </div>
        <hr class="afterinfo">

    </div>
</body>

</html>
