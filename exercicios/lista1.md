Claro! Aqui está uma lista de 15 exercícios sobre seletores CSS
(seletores básicos e seletores de atributo):

### Exercícios sobre Seletores CSS

1. **Exercício 1:** Utilize um seletor de elemento para alterar a cor de todos os parágrafos (`<p>`) para azul. => OK
    ```css
    p {
        color: blue;
    }
    ```

2. **Exercício 2:** Use um seletor de classe para definir o texto em negrito e vermelho para todos os elementos com a
   classe `.importante`. => OK
    ```css
    .importante {
        color: red;
        font-weight: bold;
    }
    ```

3. **Exercício 3:** Aplique um fundo cinza claro e centralize o texto em um elemento com o ID `#cabeçalho`. => OK
    ```css
    #cabeçalho {
        background-color: lightgrey;
        text-align: center;
    }
    ```

4. **Exercício 4:** Crie um seletor de atributo que estilize todos os inputs que possuem o atributo `type`. => OK
    ```css
    input[type] {
        border: 2px solid green;
    }
    ```

5. **Exercício 5:** Estilize todos os links (`<a>`) cujo atributo `href` contenha a palavra "example" com a cor
   vermelha. => OK
    ```css
    a[href*="example"] {
        color: red;
    }
    ```

6. **Exercício 6:** Aplique uma borda azul de 2px a todos os inputs do tipo texto (`<input type="text">`). => OK
    ```css
    input[type="text"] {
        border: 2px solid blue;
    }
    ```

7. **Exercício 7:** Use um seletor de classe para aplicar um fundo amarelo a todos os elementos com a
   classe `.destaque`.
    ```css
    .destaque {
        background-color: yellow;
    }
    ```

8. **Exercício 8:** Utilize um seletor de ID para alterar a cor de fundo do elemento com ID `#rodape` para preto e o
   texto para branco.
    ```css
    #rodape {
        background-color: black;
        color: white;
    }
    ```

9. **Exercício 9:** Crie um seletor de atributo que estilize todos os links (`<a>`) cujo atributo `href` comece com "
   https".
    ```css
    a[href^="https"] {
        text-decoration: underline;
    }
    ```

10. **Exercício 10:** Aplique uma fonte itálica a todos os elementos `<em>` usando um seletor de elemento.
    ```css
    em {
        font-style: italic;
    }
    ```

11. **Exercício 11:** Use um seletor de classe para aumentar o tamanho da fonte para 20px em todos os elementos com a
    classe `.grande`.
    ```css
    .grande {
        font-size: 20px;
    }
    ```

12. **Exercício 12:** Estilize todos os inputs do tipo senha (`<input type="password">`) com uma borda vermelha.
    ```css
    input[type="password"] {
        border: 2px solid red;
    }
    ```

13. **Exercício 13:** Utilize um seletor de atributo para aplicar uma borda amarela a todos os inputs cujo
    atributo `type` termine com "word".
    ```css
    input[type$="word"] {
        border: 2px solid yellow;
    }
    ```

14. **Exercício 14:** Crie um seletor de ID para alterar o tamanho da fonte para 24px e a cor para verde do elemento com
    ID `#titulo`.
    ```css
    #titulo {
        font-size: 24px;
        color: green;
    }
    ```

15. **Exercício 15:** Utilize um seletor de classe para aplicar uma margem de 10px a todos os elementos com a
    classe `.espacado`.
    ```css
    .espacado {
        margin: 10px;
    }
    ```

Esses exercícios ajudam a entender e praticar o uso de seletores CSS básicos e de atributo, proporcionando uma base
sólida para a estilização de elementos em documentos HTML.