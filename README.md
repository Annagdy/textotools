# textotools

[!0.1.1](https://pypi.org/project/textotools/)

[!MIT](https://opensource.org/license/mit/)

## Descrição

O pacote textotools é uma biblioteca Python para manipulação eficiente de texto em arquivos. Oferece funcionalidades como contar palavras, caracteres, substituir substrings, comprimir e descomprimir texto, contar ocorrências de palavras iguais e remover palavras de arquivos de texto.

## Instalação

Você pode instalar o pacote usando o pip:

```bash
pip install textotools
```

## Exemplo

```bash
from textotools import abrir_arquivo, contar_palavras, contar_caracteres, contar_palavras_iguais, substituir_substring, remover_palavra, compress_texto, decompress_texto 

abrir_arquivo('exemplo.txt')

quant = contar_palavras('exemplo.txt')

print(quant)

quantChar = contar_caracteres('exemplo.txt')

print(quantChar)

palavrasiguais = contar_palavras_iguais('exemplo.txt', 'anna')

print(palavrasiguais)

substituir_substring('exemplo.txt', 'odio', 'feliz')

remover_palavra('anna', 'exemplo.txt')

compress_texto('exemplo.txt')

decompress_texto('exemplo_compress.txt')
```
