//comparação de igualdade let a = 1 let b = 2 let c = 3 let d = '1'

//COMPARAÇÃO DE IGUALDADE

// = atribui valor, == comparação de valor, === valor e tipo let valor = a == d console.log (valor) let valorTipo = a === d console.log(valorTipo)

//maior let maior = a > b console.log(maior)

//maior e igual let maior_igual = a >= b console.log(maior_igual)

//Maior e igual e mesmo tipo let maior_igual_tipo = a >= b && typeof(a) === typeof(b) console.log(typeof(b)) console.log(maior_igual_tipo)

//menor let menor = a < b console.log(menor)

//menor e igual let menor_igual = a <= b console.log(menor_igual)

//diferente let diferente = a != b console.log(diferente)

//valor e tipo diferente let diferente_tipo = a !== d console.log(diferente_tipo)

//COMBINADO

//E ou AND ou & ou && let operador_end = a < b && b < c // 1 < 2 e 2 < 3 console.log (operador_end)

//OU ou OR ou | ou || let operador_or = a < b || b < c // 1 < 2 ou 2 < 3 console.log(operador_or)

function nota(nota){ //Se o aluno tirou a nota acima de 8 ele esta aprovado //Caso contrario reprovado if(nota >= 8){ return 'APROVADO'
}else{ return 'REPROVADO' } } console.log(nota(9))

function notrecuperacao(nota){ //se o aluno tirou 8 = aprovado //se tirou acima de 7 e menos de 8 = recuperação //caso contrario reprovado if(nota >=8){ return 'RECUPERAÇÃO' } else{ return 'REPROVADO' } } console.log(notrecuperacao(10))
