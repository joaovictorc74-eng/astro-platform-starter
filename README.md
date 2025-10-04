<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Vi Na Mídia Notícias</title>
  <meta name="description" content="Vi Na Mídia Notícias — Notícias de Caetité, da Bahia, do Brasil e do Mundo. Informação com credibilidade e identidade baiana." />
  <style>
    :root{
      --bg:#ffffff;
      --text:#0b1220;
      --accent-blue:#0b5ea8;
      --accent-red:#d62828;
      --muted:#6b7280;
      --card:#ffffff;
      --shadow: 0 8px 30px rgba(11,18,32,0.08);
      --maxw:1100px;
    }
    *{box-sizing:border-box;}
    body{
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Helvetica Neue", Arial;
      background:var(--bg);
      color:var(--text);
      line-height:1.5;
    }
    .topbar{
      background:linear-gradient(90deg, var(--accent-blue) 0 33%, var(--accent-red) 33% 66%, #ffffff 66% 100%);
      height:6px;
      width:100%;
    }
    header{
      border-bottom:4px solid #f3f4f6;
      padding:18px 16px;
      display:flex;
      align-items:center;
      justify-content:space-between;
      max-width:var(--maxw);
      margin:0 auto;
    }
    .brand{
      display:flex;
      align-items:baseline;
      gap:12px;
    }
    .logo{
      display:flex;
      align-items:center;
      gap:10px;
      text-decoration:none;
      color:var(--text);
    }
    .logo .flag{
      width:46px;height:30px;border-radius:4px;
      background: linear-gradient(180deg, var(--accent-blue) 0 50%, #ffffff 50% 100%);
      box-shadow:0 2px 6px rgba(0,0,0,0.08);
      border:3px solid var(--accent-red);
    }
    .logo h1{margin:0;font-size:20px;letter-spacing:0.4px}
    .logo p{margin:0;font-size:12px;color:var(--muted)}
    nav{display:flex;gap:12px;align-items:center}
    nav a{color:var(--text);text-decoration:none;padding:8px 12px;border-radius:8px;font-weight:600}
    nav a.cta{background:var(--accent-red);color:#fff}
    nav a:hover{opacity:0.9}
    .container{max-width:var(--maxw);margin:28px auto;padding:0 16px;}
    .grid{display:grid;grid-template-columns:1fr 360px;gap:24px;align-items:start;}
    .hero{
      background:var(--card);
      padding:22px;
      border-radius:12px;
      box-shadow:var(--shadow);
      margin-bottom:18px;
    }
    .hero .kicker{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(214,40,40,0.08);color:var(--accent-red);font-weight:700;font-size:12px}
    .hero h2{margin:12px 0 8px;font-size:26px;color:var(--accent-blue)}
    .hero p{margin:0 0 14px;color:var(--muted)}
    .hero .read-more{display:inline-block;padding:10px 14px;border-radius:8px;border:2px solid var(--accent-blue);color:var(--accent-blue);text-decoration:none;font-weight:700}
    .feed{display:grid;gap:14px}
    .post{
      display:flex;gap:14px;align-items:flex-start;background:#fff;padding:14px;border-radius:10px;box-shadow:0 6px 18px rgba(3,10,28,0.04)
    }
    .post .thumb{
      width:120px;height:80px;border-radius:8px;background:#e6eefc;flex-shrink:0;display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:700
    }
    .post h3{margin:0;font-size:16px;color:var(--accent-red)}
    .post p{margin:6px 0 0 0;color:var(--muted);font-size:13px}
    aside{position:relative}
    .card-side{background:#fff;padding:16px;border-radius:12px;box-shadow:var(--shadow)}
    .card-side h4{margin:0 0 8px 0;font-size:16px;color:var(--accent-blue)}
    .subscribe{display:flex;gap:8px;margin-top:10px;}
    .subscribe input{flex:1;padding:10px;border-radius:8px;border:1px solid #e6eaf0;font-size:14px}
    .subscribe button{padding:10px 12px;border-radius:8px;border:none;background:var(--accent-red);color:#fff;font-weight:700;cursor:pointer}
    footer{
      margin-top:28px;background:var(--accent-blue);color:#fff;padding:26px 16px;border-top:6px solid var(--accent-red);
    }
    .footer-inner{max-width:var(--maxw);margin:0 auto;display:flex;flex-direction:column;gap:8px;align-items:center}
    .footer-inner p{margin:2px 0;color:#f8fafc}
    .footer-inner .meta{font-weight:700;font-size:15px}
    .socials a{color:#fff;text-decoration:none;margin:0 6px;font-weight:700}
    .small{font-size:13px;color:rgba(255,255,255,0.9)}
    @media (max-width:980px){.grid{grid-template-columns:1fr}nav{display:none}}
    @media (max-width:480px){.logo h1{font-size:18px}.hero h2{font-size:20px}.post .thumb{width:100px;height:72px}}
  </style>
</head>
<body>
  <div class="topbar" aria-hidden="true"></div>
  <header>
    <div class="brand">
      <a class="logo" href="#">
        <div class="flag" aria-hidden="true"></div>
        <div>
          <h1>Vi Na Mídia Notícias</h1>
          <p>Notícias de Caetité, da Bahia, do Brasil e do Mundo</p>
        </div>
      </a>
    </div>
    <nav aria-label="Navegação principal">
      <a href="#">Home</a>
      <a href="#">Política</a>
      <a href="#">Economia</a>
      <a href="#">Cultura</a>
      <a href="#" class="cta">Assine</a>
    </nav>
  </header>
  <main class="container" role="main">
    <div class="grid">
      <section>
        <article class="hero" aria-labelledby="manchete">
          <span class="kicker">Destaque</span>
          <h2 id="manchete">Bahia em foco: análise completa dos principais impactos regionais</h2>
          <p>Uma cobertura especial com entrevistas, dados exclusivos e análises sobre os acontecimentos que movimentam nosso estado. Leia a matéria completa e acompanhe as atualizações ao vivo.</p>
          <a class="read-more" href="#">Leia a matéria</a>
        </article>
        <div class="feed" aria-live="polite">
          <article class="post">
            <div class="thumb">IMAGEM</div>
            <div>
              <h3>As eleições e a nova geografia política na Bahia</h3>
              <p>Especial com levantamento de votos, entrevistas e prognósticos sobre as mudanças no cenário estadual.</p>
            </div>
          </article>
          <article class="post">
            <div class="thumb">IMAGEM</div>
            <div>
              <h3>Economia local: crescimento e desafios pós-pandemia</h3>
              <p>Análise dos setores que mais empregam e as oportunidades para microempresários.</p>
            </div>
          </article>
          <article class="post">
            <div class="thumb">IMAGEM</div>
            <div>
              <h3>Cultura e resistência: o movimento musical que refaz a cidade</h3>
              <p>Reportagem sobre artistas locais que estão reinventando a cena cultural baiana.</p>
            </div>
          </article>
        </div>
      </section>
      <aside>
        <div class="card-side">
          <h4>Assine nossa newsletter</h4>
          <p class="small">Receba os principais destaques direto no seu e-mail — grátis.</p>
          <div class="subscribe" role="form" aria-label="Assinatura de newsletter">
            <input id="email" type="email" placeholder="seu@email.com" />
            <button type="button" onclick="alert('Obrigado! Em breve entraremos em contato.')">Assinar</button>
          </div>
        </div>
        <div style="height:16px"></div>
        <div class="card-side" style="margin-top:12px">
          <h4>Mais lidos</h4>
          <ol style="margin:8px 0 0 18px;color:var(--muted)">
            <li>Como empreender na Bahia após a crise</li>
            <li>Guia rápido: benefícios e direitos do trabalhador</li>
            <li>Entrevista: liderança jovem que transforma periferia</li>
          </ol>
        </div>
      </aside>
    </div>
  </main>
  <footer>
    <div class="footer-inner">
      <p class="meta">Vi Na Mídia Notícias</p>
      <p>CNPJ: 52.969.575/0001-10</p>
      <p>Endereço: Travessa Livramento, Bairro Ovídio Teixeira, 37 — Caetité/BA</p>
      <p class="small">Telefone: (77) 99824-2988 </p>
      <div class="socials">
        <a href="#" target="_blank">Facebook</a> |
        <a href="#" target="_blank">Instagram</a> |
        <a href="#" target="_blank">YouTube</a>
      </div>
      <p style="margin-top:10px;font-size:13px;">© 2025 Vi Na Mídia Notícias. Todos os direitos reservados.</p>
    </div>
  </footer>
</body>
</html>
