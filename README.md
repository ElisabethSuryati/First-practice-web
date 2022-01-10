# First-practice-web
This project apparently my university siakad web enaough
**Here the html codes:**
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>elearning undana</title>
    <style>
        body {
    background-color: #f5f5f5;
}

.header {
    background-color: #66cc00;
}

.header .login {
    background-color: #008000;
    width: 100%;
    height: 60px;
}

.header .login p {
    text-align: right;
}

.header .login p a {
    text-decoration: none;
    color: #ffffff;
    transition: .3s;
}

.header .login p a:hover {
    color: #d2691e;
}

.header .pic {
    width: 100%;
    height: 200px;
}

.header .pic img {
    width: 120px;
    height: auto;
    float: left;
    margin: 10px 0 0 30px;
}

.header .logo {
    text-transform: uppercase;
    margin-top: -190px;
    margin-left: 0;
    margin-bottom: 0;
}

.header .logo h2 {
    text-decoration-line: underline;
    font-weight: 800;
    text-indent: -20px;
    font-size: 30px;
    letter-spacing: 12px;
}

.header .logo h4 {
    font-size: 15px;
    text-indent: -20px;
    font-weight: 800;
}

.header .menu ul {
    float: center;
}

.header .menu ul li {
    display: inline-block;
    padding: 30px;
    margin-left: 10px;
}

.header .menu ul li a {
    color: #ffffff;
    text-decoration: none;
}

.pengisian {
    background-color: #228b22;
    border-radius: 5px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
    width: 300px;
    padding: 20px 30px;
    margin-top: 50px;
    margin-left: 10px;
    height: auto;
}

.pengisian h1 {
    text-align: center;
    margin: 0 0 20px;
    font-size: 24px;
}

.input {
    margin-bottom: 20px;
    position: relative;
}

.input label {
    display: block;
    margin-bottom: 10px;
}

.input input {
    width: 160px;
    height: 40px;
    padding: 0 15px;
    background-color: #ffffff;
    border: 2px solid #ffffff;
    border-radius: 5px;
}

.input small {
    display: block;
    color: #800000;
    font-weight: bold;
    font-size: 11px;
    padding-top: 3px;
    visibility: hidden;
}

button {
    width: 100px;
    height: 40px;
    background-color: #ffffff;
    border: 1px solid #fff;
    border-radius: 5px;
    cursor: pointer;
    display: block;
    font-size: 16px;
}

.rumit {
    background-color: #66cc00;
    margin-top: 50px;
    position: relative;
    width: 100%;
    height: 100%;
    margin-bottom: 0;
    padding-top: 50px;
    padding-bottom: 20px;
}

.rumit .gambar img {
    width: 80px;
    height: auto;
    margin-top: -30px;
    margin-left: 30px;
}

.rumit .dua {
    margin-left: 100px;
    margin-top: -50px;
    text-transform: uppercase;
    font-weight: 800;
    font-size: 10px;
    text-indent: -5px;
}

.rumit .dua h2 {
    text-decoration: underline;
    font-weight: 900;
}

.rumit .dua h4 {
    font-weight: 900;
}

.rumit .mandiri {
    margin-left: 60px;
    margin-top: 18px;
    text-indent: 15px;
}

.rumit .mandiri p {
    color: #ffffff;
    font-weight: 500;
}

.rumit .quick {
    margin-left: 500px;
    margin-top: -80px;
    text-decoration: none;
    color: #ffffff;
}

.rumit .quick h4 {
    margin-bottom: 30px;
    font-weight: lighter;
}

.rumit .quick ul li {
    text-decoration: none;
    display: flex;
}

.rumit .quick ul li a {
    color: #ffffff;
    text-decoration: none;
}

.rumit .media {
    margin-left: 700px;
    margin-top: -100px;
    text-decoration: none;
    color: #ffffff;
}

.rumit .media h4 {
    margin-bottom: 30px;
    font-weight: lighter;
}

.rumit .media ul li {
    color: #ffffff;
    text-decoration: none;
    display: flex;
}

.rumit .media ul li a {
    text-decoration: none;
    color: #ffffff;
}

.rumit .contact {
    margin-left: 900px;
    margin-top: -115px;
}

.rumit .contact h4 {
    margin-bottom: 30px;
    font-weight: lighter;
    color: #ffffff;
}

.rumit .contact ul li {
    color: #ffffff;
    text-decoration: none;
    display: flex;
}

.rumit .contact ul li a {
    color: #ffffff;
}

.footer {
    background-color: #008000;
    text-align: center;
    padding: 20px;
}

.footerr p a {
    color: #008000;
}

    </style>
</head>

<body>
    <div class="header">
        <div class="login">
            <br>
            <p><a href="">You are not logged in</a></p>
        </div>
        <div class="pic">
            <img src="undana.png">
        </div>
        <div class="logo">
            <h2>Undana</h2>
            <h4>Universitas nusa cendana</h4>
        </div>
        <br>
        <div class="menu">
            <ul>
                <li><a href="">Dashboard</a></li>
                <li><a href="">Site Home</a></li>
                <li><a href="">Panduan E-learning</a></li>
                <li><a href="">Cari Mata Kuliah</a></li>
                <li><a href="">Evaluasi Pembelajaran</a></li>
                <li><a href="">Panduan Integrasi SPADA</a></li>
            </ul>
        </div>
    </div>
    <div class="pengisian">
        <h1>Login into your account</h1>
        <form action="" id="form" class="form">
            <div class="input">
                <label for="username">Username</label>
                <input type="text" name="username" id="username" placeholder="Username" autocomplete="off">
                <small>Error message</small>
            </div>
            <div class="input">
                <label for="c-passwrod">Confimer Passwrod</label>
                <input type="password" name="c-password" id="c-password" placeholder="Password">
                <small>Error message</small>
            </div>
        </form>
        <button>Submit</button>
    </div>
    <div class="rumit">
        <div class="gambar">
            <img src="undana.png">
        </div>
        <div class="dua">
            <h2>Undana</h2>
            <h4>Universitas nusa cendana</h4>
        </div>
        <div class="mandiri">
            <p>Media Belajar Mandiri</p>
        </div>
        <div class="quick">
            <h4>Quick Links</h4>
            <ul>
                <li><a href="">About Us</a></li>
                <li><a href="">Visi & Misi</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </div>
        <div class="media">
            <h4>Follow Us</h4>
            <ul>
                <li><a href="">Facebook</a></li>
                <li><a href="">Twitter</a></li>
                <li><a href="">Google Plus</a></li>
                <li><a href="">Pinterest</a></li>
            </ul>
        </div>
        <div class="contact">
            <h4>Contact</h4>
            <ul>
                <li>Jl. Adisucipto, Penfui</li>
                <li>Phone (0380) 881580</li>
                <li>E-mail <a href="">info@undana,ac,id</a></li>
            </ul>
        </div>
    </div>
    <div class="footer">
        <p>Copyright &copy; 2015-Developed by LMSACE.com.Powered by Moodle</p>
    </div>
    <div class="footerr">
        <p><a href="">Data retention summary</a></p>
        <p><a href="">Get the mobile app</a></p>
    </div>
</body>

</html>
    **Hey guys if you find those codes and I am really sure that that one has very much bugs, I am begged for your kindness to correct them right. Anyway, I am just begginer so your help will be very mean to me**
