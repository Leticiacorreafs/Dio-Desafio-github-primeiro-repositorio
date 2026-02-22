📌 Comandos básicos (Windows / Linux / CMD)
===========================================

📂 Navegação em diretórios
--------------------------

### 🔹 `dir`

* Lista todos os arquivos e pastas.

* No CMD: digitar `dir` dentro da pasta do usuário.

### 🔹 `ls`

* No Linux, equivale ao `dir`.

* Lista os arquivos e pastas.

### 🔹 `cd`

* Usado para navegar entre pastas.

* `cd /` → vai para a raiz.

* `cd ..` → volta uma pasta.

* No Windows: pode digitar a primeira letra da pasta e usar TAB para completar.

### 🔹 `cls`

* Limpa a tela no CMD.

* * *

📁 Criar e manipular arquivos/pastas
------------------------------------

### 🔹 `mkdir`

* Cria uma nova pasta.

* Exemplo: criar pasta chamada `workspace`.

### 🔹 `cd nome_da_pasta`

* Navega até a pasta criada.

### 🔹 Criar arquivo pelo CMD

* Pode usar `echo` para criar arquivos.

### 🔹 `del`

* Deleta arquivos.

* Só deleta o que está dentro da pasta atual.

* * *

🔐 SHA-1
========

O que é?
--------

SHA-1 significa **Secure Hash Algorithm** (algoritmo de hash seguro).

* É um conjunto de funções hash criptográficas.

* Projetado pela NSA (Agência Nacional de Segurança dos EUA).

* Gera um identificador único de **40 caracteres**.

* Serve como identificação única de arquivos.

### 📌 Importância

* O resultado da criptografia gera um conjunto de caracteres.

* Cada hash é único.

* É uma forma segura de representar um arquivo.

### Exemplo:

1. Texto: `"ola mundo"`

2. Aplicando `sha1` → gera um hash (40 caracteres).

* * *

📦 Objetos Fundamentais do Git
==============================

1️⃣ Blob
--------

* Representa o conteúdo do arquivo.

* Não guarda nome, apenas o conteúdo.

2️⃣ Tree
--------

* Representa estrutura de pastas.

* Aponta para blobs e outras trees.

* Guarda os nomes dos arquivos.

Exemplo de estrutura:

README  
RAKEFILE  
LIB/  
   simplegit.rb

* README → blob

* RAKEFILE → blob

* LIB → tree

* simplegit.rb → blob

* * *

3️⃣ Commit
----------

* Junta tudo.

* Aponta para uma tree.

* Guarda:
  
  * SHA-1
  
  * Autor
  
  * Mensagem
  
  * Timestamp
  
  * Commit pai (parent)

O SHA-1 do commit é o hash de todas essas informações.

* * *

🔐 Chave SSH
============

* Forma de estabelecer conexão segura entre duas máquinas.

* Exemplo: seu computador ↔ servidor do GitHub.

* Utiliza chave pública e privada.

* Permite enviar código sem precisar digitar usuário e senha.

* * *

🔑 Token de Acesso Pessoal
==========================

* Criado no GitHub.

* Guardado na sua máquina.

* Substitui a senha.

* Usado quando o Git pede autenticação.

* * *

🧾 Comandos Git
===============

### 🔹 `git init`

* Inicializa um repositório.

### 🔹 `git add nome_arquivo`

* Adiciona arquivo específico.

### 🔹 `git add *`

* Adiciona todos os arquivos.

### 🔹 `git add .`

* Adiciona alterações atuais.

### 🔹 `git commit -m "mensagem"`

* Cria um commit com mensagem.

* * *

🧠 Áreas do Git
===============

Estados dos arquivos
--------------------

* **Untracked** → não rastreado

* **Unmodified** → não modificado

* **Modified** → modificado

* **Staged** → preparado para commit

* * *

Ambientes do Git
----------------

### 🔹 Working Directory

* Onde você trabalha.

### 🔹 Staging Area

* Onde ficam os arquivos preparados (`git add`).

### 🔹 Local Repository

* Onde ficam os commits.

### 🔹 Remote Repository

* Servidor (ex: GitHub).

* * *

🖥️ Markdown vs HTML
====================

Markdown
--------

Forma mais simples e humana de escrever HTML.

### Títulos:

# Título nível 1

## Título nível 2

### Título nível 3

#### Título nível 4

##### Título nível 5

###### Título nível 6

* * *

Equivalente em HTML:
--------------------

<h1>Título nível 1</h1>  
<h2>Título nível 2</h2>  
<h3>Título nível 3</h3>  
<h4>Título nível 4</h4>  
<h5>Título nível 5</h5>  
<h6>Título nível 6</h6>
