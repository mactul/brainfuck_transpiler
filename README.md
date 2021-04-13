brainfuck transpiler is a simple python program, easy to use, that can encode or decode brainfuck.\
\
The function `string_to_bf(string)` transforms a string, like "hello" to a brainfuck code, corresponding at this string.\
\
The function `execute(code)` can interprets a string brainfuck code.\
\
\
Example:
```py
string = input("string: ")
bf_code = string_to_bf(string)  # transpile the string entered.

print(bf_code, "\n\n")

execute(bf_code)  # execute the code generated and reprint the string entered before
```
