# Curso de Google Earth Engine (GEE)
## Para usar e alteração os Scripts do Projeto

>Esse Documento foi criado com a finalidade de dar apoio para quem não conhece, ou tem pouca experiência com JavaScript e/ou Google Earth Engine.  

### Para acessar o **CodeEditor** do GEE.
[Acesse Aqui](https://code.earthengine.google.com/)
#
## JavaScript (GEE)
### A Linguagem padrão do Google Earth Engine é o JavaScript, e possui uma biblioteca própria.

### Variáveis:
Existem alguns tipos de variáveis no JavaScript, essas variáveis se dividem por **Tipos**;
#### Tipo Texto:
Tipo texto é a forma mais simples de vincular uma **_string_** (texto) à uma variável

COD:
```
// Variável simples de texto
// Nome = 'string'
var cidade = 'Goiânia'
var pais = 'Brasil'
var nome = 'João Victor'
```
#### Tipo Lista:
Tipo lista é uma extensão do exemplo anterior, basicamente a lista supri a necessidade de criar várias variáveis, criando apenas uma com várias **_string_**, o que facilita muito na hora de estrutura o código e até mesmo a entender o *script*

COD:
```
// Nome = ['string', 'string_2', ...]
var cidades = ['Goiânia', 'Anápolis', 'Trindade', 'Aparecida de Goiânia']

// Titulo do Print, Lista[posição dentro da Lista]
print('CIDADES:', cidades[0]')
```
#### Tipo Dicionário:
O Tipo dicionário é uma evolução da lista, nesse tipo é possível criar atributos para a variável e referência-los no "print"

COD:
```
var JoaoVictor = {
    'pais' = Brasil,
    'Estado' = Goiás,
    'Cidade' = Goiânia,
    'Idade' = 24
}
print(JoaoVictor['pais'])
```
