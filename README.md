# Meu-portifolio
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio | Higor Lima</title>
  <style>
    :root {
      --verde-escuro: #051F20;
      --verde-profundo: #0B2B26;
      --verde-suave-escuro: #163832;
      --verde-medio: #235347;
      --verde-suave: #8EB69B;
      --verde-claro: #DAF1DE;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--verde-escuro);
      color: var(--verde-claro);
      line-height: 1.6;
    }

    header {
      background-color: var(--verde-profundo);
      padding: 2rem;
      text-align: center;
      border-bottom: 2px solid var(--verde-medio);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 1px;
    }

    nav {
      margin-top: 1rem;
    }

    nav a {
      margin: 0 1rem;
      color: var(--verde-suave);
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: var(--verde-claro);
    }

    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: 0 auto;
    }

    .sobre {
      background-color: var(--verde-suave-escuro);
    }

    .projetos {
      background-color: var(--verde-medio);
    }

    .skills {
      background-color: var(--verde-suave);
      color: #000;
    }

    .contato {
      background-color: var(--verde-claro);
      color: #000;
    }

    footer {
      background-color: var(--verde-escuro);
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
    }

    .projeto-card {
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      padding: 1.5rem;
      margin-bottom: 1rem;
      border: 1px solid rgba(255, 255, 255, 0.1);
    }

    .form-contato input, .form-contato textarea {
      width: 100%;
      padding: 1rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      box-sizing: border-box;
    }

    .form-contato button {
      padding: 1rem 2rem;
      background-color: var(--verde-medio);
      color: #fff;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      width: 100%;
    }

    @media (min-width: 768px) {
      .projetos-grid {
        display: flex;
        gap: 2rem;
      }

      .projeto-card {
        flex: 1;
      }
      
      .form-contato button {
        width: auto;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Higor Lima</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#projetos">Projetos</a>
      <a href="#skills">Skills</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="sobre" id="sobre">
    <h2>Sobre Mim</h2>
    <p>Sou um desenvolvedor em formação apaixonado por tecnologia e design. Busco criar soluções que unam funcionalidade e estética. Atualmente curso o terceiro semestre de Análise e Desenvolvimento de Sistemas no Centro Universitário UNISAN. Sou movido pela curiosidade e sede de conhecimento, buscando sempre colaborar com projetos inovadores e de alta performance.</p>
  </section>

  <section class="projetos" id="projetos">
    <h2>Projetos</h2>
    <div class="projetos-grid">
      <div class="projeto-card">
        <h3>Currículo Profissional</h3>
        <p>Projeto de estruturação de currículo focado em ATS e boas práticas de recrutamento para a área de tecnologia.</p>
      </div>
      <div class="projeto-card">
        <h3>Portfólio Web</h3>
        <p>Este site! Desenvolvido com HTML5 e CSS3 puro, utilizando variáveis CSS para um design consistente e responsivo.</p>
      </div>
    </div>
  </section>

  <section class="skills" id="skills">
    <h2>Habilidades</h2>
    <ul>
      <li>HTML5, CSS3, JavaScript (Básico)</li>
      <li>Lógica de Programação (Python e Java)</li>
      <li>Git e GitHub</li>
      <li>Pacote Office</li>
    </ul>
  </section>

  <section class="contato" id="contato">
    <h2>Contato</h2>
    <form class="form-contato">
      <input type="text" placeholder="Seu nome" required />
      <input type="email" placeholder="Seu e-mail" required />
      <textarea rows="4" placeholder="Sua mensagem"></textarea>
      <button type="submit">Enviar Mensagem</button>
    </form>
  </section>

  <footer>
    <p>© 2026 - Higor Ribeiro Lima. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
