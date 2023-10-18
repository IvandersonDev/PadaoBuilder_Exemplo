# Exemplo de Construção de Sanduíches em Java

Este é um exemplo simples de implementação do padrão Builder em Java para criar sanduíches de acordo com as regras especificadas. Neste exemplo, os clientes podem construir sanduíches com diferentes tipos de pão, recheios, molhos e extras.

## Como Funciona

O projeto é composto por três classes principais:

1. **Sanduiche**: Representa um sanduíche com informações sobre o tipo de pão, recheio, molhos e extras. Ele também possui um método para imprimir os detalhes do sanduíche.

2. **SanduicheBuilder**: É a classe que permite construir os sanduíches passo a passo. Você pode definir o tipo de pão, recheio, adicionar molhos e escolher um extra. Em seguida, pode criar um objeto `Sanduiche` com essas configurações.

3. **Main**: O arquivo `Main.java` demonstra exemplos de criação de sanduíches com diferentes combinações de tipos de pão, recheios, molhos e extras.

## Como Executar

Para executar o exemplo, siga estas etapas:

1. Certifique-se de que você tenha o Java instalado em seu sistema.

2. Compile os arquivos do projeto, incluindo `Sanduiche.java`, `SanduicheBuilder.java` e `Main.java`.

3. Execute o arquivo `Main.java`.

```bash
javac Sanduiche.java SanduicheBuilder.java Main.java
java Main

Sanduiche sanduiche4 = builder.setTipoPao("Italiano")
                              .setRecheio("camarão")
                              .addMolho("Mostarda")
                              .addMolho("Ketchup")
                              .setExtra("bacon")
                              .build();
sanduiche4.imprimirSanduiche();
```
## Contribuições
Se você deseja contribuir para este projeto, sinta-se à vontade para criar uma "pull request" ou abrir uma "issue" com sugestões ou correções
