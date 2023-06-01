# Desenvolvimento Web  - Projeto Game Mata Mosquito


## Table of contents

- [Visão Geral](#visão-geral)
  - [Captura de Tela](#captura-de-tela)
  - [Links](#links)
- [Meu processo](#meu-processo)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Autor](#autor)



## Visão Geral
    Este foi um projeto criado com HTML5,CSS3 intermediário, Bootstrap e Javascript, basicamente criei um jogo onde você tem que acertar um mosquito antes que ele suma se não você perdera vida, você tem 3 corações de vida, acerte os mosquitos rápidos e não deixe o tempo se esgotar.

### Captura de Tela

![](/screenshot/foto.png)

### Links

- Live Site URL: [https://desenvolvimento-web-mu.vercel.app](https://desenvolvimento-web-mu.vercel.app)

## Meu processo

### Construído com

- Semantic HTML5 markup
- CSS3
- CSS3 intermediário
- Bootstrap
- Javascript

### O que eu aprendi

  Neste projeto eu revisei as maneiras de criação e conceitos de técnicas avançadas de variáveis,operadores, switch, funções, escopo, eventos, array, DOM e etc.

```html
<div class="container">
			<div class="row">
				<div class="col">
					<div class="d-flex justify-content-center">
						<img src="imagens/game.png" />
					</div>
				</div>
			</div>
```
```css
.painel {
	position: absolute;
	width: 190px;
	padding: 10px;
	left: 0px;
	bottom: 0px;
	border-top:solid 1px #fff;
	background-color: #fff;
	opacity: 0.7
}

```
```javascript

function tamanhoAleatorio() {
	var classe = Math.floor(Math.random() * 3)
	
	switch(classe) {
		case 0:
			return 'mosquito1'
		
		case 1:
			return 'mosquito2'

		case 2:
			return 'mosquito3'
	}
}

```


## Autor

- Github - [@devbrunolucas](https://github.com/devbrunolucas)
