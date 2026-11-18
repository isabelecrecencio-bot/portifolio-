portifolio 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gabriel Santos | Desenvolvedor Front-End</title>
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif}
  body{background:#0f172a;color:#e2e8f0}
  header{padding:70px 20px;text-align:center}
  header h1{font-size:38px}
  header h1 span{color:#38bdf8}
  header p{color:#94a3b8;margin-top:10px}
  .btn{display:inline-block;margin:20px 8px 0;background:#38bdf8;color:#0f172a;padding:12px 24px;border-radius:8px;text-decoration:none;font-weight:bold}
  .btn2{background:transparent;color:#38bdf8;border:1px solid #38bdf8}
  section{max-width:900px;margin:40px auto;padding:0 20px}
  h2{margin-bottom:20px;font-size:24px}
  .grid{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px}
  @media(max-width:700px){.grid{grid-template-columns:1fr}}
  .card{background:#1e293b;padding:22px;border-radius:14px}
  .card h3{margin-bottom:8px}
  .card p{color:#94a3b8;font-size:14px;line-height:1.5}
  .tag{display:inline-block;background:#0ea5e9;color:white;padding:4px 10px;border-radius:20px;font-size:12px;margin:10px 5px 0 0}
  footer{text-align:center;padding:40px;color:#64748b}
</style>
</head>
<body>

<header>
  <p>👋 Olá, eu sou</p>
  <h1>Gabriel <span>Santos</span></h1>
  <p>Desenvolvedor Front-End | Criando sites rápidos, bonitos e funcionais</p>
  <a class="btn" href="#projetos">Ver Projetos</a>
  <a class="btn btn2" href="#contato">Contato</a>
</header>

<section>
  <h2>Sobre</h2>
  <div class="card">
    <p>Sou desenvolvedor front-end com foco em HTML, CSS, JavaScript e React. Gosto de transformar ideias em interfaces limpas e que funcionam bem no celular e no computador.</p>
    <p style="margin-top:10px;color:#94a3b8">Atualmente buscando oportunidades como freelancer e estágio.</p>
  </div>
</section>

<section>
  <h2>Habilidades</h2>
  <div class="card">
    <span class="tag">HTML</span><span class="tag">CSS</span><span class="tag">JavaScript</span><span class="tag">React</span><span class="tag">Git & GitHub</span><span class="tag">Figma</span>
  </div>
</section>

<section id="projetos">
  <h2>Projetos</h2>
  <div class="grid">
    <div class="card">
      <h3>🛒 Loja Virtual</h3>
      <p>Site de e-commerce com carrinho, filtros e página de produto responsiva.</p>
      <span class="tag">HTML</span><span class="tag">CSS</span><span class="tag">JS</span>
    </div>
    <div class="card">
      <h3>📱 App de Tarefas</h3>
      <p>App para organizar tarefas do