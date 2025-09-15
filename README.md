<!doctype html>
<html lang="ar" dir="rtl">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<title>عزّنا بفخرِنا — شخصيات سعودية بارزة</title>
<style>
  :root{
    --green:#006c35; --dark:#034a24; --light:#f5fff9; --card:#07391c; --edge:#0e3b22;
  }
  *{box-sizing:border-box}
  body{
    margin:0;padding:0;background:linear-gradient(180deg,#022010,#034a24);
    color:var(--light);font-family:"Noto Naskh Arabic","Amiri",Tahoma,Arial,sans-serif;line-height:1.9;
  }
  header{text-align:center;padding:14px 10px;border-bottom:2px solid var(--dark)}
  .flag{width:200px;display:block;margin:0 auto 12px auto}
  h1{margin:0;font-size:26px}
  p.lead{margin:2px 0 0 0;color:#cfe9dc;font-size:13px}
  .container{max-width:500px;margin:auto;padding:14px}
  .grid{display:grid;grid-template-columns:1fr;gap:16px}
  .card{
    background:var(--card);border:1px solid var(--edge);border-radius:12px;
    padding:14px;cursor:pointer;transition:.2s
  }
  .card:hover{transform:translateY(-2px);box-shadow:0 4px 15px rgba(0,0,0,.3)}
  .pill{
    display:inline-block;background:#0c3b23;color:#c6f5df;border:1px solid #135b36;
    border-radius:999px;padding:2px 8px;font-size:11px
  }
  .title{font-size:18px;margin:6px 0 4px 0}
  .meta{font-size:12px;color:#cfe9dc;margin-bottom:6px}
  .story{white-space:pre-line;text-align:justify;font-size:14px}
  footer{margin:20px 0 10px;text-align:center;font-size:11px;color:#cbead9}

  /* نافذة الصورة */
  .modal{
    display:none;position:fixed;z-index:999;left:0;top:0;width:100%;height:100%;
    background:rgba(0,0,0,0.8);align-items:center;justify-content:center;
  }
  .modal img{
    max-width:90%;max-height:80%;border-radius:12px;box-shadow:0 0 15px #000
  }
</style>
</head>
<body>

<header>
  <img class="flag" src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Flag_of_Saudi_Arabia.svg">
  <h1>عزّنا بفخرِنا</h1>
  <p class="lead">شخصيات سعودية بارزة</p>
</header>

<div class="container">
  <div class="grid">

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/4/4b/King_Salman_bin_Abdulaziz_Al_Saud_May_2023.jpg">
      <span class="pill">خادم الحرمين</span>
      <h3 class="title">الملك سلمان بن عبدالعزيز</h3>
      <div class="meta">ملك الحزم والعزم</div>
      <p class="story">قضى أكثر من 50 عامًا أميرًا للرياض ثم تولى الحكم عام 2015 وأطلق إصلاحات وتنمية شاملة ورعى توسعات الحرمين.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/b/b0/Mohammed_bin_Salman_2023_cropped.jpg">
      <span class="pill">ولي العهد</span>
      <h3 class="title">محمد بن سلمان</h3>
      <div class="meta">مهندس رؤية 2030</div>
      <p class="story">أطلق رؤية 2030 ومشروعات كبرى مثل نيوم وقاد إصلاحات اقتصادية واجتماعية كبرى.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/2/2a/Abdullah_Al_Rabeeah_2019.jpg">
      <span class="pill">الطب الإنساني</span>
      <h3 class="title">عبدالله الربيعة</h3>
      <div class="meta">رائد فصل التوائم</div>
      <p class="story">قاد أكثر من 50 عملية فصل توائم ناجحة وجعل المملكة مركزًا عالميًا، ويشرف على مركز الملك سلمان للإغاثة.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/4/4d/Adel_al-Jubeir_2018.jpg">
      <span class="pill">الدبلوماسية</span>
      <h3 class="title">عادل الجبير</h3>
      <div class="meta">صوت المملكة دوليًا</div>
      <p class="story">شغل مناصب بارزة منها سفير في واشنطن ووزير الخارجية ودافع عن مواقف المملكة عالميًا.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/3/34/Ghazi_Algosaibi.jpg">
      <span class="pill">الأدب والإدارة</span>
      <h3 class="title">غازي القصيبي</h3>
      <div class="meta">الأديب الوزير</div>
      <p class="story">جمع بين الأدب والسياسة وتولى وزارات وسفارات وترك إرثًا أدبيًا وإداريًا بارزًا.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/1/16/Iffat_Al_Thunayan.jpg">
      <span class="pill">التعليم النسائي</span>
      <h3 class="title">الأميرة عفت</h3>
      <div class="meta">رائدة تعليم المرأة</div>
      <p class="story">زوجة الملك فيصل وأول من أسس مدارس للبنات، دعمت تعليم المرأة وفتحت آفاقًا جديدة للفتيات.</p>
    </div>

    <div class="card" data-img="https://al-marsd.com/wp-content/uploads/2024/08/maher.png">
      <span class="pill">البطولة المدنية</span>
      <h3 class="title">ماهر العتيبي</h3>
      <div class="meta">أنقذ محطة وقود</div>
      <p class="story">قاد شاحنة مشتعلة بعيدًا عن محطة وقود وأنقذ عشرات الأرواح رغم إصابته الخطيرة.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/d/d2/Majed_Abdullah_in_2012.jpg">
      <span class="pill">الرياضة</span>
      <h3 class="title">ماجد عبدالله</h3>
      <div class="meta">أسطورة الكرة السعودية</div>
      <p class="story">هداف السعودية التاريخي وقائد المنتخب والنصر وحقق بطولات آسيوية ومحلية عديدة.</p>
    </div>

    <div class="card" data-img="https://upload.wikimedia.org/wikipedia/commons/4/47/Fayyad_Al-Ruwaili.jpg">
      <span class="pill">القيادة العسكرية</span>
      <h3 class="title">فياض الرويلي</h3>
      <div class="meta">رئيس الأركان</div>
      <p class="story">طيار مقاتل سابق يشغل منصب رئيس الأركان منذ 2018 وقاد تطوير قدرات الجيش السعودي.</p>
    </div>

  </div>
</div>

<footer>© إعداد وطني تعليمي — شخصيات سعودية بارزة</footer>

<!-- نافذة عرض الصور -->
<div id="modal" class="modal" onclick="this.style.display='none'">
  <img id="modalImg" src="" alt="صورة الشخصية">
</div>

<script>
  const cards = document.querySelectorAll('.card');
  const modal = document.getElementById('modal');
  const modalImg = document.getElementById('modalImg');

  cards.forEach(card => {
    card.addEventListener('click', () => {
      modalImg.src = card.dataset.img;
      modal.style.display = 'flex';
    });
  });
</script>

</body>
</html>
