<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Hocco Eatery Naranpura – Menu</title>
<link href="https://fonts.googleapis.com/css2?family=Bowlby+One&family=Hind:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#FFC93C;--ink:#1B1210;--card:#FFFFFF;--mute:#5A4636;--red:#E63B2E;--green:#1F9D55;--pink:#FF7EB6;--blue:#3D8BFF;--orange:#FF8A2B}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#241812;--ink:#FFF3D6;--card:#33231A;--mute:#CDB79A}}
:root[data-theme="dark"]{--bg:#241812;--ink:#FFF3D6;--card:#33231A;--mute:#CDB79A}
:root{box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 70px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--ink);font:600 16px/1.45 Hind,system-ui,sans-serif;
background-image:radial-gradient(color-mix(in srgb,var(--ink) 14%,transparent) 1.5px,transparent 1.6px);background-size:18px 18px}
body::before{content:"";position:fixed;inset:0 0 auto;height:env(safe-area-inset-top,0px);background:var(--bg);z-index:20}
.ticker{background:var(--ink);color:var(--bg);overflow:hidden;white-space:nowrap;padding:8px 0;font:400 .95rem "Bowlby One",Impact,sans-serif}
.ticker div{display:inline-block;padding-left:100%;animation:run 28s linear infinite}
@keyframes run{to{transform:translateX(-100%)}}
@media (prefers-reduced-motion:reduce){.ticker div{animation:none;padding-left:12px}}
header{text-align:center;padding:34px 16px 18px}
h1{font:400 clamp(3rem,15vw,6rem)/.9 "Bowlby One",Impact,sans-serif;margin:0;color:var(--red);text-shadow:4px 4px 0 var(--ink);-webkit-text-stroke:2px var(--ink);letter-spacing:1px}
.tag{display:inline-block;margin-top:18px;background:var(--green);color:#fff;border:3px solid var(--ink);box-shadow:4px 4px 0 var(--ink);padding:4px 16px;font:400 1.2rem "Bowlby One",Impact,sans-serif;transform:rotate(-3deg)}
.say{margin:18px 0 0;font-weight:700}
.call{display:inline-block;margin-top:14px;background:var(--card);color:var(--ink);border:3px solid var(--ink);box-shadow:4px 4px 0 var(--ink);padding:8px 20px;border-radius:999px;font-weight:700;text-decoration:none}
.call:active{transform:translate(3px,3px);box-shadow:1px 1px 0 var(--ink)}
nav{position:sticky;top:env(safe-area-inset-top,0px);z-index:10;display:flex;gap:10px;overflow-x:auto;padding:10px 14px;background:var(--bg);border-block:3px solid var(--ink);scrollbar-width:none}
nav a{flex:none;background:var(--c);color:#fff;text-decoration:none;font-weight:700;padding:5px 14px;border:3px solid var(--ink);border-radius:999px;box-shadow:2px 2px 0 var(--ink)}
nav a:focus-visible{outline:3px solid var(--ink);outline-offset:2px}
main{max-width:860px;margin:0 auto;padding:10px 16px 30px}
section{margin-top:44px}
h2{display:inline-block;margin:0 0 20px -4px;background:var(--c);color:#fff;border:3px solid var(--ink);box-shadow:5px 5px 0 var(--ink);padding:6px 18px;font:400 clamp(1.5rem,6vw,2.2rem)/1.1 "Bowlby One",Impact,sans-serif;transform:rotate(-2deg)}
section:nth-of-type(even) h2{transform:rotate(1.5deg)}
.note{margin:-8px 0 16px;font-weight:700;color:var(--mute)}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(290px,1fr));gap:18px}
.item{position:relative;background:var(--card);border:3px solid var(--ink);box-shadow:5px 5px 0 var(--c);border-radius:14px;padding:14px 84px 14px 16px;min-height:76px}
.item b{display:block;font-size:1.12rem;line-height:1.2;font-weight:700}
.item p{margin:6px 0 0;color:var(--mute);font-size:.9rem;font-weight:500}
.price{position:absolute;top:-12px;right:-8px;min-width:64px;text-align:center;background:var(--c);color:#fff;border:3px solid var(--ink);border-radius:999px;padding:3px 10px;font:400 1.05rem "Bowlby One",Impact,sans-serif;transform:rotate(6deg)}
.combo .item{border-style:dashed;box-shadow:5px 5px 0 var(--ink)}
.combo .item::after{content:"COMBO";position:absolute;bottom:-11px;left:14px;background:var(--ink);color:var(--bg);font:400 .7rem "Bowlby One",Impact,sans-serif;padding:2px 8px;border-radius:4px;letter-spacing:1px}
footer{text-align:center;padding:10px 16px 40px;font-weight:700}
footer a{color:var(--ink)}
</style>
</head>
<body>
<div class="ticker"><div id="tk"></div></div>
<header>
<h1>HOCCO<br>EATERY</h1>
<span class="tag">Naranpura</span>
<p class="say">OG flavour, new vibes!</p>
<a class="call" href="tel:+919712971261">📞 Call 097129 71261</a>
</header>
<nav id="nav"></nav>
<main id="menu"></main>
<footer>Hocco Eatery Naranpura · <a href="tel:+919712971261">097129 71261</a></footer>
<script>
const M=[
{t:"🫓 Hocco Classics",k:"red",i:[["Chana Puri",250,"Guaranteed one of the BEST in the world"],["Chana Kulcha",250],["Pav Bhaji",250],["Aloo Paratha",150],["Vegetable Cutlet",100,"OG Flavour, New vibes!"],["Punjabi Samosa",80,"A timeless classic with our original recipe"],["Gulab Jamun",50]]},
{t:"🍟 Fries",k:"orange",i:[["Classic Salted Fries",130],["Double Cheese Fries",170],["Chilli Cheese Fries",170,"Creamy cheese meets spicy Sriracha and crunchy green chillies – fries that bite back, in the best way"],["Peri Peri Cheese Fries",170,"Tangy, cheesy, and a little wild – Peri Peri spice and mayo turn these fries into a true flavour bomb"],["BBQ Cheese Fries",170,"Smoky BBQ sauce, melted cheese, and crunchy onions over hot fries – the perfect cheat-day indulgence"],["Korean Spicy Fries",170,"A fiery pile of fries loaded with Sriracha, gooey cheese, crunchy onions, and jalapeños – spicy, cheesy, snack time perfection"],["Chipotle Cheese Fries",170,"Smoky chipotle hits you first, then the cheese melts in – spicy, creamy, and crunchy. These fries don’t play nice"]]},
{t:"🍔 Burgers",k:"green",i:[["Paneer Taka Tak Burger",120],["Veggie Burger",90],["Cheese Aloo Tikki Burger",70],["Aloo Tikki Burger",49]]},
{t:"🥤 Beverages",k:"blue",n:"Coke, Thums Up, packaged drinks and water are sold at MRP",i:[["Coke Float",70],["Masala Chaas",40],["Coke","MRP"],["Thums Up","MRP"],["Packaged Drinks","MRP"],["Water / Aerated Water","MRP"]]},
{t:"🍫 Shakes",k:"pink",i:[["Vanilla",95],["Strawberry",95],["Classic Cold Coffee",135],["Kesar Pista",135],["Chocolate Overload",135],["Chocolate Strawberry",135],["Dry Fruit",160],["Oreo Blast",160],["Belgian Choconut",165],["Biscoff",170],["Nutella",180]]},
{t:"➕ Add On",k:"orange",i:[["Chana",190],["Bhaji",190],["Puri",60],["Kulcha",30],["Pav",30],["Bread Butter",80],["Extra Cheese",40]]},
{t:"🎁 Super Saver Combos",k:"red",c:1,i:[["Pav Bhaji & Pulao Combo",469,"Pav Bhaji + Butter Pulao + 1 Masala Chaas"],["Chana Kulcha & Pulao Combo",469,"Chana Kulcha + Butter Pulao + 1 Masala Chaas"],["Chana Puri & Pulao Combo",469,"Chana Puri + Butter Pulao + 1 Masala Chaas"],["Mexican Rice & Wrap Combo",399,"Cheese and Herb rice + Oh Mexicana Wrap"],["Burger Combo",111,"Aloo Tikki Burger + Classic Salted Fries (80g)"]]}
];
document.getElementById('tk').textContent=['Chana Puri','Pav Bhaji','Cheese Fries','Taka Tak Burger','Nutella Shake','Gulab Jamun'].map(x=>x.toUpperCase()+' ★').join('   ').repeat(2);
const nav=document.getElementById('nav'),menu=document.getElementById('menu');
M.forEach((s,n)=>{
 const id='s'+n,c=`style="--c:var(--${s.k})"`;
 nav.insertAdjacentHTML('beforeend',`<a href="#${id}" ${c}>${s.t}</a>`);
 const cards=s.i.map(([a,p,d])=>`<div class="item"><b>${a}</b>${p?`<span class="price">${p==='MRP'?'MRP':'₹'+p}</span>`:''}${d?`<p>${d}</p>`:''}</div>`).join('');
 menu.insertAdjacentHTML('beforeend',`<section id="${id}" ${c}><h2>${s.t}</h2>${s.n?`<p class="note">${s.n}</p>`:''}<div class="grid${s.c?' combo':''}">${cards}</div></section>`);
});
</script>
</body>
</html>
