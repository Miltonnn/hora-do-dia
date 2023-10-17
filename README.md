# Projeto "Hora do Dia"

<p>Este é um simples projeto em HTML, CSS e JavaScript que exibe uma saudação com base na hora do dia, acompanhada por uma imagem correspondente. 
   Este README fornecerá informações sobre o projeto, sua estrutura e como ele funciona.</p>

   ## Conteúdo do Projeto
   
   <p>O projeto consiste em três arquivos principais:</p>

   
  1. `index.html`: Este arquivo contém a estrutura HTML do projeto e é a página principal que os usuários visualizarão.

  2. `estilo.css`: Este arquivo contém as regras de estilo CSS para a página, que definem o layout e a aparência.

  3. `script.js`: Este arquivo contém o código JavaScript que determina a hora do dia e exibe a saudação apropriada.

  4. Imagens: O projeto inclui três imagens para representar as diferentes partes do dia - manhã, tarde e noite. Essas imagens são referenciadas no arquivo HTML.

  ## Funcionamento do Projeto

  <p>Quando a página é carregada, a função `carregar()` é chamada automaticamente, que faz o seguinte:</p>
  
  * Obtém as referências aos elementos HTML msg e imagem usando o getElementById.
  * Obtém a hora atual usando a classe Date.
  * Com base na hora atual, a função determina a saudação apropriada (Bom dia, Boa tarde ou Boa noite) e atualiza a mensagem exibida na página.
  * Também atualiza a imagem exibida na página de acordo com a hora do dia.
  * Modifica o plano de fundo da página para corresponder ao período do dia.

  ## Execução do Projeto

  <p>Para executar este projeto, você pode seguir estas etapas:</p>

  1. Certifique-se de que os arquivos `index.html`, `estilo.css`, `script.js` e as imagens (manha.jpg, tarde.jpg e noite.jpg) estejam na mesma pasta.
  2. Abra o arquivo `index.html` em um navegador da web. Isso exibirá a página "Hora do Dia".
  3. A página mostrará automaticamente a saudação apropriada e a imagem com base na hora atual do sistema.

  ## Personalização

  <p>Você pode personalizar este projeto da seguinte forma:</p>

* Substituir as imagens `manha.jpg`, `tarde.jpg` e `noite.jpg` por suas próprias imagens.
* Alterar as mensagens exibidas nas saudações no arquivo `script.js`.
* Personalizar o estilo da página editando as regras no arquivo `estilo.css`.

<p>Lembre-se de manter a estrutura e os IDs HTML para garantir que o código JavaScript funcione corretamente.</p>

<p>Espero que este README ajude você a entender e personalizar o projeto "Hora do Dia". Divirta-se explorando e personalizando-o de acordo com suas necessidades!</p>
<p>Pra acessar -> https://miltonnn.github.io/hora-do-dia/</p> 
