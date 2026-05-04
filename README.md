README.md 1

## 📄 README.md
markdown
# Sistema de Registro de Votos (Python)

## 📌 Descrição
Este projeto simula um sistema simples de votação para escolha de representantes de classe. O usuário pode inserir votos para três candidatos (Ana, Bruno e Carlos), e o sistema contabiliza os resultados.

## ⚙️ Funcionalidades

- Entrada contínua de votos até o usuário digitar **"fim"**
- Armazenamento dos votos em uma lista
- Validação de candidatos (evita nomes inválidos)
- Contagem de votos usando `count()`
- Identificação automática do vencedor
- Tratamento de empate entre dois ou três candidatos

## 🧠 Lógica Principal

### ✔️ Armazenamento
Os votos são guardados em uma lista:
python
votos = []

### ✔️ Contagem

Utiliza o método `count()`:
python
votos.count("Ana")

### ✔️ Identificação do vencedor

* Primeiro encontra o maior número de votos:
python
max_votos = max(votos_ana, votos_bruno, votos_carlos)

* Depois verifica quem possui essa quantidade:
python
if votos_ana == max_votos:
    vencedores.append("Ana")

### ✔️ Tratamento de empate

* Se mais de um candidato tiver o maior número de votos:
python
if len(vencedores) > 1:
    print("Empate entre:", vencedores)

## ▶️ Como Executar

1. Tenha o Python instalado
2. Execute o arquivo:


python nome_do_arquivo.py

3. Digite os votos (Ana, Bruno ou Carlos)
4. Digite **"fim"** para encerrar e ver o resultado

## 📝 Exemplo

Digite o nome do candidato: Ana
Digite o nome do candidato: Bruno
Digite o nome do candidato: Ana
Digite o nome do candidato: fim

Resultado:
Ana: 2 votos
Bruno: 1 voto
Carlos: 0 votos

Vencedor: Ana

## 📚 Conceitos Utilizados

* Listas em Python
* Estrutura de repetição (`while`)
* Condicionais (`if/else`)
* Função `count()`
* Função `max()`

## 🚀 Possíveis Melhorias

* Interface gráfica
* Armazenamento em arquivo
* Mais candidatos dinâmicos
* Percentual de votos

Se quiser, posso transformar isso em versão com **interface gráfica (Tkinter)** ou **web (HTML + JS)**.


README.md 2 

# 🧠 Simulação de Pilha (LIFO) em Python

## 📌 Descrição

Este projeto simula o comportamento de uma **pilha (stack)** utilizando Python.

A estrutura segue o princípio **LIFO (Last In, First Out)**, ou seja:

> A última palavra adicionada será a primeira a ser removida.

## ⚙️ Funcionalidades

* ➕ Adicionar palavras à pilha (`append`)
* ↩️ Desfazer a última palavra (`pop`)
* 👀 Exibir o texto atual
* ⚠️ Tratamento de erro ao tentar remover com a pilha vazia

## 🧪 Como funciona

O programa utiliza uma lista (`list`) para representar a pilha:

* `append()` → adiciona palavra no topo
* `pop()` → remove a última palavra inserida

## ▶️ Execução

1. Execute o arquivo Python:
bash
python nome_do_arquivo.py

2. Use o menu interativo:

* `1` → Adicionar palavra
* `2` → Desfazer última palavra
* `3` → Exibir texto
* `4` → Sair

## 💡 Exemplo de uso

Entrada:

Adicionar: Olá
Adicionar: Mundo

Saída:

Texto atual: Olá Mundo

Desfazendo:

Removido: Mundo
Texto atual: Olá

## 📚 Conceito aplicado

* Estrutura de dados: **Pilha (Stack)**
* Princípio: **LIFO (Last In, First Out)**

## 🚀 Possíveis melhorias

* Interface gráfica (GUI)
* Limitar tamanho da pilha
* Salvar histórico em arquivo
* Implementar comando de limpar tudo

## 👨‍💻 Autor

Projeto acadêmico para prática de estruturas de dados em Python.


README.md 3 

# 📚 Sistema de Fila de Atendimento (FIFO)

## 📌 Descrição

Este projeto simula um sistema de atendimento de alunos em uma secretaria, seguindo o modelo **FIFO (First In, First Out)**, ou seja, o primeiro aluno a entrar na fila é o primeiro a ser atendido.

## ⚙️ Funcionalidades

* ➕ **Adicionar aluno à fila**

  * Utiliza `append()` para inserir no final da lista.

* 🎯 **Atender aluno**

  * Utiliza `pop(0)` para remover o primeiro da fila.

* 📋 **Exibir fila atual**

  * Mostra todos os alunos na ordem de atendimento.

* ⚠️ **Tratamento de fila vazia**

  * Evita erros ao tentar atender sem alunos na fila.

## 🧠 Conceito Utilizado

### FIFO (First In, First Out)

Estrutura onde:

* O primeiro elemento inserido é o primeiro a sair.
* Muito utilizado em filas reais (banco, mercado, atendimento).

## ▶️ Como Executar

1. Certifique-se de ter o Python instalado.
2. Salve o código em um arquivo `.py` (ex: `fila.py`).
3. Execute no terminal:
bash
python fila.py

## 📌 Exemplo de Uso

1 - Adicionar aluno
Digite o nome do aluno: Ana

1 - Adicionar aluno
Digite o nome do aluno: João

3 - Exibir fila
1. Ana
2. João

2 - Atender aluno
Atendendo: Ana

## 🚀 Melhorias Futuras

* Interface gráfica (GUI)
* Limite máximo de fila
* Prioridade de atendimento
* Integração com banco de dados

## 👨‍💻 Autor

Projeto desenvolvido para fins educacionais.
