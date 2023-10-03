let produtos = [];
let pessoas = [];

function cadastrarProduto() {
  let produto = prompt('Digite o nome do produto:');
  produtos.push(produto);
}

function cadastrarPessoa() {
  let pessoa = prompt('Digite o nome da pessoa:');
  pessoas.push(pessoa);
}

function sortear() {
  const numeroSorteado = Math.floor(Math.random() * produtos.length);
  const produtoSorteado = produtos[numeroSorteado];
  alert('A pessoa sorteada ganhou o produto: ' + produtoSorteado);
}

function exibirMenu() {
  let escolha;
  while (true) {
    escolha = prompt('Selecione uma opção:\n1. Cadastrar Produto\n2. Cadastrar Pessoa\n3. Sortear\n4. Sair\n');

    switch (escolha) {
      case '1':
        cadastrarProduto();
        break;
      case '2':
        cadastrarPessoa();
        break;
      case '3':
        sortear();
        break;
      case '4':
        return; // Encerra o loop
      default:
        alert('Opção inválida. Tente novamente.');
    }
  }
}

exibirMenu();
