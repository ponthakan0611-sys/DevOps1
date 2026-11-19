<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>แนะนำตัว</title>
<style>
:root{
  --bg:#000;
  --surface:#0e0c08;
  --text:#efe6d2;
  --gold:#d4af37;
  --line:rgba(212,175,55,.35);
}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,sans-serif;line-height:1.7}
.wrap{max-width:56rem;margin:0 auto;padding:0 1.5rem}

.hero{min-height:100vh;display:flex;align-items:center;padding:3rem 0}
.profile{display:flex;align-items:center;gap:2.5rem;padding:2.5rem;border:1px solid var(--line);background:var(--surface)}
.photo{flex:0 0 240px;width:240px;height:300px;padding:6px;border:2px solid var(--gold)}
.photo img{width:100%;height:100%;object-fit:cover;display:block;background:#1a1610}
.info{flex:1;min-width:0}
.name{font-size:clamp(2rem,5vw,3.5rem);margin:0 0 1.25rem;color:var(--gold)}
.meta{display:flex;flex-wrap:wrap;gap:.75rem;margin:0;padding:0;list-style:none}
.meta li{padding:.35rem 1rem;border:1px solid var(--line)}

@media(max-width:760px){
  .profile{flex-direction:column;text-align:center;padding:2rem 1.25rem;gap:1.5rem}
  .photo{flex:none;width:200px;height:250px}
  .meta{justify-content:center}
}

footer{padding:2rem 0;text-align:center;color:var(--text);font-size:.9rem;border-top:1px solid var(--line)}
</style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <div class="profile">
      <div class="photo">
        <img src="profile.jpg" alt="รูปโปรไฟล์ สมชาย">
      </div>
      <div class="info">
        <h1 class="name">พลธกานต์</h1>
        <ul class="meta">
          <li><strong>ชื่อ-สกุล:</strong> พลธกานต์ ผดุงพล</li>
          <li><strong>สถานะ:</strong> นักศึกษาระดับชั้น ปวส.2</li>
          <li><strong>อายุ:</strong> 20 ปี</li>
        </ul>
      </div>
    </div>
  </div>
</header>

<footer>© 2026 สมชาย</footer>

</body>
</html>