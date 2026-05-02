
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>釜山5天4夜家庭旅遊｜Busan Family Trip</title>
  <style>
    *{box-sizing:border-box;margin:0;padding:0}
    html{scroll-behavior:smooth}
    body{font-family:-apple-system,BlinkMacSystemFont,"Noto Sans TC","Segoe UI",sans-serif;background:linear-gradient(135deg,#dff4ff 0%,#fff7ed 55%,#fef3c7 100%);color:#172033;line-height:1.65}
    a{color:inherit;text-decoration:none}
    button,input,select,textarea{font:inherit}
    .container{max-width:1120px;margin:0 auto;padding:22px 16px 60px}
    .hero{min-height:380px;display:flex;flex-direction:column;justify-content:flex-end;background:linear-gradient(rgba(15,23,42,.18),rgba(15,23,42,.65)),url("https://images.unsplash.com/photo-1601621915196-2621bfb0cd6e?auto=format&fit=crop&w=1600&q=80");background-size:cover;background-position:center;border-radius:32px;padding:34px;color:#fff;margin-bottom:18px;box-shadow:0 24px 60px rgba(15,23,42,.22);overflow:hidden}
    .hero .tag{width:max-content;background:rgba(255,255,255,.22);backdrop-filter:blur(10px);border:1px solid rgba(255,255,255,.35);padding:8px 14px;border-radius:999px;font-weight:800;font-size:14px;margin-bottom:14px}
    .hero h1{font-size:clamp(36px,7vw,72px);line-height:1.02;letter-spacing:-1.5px;margin-bottom:12px}
    .hero p{font-size:18px;opacity:.96;max-width:680px}
    .quick-nav{position:sticky;top:0;z-index:10;display:flex;gap:10px;overflow-x:auto;padding:10px 2px 16px;margin-bottom:12px;backdrop-filter:blur(12px)}
    .quick-nav a{flex:0 0 auto;background:rgba(255,255,255,.88);border:1px solid rgba(255,255,255,.8);padding:9px 14px;border-radius:999px;font-size:14px;font-weight:800;box-shadow:0 8px 22px rgba(15,23,42,.08)}
    .info-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin:8px 0 28px}
    .info-card,.day-card,.tip-card,.editor{background:rgba(255,255,255,.92);border:1px solid rgba(255,255,255,.8);border-radius:26px;padding:20px;box-shadow:0 16px 36px rgba(15,23,42,.08)}
    .info-card .label{font-size:13px;color:#64748b;font-weight:800;margin-bottom:6px}.info-card .value{font-size:19px;font-weight:900;color:#0f172a}
    .section-title{font-size:30px;letter-spacing:-.5px;margin:32px 0 16px;color:#0f172a}
    .editor{margin-bottom:26px}.editor h2{font-size:22px;margin-bottom:8px}.editor p{color:#64748b;font-size:14px;margin-bottom:14px}
    .form-grid{display:grid;grid-template-columns:repeat(12,1fr);gap:10px}.field{display:flex;flex-direction:column;gap:5px}.field label{font-size:12px;font-weight:900;color:#475569}.field input,.field select,.field textarea{width:100%;border:1px solid #cbd5e1;background:#fff;border-radius:14px;padding:10px 12px;color:#0f172a}.field textarea{min-height:74px;resize:vertical}.span-2{grid-column:span 2}.span-3{grid-column:span 3}.span-4{grid-column:span 4}.span-5{grid-column:span 5}.span-6{grid-column:span 6}.span-12{grid-column:span 12}
    .actions{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}.primary-btn,.secondary-btn,.danger-btn{border:0;border-radius:14px;padding:10px 14px;font-weight:950;cursor:pointer}.primary-btn{background:#0f172a;color:#fff}.secondary-btn{background:#e0f2fe;color:#075985}.danger-btn{background:#fee2e2;color:#b91c1c}
    .timeline{display:grid;gap:20px}.day-card{position:relative;overflow:hidden}.day-card:before{content:"";position:absolute;left:0;top:0;width:8px;height:100%;background:linear-gradient(#38bdf8,#fb923c)}
    .day-head{display:flex;align-items:flex-start;justify-content:space-between;gap:12px;margin-bottom:16px;padding-left:8px}.day-head h2{font-size:23px;color:#0f172a;line-height:1.25}.date{flex:0 0 auto;background:#eff6ff;color:#2563eb;padding:7px 12px;border-radius:999px;font-size:13px;font-weight:900}
    .spots{display:grid;gap:12px}.spot{display:grid;grid-template-columns:64px 1fr;gap:12px;background:#f8fafc;border:1px solid #e2e8f0;border-radius:20px;padding:14px;transition:.2s ease;position:relative}.spot:hover{transform:translateY(-2px);box-shadow:0 10px 26px rgba(15,23,42,.08)}
    .delete-spot{position:absolute;right:10px;top:10px;border:0;background:#fee2e2;color:#b91c1c;border-radius:999px;width:30px;height:30px;font-weight:950;cursor:pointer}.icon{width:52px;height:52px;display:grid;place-items:center;background:#fff;border-radius:18px;font-size:27px;box-shadow:inset 0 0 0 1px #e5e7eb}.time{font-size:14px;color:#0284c7;font-weight:900;margin-bottom:2px}.place{font-size:17px;font-weight:950;color:#111827;margin-bottom:4px;padding-right:34px}.desc{font-size:14px;color:#64748b;margin-bottom:10px}.badges{display:flex;flex-wrap:wrap;gap:7px;margin-bottom:10px}.badge{font-size:12px;font-weight:900;padding:5px 9px;border-radius:999px;background:#fff7ed;color:#c2410c;border:1px solid #fed7aa}.badge.easy{background:#ecfdf5;color:#047857;border-color:#bbf7d0}.badge.walk{background:#fef2f2;color:#b91c1c;border-color:#fecaca}.badge.reserve{background:#eef2ff;color:#4338ca;border-color:#c7d2fe}.links{display:flex;flex-wrap:wrap;gap:8px}.map-btn{display:inline-flex;align-items:center;gap:5px;padding:7px 10px;border-radius:12px;font-size:13px;font-weight:900;background:#0f172a;color:white}.map-btn.naver{background:#16a34a}
    .tips{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:14px;margin-top:14px}.tip-card h3{font-size:18px;margin-bottom:8px}.tip-card ul{padding-left:20px;color:#475569;font-size:14px}footer{text-align:center;color:#64748b;font-size:13px;padding:28px 0 0}
    @media(max-width:760px){.form-grid{grid-template-columns:1fr}.span-2,.span-3,.span-4,.span-5,.span-6,.span-12{grid-column:span 1}}
    @media(max-width:680px){.container{padding:14px 12px 40px}.hero{min-height:320px;border-radius:26px;padding:24px}.day-head{display:block}.date{display:inline-block;margin-top:8px}.spot{grid-template-columns:54px 1fr;padding:12px;border-radius:18px}.icon{width:46px;height:46px;font-size:24px;border-radius:16px}.place{font-size:16px}}
  </style>
</head>
<body>
  <main class="container">
    <section class="hero"><div class="tag">🇰🇷 Busan Family Trip</div><h1>釜山5天4夜<br>家庭旅遊</h1><p>8/7 – 8/12｜西面、南浦、廣安里、慶州、甘川洞、海雲台，一份適合手機查看與家人分享的完整行程。</p></section>
    <nav class="quick-nav"><a href="#editor">新增行程</a><a href="#day0">Day0</a><a href="#day1">Day1</a><a href="#day2">Day2</a><a href="#day3">Day3</a><a href="#day4">Day4</a><a href="#day5">Day5</a><a href="#tips">備註</a></nav>
    <section class="info-grid"><div class="info-card"><div class="label">住宿 1</div><div class="value">8/7–8/10 西面阿班飯店</div></div><div class="info-card"><div class="label">住宿 2</div><div class="value">8/10–8/12 Hotel Hyggelig Busan</div></div><div class="info-card"><div class="label">旅遊風格</div><div class="value">家庭旅遊・美食・海景・購物</div></div></section>

    <section class="editor" id="editor">
      <h2>＋ 新增行程卡片</h2>
      <p>填好後按「新增到行程」。新增與刪除會保存在此瀏覽器的 localStorage，重新整理也會保留。</p>
      <form id="addForm">
        <div class="form-grid">
          <div class="field span-2"><label>Day</label><select id="day" required><option value="day0">Day0</option><option value="day1">Day1</option><option value="day2">Day2</option><option value="day3">Day3</option><option value="day4">Day4</option><option value="day5">Day5</option></select></div>
          <div class="field span-2"><label>Icon</label><input id="icon" value="📍" placeholder="例：☕ 🍜 🚆" /></div>
          <div class="field span-3"><label>時間</label><input id="time" placeholder="例：14:00–15:30" /></div>
          <div class="field span-5"><label>景點 / 餐廳</label><input id="place" placeholder="例：海雲台咖啡廳" required /></div>
          <div class="field span-12"><label>描述</label><textarea id="desc" placeholder="例：下午休息、拍照、買伴手禮"></textarea></div>
          <div class="field span-4"><label>家庭友善標籤</label><select id="friendly"><option value="easy">👶 長輩OK</option><option value="walk">🚶‍♂️ 需走路</option><option value="reserve">📌 需預約</option><option value="none">不加</option></select></div>
          <div class="field span-4"><label>第二標籤</label><input id="tag2" placeholder="例：☕ 休息 / 🌊 海景" /></div>
          <div class="field span-4"><label>地圖搜尋關鍵字</label><input id="mapQuery" placeholder="不填則使用景點名稱" /></div>
        </div>
        <div class="actions"><button class="primary-btn" type="submit">新增到行程</button><button class="secondary-btn" type="button" id="exportBtn">匯出目前 HTML</button><button class="danger-btn" type="button" id="resetBtn">恢復原始行程</button></div>
      </form>
    </section>

    <h2 class="section-title">每日行程</h2><section class="timeline" id="timeline"></section>
    <h2 class="section-title" id="tips">家庭旅遊備註</h2><section class="tips"><div class="tip-card"><h3>👨‍👩‍👧 家庭友善原則</h3><ul><li>每天至少保留一段咖啡廳或飯店休息。</li><li>南浦、甘川洞、海理團路比較需要走路。</li><li>長輩累的時候可改搭計程車。</li></ul></div><div class="tip-card"><h3>📌 需要預約</h3><ul><li>Yachtholic 遊艇：提早 20 分鐘集合。</li><li>膠囊列車：8/4 早上 8 點搶票。</li><li>海雲台母牛肋排家：建議 CatchTable 訂位。</li><li>自然島鹽麵包：建議 Naver 預訂。</li></ul></div><div class="tip-card"><h3>🌐 分享成網址</h3><ul><li>這是一份單頁 HTML，可直接放到 GitHub Pages、Netlify 或 Vercel。</li><li>按「匯出目前 HTML」可下載目前版本，再上傳分享。</li></ul></div></section>
    <footer>Made for Busan Family Trip · 8/7–8/12 · Interactive itinerary</footer>
  </main>

<script>
const STORAGE_KEY = 'busanFamilyTripItineraryV1';
const dayInfo = {
  day0:{title:'Day0｜抵達釜山・入住西面',date:'8/7'}, day1:{title:'Day1｜南浦＋廣安里無人機＋遊艇',date:'8/8'}, day2:{title:'Day2｜慶州一日遊',date:'8/9'}, day3:{title:'Day3｜甘川洞＋LUGE＋THE SKY＋換飯店',date:'8/10'}, day4:{title:'Day4｜海雲台＋水族館＋膠囊列車',date:'8/11'}, day5:{title:'Day5｜早餐・退房・回程',date:'8/12'}
};
const initialItems = [
  {day:'day0',icon:'✈️',time:'19:00',place:'金海機場抵達',desc:'抵達後直接前往西面飯店，建議保留交通緩衝。',badges:[['easy','👶 長輩OK'],['','🚕 建議搭車']],query:'Gimhae International Airport'},
  {day:'day0',icon:'🏨',time:'20:00',place:'西面阿班飯店 Check-in',desc:'入住西面商圈，交通方便，晚上覓食也方便。',badges:[['easy','👶 長輩OK']],query:'Arban Hotel Busan'},
  {day:'day0',icon:'🍜',time:'21:00',place:'松亭三代豬肉湯飯',desc:'抵達後第一餐，適合安排熱湯類宵夜。',badges:[['easy','👶 長輩OK'],['','🍜 宵夜']],query:'Songjeong 3dae Gukbap Busan'},
  {day:'day1',icon:'☕',time:'09:30–10:30',place:'ALL SUNDAY 西面早餐',desc:'早上輕鬆用餐後，從西面出發去南浦。',badges:[['easy','👶 長輩OK']],query:'ALL SUNDAY Seomyeon Busan'},
  {day:'day1',icon:'🛍️',time:'11:00–15:30',place:'南浦洞｜BIFF、札嘎其市場、國際市場',desc:'逛街、小吃、襪子與棉被一條街。這段會走比較多路。',badges:[['walk','🚶‍♂️ 需走路'],['','🍢 小吃']],query:'BIFF Square Jagalchi Market Gukje Market Busan'},
  {day:'day1',icon:'☕',time:'15:30–16:30',place:'Ryui’s Coffee Bar / Cafe Nampo Yunseul',desc:'中午後休息點，讓家人補充體力。',badges:[['easy','👶 長輩OK'],['','☕ 休息']],query:"Ryui's Coffee Bar Busan"},
  {day:'day1',icon:'🏖️',time:'17:00',place:'廣安里海灘＋炸雞晚餐',desc:'海邊散步、拍照，適合晚餐放鬆。',badges:[['easy','👶 長輩OK'],['','🌊 海景']],query:'Gwangalli Beach Busan'},
  {day:'day1',icon:'⛵',time:'19:30–20:30',place:'Yachtholic 遊艇＋無人機＋煙火',desc:'需提早 20 分鐘集合，晚上是本日重點行程。',badges:[['reserve','📌 需預約'],['easy','👶 長輩OK']],query:'Yachtholic Busan'},
  {day:'day2',icon:'🏛️',time:'整天',place:'KLOOK / KKDAY 慶州一日遊',desc:'可比較接送點、景點內容與回程時間，再決定方案。',badges:[['reserve','📌 待確認'],['walk','🚶‍♂️ 需走路']],query:'Gyeongju Korea'},
  {day:'day2',icon:'🍽️',time:'晚餐',place:'Old Mansion',desc:'慶州回來後的晚餐安排。',badges:[['easy','👶 長輩OK']],query:'Old Mansion Busan'},
  {day:'day3',icon:'🎨',time:'10:00–11:00',place:'甘川洞文化村',desc:'小王子合照可能需等候，山坡路段較多。',badges:[['walk','🚶‍♂️ 需走路'],['','📸 拍照']],query:'Gamcheon Culture Village Busan'},
  {day:'day3',icon:'🍜',time:'12:00–13:30',place:'海雲台元祖老奶奶湯飯',desc:'抵達海雲台後先吃午餐，再安排下午活動。',badges:[['easy','👶 長輩OK']],query:'Haeundae Wonjo Halmae Gukbap'},
  {day:'day3',icon:'🎡',time:'14:00–18:00',place:'LUGE Skyline / 新世界免稅店 / Spa Land / Centum City',desc:'不玩 LUGE 的家人可留在免稅店、Spa Land 或百貨休息。',badges:[['reserve','📌 分組行程'],['easy','👶 可休息']],query:'Skyline Luge Busan Centum City'},
  {day:'day3',icon:'🌃',time:'19:30–20:30',place:'BUSAN X THE SKY 夜景',desc:'海雲台高空夜景，適合家庭一起拍照。',badges:[['easy','👶 長輩OK'],['','🌃 夜景']],query:'Busan X The Sky'},
  {day:'day3',icon:'🏨',time:'晚上',place:'入住 Hotel Hyggelig Busan',desc:'換到海雲台住宿，方便隔天海雲台行程。',badges:[['easy','👶 長輩OK']],query:'Hotel Hyggelig Busan'},
  {day:'day4',icon:'🐠',time:'10:00–12:00',place:'SEA LIFE 釜山水族館',desc:'室內景點，適合家庭與長輩。',badges:[['easy','👶 長輩OK'],['','☔ 雨天備案']],query:'SEA LIFE Busan Aquarium'},
  {day:'day4',icon:'🍲',time:'12:00–13:00',place:'名品海雲台蔘雞湯',desc:'午餐安排，適合補體力。',badges:[['easy','👶 長輩OK']],query:'Haeundae Samgyetang Busan'},
  {day:'day4',icon:'🛒',time:'13:30–15:30',place:'海理團路、大創、選物店、傳統市場',desc:'伴手禮與散步時間，可視體力調整。',badges:[['walk','🚶‍♂️ 需走路'],['','🛍️ 購物']],query:'Haeridan-gil Haeundae Busan'},
  {day:'day4',icon:'🥐',time:'膠囊列車前',place:'自然島鹽麵包',desc:'尾浦站入口處對面，需 Naver 預訂。',badges:[['reserve','📌 需預訂']],query:'Jayeondo Salt Bread Mipo Busan'},
  {day:'day4',icon:'🚆',time:'16:30–17:00',place:'海雲台藍線公園膠囊列車 → 青沙浦天空步道',desc:'8/4 早上 8 點預約，時間可能需往前移。',badges:[['reserve','📌 需搶票'],['walk','🚶‍♂️ 需走路']],query:'Haeundae Blue Line Park Mipo Station'},
  {day:'day4',icon:'🥩',time:'晚餐',place:'海雲台母牛肋排家',desc:'建議 CatchTable 預約，不然可能等很久。',badges:[['reserve','📌 建議訂位'],['easy','👶 長輩OK']],query:'Haeundae sogalbi Busan'},
  {day:'day5',icon:'🥣',time:'09:00',place:'大海鮑魚粥',desc:'回程前早餐，吃完整理、退房與最後補貨。',badges:[['easy','👶 長輩OK']],query:'Haeundae abalone porridge Busan'},
  {day:'day5',icon:'✈️',time:'11:00',place:'前往金海機場',desc:'建議預留交通、退稅、托運與安檢時間。',badges:[['easy','👶 長輩OK'],['','🚕 建議搭車']],query:'Gimhae International Airport'}
].map((item,index)=>({...item,id:'base-'+index}));
let items = loadItems();
function loadItems(){try{return JSON.parse(localStorage.getItem(STORAGE_KEY)) || initialItems}catch{return initialItems}}
function saveItems(){localStorage.setItem(STORAGE_KEY, JSON.stringify(items))}
function mapLink(query,type){const q=encodeURIComponent(query || 'Busan');return type==='naver'?`https://map.naver.com/p/search/${q}`:`https://www.google.com/maps/search/?api=1&query=${q}`}
function render(){const timeline=document.getElementById('timeline');timeline.innerHTML='';Object.entries(dayInfo).forEach(([day,info])=>{const article=document.createElement('article');article.className='day-card';article.id=day;article.innerHTML=`<div class="day-head"><h2>${info.title}</h2><span class="date">${info.date}</span></div><div class="spots"></div>`;const spots=article.querySelector('.spots');items.filter(i=>i.day===day).forEach(item=>spots.appendChild(createSpot(item)));timeline.appendChild(article)})}
function createSpot(item){const el=document.createElement('div');el.className='spot';const badgeHtml=(item.badges||[]).map(([cls,text])=>`<span class="badge ${cls||''}">${text}</span>`).join('');const q=item.query || item.place;el.innerHTML=`<button class="delete-spot" title="刪除">×</button><div class="icon">${item.icon||'📍'}</div><div><div class="time">${item.time||''}</div><div class="place">${item.place}</div><div class="desc">${item.desc||''}</div><div class="badges">${badgeHtml}</div><div class="links"><a class="map-btn" href="${mapLink(q,'google')}" target="_blank">Google Maps</a><a class="map-btn naver" href="${mapLink(q,'naver')}" target="_blank">Naver</a></div></div>`;el.querySelector('.delete-spot').addEventListener('click',()=>{if(confirm(`刪除「${item.place}」？`)){items=items.filter(i=>i.id!==item.id);saveItems();render()}});return el}
document.getElementById('addForm').addEventListener('submit',e=>{e.preventDefault();const friendly=document.getElementById('friendly').value;const tag2=document.getElementById('tag2').value.trim();const badges=[];if(friendly==='easy')badges.push(['easy','👶 長輩OK']);if(friendly==='walk')badges.push(['walk','🚶‍♂️ 需走路']);if(friendly==='reserve')badges.push(['reserve','📌 需預約']);if(tag2)badges.push(['',tag2]);items.push({id:'custom-'+Date.now(),day:day.value,icon:icon.value||'📍',time:time.value,place:place.value.trim(),desc:desc.value.trim(),badges,query:mapQuery.value.trim()||place.value.trim()});saveItems();render();e.target.reset();icon.value='📍';document.getElementById(day.value)?.scrollIntoView({behavior:'smooth',block:'start'})});
document.getElementById('resetBtn').addEventListener('click',()=>{if(confirm('確定恢復原始行程？你新增/刪除的項目會被清除。')){items=initialItems;saveItems();render()}});
document.getElementById('exportBtn').addEventListener('click',()=>{const blob=new Blob([document.documentElement.outerHTML],{type:'text/html;charset=utf-8'});const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download='busan-family-trip.html';a.click();URL.revokeObjectURL(a.href)});
render();
</script>
</body>
</html>
