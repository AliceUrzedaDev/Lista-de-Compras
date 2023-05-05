✨ O projeto foi feito junto ao curso do Alura!

<h1 align="center">Projeto Lista de Compras - Utilizado no Curso Objetos no JavaScript - Escola Front-End Alura</h1>

## ✔️ Tecnologias utilizadas:

- ``JavaScript``
- ``CSS``
- ``HTML``

## Instruções para utilização da Lista de Compras:

- Digite os itens que deseja comprar na sua lista e salve eles no botão "Salvar Item" ou apertando "Enter";
- Para editar o item, aperte o lápis ao lado direito do nome digitado, após aperte no próprio nome para digitar outro de sua preferência e clique no disquete para salvar;
- Para marcar o item caso for comprado, apenas clique no checkbox ao lado esquerdo do nome digitado;
- Para excluir algum item de sua lista, aperte a lixeira ao lado direito do nome digitado. 
- Fique tranquilo(a), você não irá perder seus itens digitados caso você sair da aba, eles vão continuar em sua lista.

## 📁 Acesso ao projeto

Você pode acessar o projeto feito por mim clicando [aqui]( https://aliceurzedadev.github.io/Lista-de-Compras/).

## Neste arquivo encontram-se modelos de códigos que foram utilizados no decorrer do curso: 

Código modelo da li "Comprados":

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" checked class="is-clickable" />  
            <span class="itens-comprados is-size-5"></span>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Código modelo da li "Lista de compras": 

    <li class="item-compra is-flex is-justify-content-space-between" data-value="">
        <div>
            <input type="checkbox" class="is-clickable" />
            <input type="text" class="is-size-5" value=""></input>
        </div>
        <div>
            <i class="fa-solid fa-trash is-clickable deletar"></i>
        </div>
    </li>

Input com código refatorado:

    <div>
        <input type="checkbox" checked class="is-clickable" />  
        <span class="itens-comprados is-size-5">${elemento.valor}</span>
    </div>

Ícones de edição:

    <i class="fa-regular fa-floppy-disk is-clickable"></i><i class="fa-regular is-clickable fa-pen-to-square editar"></i>
