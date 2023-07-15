<a name="variaveis"></a>1. Declaração de Variáveis:
    + Em Lua, as variáveis são declaradas usando a palavra-chave "local" seguida pelo nome da variável.
    + Exemplo: `local nome`
    + Variável numérica:
    ```lua
    local idade = 25
    ```
    + Variável de texto (string):
    ```lua
    local nome = "Felipi"
    ```
    + Variável booleana:
    ```lua
    local isAtivo = true
    ```
    + Variável vazia (nil):
    ```lua
    local valor = nil
    ```
    + Variável de tabela:
    ```lua
    local lista = {1, 2, 3, 4, 5}
    ```
    + Variável de função:
    ```lua
    local function somar(a, b)
       return a + b
    end
    ```
    + Variável global:
    ```lua
    valorglobal = 10
    ```
2. Atribuição de valores:
    + Após declarar uma variável, você pode atribuir um valor a ela usando o operador de atribuição "=", que armazena o valor na variável.
    + Exemplo: `nome = "João"`
3. Tipos de Dados:
    + Lua é uma linguagem dinamicamente tipada, o que significa que as variáveis não possuem um tipo fixo.
    + Alguns tipos de dados comuns em Lua incluem: nil, booleano, número, string, tabela e função.
4. Tipagem Automática:
    + As variáveis em Lua são tipadas automaticamente, o que significa que você não precisa especificar explicitamente o tipo ao declará-las.
    + O tipo de uma variável é determinado pelo valor atribuído a ela.
5. Convenções de Nomenclatura:
    + É recomendado usar nomes de variáveis em letras minúsculas, com palavras separadas por underline (_) para melhor legibilidade.
    + Exemplo: `idade_do_usuario`
6. Escopo das Variáveis:
    + Uma variável declarada com a palavra-chave "local" tem escopo local e só pode ser acessada dentro do bloco de código em que foi declarada.
    + Variáveis declaradas sem a palavra-chave "local" têm escopo global e podem ser acessadas em qualquer lugar do programa.
7. Concatenação de Variáveis:
    + Para concatenar strings e outras variáveis, você pode usar o operador de concatenação "..".
    + Exemplo: `mensagem = "Olá, " .. nome`
8. Uso de Variáveis:
    + Você pode usar variáveis em expressões matemáticas, condições, loops, chamadas de função e outros lugares onde valores são necessários.
9. Nil e Verificação de Nulos:
    + O valor "nil" é usado para representar a ausência de valor em Lua.
    + Para verificar se uma variável é nula, você pode usar a estrutura de controle "if" em conjunto com a palavra-chave "nil".
10. Destruição de Variáveis:
    + Lua possui coleta de lixo automática, então as variáveis não precisam ser explicitamente destruídas. A memória é liberada quando a variável não é mais referenciada.
