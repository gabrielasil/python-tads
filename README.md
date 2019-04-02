# Tipos abstratos de dados com Python

Este repositório foi pensado para quem já programa em Python, mas ainda não teve contato profundo com abstrações de alto nível como conjuntos e árvores.

> Se você ainda não teve o primeiro contato com Python, dê uma olhada neste [repositório](https://github.com/leobezerra/python-zero) 🙃

## Índice

1. [Conjuntos](#conjuntos)
2. [Dicionários](#dicionários)
3. [Listas ordenadas manualmente](#listas-ordenadas-manualmente)
4. [Listas ordenadas automaticamente](#listas-ordenadas-automaticamente)
5. [Pilhas](#pilhas)
6. [Filas e deques](#filas-e-deques)
7. [Árvores](#árvores)
8. [Consultas espaciais](#consultas-espaciais)

---

### Conjuntos

Implementações:
- Python: `set`
- C++: `unordered_set`, `unordered_multiset`

Autores:
- Anderson Pereira Torres de Sá Neto - [github/andersonptsn](https://github.com/andersonptsn)
- Danilo Miranda de Medeiros Galvão - [github/Fisiquelaz](https://github.com/Fisiquelaz)
- João Mendes Lopes Neto - [github/joaomendesln](https://github.com/joaomendesln)
- Mateus Firmino Barros - [github/mateusfb](https://github.com/mateusfb)
- Matheus Coelho Gurgel do Amaral - [github/matheuscga](https://github.com/matheuscga)

Notebook: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/set.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Dicionários

Implementações:
- Python: `dict`
- C++: `unordered_map`, `unordered_multimap`

Autores:
- João Marcos Pereira Bezerra - [github.com/marcospb19](https://github.com/marcospb19)
- João Vítor Fonseca de Mendonça - [github.com/vitor177](https://github.com/vitor177)
- Marcelo Ezequiel Moura Aragão - [github.com/marcelomoura1511](https://github.com/marcelomoura1511)
- Marlon Secundo de Oliveira Ferreira - [github.com/marlonsecundo](https://github.com/marlonsecundo)

Notebook: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/dict.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Listas ordenadas manualmente

Implementações:
- Python: `list`
- C++: `array, vector, list, forward_list`

Autores:
- Acsa Laiane Arcanjo Augusto
- Anna Beatriz de Souza Albuquerque
- Daniele Mendonça de Carvalho
- Gabriel Lucas de Medeiros Leite
- Gabriel Martins Spínola
- Maria Luiza de Araújo Azevedo

Notebook: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/list.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Listas ordenadas automaticamente

Implementações:
- Python: `sortedcontainers.SortedList`
- C++: `set`, `multiset`

Autores:
- Álvaro Prudêncio Araújo
- Felipe Rodrigues do Nascimento
- Lindonilson de Oliveira Macial
- Marcos Vinicio Araujo Delgado Junior
- Yago Beserra Marques

Notebook: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/SortedList.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

#### Pilhas

Implementações:
- Python: `queue.LifoQueue`
- C++: `stack`

Autores:
- Abraão Lincol R. Cavalcante
- Davi César de Araújo Bezerra 
- Emanuel Felipe G. Leão
- João Vitor Dias Xavier
- Lucas Vinicius Sales Dantas

Notebook: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/LifoQueue.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Filas e deques

Implementações:
- Python: `queue.Queue`, `queue.PriorityQueue` e `collections.deque`
- C++: `queue` e `deque`

Autores:
- Bruna Soares
- Eduardo Paixão
- Marlus Marcos
- Pedro Nogueira
- Rodolfo Dantas

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/Queue-deque.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Árvores

Implementações:
- Python: milhões de bibliotecas 🤠 (`pptree`, por exemplo)
- C++: bibliotecas (`Boost.PropertyTree`, por exemplo)

Autores:
- Felipe Eduardo
- Fernando Igor
- Italo Bruno 
- Keler Yohan
- Leonardo Santos

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/tree.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

---

### Consultas espaciais

Implementações:
- Python: `scipy.Spatial.KDTree`
- C++: bibliotecas

Autores:
- Gabriel Rocha de Souza
- Giovanna Karla de Macedo Felix
- Jonas Florencio
- João Paulo Carneiro
- Pedro Cardoso Carvalho

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/leobezerra/python-tads/blob/master/notebooks/KdTree.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/python-tads/master)

[Voltar para o índice](#índice)

