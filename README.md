# -HolidayInn-guest-info<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Holiday Inn Resort Phuket | Guest Information</title>
<style>
:root{
  --purple:#63369a; --purple2:#7d4db1; --light:#f7f1fb;
  --text:#29213a; --muted:#6f667c; --white:#fff;
  --gold:#d97706;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--text);
  background:linear-gradient(135deg,#fff 0%,#f8f2fc 100%);
  transition: all 0.3s ease;
}
body.rtl {
  direction: rtl;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
header{
  background:linear-gradient(135deg,#5c2f91,#8253ae);
  color:#fff;text-align:center;padding:24px 20px 24px;
  position:sticky;top:0;z-index:10;box-shadow:0 3px 16px #0002;
}
.lang-switcher-bar {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-bottom: 15px;
}
.lang-btn {
  background: rgba(255, 255, 255, 0.2);
  border: 1px solid rgba(255, 255, 255, 0.5);
  color: #fff;
  padding: 6px 14px;
  border-radius: 20px;
  cursor: pointer;
  font-size: 13px;
  font-weight: bold;
  transition: all 0.2s ease;
}
.lang-btn:hover, .lang-btn.active {
  background: #ffffff;
  color: var(--purple);
  border-color: #ffffff;
}

.logo{font-size:32px;font-weight:800;letter-spacing:-1px}
.logo small{display:block;font-size:14px;letter-spacing:4px;font-weight:500}
header h1{margin:10px 0 5px;font-size:26px}
header p{margin:0;opacity:.9;font-size:14px}
nav{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;margin-top:16px}
nav a{
  color:#fff;text-decoration:none;padding:8px 14px;border:1px solid #fff6;
  border-radius:20px;background:#fff1;font-size:13px;transition:all 0.2s;
}
nav a:hover{background:#fff2}
.hero{
  max-width:1100px;margin:25px auto 10px;padding:0 20px;
}
.hero-card{
  background:#fff;border-radius:24px;padding:28px;
  box-shadow:0 8px 30px #4e2a7614;text-align:center;
}
.hero-card h2{color:var(--purple);font-size:28px;margin:0 0 8px}
.hero-card p{color:var(--muted);font-size:16px}
.container{max-width:1100px;margin:auto;padding:10px 20px 50px}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:18px}
.card{
  background:#fff;border:1px solid #eadff2;border-radius:20px;
  padding:22px;box-shadow:0 5px 20px #4e2a7610;
}
.card.full{grid-column:1/-1}
.icon{
  width:48px;height:48px;border-radius:14px;background:var(--purple);
  color:#fff;display:flex;align-items:center;justify-content:center;
  font-size:24px;margin-bottom:12px;
}
body.rtl .icon {
  margin-left: auto;
  margin-right: 0;
}
h3{margin:0 0 10px;color:var(--purple);font-size:20px}
p{line-height:1.6}
.info-row{
  display:flex;justify-content:space-between;gap:20px;padding:11px 0;
  border-bottom:1px solid #eee6f3
}
.info-row:last-child{border-bottom:0}
.label{font-weight:700}.value{text-align:right}
body.rtl .value{text-align:left}
.notice{
  background:#f1e7f9;border-left:5px solid var(--purple);
  padding:15px 17px;border-radius:10px;margin-top:14px
}
body.rtl .notice {
  border-left: none;
  border-right: 5px solid var(--purple);
}
ul{line-height:1.8;margin-top:8px;padding-left:20px}
body.rtl ul{padding-left:0;padding-right:20px}
details{
  background:#faf7fc;border:1px solid #eadff2;border-radius:12px;
  padding:14px 16px;margin:9px 0
}
summary{cursor:pointer;font-weight:700;color:var(--purple)}
.btn{
  display:inline-block;background:var(--purple);color:#fff;text-decoration:none;
  padding:12px 18px;border-radius:25px;margin:8px 4px 0 0;font-weight:600;
}
.btn.secondary{background:#eee3f6;color:var(--purple)}

/* Map Container Styling */
.map-container {
  background: #faf7fc;
  border: 1px solid #eadff2;
  border-radius: 16px;
  padding: 20px;
  margin-top: 14px;
}

.map-grid-legend {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 20px;
  margin-top: 15px;
}

.legend-group h4 {
  color: var(--purple);
  margin: 0 0 10px 0;
  padding-bottom: 5px;
  border-bottom: 2px solid var(--purple2);
}

.legend-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.legend-list li {
  font-size: 13px;
  padding: 4px 0;
  display: flex;
  align-items: baseline;
}

.legend-badge {
  display: inline-block;
  min-width: 32px;
  font-weight: bold;
  color: var(--purple);
  font-size: 12px;
}

/* Facility Badges & Visual Grids */
.facility-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 12px;
  margin-top: 14px;
}
.facility-item {
  background: #faf7fc;
  border: 1px solid #eadff2;
  border-radius: 12px;
  padding: 14px;
}
.facility-item h4 {
  margin: 0 0 6px 0;
  color: var(--purple);
  font-size: 15px;
}
.facility-item p {
  margin: 0;
  font-size: 13px;
  color: var(--muted);
}
.tag {
  display: inline-block;
  background: #eee3f6;
  color: var(--purple);
  font-size: 11px;
  font-weight: bold;
  padding: 3px 8px;
  border-radius: 6px;
  margin-top: 8px;
}

footer{
  text-align:center;background:#5c2f91;color:#fff;padding:28px 20px
}
@media(max-width:700px){
  .grid{grid-template-columns:1fr}
  .card.full{grid-column:auto}
  header h1{font-size:22px}
  .hero-card h2{font-size:24px}
  .info-row{flex-direction:column;gap:3px}.value{text-align:left}
  body.rtl .value{text-align:right}
  .map-grid-legend {grid-template-columns: 1fr;}
}
</style>
</head>
<body>

<header>
  <!-- Language Switcher Bar -->
  <div class="lang-switcher-bar">
    <button class="lang-btn active" onclick="setLanguage('en', this)">English</button>
    <button class="lang-btn" onclick="setLanguage('zh', this)">中文 (Chinese)</button>
    <button class="lang-btn" onclick="setLanguage('ar', this)">العربية (Arabic)</button>
  </div>

  <div class="logo">Holiday Inn<small>RESORT PHUKET</small></div>
  <h1 id="hdr-title">All the information you need</h1>
  <p id="hdr-desc">Everything you need for a comfortable stay.</p>
  <nav>
    <a href="#checkin" id="nav-checkin">Check-in</a>
    <a href="#breakfast" id="nav-breakfast">Breakfast</a>
    <a href="#wifi" id="nav-wifi">Wi-Fi</a>
    <a href="#map" id="nav-map">Resort Map</a>
    <a href="#facilities" id="nav-facilities">Facilities</a>
    <a href="#kids" id="nav-kids">Kids Club</a>
    <a href="#contact" id="nav-contact">Contact</a>
    <a href="#faq" id="nav-faq">FAQ</a>
    <a href="#hotel-website" id="nav-website" style="background:var(--gold); border-color:var(--gold);">Hotel Website</a>
    <a href="#ihg" id="nav-ihg">IHG Rewards</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-card">
    <h2 id="hero-title">Welcome! ♡</h2>
    <p id="hero-desc">Thank you for choosing to stay with us.<br>We wish you a wonderful and relaxing stay.</p>
    <p><strong id="hero-sub">We're here to help · Enjoy your stay · Have a great time!</strong></p>
  </div>
</section>

<main class="container">
<div class="grid">

<!-- HOTEL WEBSITE LINK SECTION -->
<section class="card full" id="hotel-website" style="border:2px solid #d97706; background: #fffcf7;">
  <div class="icon" style="background:#d97706;">🌐</div>
  <h3 style="color:#d97706;" id="web-title">OFFICIAL HOTEL WEBSITE</h3>
  <p id="web-desc">Book directly, explore resort promotions, check room types, or make special requests on our official hotel website.</p>
  <a class="btn" style="background:#d97706;" href="https://phuket.holidayinnresorts.com/" target="_blank" id="web-btn">Visit Holiday Inn Resort Phuket Website ↗</a>
</section>

<section class="card" id="checkin">
  <div class="icon">◷</div>
  <h3 id="ci-title">CHECK-IN / CHECK-OUT</h3>
  <div class="info-row"><span class="label" id="ci-in-label">Check-in time</span><span class="value" id="ci-in-val">3:00 PM</span></div>
  <div class="info-row"><span class="label" id="ci-out-label">Check-out time</span><span class="value" id="ci-out-val">12:00 PM (noon)</span></div>
</section>

<section class="card" id="breakfast">
  <div class="icon">🍴</div>
  <h3 id="bf-title">BREAKFAST</h3>
  <div class="info-row"><span class="label" id="bf-rest-label">Restaurant</span><span class="value" id="bf-rest-val">Charm Thai Restaurant</span></div>
  <div class="info-row"><span class="label" id="bf-time-label">Time</span><span class="value" id="bf-time-val">6:30 AM – 10:30 AM</span></div>
</section>

<section class="card full" id="wifi">
  <div class="icon">⌁</div>
  <h3 id="wifi-title">WI-FI ACCESS (AFTER CHECK-IN)</h3>
  <div class="info-row"><span class="label" id="wifi-net-label">Network</span><span class="value"><strong id="wifi-net-val">HolidayInn</strong></span></div>
  <div class="info-row"><span class="label" id="wifi-user-label">Username</span><span class="value" id="wifi-user-val">Your Last Name</span></div>
  <div class="info-row"><span class="label" id="wifi-pass-label">Password</span><span class="value" id="wifi-pass-val">Room Number</span></div>
  <div class="notice" id="wifi-notice">
    <strong>Example:</strong> If your room number is <strong>1523</strong>, your Wi-Fi password is <strong>1523</strong>.
    <br>Wi-Fi can be used <strong>after check-in</strong>.
  </div>
</section>

<!-- HOTEL MAP SECTION -->
<section class="card full" id="map">
  <div class="icon">⌖</div>
  <h3 id="map-title">RESORT AREA MAP</h3>
  <p id="map-desc">Explore our resort zones, facilities, and swimming pools according to the area map.</p>
  
  <div class="map-container">
  <div style="text-align:center; margin:15px 0;">
    <img src="data:image/jpeg;base64,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rq3Sp1475A49v3fT/AFG83/C/X+R09zt5z1f/AOp43/4/e57/AOfp/wDKXXmP2I3z+37e9z+s/M3t/p335/IjrqfSv3G/Y7/3f0v8/e432/m/E3s/kdN/TfuN+x3/ALv6/vf0/e335v3G+/f0XrqvSi96QftfT+7+/f094/3X25/1O5y+/P2/4yX/AJ9v8m/d+o25+/u/vL//AEXrq3So1/8AYD4eO+49O/L2v3G+/e425/U7/CdD9/a7e53f09ztz9v+M/P+P3u/M/37f5N+79X15+/v79/e/M7Xbm/eb/AM515l32/m//AJXbb/M+3/8Ag6a539ve5233L3/3P39999/e/Odef+23/wDRf9uXv5z1f/4/b39f3ebbf9D2f2/v/m5f+/u/+m9Ldft/y4/f3O53e5u/4Wd36vf4d/t87e53P39y/eb9/f+cv+XzO1+3zvv39/8m9/4j79y/f2u119zf+e9xvuX9vdL9f+/eb2v3N3/AevvdL9ve3f8B+11+/v/wCZm/293+S25/m9rd9zf+A42vv33/N/37/eb/xfvf372/f3/wDO3X/2/wD34m2/eb332O23z9qXf8S+9+f92/6i99d/y/8Avx3v/e/+Anbvf9P++vM++432e22Xf/M3/Mzf9/d/p3+/O3v7/eb23+s5v/L/AFG3z+/f391u2/fb/P3/AOfve/8Ad+X+S3W33+/4nd23/wAv3/ub9m4f/U++43/G2+91/uN/yO1+Xv3utv3f+Qvf/m5m/mNvvd2/8m2/v7l+43W7b99ud+290tv9/f8Am/m5f0u6/m73G23/AEf7Ldb9P83+/d/35Lbb/P8Ad/uN23+vO7vf9/v/AJm99t19/pPvf3/zb7d/P23v/m/3/wCe+5ebf/E38u9vt/3+L9/efqL9v+/N+5bf+/0tvt2/6M3t/Pbbbb/+fLbb2/3+4/8Avutv+i7m9+f/ADtv/f7j/eb3ut+9y/5m9y32/m/E/wDn1G+37233v+e/S9vv79+X1/5ud/v/AJN9/vb35bfuL38m++/9/v2u109vf3t/p+p+f+e+/eb225fbv9Xf9/8Ad3v/AC+/f/P0+1297d2/2+X15fbf2vb+4ve5f+k/L++3/k3+p9vfvbv+evM9f9e/+Zut/wDPv333G22/f353L325fbfvf/P3/mX3/vf3999u3u/m39X9b2u1v/325a7fbvf/AH53O3P5E2/L2u1tv+c37X/eb932L/X9L/vbbfmNuvs+xv2vb39223m235m/bf8A0337fvvvf3N3uO35y22+37+5f1X9Pbfd3G/Y3t+91tv3v9222+X8xvyfS/7e/vbv+At+f/P8S+9y/Eutvd993N3/AD5XmN9+fv8AJve9/f8Ae++/xM79r6jbfvbv923L+0v9Lbbd32575A//2Q==" usemap="#resortmap" style="max-width:100%; height:auto; border-radius:12px; border: 1px solid #eadff2;" alt="Resort Map">
  </div>

  <div class="map-grid-legend">
    <div class="legend-group">
      <h4>Main Wing</h4>
      <ul class="legend-list">
        <li><span class="legend-badge">01</span> Main Wing Reception</li>
        <li><span class="legend-badge">02</span> Main Wing Swimming Pool</li>
        <li><span class="legend-badge">03</span> Kids Club & Kids Pool</li>
        <li><span class="legend-badge">04</span> Sea Breeze Café (Breakfast)</li>
        <li><span class="legend-badge">05</span> Terrazzo Ristorante (Italian)</li>
        <li><span class="legend-badge">06</span> Sam's Steaks & Grill</li>
        <li><span class="legend-badge">07</span> Fitness Center & Spa</li>
      </ul>
    </div>
    <div class="legend-group">
      <h4>Busakorn Wing</h4>
      <ul class="legend-list">
        <li><span class="legend-badge">08</span> Busakorn Wing Reception</li>
        <li><span class="legend-badge">09</span> Busakorn Main Pool & Bar</li>
        <li><span class="legend-badge">10</span> Busakorn Villa Pool (Adults Only)</li>
        <li><span class="legend-badge">11</span> Charm Thai Restaurant</li>
        <li><span class="legend-badge">12</span> Grab & Go Deli</li>
        <li><span class="legend-badge">13</span> Resort Gardens & Courtyard</li>
        <li><span class="legend-badge">14</span> Main Entrance / Taxi Stand</li>
      </ul>
    </div>
  </div>
</div>
</section>

<!-- FACILITIES SECTION -->
<section class="card full" id="facilities">
  <div class="icon">🏖</div>
  <h3 id="fac-title">RESORT FACILITIES & AMENITIES</h3>
  <div class="facility-grid">
    <div class="facility-item">
      <h4>Swimming Pools</h4>
      <p>4 Outdoor Pools including Main Pool, Kids Pool with Slides, and Adult-Only Villa Pool.</p>
      <span class="tag">7:00 AM – 7:00 PM</span>
    </div>
    <div class="facility-item">
      <h4>Fitness Center</h4>
      <p>Fully equipped gym with cardio and weight training equipment.</p>
      <span class="tag">24 Hours (Keycard Access)</span>
    </div>
    <div class="facility-item">
      <h4>Tea Tree Spa</h4>
      <p>Relaxing massages, body treatments, and traditional Thai spa therapies.</p>
      <span class="tag">10:00 AM – 8:00 PM</span>
    </div>
    <div class="facility-item">
      <h4>Excursion & Tour Desk</h4>
      <p>Book island tours, water sports, taxi services, and local attractions.</p>
      <span class="tag">Main Wing Lobby</span>
    </div>
  </div>
</section>

<!-- KIDS CLUB SECTION -->
<section class="card full" id="kids">
  <div class="icon">🎈</div>
  <h3 id="kids-title">KIDS CLUB (CLUB4KIDS)</h3>
  <p id="kids-desc">Fun daily activities, crafts, games, and play areas for children aged 5-12. Children under 5 are welcome with parent supervision.</p>
  <div class="info-row"><span class="label">Operating Hours</span><span class="value">9:00 AM – 5:00 PM</span></div>
  <div class="notice">
    <strong>Kids Stay & Eat Free:</strong> Kids under 12 stay free when using existing bedding and eat free from the kids' menu when accompanied by a paying adult.
  </div>
</section>

<!-- CONTACT SECTION -->
<section class="card" id="contact">
  <div class="icon">📞</div>
  <h3 id="contact-title">CONTACT & FRONT DESK</h3>
  <div class="info-row"><span class="label">Front Desk / Operator</span><span class="value">Press 0 on room phone</span></div>
  <div class="info-row"><span class="label">Resort Phone</span><span class="value">+66 (0) 76 370 200</span></div>
  <div class="info-row"><span class="label">Email</span><span class="value">reservation@holidayinn-phuket.com</span></div>
</section>

<!-- FAQ SECTION -->
<section class="card" id="faq">
  <div class="icon">❓</div>
  <h3 id="faq-title">FREQUENTLY ASKED QUESTIONS</h3>
  <details>
    <summary>Late Check-out Request?</summary>
    <p>Late check-out is subject to room availability and may incur additional charges. Please contact Front Desk (Dial 0) on your departure morning.</p>
  </details>
  <details>
    <summary>Pool Towels Information</summary>
    <p>Complimentary pool towels are available at towel stations located near each swimming pool area using your towel card.</p>
  </details>
  <details>
    <summary>Smoking Policy</summary>
    <p>All indoor areas and guest rooms are strictly non-smoking. Smoking is permitted only in designated outdoor smoking zones.</p>
  </details>
</section>

<!-- IHG REWARDS SECTION -->
<section class="card full" id="ihg">
  <div class="icon">⭐</div>
  <h3 id="ihg-title">IHG ONE REWARDS</h3>
  <p id="ihg-desc">Earn points for every stay, enjoy exclusive member rates, free Wi-Fi, and reward nights at over 6,000 hotels worldwide.</p>
  <a class="btn secondary" href="https://www.ihg.com/onerewards" target="_blank">Join or Learn More ↗</a>
</section>

</div>
</main>

<footer>
  <p>© Holiday Inn Resort Phuket. All rights reserved.</p>
</footer>

<script>
const translations = {
  en: {
    dir: 'ltr',
    hdrTitle: 'All the information you need',
    hdrDesc: 'Everything you need for a comfortable stay.',
    navCheckin: 'Check-in',
    navBreakfast: 'Breakfast',
    navWifi: 'Wi-Fi',
    navMap: 'Resort Map',
    navFacilities: 'Facilities',
    navKids: 'Kids Club',
    navContact: 'Contact',
    navFaq: 'FAQ',
    navWebsite: 'Hotel Website',
    navIhg: 'IHG Rewards',
    heroTitle: 'Welcome! ♡',
    heroDesc: 'Thank you for choosing to stay with us.<br>We wish you a wonderful and relaxing stay.',
    heroSub: 'We\'re here to help · Enjoy your stay · Have a great time!',
    webTitle: 'OFFICIAL HOTEL WEBSITE',
    webDesc: 'Book directly, explore resort promotions, check room types, or make special requests on our official hotel website.',
    webBtn: 'Visit Holiday Inn Resort Phuket Website ↗',
    ciTitle: 'CHECK-IN / CHECK-OUT',
    ciInLabel: 'Check-in time',
    ciInVal: '3:00 PM',
    ciOutLabel: 'Check-out time',
    ciOutVal: '12:00 PM (noon)',
    bfTitle: 'BREAKFAST',
    bfRestLabel: 'Restaurant',
    bfRestVal: 'Charm Thai Restaurant',
    bfTimeLabel: 'Time',
    bfTimeVal: '6:30 AM – 10:30 AM',
    wifiTitle: 'WI-FI ACCESS (AFTER CHECK-IN)',
    wifiNetLabel: 'Network',
    wifiNetVal: 'HolidayInn',
    wifiUserLabel: 'Username',
    wifiUserVal: 'Your Last Name',
    wifiPassLabel: 'Password',
    wifiPassVal: 'Room Number',
    wifiNotice: '<strong>Example:</strong> If your room number is <strong>1523</strong>, your Wi-Fi password is <strong>1523</strong>.<br>Wi-Fi can be used <strong>after check-in</strong>.',
    mapTitle: 'RESORT AREA MAP',
    mapDesc: 'Explore our resort zones, facilities, and swimming pools according to the area map.',
    facTitle: 'RESORT FACILITIES & AMENITIES',
    kidsTitle: 'KIDS CLUB (CLUB4KIDS)',
    kidsDesc: 'Fun daily activities, crafts, games, and play areas for children aged 5-12. Children under 5 are welcome with parent supervision.',
    contactTitle: 'CONTACT & FRONT DESK',
    faqTitle: 'FREQUENTLY ASKED QUESTIONS',
    ihgTitle: 'IHG ONE REWARDS',
    ihgDesc: 'Earn points for every stay, enjoy exclusive member rates, free Wi-Fi, and reward nights at over 6,000 hotels worldwide.'
  },
  zh: {
    dir: 'ltr',
    hdrTitle: '您所需的所有信息',
    hdrDesc: '为您舒适入住提供的一切所需。',
    navCheckin: '入住/退房',
    navBreakfast: '早餐',
    navWifi: '无线网络',
    navMap: '度假村地图',
    navFacilities: '设施',
    navKids: '儿童俱乐部',
    navContact: '联系我们',
    navFaq: '常见问题',
    navWebsite: '酒店官网',
    navIhg: 'IHG优悦会',
    heroTitle: '欢迎光临！♡',
    heroDesc: '感谢您选择入住我们的度假村。<br>祝您度过一段美好而放松的时光。',
    heroSub: '随时为您提供帮助 · 尽情享受您的假期！',
    webTitle: '酒店官方网站',
    webDesc: '通过我们的官方网站直接预订、探索度假村优惠、查看房型或提交特殊要求。',
    webBtn: '访问普吉岛假日度假酒店官网 ↗',
    ciTitle: '入住 / 退房',
    ciInLabel: '入住时间',
    ciInVal: '15:00',
    ciOutLabel: '退房时间',
    ciOutVal: '12:00 (中午)',
    bfTitle: '早餐信息',
    bfRestLabel: '餐厅',
    bfRestVal: 'Charm Thai 泰式餐厅',
    bfTimeLabel: '供应时间',
    bfTimeVal: '06:30 – 10:30',
    wifiTitle: 'WIFI 连接（办理入住后）',
    wifiNetLabel: '网络名称',
    wifiNetVal: 'HolidayInn',
    wifiUserLabel: '用户名',
    wifiUserVal: '您的姓氏 (Last Name)',
    wifiPassLabel: '密码',
    wifiPassVal: '房间号',
    wifiNotice: '<strong>示例：</strong>如果您的房间号是 <strong>1523</strong>，您的 Wi-Fi 密码就是 <strong>1523</strong>。<br>Wi-Fi 需在<strong>办理入住后</strong>使用。',
    mapTitle: '度假村地图',
    mapDesc: '根据区域地图探索我们的度假村区域、设施和游泳池。',
    facTitle: '度假村设施与服务',
    kidsTitle: '儿童俱乐部 (Club4Kids)',
    kidsDesc: '为5-12岁儿童提供有趣的日常活动、手工、游戏和游乐区。5岁以下儿童须在家长陪同下入场。',
    contactTitle: '联系方式与前台',
    faqTitle: '常见问题',
    ihgTitle: 'IHG 优悦会',
    ihgDesc: '每次入住均可赚取积分，享受会员专属特惠房价、免费 Wi-Fi 以及全球 6,000 多家酒店的奖励住宿。'
  },
  ar: {
    dir: 'rtl',
    hdrTitle: 'كل المعلومات التي تحتاجها',
    hdrDesc: 'كل ما تحتاجه لإقامة مريحة وممتعة.',
    navCheckin: 'تسجيل الوصول',
    navBreakfast: 'الإفطار',
    navWifi: 'واي فاي',
    navMap: 'خريطة المنتجع',
    navFacilities: 'المرافق',
    navKids: 'نادي الأطفال',
    navContact: 'اتصل بنا',
    navFaq: 'الأسئلة الشائعة',
    navWebsite: 'موقع الفندق',
    navIhg: 'مكافآت IHG',
    heroTitle: 'أهلاً وسهلاً بك! ♡',
    heroDesc: 'شكراً لاختيارك الإقامة معنا.<br>نتمنى لك إقامة رائعة ومريحة.',
    heroSub: 'نحن هنا لمساعدتك · استمتع بإقامتك · نتمنى لك وقتاً ممتعاً!',
    webTitle: 'الموقع الرسمي للفندق',
    webDesc: 'احجز مباشرة، واستكشف عروض المنتجع، وتحقق من أنواع الغرف، أو قدم طلبات خاصة على موقعنا الرسمي.',
    webBtn: 'زيارة موقع هوليداي إن ريزورت بوكيت ↗',
    ciTitle: 'تسجيل الوصول / المغادرة',
    ciInLabel: 'وقت تسجيل الوصول',
    ciInVal: '3:00 مساءً',
    ciOutLabel: 'وقت المغادرة',
    ciOutVal: '12:00 ظهراً',
    bfTitle: 'الإفطار',
    bfRestLabel: 'المطعم',
    bfRestVal: 'مطعم تشارم ثاي (Charm Thai)',
    bfTimeLabel: 'الوقت',
    bfTimeVal: '6:30 صباحاً – 10:30 صباحاً',
    wifiTitle: 'الاتصال بالواي فاي (بعد تسجيل الوصول)',
    wifiNetLabel: 'شبكة الإنترنت',
    wifiNetVal: 'HolidayInn',
    wifiUserLabel: 'اسم المستخدم',
    wifiUserVal: 'اسم العائلة',
    wifiPassLabel: 'كلمة المرور',
    wifiPassVal: 'رقم الغرفة',
    wifiNotice: '<strong>مثال:</strong> إذا كان رقم غرفتك <strong>1523</strong>، فإن كلمة مرور الواي فاي هي <strong>1523</strong>.<br>يمكن استخدام الواي فاي <strong>بعد تسجيل الوصول</strong>.',
    mapTitle: 'خريطة المنتجع',
    mapDesc: 'استكشف مناطق المنتجع والمرافق وحمامات السباحة وفقاً لخريطة المنطقة.',
    facTitle: 'مرافق وخدمات المنتجع',
    kidsTitle: 'نادي الأطفال (Club4Kids)',
    kidsDesc: 'أنشطة يومية ممتعة، وأعمال يدوية، وألعاب ومناطق لعب للأطفال من سن 5 إلى 12 عاماً. الأطفال دون سن 5 سنوات مرحب بهم تحت إشراف الوالدين.',
    contactTitle: 'الاتصال والمكتب الأمامي',
    faqTitle: 'الأسئلة الشائعة',
    ihgTitle: 'مكافآت IHG One Rewards',
    ihgDesc: 'اكتسب نقاطاً مع كل إقامة، واستمتع بأسعار حصرية للأعضاء، وواي فاي مجاني، والليالي المجانية في أكثر من 6000 فندق حول العالم.'
  }
};

function setLanguage(lang, btn) {
  // Update button active states
  document.querySelectorAll('.lang-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');

  const t = translations[lang];
  if (!t) return;

  // Update text direction
  if (t.dir === 'rtl') {
    document.body.classList.add('rtl');
  } else {
    document.body.classList.remove('rtl');
  }

  // Update element text
  document.getElementById('hdr-title').innerHTML = t.hdrTitle;
  document.getElementById('hdr-desc').innerHTML = t.hdrDesc;
  document.getElementById('nav-checkin').innerHTML = t.navCheckin;
  document.getElementById('nav-breakfast').innerHTML = t.navBreakfast;
  document.getElementById('nav-wifi').innerHTML = t.navWifi;
  document.getElementById('nav-map').innerHTML = t.navMap;
  document.getElementById('nav-facilities').innerHTML = t.navFacilities;
  document.getElementById('nav-kids').innerHTML = t.navKids;
  document.getElementById('nav-contact').innerHTML = t.navContact;
  document.getElementById('nav-faq').innerHTML = t.navFaq;
  document.getElementById('nav-website').innerHTML = t.navWebsite;
  document.getElementById('nav-ihg').innerHTML = t.navIhg;

  document.getElementById('hero-title').innerHTML = t.heroTitle;
  document.getElementById('hero-desc').innerHTML = t.heroDesc;
  document.getElementById('hero-sub').innerHTML = t.heroSub;

  document.getElementById('web-title').innerHTML = t.webTitle;
  document.getElementById('web-desc').innerHTML = t.webDesc;
  document.getElementById('web-btn').innerHTML = t.webBtn;

  document.getElementById('ci-title').innerHTML = t.ciTitle;
  document.getElementById('ci-in-label').innerHTML = t.ciInLabel;
  document.getElementById('ci-in-val').innerHTML = t.ciInVal;
  document.getElementById('ci-out-label').innerHTML = t.ciOutLabel;
  document.getElementById('ci-out-val').innerHTML = t.ciOutVal;

  document.getElementById('bf-title').innerHTML = t.bfTitle;
  document.getElementById('bf-rest-label').innerHTML = t.bfRestLabel;
  document.getElementById('bf-rest-val').innerHTML = t.bfRestVal;
  document.getElementById('bf-time-label').innerHTML = t.bfTimeLabel;
  document.getElementById('bf-time-val').innerHTML = t.bfTimeVal;

  document.getElementById('wifi-title').innerHTML = t.wifiTitle;
  document.getElementById('wifi-net-label').innerHTML = t.wifiNetLabel;
  document.getElementById('wifi-net-val').innerHTML = t.wifiNetVal;
  document.getElementById('wifi-user-label').innerHTML = t.wifiUserLabel;
  document.getElementById('wifi-user-val').innerHTML = t.wifiUserVal;
  document.getElementById('wifi-pass-label').innerHTML = t.wifiPassLabel;
  document.getElementById('wifi-pass-val').innerHTML = t.wifiPassVal;
  document.getElementById('wifi-notice').innerHTML = t.wifiNotice;

  document.getElementById('map-title').innerHTML = t.mapTitle;
  document.getElementById('map-desc').innerHTML = t.mapDesc;
  document.getElementById('fac-title').innerHTML = t.facTitle;
  document.getElementById('kids-title').innerHTML = t.kidsTitle;
  document.getElementById('kids-desc').innerHTML = t.kidsDesc;
  document.getElementById('contact-title').innerHTML = t.contactTitle;
  document.getElementById('faq-title').innerHTML = t.faqTitle;
  document.getElementById('ihg-title').innerHTML = t.ihgTitle;
  document.getElementById('ihg-desc').innerHTML = t.ihgDesc;
}
</script>

</body>
</html>
