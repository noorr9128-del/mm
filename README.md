<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>فلوسك وصحتك</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@600;800&family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
<style>
  :root{
    --cream:#F7F4EC; --cream-2:#EDE7D6; --sage:#7C9473; --gold:#C9A227;
    --teal:#2E4A45; --ink:#232019; --ink-soft:#66604F; --line: rgba(35,32,25,0.14);
    box-sizing:border-box;
    padding-top: env(safe-area-inset-top,0px);
    padding-bottom: env(safe-area-inset-bottom,0px);
  }
  @media (prefers-color-scheme: dark){
    :root:not([data-theme="light"]){
      --cream:#1B1A15; --cream-2:#232019; --sage:#9CB791; --gold:#E0BB4F;
      --teal:#B9D6CE; --ink:#EFE9DA; --ink-soft:#B7AF9B; --line: rgba(239,233,218,0.16);
    }
  }
  :root[data-theme="dark"]{
    --cream:#1B1A15; --cream-2:#232019; --sage:#9CB791; --gold:#E0BB4F;
    --teal:#B9D6CE; --ink:#EFE9DA; --ink-soft:#B7AF9B; --line: rgba(239,233,218,0.16);
  }
  html,body{height:100%;}
  html{scroll-padding-top: env(safe-area-inset-top,0px);}
  *{box-sizing:border-box;}
  body{ margin:0; background:var(--cream); color:var(--ink); font-family:'Tajawal',sans-serif; line-height:1.75; overflow-x:hidden; }
  a{color:inherit; text-decoration:none;}
  h1,h2,h3{ font-family:'Cairo',sans-serif; margin:0 0 .3em; color:var(--teal); font-weight:800; }
  .wrap{max-width:980px; margin:0 auto; padding:0 24px;}

  header{ position:sticky; top:0; z-index:30; background:var(--cream); border-bottom:1px solid var(--line); padding-top:env(safe-area-inset-top,0px); }
  nav.wrap{ display:flex; align-items:center; justify-content:space-between; padding:16px 24px; }
  .brand{ font-family:'Cairo',sans-serif; font-weight:800; font-size:1.3rem; color:var(--teal); }
  .navlinks{ display:flex; gap:4px; }
  .navlinks a{ font-family:'Tajawal'; font-size:.95rem; font-weight:500; padding:9px 18px; color:var(--ink-soft); border-bottom:2px solid transparent; }
  .navlinks a.active{ color:var(--gold); border-bottom-color:var(--gold); }

  .hero{ padding:70px 0 20px; display:grid; grid-template-columns:1.1fr .9fr; gap:30px; align-items:center; }
  .hero h1{ font-size:2.5rem; }
  .hero p.lead{ color:var(--ink-soft); max-width:44ch; font-size:1.05rem; margin-top:8px; }

  .balance{ width:100%; max-width:300px; justify-self:center; }

  .strip{ background:var(--teal); color:var(--cream); padding:44px 0; margin-top:30px; }
  .strip .wrap{ text-align:center; }
  .strip h2{ color:var(--cream); font-size:1.6rem; max-width:34ch; margin:0 auto .3em; }
  .strip p{ color:var(--cream-2); opacity:.85; max-width:52ch; margin:0 auto; }

  .twocol{ display:grid; grid-template-columns:1fr 1fr; gap:0; margin-top:0; }
  .panel{ padding:50px 34px; }
  .panel.money{ background:var(--cream-2); border-left:1px solid var(--line); }
  .panel h3{ display:flex; align-items:center; gap:10px; font-size:1.3rem; }
  .panel h3 svg{ width:30px; height:30px; }
  .panel p{ color:var(--ink-soft); font-size:.95rem; }

  .closing{ padding:56px 0 70px; text-align:center; }
  .closing p{ max-width:52ch; margin:0 auto; color:var(--ink-soft); font-size:1.05rem; }
  .closing h2{ font-size:1.6rem; }
  .cta{ display:inline-block; margin-top:22px; padding:13px 28px; background:var(--gold); color:var(--teal); border-radius:10px; font-weight:700; font-family:'Cairo'; }

  footer{ padding:30px 0 50px; text-align:center; color:var(--ink-soft); font-size:.88rem; }

  @media (max-width:760px){
    .hero{ grid-template-columns:1fr; text-align:center; }
    .twocol{ grid-template-columns:1fr; }
    .panel.money{ border-left:none; border-bottom:1px solid var(--line); }
    nav.wrap{ flex-direction:column; gap:10px; padding:14px; }
  }
</style>
</head>
<body>

<header>
  <nav class="wrap">
    <div class="brand">فلوسك وصحتك</div>
    <div class="navlinks">
      <a href="index.html" class="active">الرئيسية</a>
      <a href="tips.html">نصائح عملية</a>
    </div>
  </nav>
</header>

<section>
  <div class="wrap hero">
    <div>
      <h1>فلوسك وصحتك... توازن يبدأ بعادة صغيرة</h1>
      <p class="lead">التوفير المالي والصحة الجسدية أقرب لبعض مما تتخيل — الاثنين يبدآن بقرارات يومية بسيطة، وينتهي بحياة أكثر استقرارًا وراحة.</p>
    </div>
    <svg class="balance" viewBox="0 0 220 200" xmlns="http://www.w3.org/2000/svg">
      <line x1="110" y1="30" x2="110" y2="150" stroke="var(--teal)" stroke-width="6"/>
      <line x1="40" y1="60" x2="180" y2="60" stroke="var(--teal)" stroke-width="5"/>
      <line x1="40" y1="60" x2="40" y2="95" stroke="var(--teal)" stroke-width="3"/>
      <line x1="180" y1="60" x2="180" y2="95" stroke="var(--teal)" stroke-width="3"/>
      <circle cx="40" cy="105" r="26" fill="var(--gold)"/>
      <text x="40" y="112" font-size="20" text-anchor="middle" fill="var(--teal)" font-family="Cairo">﷼</text>
      <circle cx="180" cy="105" r="26" fill="var(--sage)"/>
      <path d="M180 92 C170 96 168 106 176 114 C180 118 184 116 186 110 C190 100 188 94 180 92 Z" fill="var(--cream)"/>
      <ellipse cx="110" cy="150" rx="30" ry="8" fill="var(--teal)"/>
      <rect x="100" y="150" width="20" height="30" fill="var(--teal)"/>
      <ellipse cx="110" cy="180" rx="34" ry="9" fill="var(--teal)"/>
    </svg>
  </div>
</section>

<div class="strip">
  <div class="wrap">
    <h2>عادة واحدة ممكن تخدم الاثنين مع بعض</h2>
    <p>لما تطبخين ببيتك بدل التوصيل، توفرين فلوس وتاكلين صحي بنفس الوقت — عادة وحدة، فايدتين.</p>
  </div>
</div>

<div class="twocol">
  <div class="panel money">
    <h3><svg viewBox="0 0 40 40"><circle cx="20" cy="20" r="18" fill="var(--gold)"/><text x="20" y="27" font-size="18" text-anchor="middle" fill="var(--teal)">﷼</text></svg> جانب التوفير</h3>
    <p>الميزانية الشهرية، قاعدة الـ24 ساعة قبل الشراء، وتتبع المصاريف الصغيرة كلها خطوات بسيطة تبني أمان مالي مع الوقت.</p>
  </div>
  <div class="panel health">
    <h3><svg viewBox="0 0 40 40"><circle cx="20" cy="20" r="18" fill="var(--sage)"/></svg> جانب الصحة</h3>
    <p>المشي اليومي، شرب الماء، والنوم المنتظم عادات بسيطة بدون تكلفة، وأثرها على جسمك وطاقتك أكبر مما تتوقعين.</p>
  </div>
</div>

<div class="closing wrap">
  <h2>ابدئي بعادة وحدة هذا الأسبوع</h2>
  <p>ما تحتاجين تغيّرين حياتك كاملة دفعة وحدة — عادة صغيرة تكررينها كل يوم كافية تبدأ الفرق.</p>
  <a class="cta" href="tips.html">شوفي النصائح العملية ←</a>
</div>

<footer>موقع "فلوسك وصحتك"</footer>

</body>
</html>
