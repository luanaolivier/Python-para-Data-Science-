# AULA 1 COMEÇANDO COM PYTHON

### Python para Data Science
Este repositório contém meus estudos iniciais em Python aplicados à análise de dados.

### Ferramentas utilizadas
- Python
- Google Colab

### Objetivo
Aprender e práticar conceitos de análise de dados e inteligência artificial.

### Python
O que é python? Linguagem de programação de alto nível. Interpretada orientada a objetos 
Quem criou? Guido Van Rossum em 1989 

## Para que serve 
Desenvolvimento web. Ciência de dados. Machine Learning. Automação de tarefas. Análise de dados.

## Google Colab 
Ferramenta do google que permite escrever e executar cod em python, ele funciona usando uma máquina virtual. 

## Comentário 
Comentário de uma linha - são comentários feitos adicionando o # no inicio de uma linha de código. Tudo o que vier depois do símbolo # será considerado um comentário. 

Comentário de várias linhas - são feitos usando um conjunto de aspas triplas ''' ou """ Tudo que estiver dentro delas será consderado comentário.

# AULA 2 - MANIPULANDO DADOS NO PYTHON

### Variáveis
Um nome associado a um valor. Se queremos acessar esse valor, dado ou informação, precisamos recorrer ao seu nome: a variavel. Exemplo, a idade do aluno é 5 - então a variavel será 'idade' e o valor dessa variavel é '5'.   No código ficará idade = 5 | utilizando a função print(idade) e a resposta será 5. 

## Tipos de variáveis
clase int - armazena números inteiros, positivo e negativo - exp: 1, 2, 3, 100 ou -5, -6, -9 

classe float - Armazena números flutuantes, números que possuem uma parte fracionada ou reais, números com virgula - exp: 3.14, 100.0 ou -0.5

classe str - Armazena strings, ou seja um texto ou sequencia de caracteres. As strings são geralmente usadas para armazenar textos e são delimitadas por aspas simples ou duplas - exp: "Olá!" , 'Aluno' ou "1234"

classe bool - Armazena valores logicos verdadeiros ou falsos. Variaveis booleanas.Sempre a primeira letra maiuscula True False - exp: True e False

## Função Type
A função type() pode ser útil para verificar o tipo de dado de uma variavel e determinar a melhor forma de manipular ou processar os dados. Para trabalhar com estatística em dados financeiros podemos verificar se os dados que temos são valores numéricos utilizando type - essa função retorna uma classe que representa o tipo de objeto passado como argumento. Dessa forma podemos usar o type para entender o tipo de dado que temos e ajusta-lo conforme a necessidade de uma análise. 

### Strings 
Formada por texto com aspas simples ' ' ou aspas duplas " ". Usamos str como string 
Os métodos são funções associadas a objetos em python. Usamos muita manipulaçãp dos objetos por isso os métodos são importantes. Alguns métodos: 

* variavel.upper() = PARA DEIXAR O TEXTO EM MAIUSCULO
* variavel.lower() = para deixar o texto em minusculo
* variavel.strip() = remove os espaços em branco
* variavel.replace('antigo','atual') = para corrigor algo que está escrito errado por exemplo, coloca o que será corrigido no caso o antigo e por qual vai ser trocado atual.

Essas ferramentas são básicas para "limpar" e "organizar" as informações básicas que chegam ao banco e dados. 

### Coletando Dados
* input() = É uma caixa de perguntas, que aparece na tela para digitarmos a resposta - mas no caso nós que faremos a pergunta. Ela espera que a pessoa digite algo e aperte o "enter". Tudo que é digitado é coletado e o input nos devolve essa informação.

Para usar o input, precisamos de um lugar para guardar a informação que o usuario digitou, nesse caso será uma variavel. 
Exeplo; nome = input () - nome é a variavel.

Para que o usuario saiba o que digitar, preciso colocar uma mensagem dentro do parenteses do input().
Exemplo; nome = input ('Escreva seu nome:') - a mensagem vai aparecer na tela e a pessoa vai digitar o nome.

O input sempre devolve string, que são textos.

Existem funções para conversão de valores:
* Inteiros, numeros inteiros: int() 
* Float para numeros com . : float()
* String: str(dado_para_conversao)
* Booleano: bool(dado_para_conversao)

Aprendi a utilizar a formatação f-string (ou formatação de string), na qual colocamos um f antes da criação da string e as variáveis entre chaves {}. 
Exemplo: 
nome = input('Escreva seu nome:')
idade = input('Qual sua idade?')
altura = float(input('Qual sua altura?'))
print(f'Olá {nome}, você tem {idade} anos e mede {altura} metros!')

O input é uma função, que faz a pergunta ao usuario e guarda essa informação.O input() sempre retorna um texto, uma string, mesmo que o usuario digite um numero, o python entende o numero como texto - é aqui que o int() entra, essa função converte um texto em número inteiro. então quando usamos int(input()) estamos dizendo "pegue o que o usuario digitou (input) e transforme isso em um número inteiro (int)

# AULA 3 - ESTRUTURAS CONDICIONAIS

### O que são estruturas condicionais? 
Permitem a execução de instruções por uma condição, se for verdadeira alguma instrução será rodada - se for FALSA outra instrução será rodada. 

* SE condição : instruções caso a condição seja VERDADEIRA
* SENÃO : instruções caso a condição seja FALSA

### IF = 
