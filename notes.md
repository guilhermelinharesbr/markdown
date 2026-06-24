# Estudo de Markdown:


**Sumário**
- Títulos/Cabeçalhos
- Negrito
- Itálico
- Tachado (strike)(riscado)
- Combinação de símbolos - negrito, itálico, tachado
- Listas Não ordenadas
- Listas Ordenadas
- Listas Aninhadas
- Listas Combinadas
- Listas de Definição
- Lista de Tarefas
- Links 
- Imagens
- Linhas Horizontais
- Quebra de linha
- Parágrafos
- Caractere de Escape
- Blocos de Códigos
- Citações
- Menções à usuários
- Tabelas
- Opções Não Nativas: Sublinhado
- Editores Offline
- Editores Online
- Site oficial

--------------------------------------------

**Títulos/Cabeçalhos** 

Usa-se o `#`. Dependendo do número de `#`, é definido o nível do cabeçalho de h1 a h6. <br> É importante ter um `espaço` entre o `#` o cabeçalho em si. <br> Outra dica importante é deixar uma `linha em branco` entre o cabeçalho e o texto para deixar o seu texto organizado.

Exemplos:
# Cabeçalho h1
## Cabeçalho h2
### Cabeçalho h3
#### Cabeçalho h4
##### Cabeçalho h5
###### Cabeçalho h6

--------------------------------------------

**Negrito** 

Usa-se o `**` ou `__`. Geralmente é mais usado `**`, justamente para ajudar a diferenciar do itálico.
- Ex: **negrito com asteriscos**
- Ex2: __negrito com sublinhados__

--------------------------------------------

**Itálico** 

Usa-se o `*` ou `_`. Geralmente é mais usado o `_`, justamente para ajudar a diferenciar do negrito.
- Ex: _itálico com sublinhado_
- Ex2: *itálico com asterisco*

--------------------------------------------

**Tachado**(strike)(riscado) 

Usa-se o `~~` para riscar uma palavra ou texto, também pode ser conhecido como _tachar_.
- Ex: ~~palavra~~
- Ex2: ~~texto completamente riscado~~

--------------------------------------------

**Combinação de símbolos - negrito, itálico, tachado**

Para que uma palavra ou texto fique em negrito e itálico ao mesmo tempo, basta combinar os símbolos.<br> Podendo somar os `**` do negrito com o `*` do itálico ficando `***`, ou somando os underscores sendo os `__` do negrito com o `_` do itálico ficando `___`.<br> Também pode-se usar combinações mais legíveis ficando `**` mais um `_`.<br> Até mesmo é possível combinar tachado com itálico ou negrito.
- Ex: *__Texto 1 em negrito e itálico usando 3 underscores__*.
- Ex2: ***Texto 2 em negrito e itálico usando 3 asteriscos***.
- Ex3: _**Texto 3 em negrito e itálico usando asteriscos e underscores**_.
- Ex4: ~~**Texto 4 em negrito e tachado usando asteriscos e tils**~~.
- Ex5: ~~_Texto 5 em itálico e tachado usando underscores e tils_~~.

--------------------------------------------

**Listas Não ordenadas**

Listas Não ordenadas são criadas usando hífens `-` , asteriscos `*` ou sinais de mais `+`. 
Para que os itens perteçam a mesma lista é preciso que eles utilizem o mesmo símbolo, se misturar os `-` com `*` ou `+` eles ficaram com uma distância um pouco maior entre si.

Ex. - Lista não ordenada simples:
- Brasil
- Argentina
- Uruguai

Ex.2 - Lista mistrurando símbolos:
- Item 1 com hífen 
  - Item 2 com hífen 
     + Subitem 1 com sinal de mais 
     + Subitem 2 com sinal de mais
       * Subitem 3 com asterisco 

Ex.3 - Mostrando como um item com símbolo diferente fica mais distante dos demais:
* Fortaleza
- Recife 
- Salvador  
- Natal

--------------------------------------------

**Listas Ordenadas**

Listas Ordenadas utilizam `números` seguidos de um ponto `.`. 
Para o Markdown é irrelevante se os números estão em ordem numérica, pois para ele se tiver um número seguido de um `.` significa que é uma lista, com o detalhe que a lista começará baseada no primeiro item dela.    

Ex: 
1. Primeiro item  
2. Segundo item
3. Terceiro item
  3.1. Subitem 1   
  3.2. Subitem 2  

Ex2:
1. Item 1 e foi escrito o número 1
8. Item 2, mas foi escrito o número `8.`, só para mostrar que a lista segue a sequência do primeiro item da lista
47. Item 3, mas foi escrito o número `47.`, só para mostrar que a lista segue a sequência do primeiro item da lista
96. Item 4, mas foi escrito o número `96.`, só para mostrar que a lista segue a sequência do primeiro item da lista
  
--------------------------------------------

**Listas Aninhadas**

Listas Aninhadas são listas dentro de outras listas. Pode-se criar uma usando `dois espaços em branco` ou um `TAB`. Para que encerrar a lista basta deixar uma linha em branco, com isso o que for digitado não estará mais na lista.

Ex. - Lista Aninhada Não ordenada, usando tanto dois espaços em branco quanto TAB:
- América do Sul
  - Brasil
    - Nordeste
      - Ceará
        - Fortaleza 
  - Argentina
  - Uruguai
  - Paraguai

--------------------------------------------

**Listas Combinadas**

Listas Combinadas são listas que misturam lista ordenadas com listas não ordenadas.

Ex de cidades mais populosas do países:
1. Brasil
     - São Paulo
     - Rio de Janeiro
     - Brasília
     - Fortaleza
2. Argentina
     - Buenos Aires
     - Córdoba
     - Rosário
3. Uruguai
     - Montevidéu
     - Salto
4. Paraguai
     - Assunção
     - Ciudad del Este
  
--------------------------------------------

**Listas de Definição**

Listas de Definição são usadas para dar uma explicação/definição de um item, como se fosse um pequeno dicionário. 
Elas não tem suporte nativo do Markdown, porém dependendo de onde está sendo escrito o Markdown ela pode funcionar, no VS Code funciona por causa da extensão `Markdown Preview Enhanced`.
Para que ela funcione é preciso que seja digitado o item, depois na `linha seguinte` digitado `:`, depois um `espaço em branco` entre os `:` e o começo da definição do item. 

Ex:

Capital
: Cidade onde se localiza o governo central de um estado.

País
: Território delimitado com Governo próprio.

Continente
: Grande extensão territorial que agrupa vários países.


--------------------------------------------

**Listas de Tarefas**

A Lista de Tarefas, é feita utilizando o hífen `-` no começo, um `espaço em branco`, dois colchetes `[ ]` e um `espaço em branco` dentro do colchetes, é um como se fosse um check-box. Para marcar um item como concluído basta colocar a letra `x` no lugar do `espaço em branco` que estava dentro dos colchetes.

Ex. Lista de compras mercantil:

- [ ] Arroz
- [x] Feijão
- [x] Macarrão
- [ ] Café
- [x] Leite

--------------------------------------------

**Links**

Para criar links, utilizamos colchetes `[]` para o texto do link e parênteses `()` para a URL.   
Ex: [Google](https://www.google.com.br)  

--------------------------------------------

**Imagens**

As imagens são inseridas de forma similar aos links, mas precedidas de um pornto de exclamação `!` .   
Ex: ![Logo do Markdown](https://img.shields.io/badge/Markdown-000?style=for-the-badge&logo=markdown&logoColor=white)

--------------------------------------------

**Linhas Horizontais**

Para adicionar uma linha horizontal, basta usar _três_ ou mais hífens `-`. Também funciona com três asteriscos `***` ou três underscores `___` isolados em uma linha.

Ex. com três hífens:  

---    

Ex.2 com dez hífens:    

----------    

Ex.3 com três asteriscos isolados em uma linha:    

***

Ex.4 com três underscores isolados em uma linha:    

___

--------------------------------------------

**Quebra de Linhas**

Para adicionar uma quebra de linha basta digitar dois `espaços` no final da linha ou usar a tag HTML `<br>`.

-------------------------------------------

**Parágrafos**

Para inserir um parágrafo basta deixar `uma ou mais linhas em branco` antes de continuar escrevendo.

-------------------------------------------

**Caractere de Escape**

O caractere de escape no markdown é o contrabarra `\`.<br>
Ex. Aqui realmete quis exibir os símbolos * junto da palavra \*\*estudo\*\*, e não tornar a palavra em negrito. 

-------------------------------------------

**Blocos de código**

Para destacar código em linha, usa-se uma crase `` ` ``. Para bloco de código, utiliza-se três crases ```` ``` ````.

Ex: Esta linha contém um `código`.     

Ex1.1: O comando `ls` serve para listar itens.   

Ex2: 
```text
Este é um bloco
de código.
```

Ex3:  
```
ls      
ping 8.8.8.8   
cat arq1    
```
       
Para destacar a sintaxe em bloco de código, deve-se especificar a linguagem após as crases.   
Ex4 para destacar um código em Python: 
```python  
print(f'Olá, Mundo!')
print(f'Olá, Mundo2!')
```

--------------------------------------------

**Citações**

Para adicionar uma citação, basta usar o símbolo `>`. É possível ter níveis de citações, também conhecidas como citações aninhadas, bastando usar o `>>`, `>>>`, etc.


Ex:
> Este é um exemplo de citação.  
> Pode ter várias linhas.

Ex2: 
> Agora um exemplo de citações aninhadas.
>> Nível 2
>>> Nível 3
>>>> Nível 4
>>>>> Nível 5

--------------------------------------------

**Menções à usuários** 

Para mencionar algum usuário, pode indicar o nome do perfil logo após o símbolo `@`.
- Ex:  [@guilhermelinharesbr](https://github.com/guilhermelinharesbr)
- Ex2: [@linhareseduardo](https://github.com/linhareseduardo)

--------------------------------------------

**Tabelas**

Para criar tabelas de maneira simples, usa-se uma variação de hífens `-` e pipes `|` .

Ex:

| Coluna 1   | Coluna 2   |
|------------|------------|
| Linha 1    | Valor 1    |
| Linha 2    | Valor 2    |
| Linha 3    | Valor 3    |
| Linha 4    | Valor 4    |

--------------------------------------------

 **Opções Não Nativas**

Não existe sintaxe nativa para `sublinhado` em Markdown.

--------------------------------------------

**Editores Offline**
- [Obsidian](https://obsidian.md/)
- [Typora](https://typora.io/)
- [VS Code](https://code.visualstudio.com/)

--------------------------------------------

**Editores Online**
- [Dillinger](https://dillinger.io/)
- [Markdown Live Preview](https://markdownlivepreview.com/)

--------------------------------------------

**Site oficial**
[Markdown - daringfireball](https://daringfireball.net/projects/markdown/)
