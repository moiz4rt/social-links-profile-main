# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge


### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Eu tentei centralizar o card usando _position: absolute_ por causa das vantagens de não ser necessário maximizar o contêiner pai pra poder colocar na posição desejada. Mas com isso deslocava-se o rodapé do crédito e se perdia as vantagens do _display: flex_ que incluem a centralização dos elementos nos dois eixos com _justify-content_ e _align-items_ e o gap, o que seria muito trabalhoso utilizando outra forma.
Em alguns casos onde precisei diminuir a margem inferior tive que mudar o _line-height_ para evitar margens negativas.
Ainda tenho uma certa insegurança em definir uma largura fixa em um contêiner por medo de quebrar o layout. Mas o layout fica muito esticado em tamanhos maiores. A solução foi usar o _max-width_.
É muito extenuante calcular proporções no olho, mas pelo menos o resultado final parece ter chegado mais perto.
Ia usar _html { font-size: 62.5% }_, mas li que era melhor manter em 100% e utilizar variáveis. Como este é um desafio pequeno não me importei em escrever variáveis, mas com certeza teria usado se fosse um projeto bem maior.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Eu tentei centralizar o card usando _position: absolute_ por causa das vantagens de não ser necessário maximizar o contêiner pai pra poder colocar na posição desejada. Mas com isso deslocava-se o rodapé do crédito e se perdia as vantagens do _display: flex_ que incluem a centralização dos elementos nos dois eixos com _justify-content_ e _align-items_ e o gap, o que seria muito trabalhoso utilizando outra forma.
Em alguns casos onde precisei diminuir a margem inferior tive que mudar o _line-height_ para evitar margens negativas.
Ainda tenho uma certa insegurança em definir uma largura fixa em um contêiner por medo de quebrar o layout. Mas o layout fica muito esticado em tamanhos maiores. A solução foi usar o _max-width_

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Live Server do Vscode](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)  - É uma maravilha não ter que ficar recarregando a página a cada pequena interação.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)