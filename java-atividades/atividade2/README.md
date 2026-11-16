## Atividades de Java — Programação Orientada a Objetos

## UML — Unified Modeling Language, Herança e Noções de Polimorfismo

## Orientações gerais
- Verifique todas as aulas antes de iniciar as atividades.
- Desenvolva cada atividade utilizando as três classes Java especificadas.
- Utilize uma classe adicional chamada Main exclusivamente para criar objetos e testar os métodos.
- Utilize a palavra-chave extends para implementar herança.
- Utilize super nos construtores das subclasses para inicializar os atributos herdados.
- Aplique encapsulamento utilizando atributos private e métodos get e set, quando necessários.
- Utilize @Override para identificar os métodos sobrescritos.
- Crie os objetos individualmente no método main, sem utilizar vetores ou listas de objetos.
- Não será necessário utilizar referências da superclasse para demonstrar polimorfismo.
- Elabore um diagrama UML de classes para cada atividade, apresentando o nome das classes, atributos com seus tipos, métodos com parâmetros e tipos de retorno, modificadores de visibilidade (+, -, #) e relacionamentos de herança.
- Utilize o diagrams.net (draw.io), StarUML ou outra ferramenta de modelagem para elaborar os diagramas.
- Organize os arquivos Java e os diagramas UML em pastas identificadas pelo número de cada atividade.
- Teste os programas e verifique se as regras estabelecidas estão sendo respeitadas.

## Atividade 1 — Sistema de Funcionários
Crie um sistema para cadastrar funcionários de uma empresa utilizando três classes:
- Funcionario — superclasse.
- Gerente — subclasse.
- Vendedor — subclasse.

# Atributos:
Classe Funcionario:
- nome
- salario
Classe Gerente:
- bonus
Classe Vendedor:
- comissao

# Métodos:
- calcularSalario()
- exibirDados()
  
# Instruções:
1. Implemente as três classes utilizando herança com extends.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método calcularSalario() nas classes Gerente e Vendedor utilizando @Override.
5. O gerente deverá receber o salário acrescido do bônus.
6. O vendedor deverá receber o salário acrescido da comissão.
7. No método main, crie um objeto da classe Gerente e outro da classe Vendedor.
8. Execute os métodos e apresente os salários calculados no terminal.
UML: desenhe o diagrama de classes contendo as três classes, seus atributos, métodos, modificadores de visibilidade e relacionamentos de herança.

## Atividade 2 — Sistema de Animais
Crie um sistema para representar diferentes animais utilizando três classes:
- Animal — superclasse.
- Cachorro — subclasse.
- Gato — subclasse.
  
# Atributos:
Classe Animal:
- nome
- idade
Classe Cachorro:
- raca
Classe Gato:
- cor

# Métodos:
- emitirSom()
- exibirDados()
  
## Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método emitirSom() nas classes Cachorro e Gato utilizando @Override.
5. O cachorro deverá emitir a mensagem "Au au!".
6. O gato deverá emitir a mensagem "Miau!".
7. No método main, crie um objeto da classe Cachorro e outro da classe Gato.
8. Execute os métodos e apresente os dados dos animais no terminal.
UML: desenhe o diagrama de classes, identificando os atributos, métodos e relacionamentos de herança.

## Atividade 3 — Sistema de Veículos
Crie um sistema para representar diferentes tipos de veículos utilizando três classes:
- Veiculo — superclasse.
- Carro — subclasse.
- Moto — subclasse.

# Atributos:
Classe Veiculo:
- marca
- modelo
- ano
Classe Carro:
- numeroPortas
Classe Moto:
- cilindradas

# Métodos:
- ligar()
- exibirInformacoes()
Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método ligar() nas classes Carro e Moto utilizando @Override.
5. O carro deverá apresentar a mensagem "Carro ligado!".
6. A moto deverá apresentar a mensagem "Moto ligada!".
7. No método main, crie um objeto da classe Carro e outro da classe Moto.
8. Execute os métodos e apresente as informações dos veículos no terminal.
UML: elabore o diagrama de classes com os atributos, métodos e relacionamentos de herança.

## Atividade 4 — Sistema de Produtos
Crie um sistema para controlar produtos de uma loja utilizando três classes:
- Produto — superclasse.
- ProdutoEletronico — subclasse.
- ProdutoAlimenticio — subclasse.

# Atributos:
Classe Produto:
- nome
- preco
Classe ProdutoEletronico:
- garantiaMeses
Classe ProdutoAlimenticio:
- dataValidade

# Métodos:
- calcularDesconto()
- exibirProduto()

## Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método calcularDesconto() nas subclasses utilizando @Override.
5. Os produtos eletrônicos deverão receber desconto de 10%.
6. Os produtos alimentícios deverão receber desconto de 5%.
7. No método main, crie dois objetos da classe ProdutoEletronico e dois objetos da classe ProdutoAlimenticio.
8. Exiba o nome, o preço original, o desconto e o preço final de cada produto.
UML: construa o diagrama das três classes, identificando atributos, métodos e relacionamentos de herança.

## Atividade 5 — Sistema Bancário
Crie um sistema bancário utilizando três classes:
- ContaBancaria — superclasse.
- ContaCorrente — subclasse.
- ContaPoupanca — subclasse.

# Atributos:
Classe ContaBancaria:
- titular
- saldo
Classe ContaCorrente:
- taxaSaque
Classe ContaPoupanca:
- taxaRendimento

# Métodos:
- depositar(double valor)
- sacar(double valor)
- exibirSaldo()

# Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Implemente o método depositar() na classe ContaBancaria.
5. Sobrescreva o método sacar() nas subclasses utilizando @Override.
6. Na conta corrente, cada saque deverá descontar também uma taxa fixa.
7. Na conta poupança, o saque deverá ocorrer sem cobrança de taxa.
8. No método main, crie um objeto da classe ContaCorrente e outro da classe ContaPoupanca.
9. Realize depósitos e saques e apresente os saldos atualizados.
UML: represente as três classes, seus atributos, métodos e relacionamentos de herança.

Regra: o saldo não poderá ficar negativo, e depósitos e saques deverão utilizar valores positivos.

# Atividade 6 — Sistema de Formas Geométricas
Crie um sistema para calcular áreas de figuras geométricas utilizando três classes:
- FormaGeometrica — superclasse abstrata.
- Circulo — subclasse.
- Retangulo — subclasse.

# Atributos:
Classe Circulo:
- raio
Classe Retangulo:
- base
- altura

# Métodos:
- calcularArea()
- exibirResultado()

# Instruções:
1. Crie a classe abstrata FormaGeometrica.
2. Declare o método abstrato calcularArea(), com retorno do tipo double.
3. Implemente as classes Circulo e Retangulo utilizando extends.
4. Utilize construtores para inicializar os atributos das subclasses.
5. Aplique encapsulamento utilizando private.
6. Sobrescreva o método calcularArea() nas duas subclasses utilizando @Override.
7. Para o círculo, utilize a fórmula: área = π × raio².
8. Para o retângulo, utilize a fórmula: área = base × altura.
9. No método main, crie um objeto da classe Circulo e outro da classe Retangulo.
10. Utilize o método exibirResultado() para apresentar as áreas calculadas.
UML: desenhe o diagrama de classes, identificando a classe abstrata, as subclasses, os atributos, os métodos e os relacionamentos de herança.

## Atividade 7 — Sistema de Biblioteca
Crie um sistema para representar diferentes materiais de uma biblioteca utilizando três classes:
- MaterialBiblioteca — superclasse.
- Livro — subclasse.
- Revista — subclasse.

# Atributos:
Classe MaterialBiblioteca:
- titulo
- anoPublicacao
Classe Livro:
- autor
Classe Revista:
- edicao

# Métodos:
- exibirInformacoes()
- calcularPrazoEmprestimo()

# Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método calcularPrazoEmprestimo() nas subclasses utilizando @Override.
5. Os livros poderão ser emprestados por 14 dias.
6. As revistas poderão ser emprestadas por 7 dias.
7. No método main, crie dois objetos da classe Livro e dois objetos da classe Revista.
8. Apresente as informações e os prazos de empréstimo de cada material.
UML: represente as classes, seus atributos, métodos e relacionamentos de herança.

## Atividade 8 — Sistema de Pagamentos
Crie um sistema para representar diferentes formas de pagamento utilizando três classes:
- Pagamento — superclasse.
- PagamentoPix — subclasse.
- PagamentoCartao — subclasse.

# Atributos:
Classe Pagamento:
- valor
Classe PagamentoPix:
- chavePix
Classe PagamentoCartao:
- numeroParcelas

# Métodos:
- processarPagamento()
- exibirComprovante()
  
# Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método processarPagamento() nas subclasses utilizando @Override.
5. No pagamento por Pix, apresente a mensagem "Pagamento via Pix realizado".
6. No pagamento por cartão, apresente a mensagem "Pagamento via cartão realizado".
7. No método main, crie um objeto da classe PagamentoPix e outro da classe PagamentoCartao.
8. Execute os métodos e apresente os comprovantes no terminal.
UML: elabore o diagrama de classes com os atributos, métodos e relacionamentos de herança.

## Atividade 9 — Sistema de Dispositivos Eletrônicos
Crie um sistema para controlar dispositivos eletrônicos utilizando três classes:
- Dispositivo — superclasse.
- Televisao — subclasse.
- Computador — subclasse.

# Atributos:
Classe Dispositivo:
- marca
- ligado
Classe Televisao:
- canal
Classe Computador:
- sistemaOperacional

# Métodos:
- ligar()
- desligar()
- exibirEstado()

# Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Implemente os métodos ligar() e desligar() na classe Dispositivo.
5. Sobrescreva o método ligar() nas subclasses utilizando @Override.
6. Ao ligar a televisão, apresente a mensagem "Televisão ligada no canal informado".
7. Ao ligar o computador, apresente a mensagem "Computador iniciando o sistema operacional".
8. No método main, crie um objeto da classe Televisao e outro da classe Computador.
9. Demonstre o funcionamento dos métodos ligar(), desligar() e exibirEstado().
UML: construa o diagrama de classes, identificando atributos, métodos, modificadores de visibilidade e relacionamentos de herança.

# Atividade 10 — Sistema de Transporte
Crie um sistema para representar diferentes meios de transporte utilizando três classes:
- Transporte — superclasse.
- Onibus — subclasse.
- Bicicleta — subclasse.

# Atributos:
Classe Transporte:
- modelo
- capacidadePassageiros
Classe Onibus:
- tarifa
Classe Bicicleta:
- tipo

# Métodos:
- mover()
- exibirInformacoes()
  
# Instruções:
1. Implemente as três classes utilizando herança.
2. Utilize construtores para inicializar os atributos.
3. Aplique encapsulamento utilizando private.
4. Sobrescreva o método mover() nas subclasses utilizando @Override.
5. O ônibus deverá apresentar a mensagem "Ônibus transportando passageiros".
6. A bicicleta deverá apresentar a mensagem "Bicicleta em movimento".
7. No método main, crie dois objetos da classe Onibus e dois objetos da classe Bicicleta.
8. Execute os métodos e apresente as informações de cada objeto no terminal.
UML: represente as três classes em um diagrama, identificando atributos, métodos, modificadores de visibilidade e relacionamentos de herança.




