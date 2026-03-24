<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Renda com IA</title>
  <style>
    :root{
      --bg:#0b0f1a;
      --card:#111827;
      --text:#e5e7eb;
      --muted:#9ca3af;
      --primary:#00d4ff;
      --primaryText:#001018;
      --stroke: rgba(255,255,255,.08);
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: Arial, sans-serif;
      background: radial-gradient(900px 500px at 50% -10%, rgba(0,212,255,.18), transparent 60%),
                  radial-gradient(700px 400px at 10% 20%, rgba(99,102,241,.12), transparent 60%),
                  var(--bg);
      color:var(--text);
    }
    .container{max-width: 980px; margin:0 auto; padding: 48px 20px;}
    .nav{display:flex; justify-content:space-between; align-items:center; gap:12px; margin-bottom:28px;}
    .brand{font-weight:800; letter-spacing:.3px;}
    .pill{
      display:inline-flex; align-items:center; gap:8px;
      border:1px solid var(--stroke); padding:8px 12px; border-radius:999px;
      color:var(--muted); font-size:14px;
      background: rgba(17,24,39,.5);
      backdrop-filter: blur(6px);
    }

    .hero{
      display:grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 22px;
      align-items:center;
      padding: 26px;
      border:1px solid var(--stroke);
      border-radius: 16px;
      background: rgba(17,24,39,.55);
      backdrop-filter: blur(8px);
    }
    @media (max-width: 860px){ .hero{grid-template-columns:1fr; text-align:center;} }

    h1{margin:0; font-size: 42px; line-height:1.05; color: var(--primary);}
    .sub{margin: 14px 0 0; font-size:18px; line-height:1.5; color:var(--text);}
    .muted{color:var(--muted);}

    .ctaRow{display:flex; gap:12px; align-items:center; margin-top:18px; flex-wrap:wrap;}
    @media (max-width: 860px){ .ctaRow{justify-content:center;} }

    .btn{
      display:inline-block;
      padding: 14px 18px;
      background: var(--primary);
      color: var(--primaryText);
      font-weight: 800;
      text-decoration:none;
      border-radius: 12px;
      border:1px solid rgba(0,0,0,.2);
    }
    .btn:hover{filter:brightness(1.05)}
    .btnSecondary{
      display:inline-block;
      padding: 14px 18px;
      background: transparent;
      color: var(--text);
      text-decoration:none;
      border-radius: 12px;
      border:1px solid var(--stroke);
    }

    .productCard{
      border:1px solid var(--stroke);
      border-radius: 16px;
      padding: 16px;
      background: rgba(11,15,26,.6);
    }
    .cover{
      width:100%;
      aspect-ratio: 4/5;
      object-fit: cover;
      border-radius: 12px;
      border:1px solid var(--stroke);
      background: rgba(255,255,255,.03);
    }
    .price{
      margin-top:12px;
      padding: 12px;
      border-radius: 12px;
      border:1px solid var(--stroke);
      background: rgba(17,24,39,.55);
      text-align:center;
    }
    .from{color:var(--muted); text-decoration: line-through;}
    .now{font-size: 22px; font-weight: 900;}
    .grid3{display:grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-top: 16px;}
    @media (max-width: 860px){ .grid3{grid-template-columns:1fr;} }

    .card{
      padding: 14px;
      border-radius: 14px;
      border:1px solid var(--stroke);
      background: rgba(17,24,39,.45);
    }
    .card h3{margin:0 0 8px; font-size:16px;}
    .card p{margin:0; color:var(--muted); line-height:1.45; font-size:14px;}

    .section{margin-top: 28px;}
    .section h2{margin:0 0 10px; font-size: 22px;}
    .testimonials{display:grid; grid-template-columns: repeat(3, 1fr); gap: 12px;}
    @media (max-width: 860px){ .testimonials{grid-template-columns:1fr;} }
    .quote{font-size:14px; color:var(--text); line-height:1.5;}
    .who{margin-top:10px; color:var(--muted); font-size:13px;}

    details{
      border:1px solid var(--stroke);
      border-radius: 14px;
      padding: 12px 14px;
      background: rgba(17,24,39,.35);
    }
    details + details{margin-top:10px;}
    summary{cursor:pointer; font-weight:700;}
    footer{margin-top:32px; text-align:center; color:var(--muted); font-size:13px;}
  </style>
</head>
<body>
  <div class="container">
    <div class="nav">
      <div class="brand">Renda com IA</div>
      <div class="pill">📱 Feito para iniciantes • Comece hoje</div>
    </div>

    <div class="hero">
      <div>
        <h1>💰 Renda com IA</h1>
        <p class="sub">Aprenda a ganhar dinheiro usando apenas o celular e Inteligência Artificial, com um método simples e direto.</p>

        <div class="ctaRow">
          <a class="btn" href="https://pay.kiwify.com.br/m1UbXtE" target="_blank" rel="noopener noreferrer">COMPRAR AGORA</a>
          <a class="btnSecondary" href="#depoimentos">Ver depoimentos</a>
          <span class="muted">Pagamento seguro via Kiwify</span>
        </div>

        <div class="grid3">
          <div class="card">
            <h3>✅ Passo a passo</h3>
            <p>Você sabe exatamente o que fazer do zero, sem enrolação.</p>
          </div>
          <div class="card">
            <h3>✅ Sem computador</h3>
            <p>Estratégia pensada para fazer pelo celular, de forma prática.</p>
          </div>
          <div class="card">
            <h3>✅ Pra iniciantes</h3>
            <p>Explicado no simples, com foco em execução e resultado.</p>
          </div>
        </div>
      </div>

      <div class="productCard">
        <img class=<img class="cover" src="capa.png" alt="Capa do produto Renda com IA" /> 
        <div class="price">
          <div class="from">De R$ 49,90</div>
          <div class="now">Por R$ 19,90</div>
          <div class="muted">Oferta por tempo limitado</div>
        </div>
        <div class="ctaRow" style="justify-content:center;">
          <a class="btn" href="https://pay.kiwify.com.br/m1UbXtE" target="_blank" rel="noopener noreferrer">QUERO COMEÇAR</a>
        </div>
      </div>
    </div>

    <div class="section" id="depoimentos">
      <h2>O que as pessoas estão dizendo</h2>
      <div class="testimonials">
        <div class="card">
          <div class="quote">“mano comprei aquele ebook de renda com IA<br>não botei fé no começo<br>mas fiz minha primeira venda em 3 dias kkk”</div>
          <div class="who">— Lucas M., SP (WhatsApp)</div>
        </div>
        <div class="card">
          <div class="quote">“sério, isso funciona mesmo?<br>eu comecei ontem e já tô criando conteúdo com IA<br>nunca foi tão fácil 😳”</div>
          <div class="who">— Ana C., RJ (Instagram DM)</div>
        </div>
        <div class="card">
          <div class="quote">“comprei e valeu a pena demais<br>é simples mas abre a mente<br>já comecei a aplicar tudo”</div>
          <div class="who">— João P., MG (Comentário)</div>
        </div>
      </div>

      <div class="testimonials" style="margin-top:12px;">
        <div class="card">
          <div class="quote">“já fiz 2 vendas hoje 😳<br>usei aquele método do ebook<br>top demais”</div>
          <div class="who">— Marcos L., BA (WhatsApp)</div>
        </div>
        <div class="card">
          <div class="quote">“melhor coisa que comprei esse mês<br>tô usando IA pra tudo agora<br>já tô vendo resultado”</div>
          <div class="who">— Camila R., PE (Direct)</div>
        </div>
        <div class="card">
          <div class="quote">“Cliquei, comprei e comecei a aplicar. Material direto e fácil de seguir.”</div>
          <div class="who">— Depoimento extra (opcional)</div>
        </div>
      </div>
    </div>

    <div class="section">
      <h2>Perguntas frequentes</h2>
      <details>
        <summary>Eu preciso ter experiência?</summary>
        <p class="muted">Não. O material é pensado para iniciantes e explicado no simples.</p>
      </details>
      <details>
        <summary>Consigo fazer só pelo celular?</summary>
        <p class="muted">Sim. A ideia é ser prático e acessível para executar no dia a dia.</p>
      </details>
      <details>
        <summary>Como eu acesso depois de comprar?</summary>
        <p class="muted">Depois do pagamento, a plataforma libera o acesso conforme as regras da Kiwify.</p>
      </details>
    </div>

    <footer>© Digital Labs</footer>
  </div>
</body>
</html>
