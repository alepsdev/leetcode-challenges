# LeetCode Challenges

Este projeto contém soluções para vários desafios do LeetCode implementados em Java usando Maven. Cada desafio é organizado em uma pasta numerada de acordo com o número do problema no LeetCode, contendo a solução e os testes correspondentes.

## Estrutura do Projeto

```
leetcode-challenges
├── src
│   ├── main
│   │   └── java
│   │       └── com
│   │           └── alepizzetti
│   │               └── challenges
│   │                   ├── p001
│   │                   │   └── Solution.java
│   │                   └── ...
│   └── test
│       └── java
│           └── com
│               └── alepizzetti
│                   └── challenges
│                       ├── p001
│                       │   └── SolutionTest.java
│                       └── ...
├── pom.xml
└── README.md
```

## Como adicionar um novo desafio

1. Crie uma nova pasta para o problema, por exemplo, `p123` para o problema 123:
   - `src/main/java/com/alepizzetti/challenges/p123/Solution.java`
   - `src/test/java/com/alepizzetti/challenges/p123/SolutionTest.java`
2. Implemente a solução na classe `Solution` dentro da pasta do problema.
3. Implemente os testes na classe `SolutionTest` correspondente.

## Como rodar os testes

```
mvn test
```

## Contribuição

Sinta-se à vontade para contribuir adicionando novos desafios ou melhorando as soluções existentes. Certifique-se de que todo novo código esteja acompanhado de testes adequados.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.