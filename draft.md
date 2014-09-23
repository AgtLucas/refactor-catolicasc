# Estudo de caso sobre acessibilidade na web

## Graziele Caroline Grossklags, Lucas da Silva

Centro Universitário Católica de Santa Catarina – Campus Jaraguá do Sul

***Resumo***. Acessibilidade na web é um tema muito pouco discutido e não recebe a devida atenção da grande maioria dos desenvolvedores web. Grande parte desse problema se da pelo fato da falta de informação e divulgação do tema. Este artigo apresenta as normas e melhores práticas para desenvolvimento de websites acessíveis, além de um estudo de caso sobre um site de uma faculdade, apresentando os problemas e as soluções para melhorar a acessibilidade do mesmo.

***Abstract***. Web accessibility it's a very underestimated topic and suffers with the lack of attention by the most of web developers. The big problem is due the poor information and disclosure about Web accessibility. This article aims to show the norms and best practices to a web for everyone, as well an use case about a College web site, pointing the problems and the solutions to accessibility improvements.

**1. Introdução**

A web é um grande ecossistema onde circula um imenso volume de informações que em sua grande maioria, são informações livres para qualquer pessoa com acesso a internet. O problema começa quando essas informações não são preparadas para pessoas que possuem alguma necessidade especial. Isso acaba ferindo uma das premissas da web, ou seja, uma web para todos. É praticamente impossível mensurar uma média de quantos sites seguem padrões e normas de acessibilidade, mas este número tende a ser muito pequeno. Acessibilidade na web significa que pessoas com necessidades especiais e/ou em idade avançada possam usar, entender, navegar e interagir com a web, além do fato de poderem contribuir para com a mesma, de qualquer dispositivo com conexão a internet.

Este artigo tem como objetivo; apresentar e explanar as normas internacionais e melhores práticas para uma web mais acessível, que vão desde a semântica, WAI (Web Accessibility Initiative), ARIA (Accessible Rich Internet Applications Suite), leitores de texto, dispositivos touchscreens para deficientes visuais, softwares, entre outros.
Como estudo de caso, um website de uma faculdade passará por uma avaliação de acessibilidade, onde os principais problemas serão listados e catalogados em níveis de gravidade de 1 a 5. A homepage deste site será reconstruída apresentando soluções para os problemas encontrados, bem como melhorias para o website em geral.

**2. O que é acessibilidade na Web**

Acessibilidade virtual é compreendida aqui como a forma de garantir a mobilidade e usabilidade de recursos computacionais (SACI, 2005), ou seja, a acessibilidade virtual consiste em eliminar as barreiras que impedem todas as pessoas de fazerem uso de sistemas computacionais.

Dentro da acessibilidade virtual, é possível destacar a acessibilidade na Internet como um dos temas mais estudados e difundidos atualmente. A acessibilidade na Internet refere-se a sites que estejam disponíveis e acessíveis na web, a qualquer hora, local, ambiente, dispositivo de acesso e por qualquer tipo de usuário. Segundo Zúnica (1999), a acessibilidade na Internet pode envolver três grandes áreas:

* **Acessibilidade ao computador:** envolve ferramentas, equipamentos ou técnicas que facilitam a navegação na web. Nesse grupo, encontram-se softwares (por exemplo, softwares falantes) e hardwares (por exemplo, mouses adaptados);
* **Acessibilidade do navegador:** esta área trata exclusivamente do software utilizado para apresentar o conteúdo de páginas web, isto é, o browser ou navegador. Esses softwares podem ser genéricos, como a internet Explorer e o Mozilla Firefox, ou ainda, específicos, que oferecem facilidades de acesso a determinados grupos de usuários, como é o caso do navegador Linux para usuários cegos; 
* **Acessibilidade no desenvolvimento de páginas web:** nesta área são estudadas regras e técnicas que devem ser seguidas para a construção de páginas acessíveis. Essas regras determinam como o conteúdo deve ser apresentado em uma página web. Elas também determinam como a navegação entre as páginas deve ser realizada, ou seja, como as páginas devem estar ligadas dentro de um site, de forma que facilitem a navegação de todas as pessoas.

Neste artigo, focaremos em acessibilidade no desenvolvimento de páginas web, ou seja, falaremos sobre web acessível, que como abordado acima é a representação de uma Web ideal, onde todas as pessoas independente do tipo de usuário (Pessoas com necessidades especiais, idosos, entre outros) teriam acesso ao seu conteúdo. Não só pessoas, mas também sistemas, uma vez que sistemas também acessam conteúdos de páginas na internet para algum propósito, dependendo do sistema, um exemplo disso que é o sistema de indexação do Google, que lê o conteúdo das páginas, da mesma forma que os leitores de telas usados por cegos, para mostrar os resultados mais relevantes de uma busca.
Acessibilidade Web também está ligada a diversos dispositivos. Hoje em dia, grande parte da população utiliza também celulares, tablets e outros dispositivos para acessar páginas da web. Se não houver uma preocupação em como as informações do site serão exibidas nestes dispositivos, há uma forte possibilidade de que seu conteúdo não seja disponibilizado adequadamente ou que sua página tenha um grande índice de rejeição. 
Existem vários fatores que podem impossibilitar ou dificultar o acesso ao conteúdo de uma página. Ao longo deste artigo veremos como podemos detectar pontos críticos de acessibilidade, normas e algumas boas práticas ao se desenvolver uma página web.

**3. A importância da acessibilidade na web**

Com a expansão e evolução das tecnologias e principalmente da internet, novas formas de comunicação e divulgação de informação foram surgindo. Nos dias atuais, é praticamente impossível encontrar um campo da atividade humana em que não haja, de algum modo, influência da web, há quem diga que, sem a web, não teríamos esse grande avanço tecnológico que temos nos dias atuais.

A demanda pelo acesso rápido as informações, muitas vezes faz com que empresas e os desenvolvedores esqueçam as minorias e foquem apenas no grande público, o que em alguns raros casos é de se entender, porém, muitas vezes há uma divisão prioritária errada do que é realmente importante e o que não é. Um exemplo clássico são navegadores de internet antigos, os chamados navegadores de legado. Muitas empresas priorizam o suporte para navegadores arcaicos pois há uma pequena fatia de usuários que ainda os utilizam, mas esquecem das pessoas que possuem alguma necessidade especial e que também têm o direito de acessar essas informações.

Websites e aplicações web que não dão a devida atenção para a acessibilidade, acabam causando problemas para essa minoria. Um exemplo disso é um website de uma loja que vende livros on-line. Digamos que, determinado formulário desta loja use a cor vermelha para diferenciar um campo obrigatório de um opcional, até aí tudo bem, o problema é se determinada pessoa que queira comprar um livro for daltônica e não conseguir distinguir a cor vermelha das demais. Este é apenas um de vários problemas que podemos notar em vários websites no nosso dia a dia. Se esta página em questão, estivesse seguindo as normas e melhores práticas para uma web mais acessível, este problema não aconteceria e o cliente poderia efetuar a compra de seu livro sem quaisquer frustrações.

**Referências**

Nicácio, J. (2010) “Técnicas de Acessibilidade – Criando uma web para todos”, http://jalvesnicacio.files.wordpress.com/2010/11/tc3a9cnicas-de-acessibilidade-web-jalves-nicc3a1cio.pdf, Setembro.

Henry, S. L (2005) “Introduction to Web Accessibility”, http://www.w3.org/WAI/intro/accessibility.php, Setembro.

Borba, A. et al. (2013) “Cartilha Acessibilidade na Web - W3C Brasil”,
http://www.w3c.br/pub/Materiais/PublicacoesW3C/cartilha-w3cbr-acessibilidade-web-fasciculo-I.pdf, Setembro.

Sonza, A. et al. (2013) “Acessibilidade e Tecnologia Assistiva - Pensando a Inclusão Sociodigital de PNEs”.
