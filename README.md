[<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Javiera Janer Cancino, abogada en Santiago. Derecho de Familia, litigación en tribunales y copropiedad inmobiliaria. Agenda tu consulta por WhatsApp." />
  <title>Javiera Janer Cancino | Abogada en Santiago</title>

  <style>
    :root{
      --ink:#0b1f3a;        /* azul marino */
      --gold:#c6a75e;       /* dorado suave */
      --bg:#ffffff;
      --muted:#6b7280;
      --card:#f6f7f9;
      --line:#e7e9ee;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans", "Helvetica Neue", sans-serif;
      color:#111;
      background:var(--bg);
      line-height:1.5;
    }

    /* Layout */
    .container{max-width:1100px; margin:0 auto; padding:0 18px;}
    .nav{
      position:sticky; top:0; z-index:50;
      background:rgba(255,255,255,.92);
      backdrop-filter:saturate(180%) blur(10px);
      border-bottom:1px solid var(--line);
    }
    .nav-inner{display:flex; align-items:center; justify-content:space-between; gap:12px; padding:12px 0;}
    .brand{display:flex; align-items:center; gap:10px; text-decoration:none; color:inherit;}
    .mark{
      width:40px; height:40px; border-radius:12px;
      background:linear-gradient(135deg, var(--ink), #123a6b);
      display:grid; place-items:center; color:#fff; font-weight:700;
      letter-spacing:.5px;
      box-shadow: 0 10px 25px rgba(11,31,58,.18);
    }
    .brand strong{display:block; color:var(--ink); font-size:14px; line-height:1.1}
    .brand span{display:block; color:var(--muted); font-size:12px; margin-top:2px}

    .menu{display:flex; gap:14px; flex-wrap:wrap; align-items:center; justify-content:flex-end;}
    .menu a{
      text-decoration:none; color:#111; font-size:14px;
      padding:8px 10px; border-radius:10px;
    }
    .menu a:hover{background:var(--card)}
    .cta{
      background:var(--ink); color:#fff !important;
      padding:10px 12px; border-radius:12px;
      box-shadow: 0 12px 28px rgba(11,31,58,.20);
    }
    .cta:hover{background:#081a31}

    /* Hero */
    .hero{
      padding:56px 0 26px;
      background:
        radial-gradient(900px 260px at 10% 0%, rgba(198,167,94,.22), transparent 60%),
        radial-gradient(800px 320px at 90% 10%, rgba(11,31,58,.18), transparent 60%);
      border-bottom:1px solid var(--line);
    }
    .hero-grid{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:22px;
      align-items:stretch;
    }
    .badge{
      display:inline-flex; align-items:center; gap:8px;
      padding:8px 12px; border-radius:999px;
      background:rgba(11,31,58,.06);
      border:1px solid rgba(11,31,58,.10);
      color:var(--ink); font-weight:600; font-size:13px;
    }
    .dot{width:8px; height:8px; border-radius:999px; background:var(--gold); box-shadow:0 0 0 4px rgba(198,167,94,.20);}
    h1{margin:14px 0 10px; font-size:44px; line-height:1.05; color:var(--ink); letter-spacing:-.8px;}
    .lead{margin:0 0 18px; color:#1f2937; font-size:16px; max-width:58ch;}
    .hero-actions{display:flex; gap:12px; flex-wrap:wrap; margin-top:14px;}
    .btn{
      display:inline-flex; align-items:center; justify-content:center; gap:8px;
      text-decoration:none; font-weight:700; font-size:14px;
      padding:12px 14px; border-radius:14px;
      border:1px solid var(--line);
      background:#fff; color:#111;
    }
    .btn.primary{background:var(--ink); color:#fff; border-color:transparent;}
    .btn.primary:hover{background:#081a31}
    .btn:hover{background:var(--card)}
    .mini{
      margin-top:12px; color:var(--muted); font-size:13px;
    }
    .panel{
      background:#fff;
      border:1px solid var(--line);
      border-radius:18px;
      padding:18px;
      box-shadow: 0 18px 50px rgba(17,24,39,.08);
    }
    .panel h3{margin:0 0 10px; color:var(--ink); font-size:16px;}
    .pill-list{display:flex; flex-wrap:wrap; gap:8px;}
    .pill{
      padding:8px 10px; border-radius:999px;
      background:var(--card);
      border:1px solid var(--line);
      font-size:13px;
    }
    .facts{margin-top:14px; display:grid; gap:10px;}
    .fact{
      display:flex; gap:10px; align-items:flex-start;
      padding:10px; border-radius:14px;
      background:rgba(11,31,58,.04);
      border:1px solid rgba(11,31,58,.08);
    }
    .icon{
      width:34px; height:34px; border-radius:12px;
      display:grid; place-items:center;
      background:rgba(198,167,94,.18);
      color:var(--ink);
      font-weight:900;
      flex: 0 0 auto;
    }
    .fact b{display:block; color:#111; font-size:14px; margin-bottom:2px}
    .fact span{display:block; color:var(--muted); font-size:13px}

    /* Sections */
    section{padding:46px 0; border-bottom:1px solid var(--line);}
    .section-title{display:flex; align-items:flex-end; justify-content:space-between; gap:12px; margin-bottom:16px;}
    .section-title h2{margin:0; color:var(--ink); font-size:26px; letter-spacing:-.4px;}
    .section-title p{margin:0; color:var(--muted); font-size:14px; max-width:60ch;}

    .cards{display:grid; grid-template-columns: repeat(3, 1fr); gap:14px;}
    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:18px;
      padding:18px;
      min-height: 190px;
    }
    .card h3{margin:0 0 8px; color:var(--ink); font-size:16px;}
    .card ul{margin:0; padding-left:18px; color:#111;}
    .card li{margin:6px 0; color:#111}
    .card p{margin:10px 0 0; color:var(--muted); font-size:13px}

    .two-col{display:grid; grid-template-columns: 1fr 1fr; gap:16px;}
    .box{
      background:#fff;
      border:1px solid var(--line);
      border-radius:18px;
      padding:18px;
    }
    .box h3{margin:0 0 10px; color:var(--ink); font-size:16px;}
    .box p{margin:0; color:#111}
    .list{margin:12px 0 0; padding-left:18px; color:#111}
    .list li{margin:6px 0}

    /* Contact */
    .contact-grid{display:grid; grid-template-columns: 1fr 1fr; gap:16px;}
    .contact-item{display:flex; gap:10px; align-items:flex-start; padding:12px; border-radius:16px; border:1px solid var(--line); background:#fff;}
    .contact-item a{color:var(--ink); font-weight:700; text-decoration:none}
    .contact-item a:hover{text-decoration:underline}
    .fine{color:var(--muted); font-size:13px; margin-top:8px}

    /* WhatsApp floating */
    .wa-float{
      position:fixed; right:16px; bottom:16px; z-index:80;
      display:flex; gap:10px; align-items:center;
      text-decoration:none;
      padding:12px 14px;
      border-radius:999px;
      background:#25D366;
      color:#fff;
      font-weight:800;
      box-shadow: 0 16px 40px rgba(0,0,0,.25);
    }
    .wa-float span{display:none}
    .wa-icon{
      width:22px; height:22px; border-radius:6px;
      display:grid; place-items:center;
      background:rgba(255,255,255,.22);
      font-weight:900;
    }

    footer{padding:22px 0; color:var(--muted); font-size:13px;}
    footer a{color:var(--ink); text-decoration:none; font-weight:700}

    /* Responsive */
    @media (max-width: 900px){
      .hero-grid{grid-template-columns: 1fr;}
      h1{font-size:38px}
      .cards{grid-template-columns:1fr}
      .two-col{grid-template-columns:1fr}
      .contact-grid{grid-template-columns:1fr}
      .wa-float span{display:inline}
    }
  </style>
</head>

<body>
  <!-- NAV -->
  <div class="nav">
    <div class="container nav-inner">
      <a class="brand" href="#inicio">
        <div class="mark">JJC</div>
        <div>
          <strong>Javiera Janer Cancino</strong>
          <span>Abogada · Santiago</span>
        </div>
      </a>

      <nav class="menu">
        <a href="#servicios">Servicios</a>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#copropiedad">Copropiedad</a>
        <a href="#contacto" class="cta">Agendar consulta</a>
      </nav>
    </div>
  </div>

  <!-- HERO -->
  <header id="inicio" class="hero">
    <div class="container hero-grid">
      <div>
        <div class="badge"><span class="dot"></span> Atención en Santiago · Consultas por WhatsApp</div>
        <h1>Defensa y representación legal con enfoque claro y estratégico.</h1>
        <p class="lead">
          Abogada con práctica enfocada en <b>Derecho de Familia</b>, <b>litigación en tribunales</b> y asesoría en
          <b>copropiedad inmobiliaria</b>. Acompañamiento profesional, comunicación directa y preparación rigurosa.
        </p>

        <div class="hero-actions">
          <a class="btn primary" href="https://wa.me/56945023625?text=Hola%20Javiera,%20quisiera%20agendar%20una%20consulta." target="_blank" rel="noopener">WhatsApp</a>
          <a class="btn" href="#contacto">Formulario de contacto</a>
        </div>

        <div class="mini">
          Respuesta rápida · Información clara · Confidencialidad y trato profesional
        </div>
      </div>

      <aside class="panel">
        <h3>Áreas principales</h3>
        <div class="pill-list">
          <div class="pill">Familia</div>
          <div class="pill">Litigación</div>
          <div class="pill">Medidas de protección</div>
          <div class="pill">Copropiedad</div>
          <div class="pill">Reglamentos</div>
        </div>

        <div class="facts">
          <div class="fact">
            <div class="icon">⚖️</div>
            <div>
              <b>Representación en tribunales</b>
              <span>Preparación de audiencias y estrategia jurídica.</span>
            </div>
          </div>
          <div class="fact">
            <div class="icon">🏢</div>
            <div>
              <b>Copropiedad (Ley 21.442)</b>
              <span>Reglamentos, asesoría a comités y gestión de conflictos.</span>
            </div>
          </div>
          <div class="fact">
            <div class="icon">📌</div>
            <div>
              <b>Atención en Santiago</b>
              <span>Coordinación de reuniones y orientación inicial.</span>
            </div>
          </div>
        </div>
      </aside>
    </div>
  </header>

  <!-- SERVICIOS -->
  <section id="servicios">
    <div class="container">
      <div class="section-title">
        <h2>Servicios</h2>
        <p>El sitio está pensado para que un cliente entienda rápido qué haces y pueda contactarte en 1 clic.</p>
      </div>

      <div class="cards">
        <div class="card">
          <h3>Derecho de Familia</h3>
          <ul>
            <li>Alimentos</li>
            <li>Cuidado personal</li>
            <li>Relación directa y regular</li>
            <li>Divorcio y acuerdos</li>
            <li>Medidas de protección</li>
          </ul>
          <p>Representación y acompañamiento con enfoque práctico, claro y centrado en resultados.</p>
        </div>

        <div class="card">
          <h3>Litigación en Tribunales</h3>
          <ul>
            <li>Representación en audiencias</li>
            <li>Preparación de estrategia</li>
            <li>Escritos e informes</li>
            <li>Seguimiento de causa</li>
          </ul>
          <p>Trabajo técnico y ordenado: evidencia, plazos y preparación para cada etapa del proceso.</p>
        </div>

        <div class="card">
          <h3>Copropiedad e Inmobiliario</h3>
          <ul>
            <li>Reglamentos de copropiedad</li>
            <li>Adecuación a Ley 21.442</li>
            <li>Asesoría a comités y administración</li>
            <li>Conflictos entre copropietarios</li>
          </ul>
          <p>Soluciones legales aplicables y documentos listos para implementación en comunidades.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- SOBRE MI -->
  <section id="sobre-mi">
    <div class="container">
      <div class="section-title">
        <h2>Sobre mí</h2>
        <p>Presentación breve, profesional y confiable (sin sonar a “marketing”).</p>
      </div>

      <div class="two-col">
        <div class="box">
          <h3>Perfil</h3>
          <p>
            Soy <b>Javiera Janer Cancino</b>, abogada con práctica enfocada en causas de familia y litigación,
            con interés y experiencia aplicada en copropiedad inmobiliaria.
            Me caracteriza una comunicación clara, compromiso ético y orientación a soluciones jurídicas efectivas.
          </p>
          <ul class="list">
            <li>Atención con confidencialidad y trato profesional</li>
            <li>Explicaciones simples y plan de acción</li>
            <li>Orden documental y seguimiento de plazos</li>
          </ul>
        </div>

        <div class="box">
          <h3>Forma de trabajo</h3>
          <ul class="list">
            <li><b>1)</b> Diagnóstico inicial y revisión de antecedentes</li>
            <li><b>2)</b> Definición de estrategia y próximos pasos</li>
            <li><b>3)</b> Representación y seguimiento continuo</li>
          </ul>
          <p class="fine">*Puedes ajustar estos puntos según tu forma real de atención.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- COPROPIEDAD -->
  <section id="copropiedad">
    <div class="container">
      <div class="section-title">
        <h2>Copropiedad: Reglamentos y asesoría</h2>
        <p>Acá te diferencias fuerte: no muchas abogadas ofrecen esto de forma clara y ordenada.</p>
      </div>

      <div class="two-col">
        <div class="box">
          <h3>¿Qué puedo hacer por tu comunidad?</h3>
          <ul class="list">
            <li>Redacción / actualización de Reglamento de Copropiedad</li>
            <li>Adecuación normativa y revisión de quórums</li>
            <li>Documentos y comunicados formales</li>
            <li>Apoyo a comité y administración</li>
          </ul>
        </div>
        <div class="box">
          <h3>Resultado esperado</h3>
          <ul class="list">
            <li>Reglamento claro, aplicable y ordenado</li>
            <li>Procedimientos definidos para evitar conflictos</li>
            <li>Base documental para decisiones de asamblea</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACTO -->
  <section id="contacto">
    <div class="container">
      <div class="section-title">
        <h2>Contacto</h2>
        <p>Responde rápido y hazlo fácil: WhatsApp siempre visible + correo + ubicación.</p>
      </div>

      <div class="contact-grid">
        <div class="box">
          <h3>Escríbeme</h3>

          <div class="contact-item">
            <div class="icon">💬</div>
            <div>
              <b>WhatsApp</b><br/>
              <a href="https://wa.me/56945023625?text=Hola%20Javiera,%20quisiera%20agendar%20una%20consulta." target="_blank" rel="noopener">+56 9 4502 3625</a>
              <div class="fine">Mensaje directo para agendar y enviar antecedentes.</div>
            </div>
          </div>

          <div class="contact-item" style="margin-top:10px;">
            <div class="icon">✉️</div>
            <div>
              <b>Correo</b><br/>
              <a href="mailto:javijaner2@gmail.com">javijaner2@gmail.com</a>
              <div class="fine">Ideal para adjuntar documentos.</div>
            </div>
          </div>

          <div class="contact-item" style="margin-top:10px;">
            <div class="icon">📍</div>
            <div>
              <b>Ubicación</b><br/>
              <span>Santiago, Chile</span>
              <div class="fine">Atención previa coordinación.</div>
            </div>
          </div>

          <div class="fine" style="margin-top:12px;">
            Horario sugerido: Lun–Vie 09:00 a 18:00 (ajústalo si quieres).
          </div>
        </div>

        <div class="box">
          <h3>Formulario rápido</h3>
          <p class="fine">GitHub Pages no trae formulario “real” por defecto. La forma gratis es usar Google Forms.</p>

          <ol class="list">
            <li>Crea un Google Form con: Nombre, Teléfono, Correo, Mensaje.</li>
            <li>En “Enviar” copia el link del formulario.</li>
            <li>Pega ese link en el botón de abajo.</li>
          </ol>

          <a class="btn primary" style="margin-top:12px;" href="https://forms.google.com" target="_blank" rel="noopener">
            Crear formulario en Google
          </a>

          <p class="fine" style="margin-top:12px;">
            Cuando tengas el link del formulario, dime y te lo dejo insertado perfecto.
          </p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      © <span id="year"></span> Javiera Janer Cancino · Abogada · Santiago ·
      <a href="#inicio">Volver arriba</a>
    </div>
  </footer>

  <a class="wa-float" href="https://wa.me/56945023625?text=Hola%20Javiera,%20quisiera%20agendar%20una%20consulta." target="_blank" rel="noopener">
    <div class="wa-icon">WA</div>
    <span>WhatsApp</span>
  </a>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>](https://github.com/sebasnowlt/javijanerabogada.git)
