# [M2S06] Ex 1 - Gerenciamento Loja
```
Vamos criar um sistema para o gerenciamento de uma Loja, cada exercício a seguir é parte do desenvolvimento do modelo conceitual desse sistema.

A loja deve ter vários produtos, cada produto tem um código que deve identificar o produto. Todos os produtos devem ter preço. O produto também deve possibilitar a entrada de um nome para o produto.
```
# [M2S06] Ex 2 - Funcionarios
```
O sistema também deve ter uma forma de guardar os funcionários, esses devem ter o nome, um identificador, salário base, e o CPF desse funcionário.

Lembrando que o campo salário deve ser numérico com 8 casas de unidade e 2 casas decimais.
```
# [M2S06] Ex 3 - Clientes Fidelizados
```
Devemos guardar os clientes fidelizados, esses também devem ter um nome, um identificador, data de nascimento, tempo de fidelização, bônus de fidelidade.

Ele também deve ter o nível de fidelidade:

Normal

Gold

Platinum

Black

Infinity

Essa fidelidade deve ser uma entidade separada com um id e o nome da fidelidade.
```
# [M2S06] Ex 4 - Relacionamentos
```
Vamos adicionar uma chave estrangeira de vendendor em produto. Nesse relacionamento devemos ter uma classes de Venda, que irá receber o id do produto e do vendedor e a quantidade de produtos vendidos.
```
# [M2S06] Ex 5 - Endereço Cliente
```
Vamos adicionar mais detalhes ao cliente fidelizado, adicione as informações de endereço a entidade de Cliente Fidelizado. Devemos ter a informação do logradouro do cliente, numero, estado e cidade.
```
# [M2S06] Ex 6 - Normalização Cliente
```
Realizar a normalização na classe de Cliente. - Devemos ter uma entidade Endereço após a normalização
```
# [M2S06] Ex 7 - Gerente
```
Crie agora uma entidade Loja e uma Entidade Gerente

A Loja deve receber um gerente e agora os funcionários vão ter a FK da Loja.
O Gerente deve herdar do Funcionário e deve ter um valor de bonus como atributo, esse bonus é por vendas realizadas no mês, por exemplo: 1000.
```
# [M2S06] Ex 8 - Defina as Formas Normais
```
Defina as primeiras 3 formas de normalização, com exemplos
```
# [M2S06] Ex 9 - Defina modelo conceitual
```
Defina modelagem conceitual de dados
```

# [M2S06] Ex 10 - Tipos de bancos de dados e SGBDs
```
Quais são os tipos de bancos de dados e defina quais são os SGBDs
```


