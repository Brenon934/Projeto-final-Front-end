# Projeto-final-Front-end
Site fictício de uma loja e-comerce com formulários de cadastros de usuário e cadastro de produtos básico.
[imgs do site.pdf](https://github.com/user-attachments/files/23667339/imgs.do.site.pdf)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Eletronicos</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!--Cabeçalho com menu de navegação-->

    <header>
        <div class="logo">
            <img src="img/logo techworld.png" alt="Logo TechWorld">
            <h1>TechWorld</h1>
        </div>
         <nav>
            <ul>
                <li><a href="#home">HOME</a></li>
                <li><a href="#produtos">PRODUTOS</a></li>
                <li><a href="pages/cadastro.html">CADASTRE-SE</a></li> 
            </ul>
         </nav>
        <div class="buscar">
            <input type="text" placeholder="Busque aqui">
            <button>Pesquisar</button>
        </div>
    </header>
    <br>

    <!--banner mais conteudo da page-->

    <main class="conteudo">
    <section id="home" class="banner">
    <img src="img/PROMOÇÂO!!!.png" alt="Promocao" width="1000" >
    <div class="texto-banner">
    </div>
  </section>

  <!--Amostra de produtos-->

  <section id="produtos" class="amostra produtos">
    <div class="containner">
        <article class="card-produto">
            <div class="card-img">
                <img src="img/notebook asus.jpg" alt="Notebook Asus" width="200" height="200">
            </div>
            <h3>Notebook Asus Tuff Gaming</h3>
            <p class="preco">R$ 4.999,90</p>
            <button>Comprar</button>
        </article>
        <br>
        <article class="card-produto">
            <div class="card-img">
                <img src="img/notebook acer.jpg" alt="Notebook Acer" width="200" height="200">
            </div>
            <h3>Notebook Acer nitro V</h3>
            <p class="preco">R$ 4.999,90</p>
            <button>Comprar</button>
        </article>
    </div>
  </section>

  <!--Avaliações-->

  <section class="avaliacoes">
    <h2>Confira a Avaliação de nossos clientes:</h2><br>
    <div class="comentarios">
        <article class="avaliacao">
        <p><strong>- Mateus R. </strong>⭐️⭐️⭐️⭐️⭐️</p><br>
        <P>Otima loja! Produtos de qualidade e boua entrega.</P><br>
        <p><strong>- Prof Gleidson </strong>⭐️⭐️⭐️⭐️⭐️</p><br>
        <P>Nota 10!!!</P><br>
        </article>
    </div>
  </section></main><br>
  
  <!--rodape-->

  <footer>
    <div class="redes-sociais">
        <a href="https://www.instagram.com/" target="_blank"><img src="img/instagram icon.png" alt="Instagram" width="40"></a>
        <a href="https://www.youtube.com/" target="_blank"><img src="img/youtube icon.png" alt="Youtube" width="40"></a></a>
        <a href="https://www.tiktok.com/login?redirect_url=https%3A%2F%2Fwww.tiktok.com%2Fpt-BR%2F&lang=en&enter_method=mandatory" target="_blank"><img src="img/tiktok icon.png" alt="Tik Tok" width="40"></a></a>
    </div>
     <p>CNPJ: 00.000.000/0000-00 | Endereço: Av. dos DF, quadra 00 lote B - Brasília, DF | Contato: (00) 4002-8922</p>
    <p>© 2025 TechWorld -Todos os direitos reservados.</p>
    <P>Site Fictício desenvolvido na Disciplina front end UDF-Centro Univertário</P>
  </footer>    
</body>
</html>
