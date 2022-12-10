# Front-End completo 2.0
Anotações, exemplos e exercicios do curso de front-end completo 2.0 na Danki Code

## Hyper Text markup language
Sendo o acrônimo HTML atualmente estamos na versão do HTML5.

Nessa versão o HTML possibilita a incorporação nativa de áudio e vídeo.
### tags
São os elementos do HTML temos tags que possuem abertura e fechamento e outras que não tem

```HTML
    <!--Com feclamento-->
    <p></p>
    <!--Sem fechamento-->
    <img src="" alt="">
```

Há tags que bloco e em linha, as de bloco ocupam o espaço todo da tela e fazem os elementos na sua sequencia aparecerem abaixo deles, os elementos em linha não afetam a posição de ocupação de outros elementos junto a si. Essa condição dos elementos é possível ser manipulada com o CSS.
### Sections e Divs
Sections e divs servem para fazer divisões no site, para ter melhor controle em suas partes.

Sections é um recurso recente, pode usar tudo com divs, mas para uma melhor organização usar sections, header, aside entre outros indica e facilita para que o browser organize o seu conteúdo.

### Tags importantes para SEO e SMO
- Bom site para gerar meta tags metatags.io.
- SEO é otimização para buscadores na Web
- SMO é otimização para buscas de site na rede social, então tudo aquilo que aparece como nome do site, imagem, descrição, isso é gerado pelo SMO.


## CSS
responśavel por estilizar dar forma visual aos elementos do HTML
### Reset CSS
Importante ter um reset CSS que retira atributos que o browser venha a atribuir aos elementos da página. Uma forma simples de fazer isso é usar como o exemplo abaixo:

```CSS
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```
### Ids e classes
Id: é indicado para usar e selecionar no JavaScript, mas também no CSS conseguimos utilizar esse modo de selecionar. é indicado usar em elementos únicos na página.

Modo de declarar um id:
```CSS
#paragrafo {
    font-size: 10px;
}
```
Classe: posso usar para vários elementos

Modo de declarar uma classe:
```CSS

.teste {
    color: red;
}

```

### Importando Fontes
Uma boa dica e muito usada é importar suas fontes pelo Google Fonts.

Ao escolher a fonte e os tamanhos que deseja, é gerado um modelo de como importar a fonte e como chamar o `font-family` dentro do elemento que está estilizando.

### manipulando atributos
é possível manipular pelo CSS um elemento pelo atributo sendo personalizado ou não

No HTML podemos definir um atributo "name" para um tag `<p></p>` com o seu valor definido como "paragrafo":
```HTML
<!--este name na tag p, não existe no HTML ele acabou de ser criado-->
<p name="paragrafo">Olá mundo</p>
```

Agora podemos selecionar esse atributo no CSS da seguinte forma:

```CSS
[name=paragrafo]{
    color: blue;
}
```

### JavaScript
Linguagem de programação, para deixar a página dinâmica, manipulando eventos e animações.

