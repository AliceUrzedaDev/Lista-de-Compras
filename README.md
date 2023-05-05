✨ O projeto foi feito junto ao curso do Alura!

<h1 align="center">Projeto Lista de Compras - Utilizado no Curso Objetos no JavaScript - Escola Front-End Alura</h1>

## ✔️ Tecnologias utilizadas:

- ``HTML``
- ``CSS``
- ``JavaScript``

## 📁 Acesso ao projeto

Você pode acessar o projeto feito por mim clicando [aqui]( https://aliceurzedadev.github.io/Lista-de-Compras/).

## Neste arquivo encontram-se modelos de códigos que foram utilizados no decorrer do curso. 

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
