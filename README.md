# Desafio1-Logica
Questão desafio 1 de lógica para computação.  

Os arquivos com nome "teste" são modificações feitas pra consertar erros e serão excluídos a posteriori.

Dicionário do desafio:
	Os conectivos lógicos são representados por: v,^,~,> e <>. Elas significam, respectivamente: OU, E, NÃO, SE, SE E SOMENTE SE.
	Os elementos lógicos são representados UNICAMENTE por letras MAIÚSCULAS.
	Os elementos \"True e False\" são representados, respectivamente, pelas letras minúsculas \'t\' e \'f\'.
	O Conectivo de NEGAÇÃO deve antes do que se deseja ser negado: ~P ou ~(P^Q).
	A frase deverá ser escrita de maneira contínua, ou seja, sem utilização do espaço na demarcação da mesma.

EXPLICAÇÃO DE FUNCIONAMENTO:
O programa exerce a função de classificar os caracteres que são possíveis dentro
dele e, com base nisso, faz comparações dos caracteres com aqueles que estão em
seguida na String, verificando se aquele caractér seguinte faz sentido e é válido
propositalmente em seguida.

Verificações:
1: Depois de um símbolo proposicional (P,Q,R,S) ou de um símbolo de verdade
(True e false), só podem aparecer: fechamento de parênteses ')' ou um conectivo.
2: Depoiis de um símbolo de conectivo, só pode aparecer 4 tipos de símbolos:
De proposição (P,Q,R), de verdade (True, False), '(' (abertura de parênteses) e
símbolo de negação ('~').
3: O símbolo de bicondição, no programa, foi expresso por <>. Caso após o char 
'<' não vier '>', o programa dá erro direto.
4:Depois de '(', só pode vir ou outro '(', um Símbolo proposicional (P,Q), um 
símbolo de verdade (True, false) ou o conectivo de negação ('~')
4.1:Depois de ')', só pode vir outro ')' ou um conectivo proposicional.
4.2:Existe um contador de parênteses, e caso tenho mais abertura de parênteses do
que fechamentos, ou vice versa, ele indica erro.
5:Após o conectivo de negação ('~'), só pode vir em seguida outro '~' ou um símbolo
proposicional/ de verdade, ou um '(' 
