### Em construção. 🌠 

#  🌟Repositório: Passo a passo de como costumizar seu perfil do GitHub!
<div align="center">
<img src="https://i.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.webp" alt="GithubGi" width=200px>
</div>

<br />

Bem vindos a esse repositório tutorial em que vou tentar ensinar um pouco de como você poderá customizar seu perfil do GitHub do jeito que você quiser! Então para isso, vamos começar do começo, a primeira coisa que temos que fazer é criar um repositorio com o nome do seu usuário, o seu perfil será o reflexo do arquivo do arquivo README.md que existe dentro desse repositório.<br/>
<p align="center">(🔆 OBS: No final do repositório, vou deixar um link com vários perfis legais para dar inspiração! 🔆) </p>


##

### > ⛩ Primeiro passo: criar um repositório com seu nome de usuário:

<br />

 - Vamos lá, para criar esse repositório primeiro vá até seu perfil (github.com/seuUsername);<br/>
 - Clique em 'Repositories' e logo embaixo em 'New' para criar um novo repositório;<br/>
 - Selecione você mesmo como dono e renomeie com seu username;
 - Volte para a aba de repositórios, clique naquele que acabou de criar e depois no icone do ✏️ ( Lápis ) no arquivo README.md para começar a editar seu código!
 
 <details>
 <summary><strong> 🗺 Imagens do primeiro passo</strong></summary><br />
 <img src="https://i.imgur.com/cHjzf2a.png" alt="Primeiro passo imagem">
 </details>
 
 ##
 
 ### > 📝 Markdown
 
 <br />
 
 Já deve ter percebido que a extensão do arquivo README é .md, isso significa Markdown: é uma sintaxe de formatação de texto! Nessa seção vou explicar um pouco mais sobre essa extensão, vai ser útil não apenas para seu perfil, mas como qualquer outro repositório que criar, e também no Slack!
 - Por sorte, o Markdown do GitHub aceita a maioria dos comandos de HTML e CSS! ( Caso queira fazer inteiramente assim, é totalmente possível! );
 - Isso significa que para utilizar uma imagem, basta usar a tag `<img/>` da mesma forma se quiser diminuir seu tamanho basta colocar width e height dentro da própria tag, explicarei mais sobre isso abaixo;
 - Também vou deixar uma documentação que explica um pouco mais sobre Markdown --> [Documentação Markdown](https://markdown.net.br/sintaxe-basica/)
 
  ~~~javascript
 const dica = () => `Para abrir uma linha de código como esta
 , basta colocar três '~~~' ou antes e depois do código` 
 ~~~
 
<details>
<summary><strong> 📓 Pequenas dicas de .MD</strong></summary><br />
 Como colocar essas pequenas bolinhas alinhando seu texto: basta colocar um - ou * ou 1., 2. etc  no começo da linha;<br/>
 
 ##
 Para colocar essa divisoria de texto ⬆️ , basta escrever ## na linha desejada. <br/>
 ##
 Para quebrar uma linha, da mesma forma que fazemos no HTML, só colocar uma tag `<br/>`
 ##
 Caso queira algum comando de CSS, como width, align=center ou diversos outros, basta colocá-lo dentro da tag desejada.<br/>
 Exemplo: `<img width="400px" src="https://apenasteste.com" alt="exemplo">`
 ##
 Vou falar sobre como colocar Emojis e Gifs na próxima seção! 🎯
 </details>
 
 ##
 
 ### > 🍁 Emojis e GIFs
 
 <br />
 
 - Para usar emojis, é muito simples, basta copiar o emoji de algum site e colar aonde quiser no seu arquivo .md!
 Vou deixar 2 sites de emojis, basta buscar o emoji desejado, copiar e colar!
 - [Primeiro site de Emoji](https://getemoji.com/assets/#objects) < Simples de usar e bom de pesquisar.
 - [Segundo site de Emoji](https://unicode.org/emoji/charts/full-emoji-list.html) < Esse é mais dificil de buscar, porém tem mais opções.
 
 <img align = "center" height="150px" width="500px" src="https://pa1.narvii.com/6431/23a5825d2ad28531e787a76ad2a3eb66b834413c_hq.gif" alt="">
 
 - Para uilizar Gifs basta usar uma tag: `<img>` com o link do gif;  Vou deixar também 2 sites para buscar GIFs!<br/>
 - [GIPHY](https://giphy.com/explore/gifty) < Maior banco de dados de Gifs no momento.
 - [Pinterest](https://br.pinterest.com) < Também relevante e contém imagens estáticas.
 
 ~~~javascript
 const dica = () => {
 `Para alinhar seu Gif ou imagem para esquerda,direita ou centro, 
 basta chamar um aling="center/right/left dentro da tag`
 }
 ~~~
 
##

### > 🔰 GitHub Stats!

<br />

- Painéis que mostram os status da sua conta, commits, estrelas, linguagens mais usadas etc;
- Pode ser customizado e tem vários temas; 
- Vou deixar o link do repositório que explica um pouco mais sobre o GitStats; --> [Repositório GitStats](https://github.com/anuraghazra/github-readme-stats)  
- Caso queira fazer algo mais rápido sem estudar o repositório, basta copiar o meu, e trocar o meu username no código pelo seu, e o tema pelo que deseja! ⏬

<br />

- `<img height="180em" width="394px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rafaelmusse&layout=compact&langs_count=7&theme=dracula"/>`
- ` <img height="180em" width="400px" src="https://github-readme-stats.vercel.app/api?username=rafaelmusse&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>`

<br />

<img src="https://i.imgur.com/5xOtRVx.png" alt="GitStats"/>

##

### > 🪐 Badges!

<br />

- Placas para personalizar e colocar links de redes sociais na sua página!
- Para funcionar o link, basta adicionar uma tag `<img>` dentro da tag `<a/>`
- Lembre-se de utilizar `target = blank` para não sair do seu perfil sempre que alguém clicar.
- Vou deixar o site com várias badges para você escolher a desejada! --> [Site Badges](https://dev.to/envoy_/150-badges-for-github-pnk)

<br />

<div>
<a href="https://github.com/rafaelmusse" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href = "https://github.com/rafaelmusse"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://instagram.com/rafaelmusse" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/Pinterest-%23E60023.svg?&style=for-the-badge&logo=Pinterest&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white" target="_blank"></a>
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" target="_blank"></a>
</div>

##

### > 💻 Icones das suas linguagens, frameworks, etc.

<br/>

<div align="center">
 <code><img align="center" alt="Js-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" title = "JavaScript"></code>
 <code><img align="center" alt="Ts-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" title ="Typescript"></code>
  <code><img align="center" alt="HTML-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" title = "HTML5"></code>
  <code><img align="center" alt="CSS-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" title = "CSS3"></code>
  <code><img align="center" alt="React-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" title = "React"></code>
  <code><img align="center" alt="git-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title = "git"></code>
  <code><img align="center" alt="NPM-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" title = "npm"></code>
  <code><img align="center" alt="Jest-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" title = "Jest"></code>
  </div>
  
 ##
  
  - Quem não gosta de mostrar com orgulho aquelas linguagens e habilidades que aprendemos com tanto esforço e gostamos tanto, não é?
  - Esse tópico será explicativo passo a passo, pois não tem muito o que alterar, todos serão iguais, só mudará as linguagens de cada um.
  1. Primeiro passo será criar uma `<div>` e dentro da mesma, criar uma tag `<a href="https://github.com/seuUsername">` para que caso alguem clique nas imagens, não seja redirecionado a uma pagina branca apenas com a imagem, pois isso seria uma péssima experiência para quem observa atentamente seu perfil.
  2. Agora precisamos encontrar nossas imagens em formato PNG e com ótima qualidade, para isso basta acessar --> [dev Icons](https://devicon.dev/)
  3. Após escolher todas suas imagens, vamos criar uma tag `<img>` colar o link da imagem, e agora mexer com o tamanho, por width! ( Eu aconselho 40px, mas teste você mesmo qual fica melhor!)
  4. Por fim, precisamos alinhar os icones lado a lado, para isto, temos várias formas, porém a qual eu recomendo será colocar uma tag `<code>` antes e depois de cada imagem, além de alinhar as imagens, cria um efeito visual interessante!
  5. Pronto! Suas linguagens e tecnologias estão prontas pra brilhar no seu perfil. ( Como extra, vou deixar 2 formas de exibição da tag `<code>`)
  
  <details>
  <summary><strong> Primeira forma ( Padrão )</strong></summary><br/>
  <div align="center">
 <code><img alt="Js-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" title = "JavaScript"></code>
 <code><img alt="Ts-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" title ="Typescript"></code>
  <code><img alt="HTML-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" title = "HTML5"></code>
  <code><img alt="CSS-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" title = "CSS3"></code>
  <code><img alt="React-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" title = "React"></code>
  <code><img alt="git-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title = "git"></code>
  <code><img alt="NPM-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" title = "npm"></code>
  <code><img alt="Jest-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" title = "Jest"></code>
  </div>
 </details>
 
 <br/>
 
 <details>
 <summary><strong> Segunda forma ( com align="center" dentro das img )</strong></summary><br/>
 <div align="center">
 <code><img align="center" alt="Js-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg" title = "JavaScript"></code>
 <code><img align="center" alt="Ts-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg" title ="Typescript"></code>
  <code><img align="center" alt="HTML-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" title = "HTML5"></code>
  <code><img align="center" alt="CSS-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" title = "CSS3"></code>
  <code><img align="center" alt="React-rafa" width="40px" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" title = "React"></code>
  <code><img align="center" alt="git-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title = "git"></code>
  <code><img align="center" alt="NPM-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/npm/npm-original-wordmark.svg" title = "npm"></code>
  <code><img align="center" alt="Jest-rafa" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" title = "Jest"></code>
  </div>
  </details>
 
 ##
 
 ### > 🐍 Cobrinha do GitHub ( SnakeGame de Commits ) !
 
 <div align="center">
 <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" alt="github snake">
 </div>
 
 Finalmente chegou a hora da tão amada cobrinha do github, muita gente quer usar, porém os passos são um pouco complicados e as vezes acaba não dando certo, mas fique tranquilo(a), vou tentar explicar da melhor maneira possivel e caso fique alguma duvida, pode me mandar mensagem no instagram ou no gmail, que vou ter prazer em ajudar!

##

### > 💡 Perfis para dar inspiração

<div align="center">
💎<a href="https://zzetao.github.io/awesome-github-profile">GitHub Profiles - Best ones!</a>💎
</div>
<br />
- Nesse site existem vários perfis incríveis, de tipos e estilos diferentes, basta procurar aquele que mais te agrada, e pra isso tem uma secção de filtros!
