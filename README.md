# duplicados.py
Exercício para retirar letras duplicadas em uma frase
def duplicados (string):
    seen = []
    result = ''

    for char in string:
        if char not in seen:
            seen.append(char)
            result += char

    return result

input_string = "Hello World!"
output_string = duplicados(input_string)
print("Output:", output_string)
