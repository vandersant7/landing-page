# Landing Page Responsiva utilizando HTML e CSS

Este projeto consiste em uma landing page responsiva desenvolvida como parte de um exercício no curso DevQuest. O objetivo principal é destacar o uso das propriedades do Grid e Flexbox para criar um layout atrativo e funcional.

## 📚Estrutura do Projeto

O projeto é estruturado da seguinte forma:

- **index.html**: Arquivo principal que contém a estrutura HTML da landing page.
- **style.css**: Arquivo de estilos CSS que define o layout e a aparência da página.
- **reset.css**: Arquivo que limpa todos os padrões dos navegadores.
- **variables.css**: Arquivo que contêm valores específicos a serem utilizados em um documento.
- **menu.css**: Arquivo contêm o menu responsivo - chamado de "menu hambuguer".
- **font-awesome.css**: Arquivo que contêm um conjunto de ícones vetoriais escalaveis.

## Tecnologias Utilizadas

- HTML5
- CSS3

## Layout Responsivo

O layout da landing page foi projetado para se adaptar a diferentes tamanhos de tela, garantindo uma experiência de usuário consistente em dispositivos móveis, tablets e desktops.

### Uso do Grid

O sistema de grid foi empregado para organizar os elementos da página de maneira eficiente. Exemplo:

```css
.about {
    grid-area: about;
    display: grid;
    grid-template-columns: 1fr 1fr;
    background-color: #fff;
}
```

Neste trecho de código, a classe `.about` utiliza o Grid para criar uma estrutura de duas colunas.

### Uso do Flexbox

O Flexbox foi empregado para alinhar e distribuir os itens dentro de cada seção da página. Exemplo:

```css
.about .item {
    padding: 20%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

A classe `.about .item` utiliza o Flexbox para centralizar os elementos internos, garantindo um espaçamento uniforme entre eles e um alinhamento vertical e horizontal adequado.

## Design Moderno

A página foi estilizada de acordo com as melhores práticas de design, incluindo:

- Cores atraentes e harmoniosas.
- Fontes legíveis e agradáveis.
- Ícones e imagens relevantes para melhorar a experiência visual do usuário.

## Como Contribuir

Se desejar contribuir para este projeto, sinta-se à vontade para fazer um fork e enviar suas melhorias através de pull requests. Suas contribuições são sempre bem-vindas!

**Nota:** Este projeto é fictício e foi criado apenas para fins educacionais no âmbito do curso DevQuest.
