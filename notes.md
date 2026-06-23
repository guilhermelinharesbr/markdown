# Estudo de Markdown:


**Sumário**
- Títulos/Cabeçalhos
- Negrito
- Itálico
- Tachado (strike)(riscado)
- Combinação de símbolos - negrito, itálico, tachado
- Listas Não ordenadas
- Listas Ordenadas
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
Ex:   - Item 1  
      - Item 2  
           + Subitem 1  
            + Subitem 2

--------------------------------------------

**Listas Ordenadas**

Listas Ordenadas utilizam números seguidos de um ponto `.` .    
Ex: 1. Primeiro item  
       1. Segundo item    
            2.1. subitem    
            2.2. subitem    

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
