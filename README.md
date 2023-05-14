# Drag And Drop

Gerenciamento de Arrastar e Soltar Simplificado

# Sobre o projeto

  O projeto Drag and Drop é uma implementação prática do conceito de arrastar e soltar (drag and drop) utilizando JavaScript. O objetivo principal é simplificar o gerenciamento dessa interação, permitindo que os elementos sejam arrastados e soltos em diferentes áreas do documento.

Neste projeto, são utilizados recursos como o dataTransfer e os eventos relacionados ao arrastar e soltar para criar a funcionalidade de drag and drop. No código fornecido, um elemento com a classe caixa pode ser arrastado e solto em duas áreas distintas, representadas pelas classes zona red e zona blue.

Ao carregar a página, são definidos os manipuladores de eventos necessários para a funcionalidade de drag and drop. O evento ondragstart é utilizado para iniciar a operação de arrastar quando o elemento com a classe caixa é arrastado. Durante esse evento, é definido o tipo de dado a ser transferido utilizando e.dataTransfer.setData(), nesse caso, definido como 'text/plain', e o ID da caixa sendo arrastada é armazenado.

O evento ondragend é utilizado para realizar ações após a conclusão do arrastar, como remover classes CSS aplicadas temporariamente. No exemplo fornecido, a classe black é removida do elemento arrastado.

Para cada área de destino com a classe zona, são definidos os eventos ondragover, ondragleave e ondrop. O evento ondragover é responsável por permitir que o elemento seja solto na área definida. Durante esse evento, e.preventDefault() é chamado para evitar comportamentos padrões indesejados. A classe zona-over é adicionada temporariamente para indicar visualmente que a área é um alvo válido para soltar o elemento arrastado.

O evento ondragleave é acionado quando o elemento arrastado é movido para fora da área de destino. Nesse evento, e.preventDefault() é novamente chamado para evitar comportamentos indesejados, e a classe zona-over é removida.

Finalmente, o evento ondrop é acionado quando o elemento arrastado é solto na área de destino. Nesse evento, e.preventDefault() é chamado para evitar comportamentos indesejados. O ID do elemento arrastado é obtido usando e.dataTransfer.getData('text/plain'), e o elemento correspondente é movido para a área de destino usando z.appendChild(elem). Em seguida, a classe zona-over é removida.

Ao explorar este projeto, você terá a oportunidade de aprender como simplificar o gerenciamento de arrastar e soltar utilizando JavaScript. Além disso, poderá compreender o uso do dataTransfer e dos eventos relacionados para manipular a interação de arrastar e soltar entre elementos.

Aproveite essa abordagem simplificada para aprimorar suas habilidades no desenvolvimento de interfaces interativas e ofereça aos usuários uma experiência mais intuitiva e envolvente em suas aplicações.

## Layout D3Js
![Drag an Drop](https://github.com/Thiago771414/imagensProjetos/blob/main/slices/mobile/DragAndDrop.png)

## Vídeo de demonstração
[[Vídeo de demonstração]](https://youtu.be/idskEjzhMrk)

# Tecnologias utilizadas

## Front end
- Java Script, HTML

# Sobre o Projeto
https://reqres.in/

# Autor

Thiago Reis Lima

https://www.linkedin.com/in/thiago-lima-2a5896166/
