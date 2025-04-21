index.html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="main.css">
</head>
<body>
    <div class="wrapper">
        <header class="header">
            <div class="container">
              <div class="head-first">
                <a href="" class="logo">
                  <img src="https://s3-alpha-sig.figma.com/img/328b/1ecc/a8f4172a6ee9ae30205716457a19f985?Expires=1745798400&Key-Pair-Id=APKAQ4GOSFWCW27IBOMQ&Signature=Ve1xyH7PmWZWAy3YhUpPq-x4cfqmHuDwKWBRqi8J9ZejPKL5Km5VagpQ0K0yVqXcF1x4kzHiQZslWlbeOmOSkDb7ZmczIFlPD56Uu5EI-G8e2HJphpgPYrfFoJSHT8jpmnTalAch6O~omkRUexaEJwQwCuneeK6L3bghRFS3C4eUUQyHeabIjz6UzlHUlV5Xh3MrGrqVXPcx3C7VYrBQJJsjdcFXquihBsDnAk5D8xBHllVgiCs4i7OS-G0kBjPo9DT7xmL2r6QHDk8vywHp0G2X0FUonPqxDOAcd~XmsPx3Fd2akaQRH5QACu4L-9LCbLJ2S~~p8ghLqXJSqz6W7g__" alt="" />
                </a>
                <ul class="item">
                  <li class="item-list">
                    <a href="" class="item-link">Home</a>
                  </li>
                  <li class="item-list">
                    <a href="" class="item-link">Our Products</a>
                  </li>
                  <li class="item-list">
                    <a href="" class="item-link">Blog</a>
                  </li>
                  <li class="item-list">
                    <a href="" class="item-link">About</a>
                  </li>
                  <li class="item-list">
                    <a href="" class="item-link">Contact</a>
                  </li>
                  <li class="item-list">
                    <a href="" class="item-link">Styleguide</a>
                  </li>
                </ul>
                <div class="basket">
                  <img src="https://s3-alpha-sig.figma.com/img/e1f2/84ae/571e3fa88206d984b4a63f0307032852?Expires=1745193600&Key-Pair-Id=APKAQ4GOSFWCW27IBOMQ&Signature=iOBOdsdq6Dz9pP2l5UrjxlffPf5eufR4ssBAdFF2XXo8PU0vmViO8SX6wPoDTWfehqVnsTYScOA1NDUIJOOSQ2iWMnUOzlOk~xm-y0veH041yx6-U4rsRVAESPCSf1tP3O6q8iGXYH9bb3ChuDEoA0qygPJurDyB-ZPvBgKEW~HjXdv-SPD4smGDUTnbvYhHLnAIj9iZZTuh8yCCH0G~TJwXlF2II2oJIJ04AdzITdXFc9k9jn2WIOOXeduX5ALKI5Jdy93sgsd7g~bOWbalKT6YzjhexIouo0JINL-GqaMivy9jsrATA6nzAYn0VdzNW7JITdqIOi7FPROzyIvPrg__" class="basket-icon" alt="" />
                  <p class="basket-text">Cart</p>
                  <span class="basket-span">0</span>
                </div>
              </div>
            </div>
            <div class="head-second">
              <p class="head-second-text">Best place to buy design</p>
              <h1 class="head-second-title">Coffee Mugs</h1>
              <p class="head-second-text2">
                The most versatile furniture system ever created. Designed to fit
                your life, made to move and grow.
              </p>
              <a href="" class="head-second-button">Explore Our Products</a>
            </div>
          </header>
          <main>
            <section>
                <div class="container">
                    <h1 class="terak" >Even the all-powerful Pointing has no control about the blind texts.</h1>
                    <p class="marquez">It is a paradisematic country, in which roasted parts of sentences fly into your mouth. Even the all-powerful Pointing has no control about the blind texts it is an almost unorthographic life One day however a small line of blind text by the name of Lorem Ipsum decided to leave for the far World of Grammar.</p>
                    <h3 class="ohmy">Read the full Story</h3>
                </div>
            </section>
          </main>
    </div>
</body>
</html>
main.css:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  .header{
margin-top: 80px;
margin-left: 30px;
  }
  .wrapper {
    width: 100%;
    overflow: hidden;
  }
  .container {
    max-width: 940px;
    margin: 0 auto;
  }
  .head-first {
    display: flex;
    justify-content: space-between;
    height: 80px;
    align-items: center;
  }
  .logo {
  }
  .item {
    list-style-type: none;
    display: flex;
    gap: 30px;
  }
  .item-list {
  }
  .item-link {
    text-decoration: none;
    font-family: Karla;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: #1d1f2e;
  }
  .basket {
    display: flex;
    gap: 10px;
    align-items: center;
    padding-bottom: 5px;
    border-bottom: 2px solid #a25f4b4d;
  }
  .basket-icon {
  }
  .basket-text {
    font-family: Karla;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: #1d1f2e;
  }
  .basket-span {
    width: 20px;
    height: 18px;
    background-color: #1d1f2e;
    border-radius: 50%;
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .head-second {
    padding-top: 159px;
    width: 90%;
    height: 530px;
    background-image: url(assets/images/bc\ image\ 1.jpg);
    background-size: 100% 100%;
    background-repeat: no-repeat;
    margin: 0 auto;
  }
  .head-second-text {
    font-family: Karla;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    letter-spacing: 2px;
    text-align: center;
    text-transform: uppercase;
    color: #ffffff;
    margin-bottom: 15px;
  }
  .head-second-title {
    font-family: Karla;
    font-weight: 400;
    font-size: 47px;
    line-height: 60px;
    letter-spacing: 0%;
    text-align: center;
    margin-bottom: 15px;
    color: #ffffff;
  }
  .head-second-text2 {
    font-family: Karla;
    font-weight: 400;
    font-size: 17px;
    line-height: 30px;
    margin-bottom: 15px;
    letter-spacing: 0%;
    text-align: center;
    color: #ffffff;
  }
  .head-second-button {
    margin-bottom: 15px;
    font-family: Karla;
    font-weight: 400;
    font-size: 12px;
    line-height: 18px;
    letter-spacing: 2px;
    text-align: center;
    text-transform: uppercase;
    color: #1d1f2e;
    box-shadow: 0px 2px 6px 0px #1d1f2e1a;
    background-color: #ffffff;
    text-decoration: none;
    display: block;
    width: 231px;
    margin: 0 auto;
  }
  .terak{
    font-family: Karla;
font-weight: 400;
font-size: 28px;
line-height: 40px;
letter-spacing: 0%;
text-align: center;
margin-top: 150px;
margin-left: 3px;
  }
  .marquez{
    font-family: Karla;
font-weight: 400;
font-size: 16px;
line-height: 28px;
letter-spacing: 0%;
text-align: center;
margin-top: 99px;
margin-bottom: 100px;
  }
  .ohmy{
    font-family: Karla;
font-weight: 400;
font-size: 15px;
line-height: 28px;
letter-spacing: 0%;
text-align: center;
width: 133;
height: 28;
color: #A25F4B;
text-decoration: underline;
  }
