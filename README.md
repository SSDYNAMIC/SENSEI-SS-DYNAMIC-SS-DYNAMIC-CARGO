# SENSEI-SS-DYNAMIC-SS-DYNAMIC-CARGO
YUAN RMB - MYR @ RM CONVERTER CBM - VOLUMETRIC WEIGHT KG CARCULATOR
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>SENSEI SS DYNAMIC | SS DYNAMIC CARGO</title><style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#000;
color:#fff;
}

header{
background:linear-gradient(rgba(0,0,0,.85),rgba(0,0,0,.85)),
url('https://images.unsplash.com/photo-1521295121783-8a321d551ad2');
background-size:cover;
background-position:center;
padding:100px 20px;
text-align:center;
}

header h1{
color:#ff0000;
font-size:55px;
}

header h2{
margin-top:10px;
font-size:28px;
}

.flags{
font-size:70px;
margin:20px 0;
}

.container{
max-width:1200px;
margin:auto;
padding:40px 20px;
}

.box{
background:#111;
padding:25px;
margin-bottom:30px;
border-radius:15px;
border:1px solid #333;
}

h3{
color:#ff0000;
margin-bottom:20px;
}

input{
width:100%;
padding:12px;
margin-bottom:15px;
border:none;
border-radius:8px;
background:#222;
color:white;
}

button{
background:#ff0000;
color:white;
padding:12px 25px;
border:none;
border-radius:8px;
cursor:pointer;
font-weight:bold;
}

button:hover{
background:#cc0000;
}

.result{
margin-top:15px;
font-size:22px;
color:#00ff66;
font-weight:bold;
}

.links a{
display:block;
background:#111;
padding:15px;
margin-bottom:10px;
text-decoration:none;
color:white;
border-left:5px solid red;
border-radius:8px;
}

footer{
background:#111;
padding:30px;
text-align:center;
margin-top:50px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
width:70px;
height:70px;
background:#25D366;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
font-size:35px;
text-decoration:none;
color:white;
}

</style></head><body><header><div class="flags">
🇨🇳 🇲🇾
</div><h1>SENSEI SS DYNAMIC</h1><h2>SS DYNAMIC CARGO</h2><p>China Import • Cargo Forwarder • Borong China Specialist</p></header><div class="container"><div class="box"><h3>YUAN RMB ➜ MYR CONVERTER</h3><input type="number" id="rmb" placeholder="Enter RMB"><button onclick="convertRMB()">
Convert Now
</button><div class="result" id="rmbResult">
RM 0.00
</div></div><div class="box"><h3>CBM CALCULATOR</h3><input type="number" id="length" placeholder="Length (CM)"><input type="number" id="width" placeholder="Width (CM)"><input type="number" id="height" placeholder="Height (CM)"><button onclick="calculateCBM()">
Calculate CBM
</button><div class="result" id="cbmResult">
0.000 CBM
</div></div><div class="box"><h3>VOLUMETRIC WEIGHT CALCULATOR</h3><input type="number" id="vLength" placeholder="Length (CM)"><input type="number" id="vWidth" placeholder="Width (CM)"><input type="number" id="vHeight" placeholder="Height (CM)"><button onclick="calculateVolumetric()">
Calculate Volumetric Weight
</button><div class="result" id="volResult">
0 KG
</div></div><div class="box"><h3>CBM ➜ WEIGHT KG CONVERTER</h3><input type="number" id="cbmkg" placeholder="Enter CBM"><button onclick="convertCBMtoKG()">
Convert To KG
</button><div class="result" id="kgResult">
0 KG
</div></div><div class="box links"><h3>USEFUL CURRENCY TOOLS</h3><a href="https://www.xe.com" target="_blank">
XE Currency Converter
</a><a href="https://wise.com" target="_blank">
Wise
</a><a href="https://www.westernunion.com" target="_blank">
Western Union
</a><a href="https://www.xtransfer.com" target="_blank">
XTransfer
</a><a href="https://www.google.com/finance/beta/quote/CNY-MYR" target="_blank">
Google Finance CNY/MYR
</a></div></div><footer><h2>SENSEI SS DYNAMIC</h2><p>SS DYNAMIC CARGO</p><p>China 🇨🇳 ➜ Malaysia 🇲🇾</p><p>𝐒𝐞𝐧𝐬𝐞𝐢𝐒𝐒𝐃𝐲𝐧𝐚𝐦𝐢𝐜 & 𝐒𝐒𝐃𝐲𝐧𝐚𝐦𝐢𝐜𝐂𝐚𝐫𝐠𝐨 #SenseiSSDynamic #SSDynamicCargo</p></footer><a href="https://wa.me/601151453147"
class="whatsapp"
target="_blank">
☎
</a>

<script>

function convertRMB(){

let rmb =
parseFloat(document.getElementById('rmb').value);

let rate = 0.61;

let myr = rmb * rate;

document.getElementById('rmbResult').innerHTML =
"RM " + myr.toFixed(2);

}

function calculateCBM(){

let l =
document.getElementById('length').value;

let w =
document.getElementById('width').value;

let h =
document.getElementById('height').value;

let cbm =
(l*w*h)/1000000;

document.getElementById('cbmResult').innerHTML =
cbm.toFixed(3) + " CBM";

}

function calculateVolumetric(){

let l =
document.getElementById('vLength').value;

let w =
document.getElementById('vWidth').value;

let h =
document.getElementById('vHeight').value;

let volumetric =
(l*w*h)/6000;

document.getElementById('volResult').innerHTML =
volumetric.toFixed(2) + " KG";

}

function convertCBMtoKG(){

let cbm =
document.getElementById('cbmkg').value;

let kg =
cbm * 167;

document.getElementById('kgResult').innerHTML =
kg.toFixed(2) + " KG";

}

</script></body>
