# Recipe Page | Desafio do Frontend Mentor

<div>
  <img src="./src/images/gif_final_page.gif" alt="Gif do resultado final da página">
</div>

### [Veja a página clicando aqui!](https://miguel-dalmeida.github.io/recipe-page_project/) 

## __Sumário__

- [Apresentação](#apresentação)
- [Explicação do Projeto](#explicação-do-projeto)
- [Ferramentas e Tecnologias Utilizadas](#ferramentas-e-tecnologias-utilizadas)
- [Principais Recursos e Abordagens](#principais-recursos-e-abordagens)
- [Aprendizado Adquirido](#aprendizado-adquirido)
- [Desenvolvimento Contínuo](#desenvolvimento-contínuo)
- [Agradecimentos e Conclusão](#agradecimentos-e-conclusão)
- [Contato](#contato)
- [Licença de Uso](#licença-de-uso)

## __Apresentação__

Muito prazer, meu nome é Mário Miguel e sou estudante de Desenvolvimento Web. Atualmente, sou aluno do curso __DevQuest__ da *Dev em Dobro*, com foco em formação de desenvolvedores web Fullstack.

Gostaria de explicar brevemente o motivo pelo qual decidi recriar a __*Recipe Page*__. Após concluir os módulos de HTML e CSS Avançado e os desafios práticos propostos pelo curso, o próximo passo seria iniciar o módulo de JavaScript básico. No entanto, percebi que ainda precisava de mais prática nas linguagens HTML e CSS antes de avançar para o JavaScript. Foi então que resolvi criar o projeto [__*Lapidando HTML e CSS*__](https://gigantic-chef-a6f.notion.site/Lapidando-HTML-e-CSS-1a4cd10b93ab8081a48cf19eeef02d02), no qual recriarei quatro interfaces do Frontend Mentor como forma de aprimorar minhas habilidades nessas tecnologias.

## __Explicação do Projeto__
Como foi dito acima, esse desafio faz parte do programa [__*Lapidando HTML e CSS*__](https://gigantic-chef-a6f.notion.site/Lapidando-HTML-e-CSS-1a4cd10b93ab8081a48cf19eeef02d02) e é o primeiro desafio do __Frontend Mentor__ que estou recriando.

Escolhi a __Recipe Page__ como o primeiro desafio porque ela foca no uso de __Semântica e Estrutura HTML__, conhecimentos considerados fundamentos iniciais. Nos próximos desafios, vou explorar tópicos como CSS Flexbox, CSS Grid e outros, em uma sequência pensada para que a dificuldade e o conhecimento exigido evoluam de forma cronológica e estratégica.

Falando especificamente sobre o projeto, trata-se de uma página simples de receita, que ensina como fazer um omelete clássico. O layout do site inclui uma introdução à receita, informações sobre o tempo de preparo, lista de ingredientes, instruções passo a passo e detalhes nutricionais. O design é minimalista, utilizando cores mais neutras, como bege, branco, marrom, roxo e rosa claro, o que transmite uma sensação de simplicidade e aconchego.

## __Ferramentas e Tecnologias Utilizadas__
<div style="display: inline_block" align="center"><br>
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Markdown" height="40" width="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/markdown/markdown-original.svg" />
</div>


## __Principais Recursos e Abordagens__

- **Tags semânticas**: Utilização de tags semânticas como `<header>`, `<footer>`, `<main>`, entre outras, para garantir uma melhor estruturação do conteúdo e facilitar a acessibilidade e a indexação por mecanismos de busca (SEO).  
**Nota**: *Para codificar o arquivo `index.html` seguindo corretamente as diretrizes de semântica e acessibilidade, consultei o artigo __Tudo o que você Precisa Saber sobre as Tags Semânticas__, redigido por mim anteriormente e baseado nas documentação da MDN Web Docs. Caso queira ter acesso a esse artigo, basta [__Clicar Aqui__](https://gigantic-chef-a6f.notion.site/Artigo-Tudo-o-que-voc-Precisa-Saber-sobre-as-Tags-Sem-nticas-3edf48fa41224948a9734746395c98a6?pvs=74).

- **Tabela em HTML**: Utilização da tag `<table>` para estruturar e apresentar informações nutricionais de forma organizada.

- **Tag `<picture>`**: Implementação da tag `<picture>` para otimizar o carregamento de imagens, permitindo o uso de diferentes formatos e resoluções conforme o tamanho da tela do usuário.

- **Fontes do Google Fonts**: Inclusão das fontes *Young Serif* e *Outfit*.

- **Unidade de medida relativa (rem)**: Garantia de escalabilidade dentro do projeto (com essa abordagem, um ponto de alteração reflete em toda a página).

- **Variáveis CSS**: Emprego de variáveis CSS para centralizar e reutilizar as cores do projeto. Por mais que o projeto seja pequeno e não exija necessariamente a criação de um arquivo `variables.css`, decidi definir variáveis para praticar. 

- **CSS Flexbox**: Aplicação do _Flexbox_ para a disposição e alinhamento de elementos.

- **Desktop First**: A abordagem inicial foi a criação do layout com foco em dispositivos desktop, seguido de ajustes para telas menores utilizando media queries.

- **Media Queries**: Aplicação de media queries para garantir que o layout se adapte adequadamente a diferentes tamanhos de tela.

- **Pseudo-classes**: Utilização de pseudo-classes como `:hover` e `:is`.

- **Pseudo-elementos**: Utilização de pseudo-elementos como `::marker` e `::before`.
- **Propriedades `transition`**: Uso de transições CSS para elevar a estética da aplicação.

- **Prefixos `-webkit-`, `-ms-` e `-o-`**: Inclusão de prefixos em propriedades CSS para garantir compatibilidade com versões antigas de navegadores.  
  *__Nota:__ Utilizei o site [Autoprefixer CSS online](https://autoprefixer.github.io/) para incluir os prefixos automaticamente.*

## __Desafios Enfrentados__

No geral, o desenvolvimento deste projeto foi tranquilo. A criação do arquivo `index.html` fluiu tranquilamente, afinal tenho em mãos o artigo [__Tudo o que você Precisa Saber sobre as Tags Semânticas__](https://gigantic-chef-a6f.notion.site/Artigo-Tudo-o-que-voc-Precisa-Saber-sobre-as-Tags-Sem-nticas-3edf48fa41224948a9734746395c98a6), que sempre funciona como uma ótima fonte de consulta para codificação de uma marcação semântica e bem estruturada.  

A nomeação das classes me tomou bons minutos, porém consegui atingir um resultado bem padronizado e coeso. Posso dizer o mesmo da criação das variáveis.

Os desafios mais notáveis surgiram ao estilizar as listas das e a tabela da seção *Nutrition*.  

No caso das listas, percebi que os bullets das `<ul>` das seções *Preparation Time* e *Ingredients* estavam desalinhados verticalmente em relação ao conteúdo das `<li>`. Para corrigir isso, removi o estilo padrão das listas (`list-style: none`) e recriei os bullets manualmente com o pseudo-elemento `::before`. Em seguida, utilizei Flexbox para alinhar os itens corretamente. __Veja um exemplo real da solução aplicada à seção *Preparation Time*:__  

```css
.main-container .recipe-preparation .preparation-list {
    list-style: none;
    margin-left: 1.3rem;
}

.main-container .recipe-preparation .preparation-list li {
    display: flex;
    align-items: center;
    margin-bottom: -1rem;
}

.main-container .recipe-preparation .preparation-list li::before {
    content: "·";
    color: var(--preparation-section-list-bullets-color, hsl(332, 51%, 32%));
    font-size: 3rem;
    margin-right: 2.5rem;
}
```

Já na tabela, o problema estava relacionado às linhas divisórias. Inicialmente, tentei utilizar *CSS Flexbox* e `display: block` nos elementos da `<table>`, mas isso interferiu no comportamento natural das células e linhas, dificultando o controle do espaçamento entre as bordas. Após alguns testes, compreendi que o ideal era manter a estrutura padrão da tabela, sem forçar modificações no `display`. Depois desse ajuste, a estilização fluiu sem complicações.

Enfrentar esses desafios exigiu paciência e algumas pesquisas, mas, no final, cada obstáculo superado contribuiu para meu amadurecimento como desenvolvedor. Agora, sei lidar melhor com esses aspectos e posso evitar esses mesmos problemas em projetos futuros.

## __Aprendizado Adquirido__

Inicialmente, imaginei que a __*Recipe Page*__ não me traria grandes aprendizados, por se tratar de uma interface simples. No entanto, fui surpreendido pelo quanto evoluí ao longo do processo.

Um dos principais avanços foi na nomeação de classes e na criação de variáveis CSS para cores. Após alguns ajustes, consegui definir um padrão claro e intuitivo, tornando o código mais organizado e fácil de manter. Essa bagagem adquirida certamente facilitará o desenvolvimento dos próximos projetos.

Além disso, aprofundei meus conhecimentos no uso da tag `<picture>`, que utilizei para fornecer imagens adaptáveis conforme a largura da tela. Também descobri a ferramenta [__Squoosh__](https://squoosh.app/), que me permitiu reduzir o tamanho da imagem `image-omelette.jpeg` (Fornecida pelo *Frontend Mentor*) e criar versões otimizadas dessa imagem para diferentes dispositivos (Celular e Tablet). Isso melhorou o desempenho do site, impactando positivamente a experiência do usuário.

Outro ponto importante foi a estilização das listas. Reforcei conceitos sobre a propriedade `list-style` e explorei o uso do pseudo-elemento `::before` para replicar com precisão o design proposto pelo *Frontend Mentor*.

Também revisitei meus resumos sobre estruturação de tabelas em HTML, consultando o material [__HTML básico__](https://gigantic-chef-a6f.notion.site/HTML-b-sico-2566304e0ff240df9008281ea68f1dfa?pvs=73), especialmente as anotações da __Aula 13: Tabelas__, do curso *DevQuest*. No processo, utilizei tags como `<table>`, `<caption>`, `<tbody>`, `<tr>`, `<th>` e `<td>` para organizar a tabela de informações nutricionais. Além disso, aprofundei meu entendimento sobre como aplicar estilos em tabelas sem comprometer sua estrutura original.

É claro que muitos outros aprendizados surgiram ao longo do desenvolvimento, mas esses foram os mais significativos. Caso queira saber mais sobre o que aprendi, acesse a página [__*Lapidando HTML e CSS*__](https://gigantic-chef-a6f.notion.site/Lapidando-HTML-e-CSS-1a4cd10b93ab8081a48cf19eeef02d02) e procure por __Conhecimento Adquirido: Recipe Page__. Lá, organizei todas as anotações sobre os aprendizados adquiridos com esse projeto, que servirão como fonte de consulta para estudos futuros.

## __Desenvolvimento Contínuo__  

Com a conclusão deste projeto, sigo para o próximo desafio: __Product Preview Card Component__, também do *Frontend Mentor*. Enquanto a __*Recipe Page*__ teve como foco o HTML semântico, este novo desafio terá como objetivo testar meus conhecimentos em *CSS Flexbox*.  

Antes de avançar para o módulo de JavaScript Básico, ainda tenho mais três projetos para praticar. Mas fique tranquilo, pois toda essa jornada de aprimoramento em HTML e CSS continuará sendo documentada detalhadamente. 

## __Agradecimentos e Conclusão__

Se você chegou até aqui, meu sincero obrigado por dedicar seu tempo a explorar este projeto e acompanhar minha jornada. Completar esse desafio foi uma grande conquista, e cada passo reforça minha certeza de que estou no caminho certo para conquistar minha primeira vaga como desenvolvedor web júnior.

Também não posso deixar de agradecer ao [**DevQuest**](https://www.youtube.com/@DevemDobro), curso do qual sou aluno, por todo o suporte e conhecimento ensinado ao longo da minha jornada.  

<div align="center">
      <a href="https://www.youtube.com/@DevemDobro">
        <img src="./src/images/devquest_dev_em_dobro_logo.jpg" width="150px" alt="Logo da empresa DevQuest - Dev em Dobro"/>
      </a>
</div>
<br>

Um grande abraço e até o próximo projeto. __Bora codar!__

## __Contato__

 <div style="margin-bottom: 20px;">
    <a style="padding-right: 3px;" href="https://www.linkedin.com/in/mariomigueldealmeida/"><img
        src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
    <a href="mailto:mariomigueldealmeida@gmail.com"><img
        src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
  </div>

## __Licença de Uso__  

Este código está disponível exclusivamente para fins educacionais. Qualquer outro tipo de utilização não está autorizada.   

<br>
<div align="center">
  <img src="https://i.imgur.com/kwfpJJn.gif" alt="Imagem representando união e parceria" width="80%">
</div>