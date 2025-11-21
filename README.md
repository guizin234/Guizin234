## Guilherme 👋

<!doctype html>
h1{margin:0;font-size:28px}
p.lead{color:var(--muted);margin-top:6px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:24px}
.card{background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6)}
.skills ul{list-style:none;padding:0;margin:0;display:flex;flex-wrap:wrap;gap:8px}
.skills li{background:#071026;padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted)}
a.btn{display:inline-block;margin-top:12px;padding:10px 14px;border-radius:10px;background:var(--accent);color:#042027;text-decoration:none;font-weight:600}
footer{margin-top:32px;color:var(--muted);font-size:13px}
@media(max-width:520px){header{flex-direction:column;align-items:flex-start}.avatar{width:72px;height:72px}}
</style>
</head>
<body>
<div class="container">
<header>
<div class="avatar">GA</div>
<div>
<h1>Guilherme — Analista em formação</h1>
<p class="lead">Estudante de Análise e Desenvolvimento de Sistemas • Foco em Power BI e MySQL</p>
<a class="btn" href="#projects">Ver projetos</a>
</div>
</header>


<main>
<section class="cards" style="margin-top:28px">
<div class="card">
<h3>Sobre</h3>
<p class="muted">Sou estudante apaixonado por dados. Gosto de transformar números em insights e criar relatórios que ajudem na tomada de decisão.</p>
</div>


<div class="card skills">
<h3>Habilidades</h3>
<ul>
<li>Power BI</li>
<li>MySQL</li>
<li>Modelagem de dados</li>
<li>Excel (avançado)</li>
<li>Git</li>
</ul>
</div>


<div class="card">
<h3>Educação</h3>
<p>Cursando: Análise e Desenvolvimento de Sistemas</p>
</div>
</section>


<section id="projects" style="margin-top:22px">
<h2>Projetos</h2>
<div class="cards" style="margin-top:12px">
<div class="card">
<h4>Dashboard de Vendas</h4>
<p class="muted">Dashboard em Power BI com KPIs, segmentação e análise temporal.</p>
<a class="btn" href="#">Ver detalhes</a>
</div>


<div class="card">
<h4>Queries MySQL — Produção</h4>
<p class="muted">Scripts para extrair indicadores de produção e OEE.</p>
<a class="btn" href="#">Ver código</a>
</div>


<div class="card">
<h4>Site Pessoal</h4>
<p class="muted">Página simples hospedada no GitHub Pages.</p>
<a class="btn" href="#">Ver site</a>
</div>
</div>
</section>


<section style="margin-top:22px" class="card">
<h3>Contato</h3>
<p class="muted">Email: <a href="mailto:seu-email@example.com">seu-email@example.com</a></p>
<p class="muted">LinkedIn: <a href="#">seu-linkedin</a></p>
</section>
</main>


<footer>
Feito por Guilherme — Estudante de Análise e Desenvolvimento de Sistemas
</footer>
</div>
</body>
</html>
