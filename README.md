Linktree - Henrique Vieira
Este projeto é uma página simples de Linktree para Henrique Vieira, um Software Developer. A página permite acessar rapidamente seus perfis em redes sociais como Instagram, LinkedIn e GitHub. O design é estilizado com CSS e inclui animações sutis.

Funcionalidades
Exibe a foto de perfil e informações de contato do desenvolvedor.
Links para perfis do Instagram, LinkedIn e GitHub com ícones estilizados.
Animação de "bounce" aplicada à imagem de perfil.
Efeitos de hover nos links com mudança de cor e leve aumento.
Arquivos
O projeto contém dois arquivos principais:

index.html: Arquivo HTML que contém a estrutura da página.
style.css: Arquivo CSS que aplica o estilo e animações à página.
Estrutura do Projeto
HTML (index.html)
O arquivo HTML define a estrutura básica da página, com os seguintes elementos principais:

Uma imagem de perfil com um efeito de animação.
Títulos que indicam o nome e a profissão do desenvolvedor.
Links para redes sociais com ícones personalizados usando Font Awesome.
Exemplo de código HTML:

html
<img src="./imagem.jpg" width="150" alt="imagemPerfil" />
<h1>Henrique Vieira</h1>
<h2>Software Developer</h2>
<p>Bem-vindo a minha página!</p>
<a href="https://www.instagram.com/euvieirahv/"><i class="fab fa-instagram"></i> Instagram</a>
<a href="https://www.linkedin.com/in/henrique-s-vieira-7652891a9/"><i class="fab fa-linkedin"></i> Linkedin</a>
<a href="https://github.com/henriquevieiragt"><i class="fab fa-github"></i> Github</a>
CSS (style.css)
O arquivo CSS adiciona uma série de estilos e animações:

Imagem de perfil com bordas arredondadas, sombra e efeito de "bounce".
Cor de fundo com um gradiente linear de azul escuro a azul claro.
Estilização dos links com cor de fundo branca, sombra e transição de efeito ao passar o mouse.
Uso de keyframes para a animação da imagem, criando um efeito de leve "pulo".
Exemplo de código CSS:

css
img {
  border-radius: 75px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  animation: bounce 2s infinite;
  margin-top: 20px;
}

a {
  background-color: white;
  font-size: 20px;
  border-radius: 10px;
  padding: 10px;
  display: block;
  margin: 10px 500px;
  color: slateblue;
  text-decoration: none;
  transition: transform 0.5s ease;
}

Tecnologias Utilizadas
HTML5: Utilizado para a estruturação do conteúdo.
CSS3: Utilizado para o design, animações e responsividade.
Font Awesome: Para os ícones das redes sociais.
