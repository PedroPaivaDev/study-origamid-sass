# Le Scone
#### _Restaurante_
Projeto final do curso de SASS da Origamid.

![](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white) ![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  ![](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

## Descrição
A [landing-page](https://study-origamid-sass.vercel.app/) foi desenvolvida com o pré-processador **SASS**, para fazer a compilação em CSS. Foram utilizados vários métodos do SASS, para otimizar a escrita do código CSS.
- [Variáveis](https://sass-lang.com/documentation/variables)
- [Aninhamento de elementos](https://sass-lang.com/documentation/style-rules)
- [*Mixin*: argumentos e conteúdo](https://sass-lang.com/documentation/at-rules/mixin)
- [*Extend*](https://sass-lang.com/documentation/at-rules/extend)
- [Operadores](https://sass-lang.com/documentation/operators)
- [Condicionais](https://sass-lang.com/documentation/at-rules/control/if)
- [Métodos de cores](https://sass-lang.com/documentation/modules/color)
- [Funções](https://sass-lang.com/documentation/at-rules/function)
- [*Loop: for*](https://sass-lang.com/documentation/at-rules/control/for)
- [*Loop: while*](https://sass-lang.com/documentation/at-rules/control/while)
- [*Loop: each*](https://sass-lang.com/documentation/at-rules/control/each)

<img src="./img/gifSASS.gif" alt="gif"/>

## Instruções

A primeira seção é uma introdução mostrando o horário de funcionamento do restaurante, sua localização e contato. A seção seguinte é um cardápio com as principais porções de entrada e os pratos principais.

Na seção de contato, o cliente pode inserir seus dados para fazer uma reserva e também conferir a localização no mapa.

> Caso você seja um desenvolvedor, use as instruções abaixo para instalar as dependências e sugerir alterações para a aplicação.

É possível verificar o conteúdo estudado durante o curso, selecionando o histórico de [commits].

Não é necessária a instalação de dependências de desenvolvimento para esse projeto, mas é preciso usar alguma ferramenta para observar o arquivo style.scss e compilar o código para um arquivo style.css. Para fazer isso, basta instalar globalmente o SASS usando o NPM:
```sh
npm install -g sass
```
Após a instalação do SASS, você pode simplesmente abrir o seu editor de código (ex.: VSCode) e clonar o repositório.
```sh
git clone https://github.com/PedroPaivaDev/study-origamid-sass
```
Para fazer o SASS observar as alterações feitas no arquivo style.scss, abra o seu terminal e digite o comando especificando os caminhos dos arquivos desde a raiz do projeto:
```sh
sass --watch sass/style.scss:css/style.css
```
É recomendada a instalação da extensão [live-server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), para que a página seja recarregada a cada alteração feita no código.

## Evolução do projeto

O curso foi dividio em três partes, que podem ser vistas nas *branchs* do projeto e nos deploys abaixo:

| Parte | Conteúdo desenvolvido |
| ------ | ------ |
| [Fundamentos do SASS](https://study-origamid-sass-git-fundamentals-pedropaivadev.vercel.app/) | Essa *branch* foi criada para armazenar os testes de uso dos métodos e funções |
| [SASS na prática](https://study-origamid-sass-git-practice-pedropaivadev.vercel.app/) | Foi importado o projeto Bikcraft do curso de Design da Origamid e refatorado o seu CSS usando o SASS |
| [Projeto Final](https://study-origamid-sass-git-project-pedropaivadev.vercel.app/) | A landing page foi escrita do zero, considerando as melhores práticas de uso do SASS |

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

[commits]: <https://github.com/PedroPaivaDev/study-origamid-bootstrap/commits/main>