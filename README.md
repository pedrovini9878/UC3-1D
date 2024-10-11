# Caderno virtual - Lógica da Programação e Algoritmos
Boas vindas! Este é seu caderno virtual. Aqui você deverá guardar todos os conceitos aprendidos e atiuvidades dessa unidade curricular. 


## Conteúdo Técnico
Escreva aqui os conteúdos aprendidos.



## Atividades desenvolvidas
Escreva aqui as atividades desenvolvidas em sala e para casa. Você pode detelhar a atividade e usar links das atividades do codepen e vídeos desenvolvidos em sala. 
```js
const nome = prompt ("qual o seu nome")
const lanche = prompt("diga seu lanche")

const combo = prompt ('deseja comprar nosso combo feliz?')
if(combo == 'sim') {
  console.log(`parabens ${nome},voce ganhou um, brinde`)
}
console.log("muito obrigado,volte sempre!")
// Caderno Virtual
const cadernoVirtual = {
  // String: Nome do Caderno
  titulo: "Meu Caderno Virtual",

  // Number: Número de páginas
  numeroDePaginas: 100,

  // Boolean: Se está completo ou não
  estaCompleto: false,

  // Object: Dados do autor
  autor: {
    nome: "João Silva",
    idade: 25,
    profissão: "Estudante"
  },

  // Array: Lista de notas (páginas do caderno)
  paginas: [
    { pagina: 1, conteudo: "Introdução ao JavaScript" },
    { pagina: 2, conteudo: "Tipos de dados em programação" },
    { pagina: 3, conteudo: "Operadores e expressões" }
  ]
};

// Acessando os dados
console.log(cadernoVirtual.titulo); // "Meu Caderno Virtual"
console.log(cadernoVirtual.numeroDePaginas); // 100
console.log(cadernoVirtual.estaCompleto); // false
console.log(cadernoVirtual.autor.nome); // "João Silva"
console.log(cadernoVirtual.paginas[0].conteudo); // "Introdução ao JavaScript"

String: "Meu Caderno Virtual" é o título do caderno.
Number: 100 é o número de páginas.
Boolean: false indica se o caderno está completo ou não.
Object: O objeto autor contém informações sobre o autor do caderno.
Array: A array paginas armazena objetos, representando as diferentes páginas com seus conteúdos.
```
