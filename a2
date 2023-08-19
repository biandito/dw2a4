function Produto (nome,descricao,preco,codigoDeBarras) {
    this.nome;
    this.descricao;
    this.codigoDeBarras;
}

this.getNome = function(){
    return this.nome
};

this.setNome = function (novoNome) {
this.nome = novoNome

};
this.getDescricao = function(){
    return this.descricao
};

this.setDescricao = function (novaDescricao) {
this.descricao = novaDescricao 

};
this.getPreco = function(){
    return this.preco
};

this.setDescricao = function (novoPreco) {
this.preco = novoPreco 

};
{

}

// desconto
Produto.prototype.calculaDesconto = function(porcentagemDesconto) {
  const desconto = (porcentagemDesconto / 100) * this.preco;
  return this.preco - desconto;
};

// aumenta preço 
Produto.prototype.aumentaPreco = function(porcentagemAumento) {
  const aumento = (porcentagemAumento / 100) * this.preco;
  return this.preco + aumento;
};

// produtos
const cereal = new Produto("Cereal", "Cereal Matinal", 5, "123");
const geleia = new Produto("Geleia", "Morango", 3, "456");
const pao = new Produto("Pão", "Francês", 2, "789");

// teste
console.log(cereal.calculaDesconto(10));
console.log(cereal.aumentaPreco(5));

