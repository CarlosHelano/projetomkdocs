## Sobre o Respbuilder
---

O **Respbuilder** é um módulo responsável por processar dados e enviar para o frontend diretivas de construção de telas de forma descritiva por meio de um arquivo JSON. Isso permite que telas sejam criadas dinamicamente sem necessidade de modificação no código do aplicativo.

O elemento fundamental do Respbuilder é a **RespbuilderView**, que representa uma seção na tela. Cada arquivo respbuilder contém um array de RespbuilderViews, e cada view pode conter múltiplos componentes que serão renderizados na interface.

## RespbuilderView
---
### Conceito

#### O que é a RespbuilderView? 

A **RespbuilderView** é o container principal que agrupa componentes em uma seção da tela. Ela funciona como um cartão (card) visualmente separado, com um título destacado e uma lista de componentes que serão renderizados dentro dela.

> 🎯 Observe: Esta seção que você está lendo agora é uma RespbuilderView! O título "RespbuilderView - Conceito" que você vê no topo é o parâmetro nome, e este texto explicativo está dentro de um componente do tipo **TEXTVIEW** na lista de **componentes**.

Cada RespbuilderView possui os seguintes parâmetros:

* **nome**: String que define o título da seção, exibido com destaque visual
* **compartilhar**: Boolean que controla a exibição de um ícone para compartilhar screenshot da seção
* **manterHistorico**: Boolean que indica se a navegação deve retornar para a tela anterior
* **componentes**: Lista de componentes que serão renderizados dentro da seção

## Teste

aaaa
