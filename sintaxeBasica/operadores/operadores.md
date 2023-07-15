1. Operadores Aritméticos:
    + `+`: Soma dois valores.
    ```lua
    local a = 5
    local b = 3
    local resultado = a + b -- resultado será 8
    ```
    + `-`: Subtrai um valor de outro.
    ```lua
    local a = 10
    local b = 4
    local resultado = a - b -- resultado será 6
    ```
    + `*`: Multiplica dois valores.
    ```lua
    local a = 3
    local b = 6
    local resultado = a * b -- resultado será 18
    ```
    + `/`: Divide um valor pelo outro.
    ```lua
    local a = 10
    local b = 2
    local resultado = a / b -- resultado será 5
    ```
    + `%`: Retorna o resto da divisão entre dois valores.
    ```lua
    local a = 10
    local b = 3
    local resultado = a % b -- resultado será 1
    ```
    + `^`: Calcula a potência de um valor.
    ```lua
    local a = 2
    local b = 3
    local resultado = a ^ b -- resultado será 8
    ```
2. Operadores de Comparação:
    + `==`: Verifica se dois valores são iguais.
    ```lua
    local a = 5
    local b = 5
    local igual = (a == b) -- igual será true
    ```
    + `~=`: Verifica se dois valores são diferentes.
    ```lua
    local a = 10
    local b = 5
    local diferente = (a ~= b) -- diferente será true
    ```
    + `<`: Verifica se um valor é menor que o outro.
    ```lua
    local a = 3
    local b = 6
    local menor = (a < b) -- menor será true
    ```
    + `>`: Verifica se um valor é maior que o outro.
    ```lua
    local a = 8
    local b = 4
    local maior = (a > b) -- maior será true
    ```
    + `<=`: Verifica se um valor é menor ou igual ao outro.
    ```lua
    local a = 4
    local b = 4
    local menorIgual = (a <= b) -- menorIgual será true
    ```
    + `>=`: Verifica se um valor é maior ou igual ao outro.
    ```lua
    local a = 7
    local b = 7
    local maiorIgual = (a >= b) -- maiorIgual será true
    ```
3. Operadores Lógicos:
    + `and`: Retorna verdadeiro se as duas expressões forem verdadeiras.
    ```lua
    local a = true
    local b = false
    local resultado = (a and b) -- resultado será false
    ```
    + `or`: Retorna verdadeiro se pelo menos uma das expressões for verdadeira.
    ```lua
    local a = true
    local b = false
    local resultado = (a or b) -- resultado será true
    ```
    + `not`: Inverte o valor de uma expressão lógica.
    ```lua
    local a = true
    local resultado = not a -- resultado será false
    ```
4. Operadores de Concatenação:
    + `..`: Concatena duas strings.
    ```lua
    local string1 = "Olá"
    local string2 = "mundo!"
    local resultado = string1 .. " " .. string2
    print(resultado) -- irá imprimir "Olá mundo!"
    ```
5. Operadores de Atribuição:
    + `=`: Atribui um valor a uma variável.
    ```lua
    local x = 10
    ```
    + `+=`, `-=`, `*=`, `/=`: Realiza uma operação aritmética e atribui o resultado a uma variável.
    ```lua
    local x = 5
    x += 3 -- equivalente a x = x + 3, x será 8

    local y = 10
    y -= 2 -- equivalente a y = y - 2, y será 8

    local z = 3
    z *= 4 -- equivalente a z = z * 4, z será 12

    local w = 10
    w /= 5 -- equivalente a w = w / 5, w será 2
    ```
6. Operadores de comprimento:
    + `#`: Retorna o comprimento de uma string ou tabela.
    ```lua
    local texto = "Olá, Lua!"
    local tamanho = #texto
    print(tamanho) -- irá imprimir 10

    -- array
    local tabela = {10, 20, 30, 40, 50}
    local tamanho = #tabela
    print(tamanho) -- irá imprimir 5
    ```
7. Operadores de Tabela:
    + `.`: Acessa um campo específico em um tabela.
    + `[]`: Acessa um elemento em um uma tabela usando uma chave.
    ```lua
    local pessoa = {nome = "João", idade = 30}
    print(pessoa.nome) -- imprime "João"
    print(pessoa["idade"]) -- imprime 30
    ```
