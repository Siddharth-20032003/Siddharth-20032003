<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
      integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
      crossorigin="anonymous"
      referrerpolicy="no-referrer"
    />
    <title>Document</title>
  </head>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    .main {
      width: 100%;
      height: 100vh;
    }
    .header {
      width: 100%;
      height: 50px;
      background-color: orange;
      display: flex;
    }

    .logo {
      width: 10%;
      height: 50px;
    }

    .logo > a > img {
      width: 100%;
      height: 100%;
    }

    .search {
      width: 60%;
      height: 100%;
      background-color: aqua;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 25px;
    }

    .search > input {
      padding: 7px;
    }

    .search > a > button {
      padding: 7px;
    }

    .menu {
      width: 30%;
      height: 100%;
      background-color: blueviolet;
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 25px;
    }

    .menu > button {
      padding: 7px;
      border: none;
      border-radius: 20px;
    }

    #log {
      background-color: rgb(30, 255, 86);
    }

    #sign {
      background-color: rgb(235, 131, 11);
    }
  </style>
  <style>
    .banner {
      height: 39%;
      width: 100%;
      background-color: rgb(196, 47, 47);
    }
    .image {
      height: 100%;
      width: 100%;
      background-color: green;
    }
    .banner > .image > img {
      height: 100%;
      width: 100%;
    }
    #footer {
      height: 70px;
      width: 100%;
      background-color: black;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    #social {
      color: white;
    }
    #footer > .bekar {
      color: white;
    }
    #social > a > img {
      height: 50px;
      width: 50px;
    }

    .poster {
      height: 40%;
      width: 100%;
      background-color: white;
      box-shadow: 0px 0px 10px gray;
      display: flex;
    }
    .writings {
      display: flex;
      width: 100%;
      height: 352px;
      font-family: "Arial";
    }
    .notes {
      width: 33.33%;
      overflow: auto;
    }
    .notes > p {
      font-size: 25px;
    }
    .poster {
      width: 33.33%;
      height: 100%;
    }
    .poster > img {
      width: 100%;
      height: 100%;
    }
    .video {
      width: 33.33%;
    }

    .video > .typed {
      overflow: hidden;
      white-space: nowrap;
      border-right: 2px solid;
      width: 0;
      animation: typing 5s steps(30, end) forwards, blinking 1s infinite;
    }
    @keyframes typing {
      from {
        width: 0;
      }
      to {
        width: 50%;
      }
    }
    @keyframes blinking {
      0% {
        border-right-color: transparent;
      }
      50% {
        border-right-color: rgb(0, 0, 0);
      }
      100% {
        border-right-color: transparent;
      }
    }

    .writing > .poster {
      overflow: hidden;
    }
  </style>
  <body>
    <div class="main">
      <div class="header">
        <div class="logo">
          <a href="">
            <img src="shopping9.gif" alt="not load" />
          </a>
        </div>
        <div class="search">
          <input type="text" placeholder="Search" />
          <a href="#"> <button>search</button></a>
          <a href="#"> <button>services</button></a>
          <a href="#"> <button>contact</button></a>
        </div>
        <div class="menu">
          <button id="log">LOG IN</button>
          <button id="sign">SIGN UP</button>
        </div>
      </div>
      <div class="banner">
        <div class="image">
          <img src="flipkart about.gif" alt="" />
        </div>
      </div>
      <div class="writings">
        <div class="notes">
          <h1><u>LEAVE A MARK</u></h1>
          <p class="typed">
            <strong
              >We're known more by the impact we create<br />
              than the titles we hold. Impact that is brought by<br />
              working together on audacious challenges at scale<br />
              with an aim to revolutionize for the Indian customer.<br />
              We believe great ideas can emerge from anywhere<br />
              and must be backed. Our people - backed by our<br />
              culture of end-to-end ownership - have revolutionised<br />
              India's e-commerce sector - several times over...!
            </strong>
          </p>
        </div>
        <div class="poster">
          <img src="leave a mark.png" alt="" />
        </div>
        <div class="video">
          <iframe
            width="100%"
            height="100%"
            src="https://www.youtube.com/embed/aFZYw8JFgec?si=lryJ8lOu2C_j4vAI"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen
          ></iframe>
        </div>
      </div>
      <div id="footer">
        <div class="bekar">Copyright &copy; All Right Reserve</div>
        <div id="social">
          Follow Us:
          <a href="https://twitter.com" target="_self">
            <img src="twitter.png" />
          </a>
          <a href="https://whatsapp.com" target="_blank">
            <img src="whatsapp.png" />
          </a>
          <a href="https://web.facebook.com/" target="_blank">
            <img src="fb.png"
          /></a>
        </div>
      </div>
    </div>
  </body>
</html>
