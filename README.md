# Página Pessoal de Rodrigo Simão

Este é o código fonte da página pessoal de Rodrigo Simão, projetada para apresentar informações sobre sua trajetória, formação, experiências profissionais e portfólio.

## Estrutura do Projeto

A página foi construída usando as tecnologias básicas para desenvolvimento web: **HTML**, **CSS** e **JavaScript**. Possui um layout responsivo e moderno, adequado para exibição em dispositivos móveis e desktops.

### Funcionalidades Principais

- **Navegação Fixa:** Uma barra de navegação fixa no topo com links para as seções principais.
- **Introdução com Imagem:** Uma seção inicial com um texto de boas-vindas e uma imagem destacada.
- **Seção Sobre Mim:** Descreve informações pessoais com uma imagem estilizada.
- **Seção Formação:** Apresenta informações acadêmicas com imagens representativas da universidade.
- **Seção Experiência Profissional:** Resume as experiências do autor com desenvolvimento backend e web.
- **Portfólio:** Contém um link para projetos destacados.
- **Rodapé Personalizado:** Inclui direitos autorais.

## Estrutura do Código

### HTML

1. **Header:** 
   - Inclui uma barra de navegação fixa com links para as seções.
   - Adiciona uma funcionalidade de menu responsivo (menu hambúrguer).

2. **Seções:**
   - `intro`: Apresentação inicial com texto e imagem.
   - `sobre`: Informações pessoais e hobbies.
   - `formacao`: Dados acadêmicos e imagens relacionadas.
   - `profissional`: Experiência profissional em desenvolvimento.
   - `portfolio`: Destaque para projetos e link para o portfólio online.

3. **Footer:**
   - Exibe informações de direitos autorais.

### CSS

1. **Global Reset:** Zera margens, espaçamentos e define estilos básicos como `box-sizing` e `font-family`.
2. **Responsividade:**
   - Inclui um breakpoint para telas com largura menor que 768px.
   - Ajusta o layout e tamanho dos elementos para dispositivos móveis.
3. **Estilos Específicos:**
   - Imagens arredondadas e com bordas.
   - Texturas de fundo nas seções.
   - Destaques em amarelo (`#FF9800`) para títulos e elementos importantes.
   - Sombras e bordas suaves para cartões e imagens.

### JavaScript

- Inclui uma funcionalidade para o menu hambúrguer, alternando a visibilidade do menu em dispositivos móveis.

```javascript
document.getElementById("menu-icon").addEventListener("click", function() {
    const menu = document.getElementById("menu");
    menu.classList.toggle("active");
});
