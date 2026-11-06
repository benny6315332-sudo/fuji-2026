[index.html](https://github.com/user-attachments/files/34458863/index.html)
# fuji-2026
FUJI 2026
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>FUJI 2026 — 富士山與東京旅程手帖</title>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter+Tight:wght@500;800&family=JetBrains+Mono:wght@400;500&family=Noto+Sans+TC:wght@400;500;700;900&display=swap">
<style>
:root{--bg:#f6f6f4;--ink:#141412;--mute:#6b6b66;--line:#d5d3ca;--card:#fff;--note:#f0eee3;--tab:#e6e3d9;--rail:#2b2b29;--ac:#d9522b;--chip:#ecebe6;
--sans:"Noto Sans TC",system-ui,sans-serif;--disp:"Inter Tight","Noto Sans TC",sans-serif;--mono:"JetBrains Mono",ui-monospace,monospace;
box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#141412;--ink:#f2f1ec;--mute:#a09f98;--line:#33332f;--card:#1d1d1a;--note:#27261f;--tab:#2b2a25;--chip:#2b2b27}}
:root[data-theme="dark"]{--bg:#141412;--ink:#f2f1ec;--mute:#a09f98;--line:#33332f;--card:#1d1d1a;--note:#27261f;--tab:#2b2a25;--chip:#2b2b27}
*,*::before,*::after{box-sizing:border-box}html{scroll-padding-top:130px}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.65 var(--sans);-webkit-text-size-adjust:100%}
a{color:inherit}button{font:inherit;color:inherit;cursor:pointer;border:0;background:none}:focus-visible{outline:2px solid var(--ac);outline-offset:3px}
.frame{max-width:720px;margin:0 auto;border-inline:1px solid var(--line);min-height:100vh}
header{display:flex;align-items:center;justify-content:space-between;gap:8px;padding:14px 18px}
.logo{display:flex;align-items:center;gap:2px;text-decoration:none;font:800 24px/1 var(--disp);letter-spacing:-.02em;flex:none}
.logo u{text-decoration-thickness:3px;text-underline-offset:4px}.logo span{font-weight:500;font-size:22px}
.logo svg{width:38px;height:23px;margin-right:2px}
.vol{font:400 9.5px/1.35 var(--mono);letter-spacing:.05em;max-width:92px;flex:1}
.tools{position:relative;flex:none}.tools>button{background:#141412;color:#fff;border-radius:999px;padding:11px 18px;font-size:14px;white-space:nowrap;box-shadow:0 0 0 1px var(--line)}
.menu{position:absolute;right:0;top:52px;width:236px;background:var(--card);border:1px solid var(--line);border-radius:26px;padding:16px;box-shadow:0 16px 44px rgba(0,0,0,.2);z-index:40}
.menu[hidden]{display:none}.menu p{margin:0 0 8px;font-size:12px;color:var(--mute)}
.chips{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:12px}
.chip{border:1px solid var(--line);border-radius:999px;padding:6px 14px;font-size:13px}
.chip[aria-pressed=true]{background:#141412;color:#fff;border-color:#141412}
.wide{width:100%;border-radius:999px;padding:11px;background:var(--chip);font-weight:500;font-size:14px}
.tabs{position:sticky;top:0;z-index:30;display:grid;grid-template-columns:repeat(4,1fr);background:var(--bg);border-block:1px solid var(--line)}
.tabs a{text-align:center;padding:15px 2px 13px;text-decoration:none;font-weight:700;font-size:14.5px;border-bottom:4px solid transparent}
.tabs a[aria-current=true]{background:var(--tab);border-color:#141412}
.panel{display:none;padding:0 0 70px}.panel.on{display:block}.pad{padding:0 22px}
/* hero */
.hero{padding:44px 22px 0}.coord{font:400 13px var(--mono);letter-spacing:.14em}
.hero h1{margin:30px 0 22px;font:800 clamp(44px,14vw,78px)/.95 var(--disp);letter-spacing:-.055em}
.hero .sub{font-size:19px;margin:0 0 30px}.hero hr{border:0;border-top:2px solid var(--line);margin:0 0 20px}
.meta{display:flex;justify-content:space-between;gap:10px;font:400 13px var(--mono);letter-spacing:.06em;flex-wrap:wrap}.meta+.meta{color:var(--mute);margin-top:12px}
.mtn{position:relative;margin:26px 0 0}.mtn canvas{display:block;width:100%;height:auto}
.pause{display:block;margin:10px 0 0 auto;border:1px solid var(--line);background:var(--bg);padding:7px 14px;font-size:12px;border-radius:999px}
.cta{display:flex;justify-content:center;align-items:center;margin:22px 22px 0;background:#141412;color:#fff;text-decoration:none;border-radius:999px;padding:20px;font-weight:700;font-size:18px}
.foot{display:flex;justify-content:space-between;padding:24px 22px;font:400 11px var(--mono);letter-spacing:.05em;color:var(--mute)}
/* glass rail */
.rail{position:sticky;top:var(--th,57px);z-index:20;background:var(--rail);border-radius:0;padding:8px 8px 10px;overflow-x:auto;scrollbar-width:none;scroll-snap-type:x proximity}
.rail::-webkit-scrollbar{display:none}
.days{position:relative;display:flex;min-width:166.66%}
.days button{position:relative;z-index:2;flex:1 0 20%;padding:13px 0;text-align:center;color:#f1f0ea;border-radius:999px;scroll-snap-align:start;font-family:var(--mono);line-height:1.5}
.days b{display:block;font-weight:400;font-size:17px;letter-spacing:.08em}.days i{display:block;font-style:normal;font-size:14px;opacity:.8}
.days button[aria-selected=true]{color:#1b1b19}
.pill{position:absolute;z-index:1;top:0;bottom:0;left:0;width:20%;border-radius:999px;
background:linear-gradient(180deg,#fbfbf9 0,#e6e5e0 60%,#d8d7d1);
box-shadow:inset 0 2px 2px #fff,inset 0 -3px 6px rgba(0,0,0,.14),0 8px 22px rgba(0,0,0,.4);
transition:transform .42s cubic-bezier(.34,1.4,.5,1)}
/* plan */
.now{margin:22px 22px 30px;border:1px solid var(--line);border-left:4px solid var(--ac);padding:16px 18px;background:var(--bg)}
.now small{display:block;color:var(--mute);font-size:13px;margin-bottom:8px}
.now div{display:flex;gap:12px;align-items:baseline;margin-bottom:4px}.now em{font:500 12px var(--mono);font-style:normal;color:var(--ac);min-width:40px}
.now summary{margin-top:10px;font-weight:700;font-size:14px;color:var(--mute);cursor:pointer;list-style:none}.now summary::-webkit-details-marker{display:none}.now details a{display:block;padding:6px 0;font-size:14px}
.dh{display:flex;gap:16px;align-items:flex-start;padding:0 22px}.dh .n{font:800 66px/.9 var(--disp);letter-spacing:-.06em}
.dh small{font:400 13px var(--mono);letter-spacing:.12em}.dh h2{margin:2px 0 4px;font:900 26px/1.25 var(--sans)}.dh p{margin:0;color:var(--mute)}
.rem{background:var(--note);border-radius:22px;margin:22px 22px 26px;padding:18px 20px}.rem h3{margin:0 0 8px;font-size:17px}.rem p{margin:0 0 8px;font-size:15.5px}.rem p:last-child{margin:0}
.tl{list-style:none;margin:0 22px;padding:0 0 0 24px;border-left:2px solid var(--line)}
.tl>li{position:relative;margin:0 0 18px;background:var(--card);border:1px solid var(--line);border-radius:26px;padding:18px}
.tl>li::before{content:"";position:absolute;left:-33px;top:26px;width:14px;height:14px;border-radius:50%;background:#141412;border:3px solid var(--bg)}
.tl>li.key{border-color:var(--ac)}.tl>li.done{opacity:.55}.tl>li.done h4{text-decoration:line-through}
.row{display:flex;justify-content:space-between;gap:12px}.t{font:400 14px var(--mono);color:var(--mute)}
.tl h4{margin:6px 0 0;font:700 21px/1.35 var(--sans)}.tl h4 em{font:500 11px var(--mono);font-style:normal;color:var(--ac);margin-left:6px}
.ph{flex:0 0 78px;height:78px;border-radius:18px;background:var(--chip);display:grid;place-items:center;font-size:30px;border:1px solid var(--line)}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin:12px 0}.tag{background:#141412;color:#fff;font-size:13px;font-weight:700;padding:4px 13px;border-radius:999px}
.desc{margin:0 0 10px;color:var(--mute);font-size:15px}
.ck{display:flex;align-items:center;gap:8px;margin:10px 0;font-size:15px}.ck input{width:22px;height:22px;accent-color:#141412;border-radius:6px}
.nt{background:var(--note);border-left:4px solid var(--ac);padding:12px 14px;margin:8px 0;font-size:15px;line-height:1.6}
.acts{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
.acts button,.acts a{font-size:14px;font-weight:700;background:var(--chip);border:1px solid var(--line);border-radius:999px;padding:9px 16px;text-decoration:none}
.more{background:var(--chip);border-radius:16px;padding:14px;margin-top:10px;font-size:14.5px}.more[hidden]{display:none}.more a{display:inline-block;margin-top:8px;background:#141412;color:#fff;border-radius:999px;padding:8px 14px;text-decoration:none;font-weight:700;font-size:13px}
/* race day (dark) */
.dark{background:#111110;color:#f2f1ec;padding-bottom:34px}
.dark .now{background:none;border:0;border-bottom:1px solid #2f2f2b;margin:0;padding:24px 22px 26px}
.dark .now small,.dark .now summary{color:#9a9990}.dark .dh{padding-top:28px}
.dark .dh .n{color:var(--ac)}.dark .dh p{color:#d9d8d0}.dark .dh small{color:#c4c3bb}
.dark .rem{background:#f0eee3;color:#141412}.dark .tl{border-color:#33332f}
.dark .tl>li{background:#fff;color:#141412}.dark .tl>li::before{background:#f2f1ec;border-color:#111110}
.stats{display:grid;grid-template-columns:repeat(3,1fr);border:1px solid #33332f;margin:0 22px 28px}
.stats div{padding:18px 14px;border-left:1px solid #33332f}.stats div:first-child{border-left:0}
.stats small{display:block;font-size:11.5px;color:#a8a79f;letter-spacing:.02em}
.stats b{display:block;font:500 33px/1.1 var(--mono);color:var(--ac);margin:14px 0 16px;letter-spacing:-.02em}
.stats span{font-size:13px;color:#cfcec6;line-height:1.55;display:block}
/* info */
.sec{padding:26px 22px 0}.sec .k{font:400 12px var(--mono);letter-spacing:.1em;display:flex;justify-content:space-between}
.tk{border:1px solid var(--line);border-radius:26px;padding:20px;margin-top:14px;background:var(--card)}
.tk .k{font:400 11.5px var(--mono);color:var(--mute);letter-spacing:.08em}
.rt{display:flex;justify-content:space-between;align-items:center;font:800 38px/1.1 var(--disp);letter-spacing:-.03em;margin:12px 0}.rt s{text-decoration:none;font-weight:400;color:var(--mute)}
.tk h3{margin:6px 0;font-size:22px}.tk p{margin:4px 0 0;color:var(--mute);font-size:14.5px}
.prog{font:800 40px/1 var(--disp);margin:16px 0 4px}.prog small{font:400 12px var(--mono);letter-spacing:.1em;color:var(--mute);margin-left:8px}
.cl{list-style:none;margin:16px 0 0;padding:0}.cl li{display:flex;gap:14px;padding:16px 0;border-top:1px solid var(--line)}
.cl input{flex:0 0 24px;width:24px;height:24px;accent-color:#141412}.cl b{display:block;font-size:16px}.cl span{font-size:14px;color:var(--mute)}.cl li.on b{text-decoration:line-through;color:var(--mute)}
.know h3{margin:26px 0 8px;font-size:18px}.know ul{margin:0;padding-left:20px}.know li{margin:0 0 8px;font-size:15px}
.src{font-size:13.5px;color:var(--mute);background:var(--note);border-radius:22px;padding:14px 18px;margin-top:22px}
@media print{header,.tabs,.rail,.now,.acts,.tools,.cta,.pause{display:none!important}.panel{display:block!important}.frame{border:0}}
@media(prefers-reduced-motion:reduce){.pill{transition:none}}
</style>
</head>
<body><div class="frame">
<header><a class="logo" href="#overview" aria-label="FUJI/26"><svg viewBox="0 0 44 26" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linejoin="round"><path d="M2 25 17 4l5 7 4-5 14 19M12 12l5 4 5-6 4 5"/></svg><u>FUJI</u><span>/26</span></a><span class="vol">FIELD NOTES — VOL. 001</span>
<div class="tools"><button id="tbtn" aria-expanded="false">旅程工具 ⋯</button><div class="menu" id="menu" hidden><p>同行視角</p><div class="chips" id="roles"></div><button class="wide" onclick="print()">列印 / 存成 PDF</button></div></div></header>
<nav class="tabs" id="tabs"><a href="#overview" data-p="overview">旅程總覽</a><a href="#plan" data-p="plan">行程規劃</a><a href="#transport" data-p="transport">交通住宿</a><a href="#notes" data-p="notes">提醒事項</a></nav>

<section class="panel" id="p-overview"><div class="hero"><div class="coord">35°30′ N / 138°45′ E</div>
<h1>FUJI MARATHON 2026 &amp; TOKYO EXPEDITION.</h1><p class="sub">東京慶生 × 富士山環湖 17K × 好友自駕巡禮</p><hr>
<div class="meta"><span>11 — 15 DECEMBER 2026</span><span>FRI → TUE / 05 DAYS</span></div><div class="meta"><span>ASAKUSA → NAKANO → FUJI</span></div>
<div class="mtn"><canvas id="cv" role="img" aria-label="以點陣繪成的富士山"></canvas><button class="pause" id="pz">暫停動畫 ‖</button></div></div>
<a class="cta" href="#day-1">查看五日行程 →</a>
<div class="foot"><span>FUJI / 26 — A JOURNEY IN FIVE CHAPTERS.</span><a href="#overview" onclick="scrollTo(0,0)">BACK TO TOP ↑</a></div></section>

<section class="panel" id="p-plan"><div class="rail" id="rail"><div class="days" id="days"><div class="pill" id="pill"></div></div></div><div id="daybody"></div></section>

<section class="panel" id="p-transport"><div class="sec"><div class="k"><span>01 / LOGISTICS &amp; BASECAMPS</span><span>交通・住宿速查</span></div>
<div class="tk"><div class="k">OUTBOUND / 好友團 · 12.12 SAT</div><div class="rt">KHH <s>→</s> NRT T1</div><b>BR108　07:00 → 11:25</b><p>長榮航空・高雄小港 → 東京成田。先遣組 12/11 去程航班待補。</p></div>
<div class="tk"><div class="k">INBOUND / 全員 · 12.15 TUE</div><div class="rt">NRT T1 <s>→</s> KHH</div><b>BR107　12:45 → 15:40</b><p>長榮航空・東京成田 → 高雄小港。航班時刻依提供資料，待核對訂位。</p></div>
<div class="tk"><div class="k">BASE 01 / 12.11 — 12.12 · 先遣組</div><h3>NO SERVICE HOTEL asakusa</h3><p>淺草・隅田川畔<br>東京都台東区浅草 1-8-4</p><div class="acts"><button data-copy="東京都台東区浅草 1-8-4">📋 複製日文地址</button><a target="_blank" rel="noopener" href="https://www.google.com/maps/search/?api=1&query=NO+SERVICE+HOTEL+asakusa">📍 MAP ↗</a></div></div>
<div class="tk"><div class="k">BASE 02 / 12.12 — 12.15 · 全員 3 晚</div><h3>Tany’s House Stay&amp;HOTEL TOKYO-NAKANO-YAYOICHO</h3><p>中野新橋站步行約 7 分・往新宿路線待核對<br>〒164-0013 東京都中野区弥生町 1-54-16<br>IN 12.12 16:00 / OUT 12.15 10:00</p><div class="acts"><button data-copy="〒164-0013 東京都中野区弥生町 1-54-16">📋 複製日文地址</button><a target="_blank" rel="noopener" href="https://www.google.com/maps/search/?api=1&query=Tany%27s+House+Stay+HOTEL+TOKYO-NAKANO-YAYOICHO">📍 MAP ↗</a></div></div></div></section>

<section class="panel" id="p-notes"><div class="sec"><div class="k"><span>BEFORE YOU GO / QUEST LOG</span><span>旅程知識庫</span></div>
<div class="prog"><span id="pn">0</span> / <span id="pt">0</span><small>COMPLETED</small></div><p class="desc" style="color:var(--mute);font-size:14px;margin:6px 0 0">勾選進度保存在這台裝置的瀏覽器，換裝置不會同步。</p><ul class="cl" id="cl"></ul>
<div class="know"><h3>需要確認的時間衝突</h3><ul><li>Day 2：原定 15:00 會合，住宿入住為 16:00；提前寄放行李須先取得住宿方同意。</li><li>豪德寺 16:45–18:00 為原規劃，冬季開放與天黑時間待確認。</li><li>Day 3–4：確認河口湖取車、中野坂上異地還車、ETC 卡及門市營業時間。</li><li>Day 5：10:57 抵達機場至 12:45 起飛僅 1 小時 48 分，建議改搭更早班車。</li><li>12/14 退房為指定流程，但住宿資料為 12/15 退房，請確認實際退房日期。</li></ul>
<h3>餐飲、營業與預約</h3><ul><li>らぁ麺や 嶋：預約／整理券制度及 12/14 營業狀態待確認。</li><li>THOUSAND COFFEE：營業日及甜點供應待確認。</li><li>忍野八海：14:45 抵達時午餐時段可能已結束。</li><li>御殿場 Outlet：冬季通常 19:00 打烊。</li><li>焼肉よしのNEXT：確認營業時間及訂位。</li></ul></div>
<p class="src">此手帖依提供的行程與截圖製作，尚未查核官方航班、鐵道、賽事與店家資訊。MAP 連結以地點名稱開啟 Google Maps 搜尋，入住前請核對訂房確認信。</p></div></section>
</div>
<script>
const $=s=>document.querySelector(s),$$=s=>[...document.querySelectorAll(s)];
const store={get(k){try{return localStorage.getItem(k)}catch(e){return null}},set(k,v){try{localStorage.setItem(k,v)}catch(e){}}};
const TW="Tany's House Stay HOTEL TOKYO-NAKANO-YAYOICHO",TA="〒164-0013 東京都中野区弥生町 1-54-16",NS="NO SERVICE HOTEL asakusa",NA="東京都台東区浅草 1-8-4";
const D=[
{d:"12.11",w:"FRI",n:"01",h:"淺草入住・墨田慶生",s:"東京第一夜，為生日乾杯。",m:["東京都台東区浅草 1-8-4。全無人智慧電子鎖；出發前完成線上登記，入住前 1–2 天索取大門與房門密碼。無電梯、10:00 前退房，不接受延遲退房；提早抵達請用車站 Coin Locker。"],
i:[{t:"15:00–23:00",h:"NO SERVICE HOTEL asakusa・入住",r:["先遣組"],g:["🏠 住宿"],ic:"🧳",k:1,n:["提醒：全無人智慧電子鎖；出發前完成線上登記，入住前 1–2 天索取大門與房門密碼。無電梯、10:00 前退房，不接受延遲退房。提早抵達請用車站 Coin Locker。","提醒：門鎖詢問範本：Hello, our reservation number is [編號]. We plan to arrive around [時間]. Could you please send us the door lock code in advance?"],a:NA,q:NS},
{t:"傍晚",h:"隅田川與淺草散步",r:["先遣組"],ic:"🌇",p:"河岸散步，留點胃口給慶生晚餐。",q:"隅田川 淺草",tip:"目前沒有明確地標名稱；詳細地址請於 Google Maps 核對。"},
{t:"晚餐待訂",h:"墨田區・Bistro 慶生候選",r:["先遣組"],ic:"🍽️",n:["提醒：預算 ¥7,000–¥9,000／人。候選：遠藤利三郎商店（押上）、大人洋食 Bistro1996、錦糸町 101号室、Étape（本所吾妻橋）、錦糸町ビストロ 日タン。名稱依錄影整理，請核對；確認營業日與整理券，備註 Birthday Dessert Plate。"],q:"墨田區 Bistro"}]},
{d:"12.12",w:"SAT",n:"02",h:"好友團會合・中野",s:"好友團抵達成田，全員在中野會合。",m:["原定 15:00 會合，住宿 16:00 才能入住；提前寄放行李須先取得住宿方同意。","豪德寺冬季開放與天黑時間待確認，可能需提前或另排日期。"],
i:[{t:"07:00",h:"BR108 高雄 → 東京成田",r:["好友團"],g:["✈️ 航班"],ic:"✈️",p:"11:25 抵達成田 T1。",q:"成田機場 第1航廈"},
{t:"15:00",h:"全員會合",r:["全員"],ic:"🤝",p:"原規劃時間，需對照入住時間。"},
{t:"16:00",h:"入住 Tany’s House",r:["全員"],g:["🏠 住宿"],ic:"🛏️",k:1,p:"中野新橋站步行約 7 分。12/15 10:00 退房。",a:TA,q:TW},
{t:"16:45",h:"豪德寺",r:["全員"],g:["待確認"],ic:"🐱",p:"原規劃 16:45–18:00，開放時間待確認。",q:"豪德寺"},
{t:"晚間",h:"備妥賽事裝備",r:["選手"],ic:"🎽",p:"跑鞋、跑衣、保暖外套、寄物用品、早餐、能量補給、水，並預約計程車。"}]},
{d:"12.13",w:"SUN",n:"03",race:1,eb:"RACE DAY",h:"RACE DAY・跑向富士山",s:"完賽後自駕：忍野八海 → 御殿場 → 中野",m:["從 Tany’s House 搭預約計程車，預估 8–10 分鐘；另留集合點步行與候車餘裕。","新宿西口工學院大學旁巴士處集合，於車上領取號碼布、計時晶片與掛帶。官方 Transportation Only／單程 ¥22,000，詳情以確認信為準。"],
st:[["BUS DEPARTURE","05:00","新宿西口出發"],["DISTANCE","17 KM","河口湖環湖賽事"],["RETURN DRIVE","20:15","御殿場 → 中野／翌日還車"]],
i:[{t:"04:20",h:"計程車出發・前往新宿西口",r:["選手"],ic:"🚕",p:"04:00 先吃早餐，再搭預約計程車前往集合點。",q:"新宿西口"},
{t:"04:35–05:00",h:"專車報到・05:00 準時發車",r:["選手"],g:["🚌 交通"],ic:"🚌",k:1,p:"新宿西口工學院大學旁巴士處集合，車上領取號碼布、計時晶片與掛帶。",q:"新宿西口 工學院大學 巴士"},
{t:"09:00",h:"17K 起跑",r:["選手"],g:["🏃 賽事"],ic:"🏃",k:1,p:"依提供規劃。"},
{t:"14:00",h:"河口湖 Toyota 取車",r:["全員"],g:["🚗 自駕"],ic:"🚗",p:"確認 ETC 卡。",q:"Toyota Rent a Car 河口湖"},
{t:"14:45",h:"忍野八海",r:["全員"],ic:"⛲",p:"午餐時段可能已結束，先確認供餐。",q:"忍野八海"},
{t:"傍晚",h:"御殿場 Outlet",r:["全員"],ic:"🛍️",p:"冬季通常 19:00 打烊。",q:"御殿場 Premium Outlets"},
{t:"晚餐",h:"焼肉よしのNEXT",r:["全員"],g:["待確認"],ic:"🥩",p:"確認營業時間及訂位。",a:"御殿場市ぐみ沢36-5",q:"焼肉よしのNEXT 御殿場"},
{t:"20:15",h:"自駕回中野",r:["全員"],ic:"🌃",p:"約 22:15 抵達，保留塞車彈性。"}]},
{d:"12.14",w:"MON",n:"04",h:"還車・東京日常",s:"一早還車，剩下的時間留給東京。",m:["08:45–09:00 為預排還車時段，需依中野坂上店營業時間調整。","12/14 退房為指定流程，原住宿資料為 12/15，請確認實際日期與行李寄放。"],
i:[{t:"08:45",h:"Toyota 中野坂上店還車",r:["全員"],g:["🚗 自駕","待確認"],ic:"⛽",k:1,p:"還車前加滿油並保留收據。",q:"Toyota Rent a Car 中野坂上"},
{t:"待補",h:"らぁ麺や 嶋",r:["全員"],g:["待確認"],ic:"🍜",p:"預約／整理券制度及營業狀態待確認。",q:"らぁ麺や 嶋"},
{t:"待補",h:"THOUSAND COFFEE",r:["全員"],g:["待確認"],ic:"☕",p:"營業日及甜點供應待確認。",q:"THOUSAND COFFEE"}]},
{d:"12.15",w:"TUE",n:"05",h:"整裝返程・東京 → 高雄",s:"收好五天的風景，把富士山帶回日常。",m:["改搭更早 N’EX 或評估 Skyliner 轉乘，目標 10:15–10:30 前到成田櫃檯。原 10:57 抵達至 12:45 起飛只剩 1 小時 48 分，時間緊繃。","住宿最晚 10:00 退房，但需依更早機場列車時間提前離開。10:00 才出發無法 10:15–10:30 到成田。"],
i:[{t:"提早",h:"提早退房 Tany’s House・退房",r:["全員"],g:["🏠 住宿"],ic:"🧳",k:1,a:TA,q:TW},
{t:"待補",h:"依機場班次提前 中野新橋 → 新宿站",r:["全員"],ic:"🚆",p:"搭 N’EX 或 Skyliner 轉乘。"},
{t:"10:15",h:"抵達成田櫃檯",r:["全員"],ic:"🛄",k:1,p:"目標 10:15–10:30。"},
{t:"12:45",h:"BR107 成田 → 高雄",r:["全員"],g:["✈️ 航班"],ic:"✈️",k:1,p:"15:40 抵達高雄小港。"}]}];
const ROLES=["全部","先遣組","選手","好友團"];let role="全部",cur=0;
const ok=r=>role==="全部"||r.includes("全員")||r.includes(role);
const mp=q=>`https://www.google.com/maps/search/?api=1&query=${encodeURIComponent(q)}`;
$("#roles").innerHTML=ROLES.map(r=>`<button class="chip" aria-pressed="${r===role}">${r}</button>`).join("");
$("#roles").onclick=e=>{const c=e.target.closest(".chip");if(!c)return;role=c.textContent;$$(".chip").forEach(x=>x.setAttribute("aria-pressed",x===c));draw()};
D.forEach((x,k)=>{const b=document.createElement("button");b.setAttribute("role","tab");b.innerHTML=`<b>DAY ${x.n}</b><i>${x.d} ${x.w}</i>`;b.onclick=()=>{location.hash="day-"+(k+1)};$("#days").append(b)});
function draw(){const x=D[cur],L=x.i.filter(i=>ok(i.r));
$$(".days button").forEach((b,k)=>b.setAttribute("aria-selected",k===cur));$("#pill").style.transform=`translateX(${cur*100}%)`;
const rail=$("#rail"),w=rail.scrollWidth/5;rail.scrollTo({left:Math.max(0,(cur-1)*w),behavior:"smooth"});
const pv=L.slice(0,2);
$("#daybody").className=x.race?"dark":"";$("#daybody").innerHTML=`<div class="now"><small>預覽 · 2026.${x.d} · 日本時間</small>${pv.map((i,k)=>`<div><em>${k?"NEXT":"FIRST"}</em><span>${/^\d/.test(i.t)?i.t+" ":""}${i.h}</span></div>`).join("")||"這個視角當天沒有行程"}${pv.some(i=>i.q)?`<details><summary>▶ 更多操作・地圖與地址</summary>${pv.filter(i=>i.q).map(i=>`<a target="_blank" rel="noopener" href="${mp(i.q)}">📍 ${i.h}</a>`).join("")}</details>`:""}</div>
<div class="dh"><div class="n">${x.n}</div><div><small>2026.${x.d} / ${x.w}${x.eb?" / "+x.eb:""}</small><h2>${x.h}</h2><p>${x.s}</p></div></div>
<div class="rem"><h3>✦ 今日先記住</h3>${x.m.map(m=>`<p>${m}</p>`).join("")}</div>
${x.st?`<div class="stats">${x.st.map(a=>`<div><small>${a[0]}</small><b>${a[1]}</b><span>${a[2]}</span></div>`).join("")}</div>`:""}<ol class="tl">${L.map(i=>{const id=`done-${cur}-${x.i.indexOf(i)}`,dn=store.get(id)==="1";return `<li class="${i.k?"key":""}${dn?" done":""}"><div class="row"><div><div class="t">${i.t}</div><h4>${i.h}${i.k?"<em>NEXT</em>":""}</h4></div><div class="ph" aria-hidden="true">${i.ic||"•"}</div></div>
<div class="tags">${(i.g||[]).concat(i.r.filter(r=>r!=="全員").length?i.r:["全員"]).map(t=>`<span class="tag">${t}</span>`).join("")}</div>${i.p?`<p class="desc">${i.p}</p>`:""}
<label class="ck"><input type="checkbox" data-id="${id}" ${dn?"checked":""}>完成 ✔︎</label>${(i.n||[]).map(n=>`<div class="nt">✦ ${n}</div>`).join("")}
${i.q?`<div class="acts"><button data-more>📍 查看路線與地圖 ▾</button>${i.a?`<button data-copy="${i.a}">📋 複製地址</button>`:""}</div><div class="more" hidden><b>交通／行程提示</b><br>${i.a||i.q}${i.tip?`<br>${i.tip}`:""}<br><a target="_blank" rel="noopener" href="${mp(i.q)}">在 Google Maps 開啟導航 ↗</a></div>`:""}</li>`}).join("")}</ol>`}
const CL=[["出發前｜護照與旅行文件","確認護照、機票、住宿確認信與旅遊保險資料。"],["出發前｜核對航班與先遣組去程","確認 BR108／BR107 訂位；補上 12/11 先遣組航班。"],["出發前｜賽事專車與報到","確認 Transportation Only 訂單、領取人員、集合點。"],["出發前｜N’EX 時刻與指定席","核對 N’EX 時刻，完成所需訂位。"],["12/12｜行李寄放與入住","先確認 Tany’s House 正式入住時間為 16:00。"],["12/12｜賽事裝備點檢","跑鞋、跑衣、保暖外套、寄物用品、早餐、補給、水。"],["12/12｜預約隔日 04:20 計程車","確認上車地點與時間。"],["12/13｜04:00 早餐與跑步補給","04:20 出發、04:35 報到。"],["12/13｜Toyota 河口湖取車","確認 ETC 卡與營業時間。"],["12/13｜御殿場 Outlet 與晚餐","確認 Outlet 打烊時間與焼肉よしのNEXT 訂位。"],["12/14｜中野坂上店還車","加滿油、保留收據、確認 08:45–09:00 時段。"],["12/14｜らぁ麺や 嶋與 THOUSAND COFFEE","確認營業日、整理券與甜點供應。"],["12/15｜提早退房與前往成田","目標 10:15–10:30 抵達成田櫃檯。"]];
$("#cl").innerHTML=CL.map((c,k)=>`<li><input type="checkbox" data-c="c${k}" aria-label="${c[0]}"><div><b>${c[0]}</b><span>${c[1]}</span></div></li>`).join("");$("#pt").textContent=CL.length;
function cnt(){$("#pn").textContent=$$("#cl input:checked").length}
$$("#cl input").forEach(i=>{i.checked=store.get(i.dataset.c)==="1";i.closest("li").classList.toggle("on",i.checked)});cnt();
document.addEventListener("change",e=>{const t=e.target;if(t.dataset.c){store.set(t.dataset.c,t.checked?"1":"0");t.closest("li").classList.toggle("on",t.checked);cnt()}
if(t.dataset.id){store.set(t.dataset.id,t.checked?"1":"0");const li=t.closest("li");li.classList.toggle("done",t.checked)}});
document.addEventListener("click",e=>{const c=e.target.closest("[data-copy]");if(c){const t=c.dataset.copy,o=c.textContent;(navigator.clipboard?navigator.clipboard.writeText(t):Promise.reject()).catch(()=>{}).finally(()=>{c.textContent="已複製 ✔︎";setTimeout(()=>c.textContent=o,1200)})}
const m=e.target.closest("[data-more]");if(m){const b=m.closest("li").querySelector(".more");b.hidden=!b.hidden}
if(!e.target.closest(".tools"))$("#menu").hidden=true});
$("#tbtn").onclick=()=>{const m=$("#menu");m.hidden=!m.hidden;$("#tbtn").setAttribute("aria-expanded",!m.hidden)};
function route(){document.documentElement.style.setProperty("--th",$("#tabs").offsetHeight+"px");const h=location.hash.slice(1)||"overview";let p=h;const m=h.match(/^day-(\d)$/);if(m){p="plan";cur=Math.min(4,Math.max(0,m[1]-1))}
if(!$("#p-"+p))p="overview";$$(".panel").forEach(e=>e.classList.toggle("on",e.id==="p-"+p));$$("#tabs a").forEach(a=>a.setAttribute("aria-current",a.dataset.p===p));
if(p==="plan")draw();if(p==="overview")start();scrollTo(0,0)}
/* halftone Fuji: scanline dot-matrix, dissolves between two poses */
const cv=$("#cv"),cx=cv.getContext("2d"),fA=document.createElement("canvas"),fB=document.createElement("canvas"),
gA=fA.getContext("2d",{willReadFrequently:true}),gB=fB.getContext("2d",{willReadFrequently:true});
let raf=0,paused=matchMedia("(prefers-reduced-motion:reduce)").matches,T=0;
const LOOP=18,LV=[0,.26,.52,.78,1];
const hs=(a,b)=>{const x=Math.sin(a*127.1+b*311.7)*43758.5453;return x-Math.floor(x)};
const sm=(a,b,x)=>{x=Math.min(1,Math.max(0,(x-a)/(b-a)));return x*x*(3-2*x)};
const mix=(t,on,off,d)=>sm(on,on+d,t)*(1-sm(off,off+d,t));
function pose(g,w,h,B,t){
g.setTransform(1,0,0,1,0,0);g.fillStyle="#fff";g.fillRect(0,0,w,h);
const sc=1+.022*Math.sin(6.2832*t/LOOP);g.setTransform(sc,0,0,sc,w*.5*(1-sc),h*.9*(1-sc));
const X=u=>u*w,Y=v=>v*h;
if(B){g.fillStyle="#a8a8a8";g.beginPath();g.arc(X(.79),Y(.2),h*.1,0,6.2832);g.fill()}
const body=()=>{g.beginPath();g.moveTo(X(.435),Y(.08));g.quadraticCurveTo(X(.3),Y(.45),X(.115),Y(.9));g.lineTo(X(.885),Y(.9));g.quadraticCurveTo(X(.7),Y(.45),X(.565),Y(.08));g.closePath()};
g.save();body();g.clip();
let q=g.createLinearGradient(0,Y(.3),0,Y(.9));q.addColorStop(0,"#4d4d4d");q.addColorStop(1,"#2c2c2c");g.fillStyle=q;g.fillRect(0,0,w,h);
q=g.createLinearGradient(X(.1),0,X(.9),0);q.addColorStop(0,"rgba(255,255,255,.2)");q.addColorStop(.5,"rgba(255,255,255,0)");q.addColorStop(1,"rgba(0,0,0,.16)");g.fillStyle=q;g.fillRect(0,0,w,h);
const sl=u=>.345+(B?.07:0)+.035*Math.sin(u*19+.7)+.03*Math.sin(u*41)+.1*Math.abs(u-.5);
g.fillStyle="#bdbdbd";g.beginPath();g.moveTo(0,0);g.lineTo(w,0);for(let k=24;k>=0;k--){const u=k/24;g.lineTo(X(.1+.8*u),Y(sl(.1+.8*u)))}g.lineTo(0,Y(sl(.1)));g.closePath();g.fill();
g.fillStyle="#1a1a1a";for(let k=0;k<26;k++){const u=.12+.76*k/25;if(hs(k,3.3)>.5){g.beginPath();g.ellipse(X(u),Y(sl(u)+.03),w*.022,h*.018,0,0,6.2832);g.fill()}}
g.restore()}
function paint(){
const W=cv.clientWidth||340,H=Math.round(W*.6),r=Math.min(3,devicePixelRatio||1),step=Math.max(3.2,W/112),rs=step*1.5,cols=Math.ceil(W/step),rows=Math.ceil(H/rs);
if(cv.width!==Math.round(W*r)||cv.height!==Math.round(H*r)){cv.width=Math.round(W*r);cv.height=Math.round(H*r);cv.style.height=H+"px"}
if(fA.width!==cols||fA.height!==rows){fA.width=fB.width=cols;fA.height=fB.height=rows}
const t=T%LOOP;pose(gA,cols,rows,0,t);pose(gB,cols,rows,1,t);
const A=gA.getImageData(0,0,cols,rows).data,Bd=gB.getImageData(0,0,cols,rows).data,mL=mix(t,4.5,11.5,1.8),mR=mix(t,6.5,13.5,1.8),tick=Math.floor(t*7);
cx.setTransform(r,0,0,r,0,0);cx.clearRect(0,0,W,H);cx.fillStyle=getComputedStyle(document.body).color;cx.beginPath();
for(let j=0;j<rows;j++){const py=(j+.5)*rs,sh=hs(j,tick)>.965?Math.round((hs(tick,j)-.5)*8):0;
for(let i=0;i<cols;i++){const si=Math.min(cols-1,Math.max(0,i-sh)),m=i<cols/2?mL:mR,sd=.55*hs(i,j)+.45*hs(j*3.1,7.7);
let v=(1-(sd<m?Bd:A)[(j*cols+si)*4]/255-.16)/.42;v=Math.min(1,Math.max(0,v));
if(m>.001&&m<.999){const dd=Math.abs(sd-m);if(dd<.12){v*=dd/.12;if(hs(i+tick,j)<=.4)v*=.3}}
v*=.86+.14*Math.sin(t*3.2+sd*40);
let l=0;for(let k=4;k>0;k--)if(v>=LV[k]-.13){l=k;break}
if(!l)continue;const x=(i+.5)*step,rad=step*.46*(l===1?.38:LV[l]);cx.moveTo(x+rad,py);cx.arc(x,py,rad,0,6.2832)}}
cx.fill()}
function loop(n){const d=Math.min(.05,(n-(loop.l||n))/1000);loop.l=n;T+=d;paint();if(!paused)raf=requestAnimationFrame(loop)}
function start(){cancelAnimationFrame(raf);loop.l=0;paint();if(!paused)raf=requestAnimationFrame(loop)}
$("#pz").onclick=()=>{paused=!paused;$("#pz").textContent=paused?"播放動畫 ▶":"暫停動畫 ‖";start()};
addEventListener("resize",paint);addEventListener("hashchange",route);route();
</script>
</body>
</html>
