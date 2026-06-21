# SENSEI-SS-DYNAMIC-SS-DYNAMIC-CARGO
SENSEI SS DYNAMIC & SS DYNAMIC CARGO
CBM CALCULATOR
VOLUMETRIC CARCULATOR
CBM - WEIGHT KG CONVERTER
WEIGHT KG - CBM CONVERTER
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0"><title>𝐒𝐄𝐍𝐒𝐄𝐈 𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂 | 𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂 𝐂𝐀𝐑𝐆𝐎</title><style>

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

.hero{
background:linear-gradient(rgba(0,0,0,.8),rgba(0,0,0,.8)),
url('https://images.unsplash.com/photo-1521295121783-8a321d551ad2');
background-size:cover;
background-position:center;
padding:80px 20px;
text-align:center;
}

.hero h1{
font-size:50px;
color:red;
}

.hero h2{
margin-top:10px;
}

.flags{
font-size:50px;
margin-bottom:20px;
}

.container{
max-width:1200px;
margin:auto;
padding:40px 20px;
}

.card{
background:#111;
padding:25px;
border-radius:15px;
border:1px solid #333;
margin-bottom:25px;
}

.title{
color:red;
margin-bottom:20px;
font-size:30px;
text-align:center;
}

input{
width:100%;
padding:12px;
margin-top:10px;
margin-bottom:10px;
background:#222;
border:none;
border-radius:8px;
color:white;
}

button{
width:100%;
padding:15px;
background:red;
color:white;
border:none;
border-radius:8px;
cursor:pointer;
font-size:16px;
font-weight:bold;
}

button:hover{
background:#cc0000;
}

.result{
margin-top:15px;
font-size:24px;
font-weight:bold;
color:#00ff88;
text-align:center;
}

.links{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
}

.links a{
background:#111;
padding:20px;
border-radius:12px;
text-decoration:none;
color:white;
border:1px solid #333;
text-align:center;
}

.links a:hover{
border-color:red;
}

footer{
background:#111;
padding:30px;
text-align:center;
margin-top:50px;
}

</style></head><body><section class="hero"><div class="flags">
🇨🇳 🇲🇾
</div><h1>𝐒𝐄𝐍𝐒𝐄𝐈 𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂</h1><h2>𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂 𝐂𝐀𝐑𝐆𝐎</h2><p>China Import • Cargo Forwarder • RMB Converter • CBM Tools</p></section><div class="container"><div class="card"><h2 class="title">RMB ➜ MYR CONVERTER</h2><input type="number" id="rmb" placeholder="Enter RMB"><button onclick="convertRMB()">
Convert RMB To MYR
</button><div class="result" id="rmbResult">
RM 0.00
</div></div><div class="card"><h2 class="title">CBM CALCULATOR</h2><input type="number" id="length" placeholder="Length (cm)">
<input type="number" id="width" placeholder="Width (cm)">
<input type="number" id="height" placeholder="Height (cm)"><button onclick="calculateCBM()">
Calculate CBM
</button><div class="result" id="cbmResult">
0.000 CBM
</div></div><div class="card"><h2 class="title">VOLUMETRIC WEIGHT</h2><input type="number" id="vlength" placeholder="Length (cm)">
<input type="number" id="vwidth" placeholder="Width (cm)">
<input type="number" id="vheight" placeholder="Height (cm)"><button onclick="calculateVolumetric()">
Calculate KG
</button><div class="result" id="volResult">
0 KG
</div></div><div class="card"><h2 class="title">CBM ➜ KG CONVERTER</h2><input type="number" id="cbmkg" placeholder="Enter CBM"><button onclick="cbmToKg()">
Convert
</button><div class="result" id="cbmkgResult">
0 KG
</div></div><div class="card"><h2 class="title">KG ➜ CBM CONVERTER</h2><input type="number" id="kgcbm" placeholder="Enter Weight KG"><button onclick="kgToCbm()">
Convert
</button><div class="result" id="kgcbmResult">
0 CBM
</div></div><div class="card"><h2 class="title">USEFUL LINKS</h2><div class="links"><a href="https://www.xe.com" target="_blank">
XE Currency Converter
</a><a href="https://wise.com" target="_blank">
Wise
</a><a href="https://www.westernunion.com" target="_blank">
Western Union
</a><a href="https://www.xtransfer.com" target="_blank">
XTransfer
</a><a href="https://www.google.com/finance/beta/quote/CNY-MYR" target="_blank">
Google Finance CNY/MYR
</a></div></div></div><footer><h2 style="color:red;">
𝐒𝐄𝐍𝐒𝐄𝐈 𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂
𝐒𝐞𝐧𝐬𝐞𝐢𝐒𝐒𝐃𝐲𝐧𝐚𝐦𝐢𝐜
#SenseiSSDynamic
</h2><h3>
𝐒𝐒 𝐃𝐘𝐍𝐀𝐌𝐈𝐂 𝐂𝐀𝐑𝐆𝐎
𝐒𝐒𝐃𝐲𝐧𝐚𝐦𝐢𝐜𝐂𝐚𝐫𝐠𝐨
#SSDynamicCargo
</h3><p>
China Warehouse | Cargo Consolidation | Air Freight | Sea Freight
</p><p>
🇨🇳 CHINA ➜ 🇲🇾 MALAYSIA
</p></footer><script>

function convertRMB(){

let rmb=document.getElementById("rmb").value;

let rate=0.65;

let myr=rmb*rate;

document.getElementById("rmbResult").innerHTML=
"RM "+myr.toFixed(2);

}

function calculateCBM(){

let l=document.getElementById("length").value;
let w=document.getElementById("width").value;
let h=document.getElementById("height").value;

let cbm=(l*w*h)/1000000;

document.getElementById("cbmResult").innerHTML=
cbm.toFixed(3)+" CBM";

}

function calculateVolumetric(){

let l=document.getElementById("vlength").value;
let w=document.getElementById("vwidth").value;
let h=document.getElementById("vheight").value;

let kg=(l*w*h)/6000;

document.getElementById("volResult").innerHTML=
kg.toFixed(2)+" KG";

}

function cbmToKg(){

let cbm=document.getElementById("cbmkg").value;

let kg=cbm*167;

document.getElementById("cbmkgResult").innerHTML=
kg.toFixed(2)+" KG";

}

function kgToCbm(){

let kg=document.getElementById("kgcbm").value;

let cbm=kg/167;

document.getElementById("kgcbmResult").innerHTML=
cbm.toFixed(3)+" CBM";

}

</script></body>
