# Clone-Facebook-Website

<h2 align="center">Clon Facebook---Sign in or register</h2>

<img src="./img/index_html.jpg">


Here's my `index.html`:

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="shortcut icon" href="./img/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="./css/style.css">

    <title>Facebook - Sign in or register</title>
</head>
<body>
    <div class="main">
        <div class="logo">
            <img src="./img/facebook.svg" alt="facebook logo">
            <div class="text-main">
                <h2>Facebook helps you connect and share with the people in your life.</h2>
            </div>
        </div>
        <div class="container">
            <input type="email" name="mail" id="mail" placeholder="Email or phone number">
            <input type="password" name="pass" id="pass" placeholder="Password">
            <button class="login-btn">Log in</button>
            <a href="#" class="text-forgot">Have you forgotten the password?</a>
            <div class="style"></div>
            <div class="create-account-btn">
                <a href="#" role="button" class="button">create new account</a>
            </div>
        </div>
        <div class="text">
            <a href="#" class="text-link">Create a page</a>
            <p>for a celebrity, a brand or a company.</p>
        </div>
    </div>
</body>
</html>
```

<img src="./img/clone-facebook-website.jpg">


Here's my `style.css`:

```css

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: Helvetica, sans-serif;
  background-color: #f0f2f5;
}
.main {
  height: 80vh;
  margin: 0px 0 200px 0;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-top: 40px;
}
.logo {
  display: flex;
  padding: 0;
  margin: 0;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.logo img {
  position: relative;
  width: 350px;
  height: 100px;
  top: 163px;
  right: 400px;
}
.logo .text-main {
  position: relative;
  width: 61%;
  top: 153px;
  right: 270px;
}
.logo h2 {
  text-align: left;
  font-size: 27px;
  font-weight: lighter;
  vertical-align: inherit;
}
.container {
  position: relative;
  width: 390px;
  height: 400px;
  display: flex;
  border: none;
  border-radius: 5px;
  align-items: center;
  flex-direction: column;
  background-color: #fff;
  box-shadow: 0 0 10px 1px rgba(0, 0, 0, 0.2);
  top: -40px;
  left: 265px;
}
input {
  width: 90%;
  height: 50px;
  margin: 20px 0 -10px 0;
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 5px;
  font-size: 17px;
  padding-left: 17px;
  font-weight: 500;
  outline-style: none;
}
input::placeholder {
  color: rgba(0, 0, 0, 0.459);
  font-weight: 500;
}
input:focus::placeholder {
  color: rgba(0, 0, 0, 0.26);
}
input:focus {
  border: 1px solid #1877f2;
  box-shadow: 0 0 1px 1px #1876f256;
}
button {
  width: 90%;
  height: 50px;
  margin: 25px;
  border: none;
  border-radius: 5px;
  background: #1877f2;
  color: #fff;
  font-size: large;
  font-weight: bold;
  cursor: pointer;
}
button:hover {
  background: #1366d1;
}
.container .create-account-btn {
  display: flex;
  width: 46%;
  height: 50px;
  border-radius: 6px;
  background: #42b72a;
  align-items: center;
  justify-content: center;
  margin: 14px 0 20px 0;
  cursor: pointer;
}
.container .create-account-btn a.button {
  color: #fff;
  font-size: 16px;
  font-weight: bold;
  text-decoration: none;
}
.container .create-account-btn:hover {
  background: #3ba327;
}
.container .text-forgot {
  position: relative;
  color: #1877f2;
  text-decoration: none;
  font-size: 14px;
  margin: 10px;
  top: -17px;
}
.container .text-forgot:hover {
  text-decoration: underline;
}
.style {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
}
.style::before {
  content: "";
  position: absolute;
  display: block;
  height: 0.1px;
  width: 350px;
  top: -10px;
  background: rgba(0, 0, 0, 0.2);
}
.main .text {
  position: relative;
  display: flex;
  margin: 20px;
  font-size: 13px;
  align-items: center;
  justify-content: center;
  bottom: 28px;
  left: 263px;
}
.main .text .text-link {
  color: #000;
  text-decoration: none;
  font-weight: bolder;
  padding-right: 3.6px;
}
.main .text .text-link:hover {
  text-decoration: 1px underline;
}
@media screen and (max-width: 950px) {
  .logo {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .logo img {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 250px;
    height: 90px;
    top: 0px;
    right: 0px;
  }
  .logo .text-main {
    position: relative;
    width: 50%;
    top: 0px;
    left: 0px;
  }
  .logo h2 {
    text-align: left;
    font-size: 24px;
    font-weight: lighter;
    vertical-align: inherit;
  }
  .container {
    position: relative;
    width: 390px;
    height: 400px;
    margin-top: 40px;
    display: flex;
    top: 0px;
    left: 0px;
  }
  .main .text {
    position: relative;
    display: flex;
    margin: 20px;
    font-size: 13px;
    align-items: center;
    justify-content: center;
    bottom: -10px;
    left: 0px;
  }
}
@media screen and (max-width: 700px) {
  .logo {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .logo img {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 450px;
    height: 100px;
    top: 0px;
    right: 0px;
  }
  .logo .text-main {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 60%;
    top: 0px;
    left: 0px;
  }
  .logo h2 {
    text-align: left;
    font-size: 24px;
    font-weight: lighter;
    vertical-align: inherit;
  }
  .container {
    position: relative;
    width: 390px;
    height: 400px;
    margin-top: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0px;
    left: 0px;
  }
  .main .text {
    position: relative;
    display: flex;
    margin: 20px;
    font-size: 13px;
    align-items: center;
    justify-content: center;
    bottom: -10px;
    left: 0px;
  }
}
@media screen and (max-width: 600px) {
  .logo {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .logo img {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 450px;
    height: 100px;
    top: 0px;
    right: 0px;
  }
  .logo .text-main {
    position: relative;
    width: 70%;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0px;
    left: 0px;
  }
  .logo h2 {
    text-align: left;
    font-size: 24px;
    font-weight: lighter;
    vertical-align: inherit;
  }
  .container {
    position: relative;
    width: 390px;
    height: 400px;
    margin-top: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0px;
    left: 0px;
  }
  .main .text {
    position: relative;
    display: flex;
    margin: 20px;
    font-size: 13px;
    align-items: center;
    justify-content: center;
    bottom: -10px;
    left: 0px;
  }
}
@media screen and (max-width: 500px) {
  .logo {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
  }
  .logo img {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 450px;
    height: 100px;
    top: 0px;
    right: 0px;
  }
  .logo .text-main {
    position: relative;
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0px;
    left: 0px;
  }
  .logo h2 {
    text-align: left;
    font-size: 24px;
    font-weight: lighter;
    vertical-align: inherit;
  }
  .container {
    position: relative;
    width: 390px;
    height: 400px;
    margin-top: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0px;
    left: 0px;
  }
  .main .text {
    position: relative;
    display: flex;
    margin: 20px;
    font-size: 13px;
    align-items: center;
    justify-content: center;
    bottom: -10px;
    left: 0px;
  }
}
```
