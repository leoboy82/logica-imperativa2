# logica-imperativa2

Claro! Abaixo está o exemplo em formato Markdown (.md):

```markdown
## Alocar pessoas no restaurante

Para alocar corretamente as pessoas em diferentes áreas do restaurante, vamos seguir as seguintes regras:

1. Grupos de **5 ou mais pessoas** serão alocados no **1º andar**.
2. Clientes **fumantes** ou com **animais de estimação** serão alocados na **área externa**.
3. Outros grupos de pessoas serão alocados no **térreo**.

### Pseudocódigo:

```plaintext
Algoritmo AlocarNoRestaurante
    // Perguntar sobre a quantidade de pessoas no grupo
    Escrever("Quantas pessoas estão no grupo?")
    Ler(quantidadeDePessoas)

    // Perguntar sobre fumantes ou animais de estimação
    Escrever("Algum dos clientes é fumante ou tem animais de estimação? (S/N)")
    Ler(respostaFumanteAnimais)

    // Verificar a área de alocação de acordo com as respostas
    Se (quantidadeDePessoas >= 5) Então
        Escrever("Você será alocado no 1º andar.")
    Senão
        Se (respostaFumanteAnimais == "S") Então
            Escrever("Você será alocado na área externa.")
        Senão
            Escrever("Você será alocado no térreo.")
        Fim Se
    Fim Se

Fim Algoritmo
```

Neste pseudocódigo, utilizamos estruturas condicionais (Se-Senão) para determinar a área de alocação de acordo com as respostas fornecidas. Primeiro, perguntamos quantas pessoas estão no grupo e armazenamos a resposta na variável `quantidadeDePessoas`. Em seguida, perguntamos se há algum fumante ou animal de estimação no grupo e armazenamos a resposta na variável `respostaFumanteAnimais`.

Depois, com base nas respostas, determinamos a área de alocação conforme as regras do restaurante. Essa lógica permite alocar corretamente os clientes em uma das três áreas disponíveis no restaurante: térreo, 1º andar ou área externa.
```

