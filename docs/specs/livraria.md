# Especificação do Sistema — Aplicativo de Livraria

---

## Módulo 1: Catálogo e Busca

### US01 - Pesquisar livros

**História de Usuário:**

Como cliente, eu quero pesquisar livros no aplicativo, para encontrar os livros que desejo consultar.

**Critérios de Aceite:**

- **Cenário:** Pesquisar um livro pelo título
  - **Dado** que existem livros cadastrados no sistema
  - **Quando** o cliente pesquisar por "Dom Casmurro"
  - **Então** o sistema deve apresentar o livro correspondente

---

### US02 - Consultar informações do livro

**História de Usuário:**

Como cliente, eu quero consultar as informações de um livro, para conhecer seus dados antes de decidir pela compra.

**Critérios de Aceite:**

- **Cenário:** Visualizar informações de um livro
  - **Dado** que o cliente encontrou um livro
  - **Quando** acessar os detalhes do livro
  - **Então** o sistema deve apresentar o título, autor e preço

---

### US03 - Consultar disponibilidade

**História de Usuário:**

Como cliente, eu quero consultar a disponibilidade de um livro, para saber se ele está disponível para compra.

**Critérios de Aceite:**

- **Cenário:** Visualizar disponibilidade
  - **Dado** que o cliente está visualizando os detalhes de um livro
  - **Quando** consultar a disponibilidade
  - **Então** o sistema deve informar se o livro está disponível

---

### US04 - Consultar disponibilidade em uma loja

**História de Usuário:**

Como cliente, eu quero verificar se um livro está disponível em uma loja específica, para saber onde posso encontrá-lo.

**Critérios de Aceite:**

- **Cenário:** Consultar disponibilidade em uma loja
  - **Dado** que o cliente está consultando um livro
  - **Quando** selecionar uma loja específica
  - **Então** o sistema deve informar se o livro está disponível nessa loja

---

## Módulo 2: Informações de Compra

### US05 - Consultar preço

**História de Usuário:**

Como cliente, eu quero consultar o preço de um livro, para saber quanto ele custa antes da compra.

**Critérios de Aceite:**

- **Cenário:** Visualizar preço do livro
  - **Dado** que o cliente está visualizando os detalhes de um livro
  - **Quando** consultar as informações do livro
  - **Então** o sistema deve apresentar o preço

---

### US06 - Consultar horário da livraria

**História de Usuário:**

Como cliente, eu quero consultar o horário de funcionamento da livraria, para saber quando posso visitar a loja.

**Critérios de Aceite:**

- **Cenário:** Visualizar horário de funcionamento
  - **Dado** que o cliente está utilizando o aplicativo
  - **Quando** consultar o horário da livraria
  - **Então** o sistema deve apresentar os horários de funcionamento

---

### US07 - Consultar localização da livraria

**História de Usuário:**

Como cliente, eu quero consultar a localização da livraria, para saber onde a loja está localizada.

**Critérios de Aceite:**

- **Cenário:** Visualizar localização
  - **Dado** que o cliente está utilizando o aplicativo
  - **Quando** consultar a localização da livraria
  - **Então** o sistema deve apresentar a localização da loja

---

## Módulo 3: Recomendações

### US08 - Receber recomendações de livros

**História de Usuário:**

Como cliente, eu quero receber recomendações de livros, para descobrir livros que possam ser do meu interesse.

**Critérios de Aceite:**

- **Cenário:** Receber recomendações
  - **Dado** que existem livros cadastrados
  - **Quando** o cliente solicitar recomendações
  - **Então** o sistema deve apresentar uma lista de livros recomendados
