
##  Do Java ao JS: Partindo da visão Orientada à Objetos para o Paradigma Funcional

*Entenda a Programação Funcional utilizando analogia aos conceitos e aspectos da Programação Orientada à Objetos*

### Diferenças entre paradigmas

Independente do Paradigma de Programação adotado, é constatado que todos possuem conceitos sobre a forma de fazer o desenvolvimento das aplicações, recomendações de tecnicas de desenvolvimento em particular e utilização padrões para a construção de um código/software considerado de qualidade. Na Programação Funcional não é diferente. 
Esses conceitos do paradigma, padrões e técnicas utilizadas serão discutidas ao longo do texto utilizando como referência uma ideia existente na programação orientada a objetos e como esta é tratada na programação funcional. 

### Introdução à Programação Funcional

De forma simplificada, aprendemos que na visão Orientada à Objetos devemos tratar as partes integrantes do sistema como representações de classes que irão compor os chamados objetos, estes objetos são instâncias de uma classe e possuem características e serviços específicos, partindo de quatro pilares principais: abstração, encapsulamento, herança e polimorfismo.
Esses pilares nos quais a orientação à objetos baseia-se estão relacionados à adoção de uma espécie de representação do mundo real ao realizar a modelagem da solução. 

Diferente desta visão onde o foco do software está voltado em objetos e como estes tentam mapear o mundo real para o computacional, temos o conceito de programação funcional: 

>   A programação funcional é entendida como um paradigma que visa a criação de soluções geradas à partir de funções obedientes à definição matemática, sendo caracterizadas por possuir uma entrada e saída de dados bem definidas, com a presença da imutabilidade nos dados trabalhados, promovendo a diminuição/exclusão de *side-effects* nas aplicações.

Em contrapartida ao que chamamos de pilares da programação orientada à objetos, existem alguns conceitos gerais que são fundamentais para programação funcional. São os conceitos de *pure functions*, *first class*, *high-order functions* e *function composition*.

### Orientação à Objetos vs Programação Funcional: Conceitos fundamentais  

> ***Pure functions***: uma função é dita pura se esta executa uma única ação bem definida e não realiza alterações fora do seu escopo. 

Desta maneira, podemos inferir que nenhuma modificação da estrutura que a evocou ou operação de I/O (*Input/Output*) é permitida nessa classificação. Dentro deste contexto podemos fazer uma comparação ao que chamamos de Encapsulamento no mundo OO (*Object Oriented*). 

O encapsulamento é a técnica utilizada para segurança no acesso e modificação dos recursos nos sistemas orientados à objetos, promovendo a ocultação dos detalhes de funcionamento dos serviços disponíveis. Esta técnica no mundo de FP(*Functional Programming*) pode ser associado ao conceito de *Pure Function*, uma vez que uma função pura não modifica o objeto que que faz a chamada da função à ser executada, têm um objetivo claro de funcionamento e trabalha com dados imutáveis, de forma a mostrar uma mesma saída a parâmetros iguais, promovendo um ambiente fechado com relação à efeitos colaterais. 

> ***First Class***: 

### Referências

WARBURTON, Richard. **Object-Oriented vs. Functional Programming: Bridging the Divide Between Opposing Paradigms**. 1ª edição. Califórnia: O’Reilly Media, 2006.

**Programação Funcional**. Wikipédia. Disponível em: <https://pt.wikipedia.org/wiki/Programação_funcional>. Acesso em: 02 mai. 2018.

**Functional programming paradigms in modern JavaScript: Pure functions**. Hackermoon. Disponível em: <https://hackernoon.com/functional-programming-paradigms-in-modern-javascript-pure-functions-797d9abbee1>. Acesso em: 09 mai. 2018.
