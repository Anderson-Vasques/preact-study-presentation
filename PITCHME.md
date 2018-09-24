@title[Preact]
# Preact

---
@title[Preact]

![Preact](assets/preact.png)

###### Fast 3kB alternative to React with the same modern API.

![Press Down Key](assets/down-arrow.png)

+++
@title[2]


```javascript
/** @jsx h */

import {h, render, Component} from 'preact';
const HelloWorld = () => (
  <div>
    <p>Hello World</p>
  </div>
);

render(<HelloWorld />, document.body);
```
+++
@title[3]
### Minhas ideias

@snap[west] 
@ul

Aprender a usar PREACT e os funcionamentos internos
USAR PREACT
DIFERENÇAS PREACT X REACT
VDOM
DIFF
COMPONENTS
JSX
REATIVIDADE
CONQUISTAR O MUNDO @ulend @snapend

+++
@title[4]
![Preact](assets/preact.png)
[Funcionamento interno](https://cdn-images-1.medium.com/max/2000/1*TF0TZszVwpYc1Pba7Dbk7Q.png)

+++
@title[5]
### O que eu consegui até agora

@snap[now] 
@ul

USAR PREACT
JSX
VDOM (meh) @ulend @snapend
---

### Efeitos

![Press Down Key](assets/down-arrow.png)

+++
@title[hide/show efect]

###### Escondendo elementos com o método **hide()**

```javascript
var paragraphs = $('p');
paragraphs.hide();
```

@[1](Selecionar todos as tags **p** do documento)
@[2](Esconder todas as tags **p**. O jQuery modifica o estilo do elemento adicionando um atributo **style** e adiciona o valor **none** para a propriedade **display**)

+++
