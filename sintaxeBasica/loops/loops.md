+ Loop while:
O loop `while` executa um bloco de código repetidamente enquanto uma condição for verdadeira.
```lua
local contador = 1
while contador <= 5 do
   print(contador)
   contador = contador + 1
end
```
Nesse exemplo, o bloco de código dentro do loop `while` será executado enquanto a condição `contador <= 5` for verdadeira. A cada iteração, o valor de `contador` é incrementado em 1.

+ Loop `repeat-until`:
O loop `repeat-until` executa repetidamente um bloco de código até que uma condição seja verdadeira.
```lua
local contador = 1
repeat
   print(contador)
   contador = contador + 1
until contador > 5
```
Nesse exemplo, o bloco de código dentro do loop `repeat` será executado pelo menos uma vez e continuará sendo executado até que a condição `contador > 5` seja verdadeira. A cada iteração, o valor de `contador` é incrementado em 1.

+ Loop `for`:
O loop `for` é usado para iterar sobre uma sequência específica de valores.
```lua
for i = 1, 5 do
   print(i)
end
```
Nesse exemplo, o loop `for` itera de 1 a 5, atribuindo cada valor a `i`, e executa o bloco de código dentro do loop para cada valor de `i`.

+ Loop `for in ipairs`:
O loop `for in ipairs` é usado para iterar sobre os elementos numerados de uma tabela sequencial.
```lua
local lista = {"maçã", "banana", "laranja"}
for indice, valor in ipairs(lista) do
   print(indice, valor)
end
```
Nesse exemplo, o loop `for in ipairs` itera sobre os elementos da tabela lista e atribui o índice do elemento a `indice` e o valor do elemento a `valor`. O bloco de código dentro do loop é executado para cada elemento da tabela sequencial.

+ Loop `for in pairs` (Loop genérico):
O loop `for in pairs` é usado para iterar sobre todos os elementos de uma tabela, incluindo chaves e valores.
```lua
local tabela = {a = 1, b = 2, c = 3}
for chave, valor in pairs(tabela) do
   print(chave, valor)
end
```
Nesse exemplo, o loop `for in pairs` itera sobre todos os elementos da tabela `tabela`, atribuindo a chave do elemento a `chave` e o valor do elemento a `valor`. O bloco de código dentro do loop é executado para cada par chave-valor da tabela.
