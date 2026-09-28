1. Como você montou a estrutura básica do arquivo index.html? Explique a função de \<!DOCTYPE
html>, \<html>, \<head> e \<body>.

Eu segui o padrão:
```html
<!DOCTYPE html> <!-- Sinaliza que o arquivo é um HTML -->

<html> <!-- A raiz do html -->
    <head> <!-- Contém todas as configurações e definições da página que não aparecem no corpo da página -->
        ...
    </head>
    <body> <!-- Contém toda a estrutura visual da página -->
        ...
    </body>
</html>
```

2. O que você colocou dentro do \<head> e qual é a função de cada elemento utilizado?
Utilizei o `<meta charset="UTF-8>"` pra definir o codificador de caracteres correto de simbolos e acentos, o `<meta name="viewport">` para ajustar a largura da página com a largura do dispositivo, o `<title>` para definir o título do navegador e o `<style>` para personalizar os elementos do body.

3. Como você utilizou as duas \<div> para separar e organizar os conteúdos da página? Informe também
os nomes das classes criadas.
Eu utilizei a primeira div com a classe perfil para fazer um "cartão" com background e borda centralizado com os dois parágrafos e a lista de interesses. Já a segunda div com a classe objetivos eu usei apenas para separar com uma margem no topo.

4. Como você aplicou o CSS dentro da tag \<style>? Apresente um seletor, uma propriedade e um valor
existentes no seu código.
Eu usei seletores de elementos como body, p, h1, e seletores de classes como perfil, texto-perfil para modificar a aparencia de certos elementos, como o tamanho da margem ou cor de fundo dos elementos como a propriedade text-align:center para centralizar o texto.

5. Quais cores e propriedades visuais você escolheu e qual foi o resultado observado no navegador?
Escolhi uma azul claro como cor principal as demais cores sendo complementares a ela, mexendo propriedades como color e backgroud color. O site ficou menos monóto.

6. Qual alteração ou correção foi necessária depois que você testou a página? Caso não tenha ocorrido
erro, explique como realizou o teste.
Eu tive que ajustar o tamanho da página que eu adicionei um heigth pro body e centralização/margem dos elementos.
