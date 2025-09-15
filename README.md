<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>عزّنا بفخرِنا — شخصيات سعودية بارزة</title>
  <style>
    :root{
      --green:#0a5c3d;
      --dark:#053824;
      --light:#fafdfb;
      --sand:#d8c7a1;
      --card:#0f3d28;
      --edge:#146644;
    }
    *{box-sizing:border-box}
    body{
      margin:0;padding:0;
      background:linear-gradient(180deg,#032015,#065233);
      color:var(--light);
      font-family:"Noto Naskh Arabic","Amiri",Tahoma,Arial,sans-serif;
      line-height:1.9
    }
    header{
      text-align:center;
      padding:30px 15px;
      border-bottom:4px solid var(--green);
      background:var(--dark);
      position:relative;
    }
    header::after{
      content:"";
      position:absolute;
      bottom:-12px;left:0;right:0;
      height:12px;
      background: repeating-linear-gradient(
        45deg, var(--sand), var(--sand) 10px, var(--green) 10px, var(--green) 20px
      );
    }
    .flag{width:280px;display:block;margin:0 auto 14px auto}
    h1{margin:0;font-size:42px;color:var(--sand)}
    p.lead{margin:6px 0 0 0;color:#d9f5e7}

    .container{max-width:1200px;margin:auto;padding:30px 20px}
    .grid{
      display:grid;
      grid-template-columns: repeat(3, 1fr);
      gap:24px;
    }
    @media(max-width:900px){
      .grid{grid-template-columns: repeat(2, 1fr);}
    }
    @media(max-width:600px){
      .grid{grid-template-columns: 1fr;}
    }
    .card{
      background:var(--card);
      border:2px solid var(--edge);
      border-radius:16px;
      padding:20px;
      transition:.3s;
      position:relative;
      overflow:hidden;
    }
    .card:hover{
      transform:translateY(-6px);
      box-shadow:0 10px 30px rgba(0,0,0,.35);
    }
    .pill{
      display:inline-block;
      background:var(--green);
      color:#fff;
      border-radius:999px;
      padding:4px 12px;
      font-size:12px;
      letter-spacing:.5px;
    }
    .title{
      display:flex;
      align-items:center;
      gap:8px;
      font-size:22px;
      margin:10px 0 4px 0;
      color:var(--sand);
    }
    .title svg{
      width:20px;
      height:20px;
      fill:var(--green);
      flex-shrink:0;
    }
    .meta{font-size:14px;color:#d1ebdf;margin-bottom:10px}
    .story{white-space:pre-line;text-align:justify;font-size:15px;color:#f3fef8}

    footer{
      margin-top:40px;
      text-align:center;
      font-size:13px;
      color:#d9f5e7;
      padding:20px 0;
      border-top:2px solid var(--green);
      background:var(--dark);
    }
  </style>
</head>
<body>
  <header>
    <img class="flag" src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Flag_of_Saudi_Arabia.svg" alt="علم المملكة العربية السعودية"/>
    <h1>عزّنا بفخرِنا</h1>
    <p class="lead"> شخصيات سعودية بارزة</p>
  </header>

  <div class="container">
    <div class="grid">

      <!-- الملك سلمان -->
      <div class="card">
        <span class="pill">خادم الحرمين</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          الملك سلمان بن عبدالعزيز
        </h3>
        <div class="meta">ملك الحزم والعزم</div>
        <p class="story">
الملك سلمان بن عبدالعزيز آل سعود، وُلد عام 1935، وتولّى الحكم في يناير 2015...
        </p>
      </div>

      <!-- محمد بن سلمان -->
      <div class="card">
        <span class="pill">ولي العهد</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          محمد بن سلمان بن عبدالعزيز
        </h3>
        <div class="meta">مهندس التحول الوطني</div>
        <p class="story">
الأمير محمد بن سلمان وُلد عام 1985، وهو ولي العهد ورئيس مجلس الوزراء السعودي...
        </p>
      </div>

      <!-- الدكتور عبدالله الربيعة -->
      <div class="card">
        <span class="pill">الطب الإنساني</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          الدكتور عبدالله الربيعة
        </h3>
        <div class="meta">رائد فصل التوائم السيامية</div>
        <p class="story">
الدكتور عبدالله الربيعة، وُلد عام 1955، يُعتبر من أبرز الجراحين السعوديين...
        </p>
      </div>

      <!-- عادل الجبير -->
      <div class="card">
        <span class="pill">الدبلوماسية</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          عادل الجبير
        </h3>
        <div class="meta">صوت المملكة في المحافل الدولية</div>
        <p class="story">
عادل الجبير، وُلد عام 1962، أحد أبرز الشخصيات الدبلوماسية في المملكة...
        </p>
      </div>

      <!-- غازي القصيبي -->
      <div class="card">
        <span class="pill">الأدب والإدارة</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          غازي القصيبي
        </h3>
        <div class="meta">الأديب الوزير</div>
        <p class="story">
غازي القصيبي (1940–2010) أديب وسياسي وإداري سعودي بارز...
        </p>
      </div>

      <!-- الأميرة ريما -->
      <div class="card">
        <span class="pill">التمكين</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          الأميرة ريما بنت بندر
        </h3>
        <div class="meta">رائدة الدبلوماسية النسائية</div>
        <p class="story">
الأميرة ريما بنت بندر بن سلطان، وُلدت عام 1975، شخصية بارزة في تمكين المرأة...
        </p>
      </div>

      <!-- سلطان بن سلمان -->
      <div class="card">
        <span class="pill">الفضاء</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          الأمير سلطان بن سلمان
        </h3>
        <div class="meta">أول رائد فضاء عربي مسلم</div>
        <p class="story">
الأمير سلطان بن سلمان، وُلد عام 1956، دخل التاريخ كأول عربي ومسلم يصعد إلى الفضاء...
        </p>
      </div>

      <!-- سالم الدوسري -->
      <div class="card">
        <span class="pill">الرياضة</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          سالم الدوسري
        </h3>
        <div class="meta">نجم الأخضر</div>
        <p class="story">
سالم الدوسري، وُلد عام 1991، لاعب كرة قدم سعودي دولي ونجم نادي الهلال...
        </p>
      </div>

      <!-- ريانة برناوي -->
      <div class="card">
        <span class="pill">الفضاء</span>
        <h3 class="title">
          <svg viewBox="0 0 24 24"><path d="M12 2l3 6h6l-4.8 4 1.8 6L12 14l-6 4 1.8-6L3 8h6z"/></svg>
          ريانة برناوي
        </h3>
        <div class="meta">أول سعودية في الفضاء</div>
        <p class="story">
ريانة برناوي، وُلدت عام 1988، باحثة سعودية متخصصة في العلوم الحيوية...
        </p>
      </div>

    </div>
  </div>

  <footer>
    © إعداد وطني تعليمي — شخصيات سعودية بارزة
  </footer>
</body>
