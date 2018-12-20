# Challenges
Some small challenges i invented.

# DESAFIO 1
Ler o [seguinte arquivo](http://dados.df.gov.br/dataset/3a3b7b40-c715-439d-9dff-f22b47fc5994/resource/f4422c06-a041-46cc-9d89-9d09ffae1c70/download/2018-12-19-infracoes.csv) .csv e gerar um arquivo .csv para cada um dos itens:
+ Número de Infrações Graves, por dia e tipo e por hora.
+ Quantas Infrações foram realizadas com Motocicletas?
+ Numero de infrações por gravidade
+ Qual horário tem o maior número de infrações?
+ Qual o tipo de Infração mais comum?

### Parte 1
Fazer usando qualquer biblioteca de sua preferência.

### Parte 2
Resolver sem o uso de qualquer biblioteca.

# DESAFIO 2
Um programa que recebe um texto qualquer (pode ser um arquivo .txt ou uma simples string) e retorna o texto criptografado em [leet speak](https://pt.wikipedia.org/wiki/Leet).

### Parte 1
Retorna a string da maneira mais simples possivel como no exemplo

_Seja bem-vindo à Wikipédia, uma enciclopédia livre e gratuita, feita por pessoas como você em mais de 200 idiomas!_ 
**--vai virar-->** 
53j4 b3m-vind0 à Wikipédi4, um4 3ncic10pédi4 1ivr3 3 gr47ui74, f3i74 p0r p35504s c0m0 v0cê 3m m4is d3 200 idi0m4s! 

### Parte 2
O céu é o limite, tente retornar strings mais complexas, como:

53j4 b3M-vInd0 Ah wIKiPeHdI4, uM4 3nCIc10peHDi4 1iVR3 3 Gr47Ui74, pH3i74 p0R p35504z c0M0 v0CeH 3m M4iz d3 200 iDi0m4Z!

ou

53_| 4 8 3|\/| -\/ ! |\| |) 0 4 |-| \|/ ! |< ! |> 3|-||) ! 4, |_| |\/| 4 3|\| ( ! ( 10|> 3 |-| |) ! 4 1! \/ .- 3 3 6 .- 47|_| ! 74, |> |-| 3! 74 |> 0.- |> 355042 ( 0|\/| 0 \/ 0( 3 |-| 3|\/| |\/| 4! 2 |) 3 200 ! |) ! 0|\/| 42 !

### Parte 3
Adicione um switch para que o usuário selecione a complexidade, por exemplo: 
```
$ python leet.py --difficulty 1
```
