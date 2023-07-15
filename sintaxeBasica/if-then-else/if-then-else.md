No Lua, a estrutura condicional "if-then-else" é usada para tomar decisões com base em uma condição. Ela permite executar diferentes blocos de código dependendo do resultado dessa condição. Aqui está um exemplo básico de como usar o "if-then-else" em Lua:
```lua
local idade = 18

if idade >= 18 then
    print("Você é maior de idade.")
else
    print("Você é menor de idade.")
end
```
Nesse exemplo, a variável `idade` é definida como 18. A estrutura "if-then-else" avalia a condição `idade >= 18`. Se essa condição for verdadeira, o bloco de código dentro do `if` será executado e a mensagem "Você é maior de idade." será impressa. Caso contrário, o bloco de código dentro do `else` será executado e a mensagem "Você é menor de idade." será impressa.

Você também pode ter múltiplas condições usando "elseif" para lidar com casos adicionais. Veja o exemplo a seguir:
```lua
local nota = 85

if nota >= 90 then
    print("Você obteve uma nota A.")
elseif nota >= 80 then
    print("Você obteve uma nota B.")
elseif nota >= 70 then
    print("Você obteve uma nota C.")
else
    print("Você obteve uma nota abaixo de C.")
end
```
Nesse exemplo, o código avalia a variável `nota` e imprime a mensagem correspondente de acordo com a faixa de notas. Se a nota for maior ou igual a 90, a mensagem "Você obteve uma nota A." será impressa. Se a nota estiver entre 80 e 89, a mensagem "Você obteve uma nota B." será impressa, e assim por diante. Se nenhuma das condições anteriores for atendida, a mensagem "Você obteve uma nota abaixo de C." será impressa.
