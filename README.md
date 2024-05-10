function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
  function facaCompras(livroA, livroB) {

  let soma = livroA + livroB;
  console.log("A soma dos preços dos livros é: R$ " + soma + ",00");
}

facaCompras(50, 50);
facaCompras(72, 28); 

}
