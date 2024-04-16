# Somatorio

# Soma de Números Pares até 500

Este programa em C calcula a soma de todos os números pares até o limite de 500.

## Requisitos

Para compilar e executar este programa, é necessário um compilador C instalado no seu sistema. Você pode usar o GCC ou outro compilador de sua preferência.

## Como Usar

1. Clone este repositório ou baixe o arquivo `codigo.c`.
2. Abra um terminal e navegue até o diretório onde o arquivo `codigo.c` está localizado.
3. Compile o código-fonte usando o seguinte comando:

    ```
    gcc codigo.c -o soma_numeros_pares
    ```

4. Execute o programa recém-compilado:

    ```
    ./soma_numeros_pares
    ```

5. O programa calculará a soma de todos os números pares até 500 e exibirá o resultado.

## Exemplo

```
Numeros pares existentes até 500
125250
```

## Observações

- Este programa utiliza um loop `for` para percorrer todos os números de 1 a 500.
- Para cada número no intervalo, verifica se é par utilizando o operador `%`.
- Se o número for par, ele é somado à variável `soma`.
- Ao final do loop, a soma total dos números pares é exibida.

