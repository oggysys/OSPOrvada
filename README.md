<!DOCTYPE html>
<html lang="gu">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>OSP Orvada</title>

<style>
body{
margin:0;
font-family: 'Segoe UI', sans-serif;
background: linear-gradient(135deg,#141e30,#243b55);
color:white;
text-align:center;
overflow-x:hidden;
}

/* Logo Glow */
.logo{
width:120px;
height:120px;
margin:30px auto 10px;
border-radius:50%;
background: radial-gradient(circle,#00f2fe,#4facfe);
display:flex;
align-items:center;
justify-content:center;
font-size:35px;
font-weight:bold;
box-shadow:0 0 40px #00f2fe,0 0 80px #4facfe;
animation: pulse 2s infinite alternate;
}

@keyframes pulse{
from{transform:scale(1);}
to{transform:scale(1.08);}
}

h1{
font-size:32px;
margin:10px 0;
}

.subtitle{
color:#00f2fe;
margin-bottom:25px;
font-size:18px;
}

/* Services Grid */
.services{
display:grid;
grid-template-columns:1fr 1fr;
gap:15px;
padding:0 20px;
max-width:500px;
margin:auto;
}

.service-btn{
padding:15px;
border-radius:15px;
font-weight:bold;
cursor:pointer;
transition:0.3s;
box-shadow:0 0 20px rgba(255,255,255,0.2);
}

.service-btn:hover{
transform:scale(1.05);
box-shadow:0 0 30px white;
}

/* Different Colors */
.btn1{background:linear-gradient(45deg,#ff512f,#dd2476);}
.btn2{background:linear-gradient(45deg,#24c6dc,#514a9d);}
.btn3{background:linear-gradient(45deg,#00b09b,#96c93d);}
.btn4{background:linear-gradient(45deg,#f7971e,#ffd200);}
.btn5{background:linear-gradient(45deg,#e43a15,#e65245);}
.btn6{background:linear-gradient(45deg,#396afc,#2948ff);}
.btn7{background:linear-gradient(45deg,#8e2de2,#4a00e0);}
.btn8{background:linear-gradient(45deg,#ff9966,#ff5e62);}
.btn9{background:linear-gradient(45deg,#00f260,#0575e6);}

/* Contact */
.contact{
margin-top:30px;
font-size:18px;
line-height:1.8;
}

/* WhatsApp Button */
.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 18px;
border-radius:50%;
font-size:22px;
text-decoration:none;
box-shadow:0 0 20px #25D366;
animation: glow 1.5s infinite alternate;
}

@keyframes glow{
from{box-shadow:0 0 10px #25D366;}
to{box-shadow:0 0 30px #25D366;}
}

</style>
</head>

<body>

<div class="logo">OSP</div>

<h1>ઓનલાઇન સર્વિસ પોઇન્ટ</h1>
<div class="subtitle">Cyber Cafe & Digital Services - Orvada</div>

<div class="services">
<div class="service-btn btn1">PAN Card સેવા</div>
<div class="service-btn btn2">Aadhaar Update</div>
<div class="service-btn btn3">Voter ID</div>
<div class="service-btn btn4">Digital Signature</div>
<div class="service-btn btn5">Online Form</div>
<div class="service-btn btn6">Light Bill ચુકવણી</div>
<div class="service-btn btn7">Ticket Booking</div>
<div class="service-btn btn8">7/12 & 8A સેવા</div>
<div class="service-btn btn9">eShram Card</div>
</div>

<div class="contact">
📞 9773167763 <br>
📷 Instagram: @osp_orvada <br>
📧 opsorvada@gmail.com
</div>

<a class="whatsapp" href="https://wa.me/919773167763" target="_blank">💬</a>

</body>
</html>
