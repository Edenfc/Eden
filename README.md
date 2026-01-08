# Eden
**Portfólio**

Olá! 👋  
Sou estudante de **Tecnologia em Banco de Dados** e atuo como **Auxiliar de TI**.  
Este repositório reúne projetos simples e práticos voltados para **SQL, lógica de programação e boas práticas**, com foco em vagas de **Programador Júnior**.

---

## 🚀 Objetivo
Demonstrar minha base técnica em banco de dados, organização de código e versionamento, além da minha evolução constante na área de desenvolvimento.

---

## 🛠️ Tecnologias e Conhecimentos

* **Banco de Dados:** SQL Server / MySQL (conceitos)
* **SQL:** SELECT, INSERT, UPDATE, DELETE, JOIN, GROUP BY, ORDER BY
* **Lógica de Programação:** variáveis, condicionais, laços
* **Programação:** conceitos de POO
* **Controle de Versão:** Git e GitHub
* **Sistemas:** noções de backend e integração com banco

---

## 📂 Projetos

### 🔹 Projeto 1 – Cadastro de Clientes (SQL)

**Descrição:** Banco de dados para cadastro de clientes e pedidos, simulando um sistema comercial.

**Funcionalidades:**

* Cadastro de clientes
* Registro de pedidos
* Relatórios de vendas por cliente

**Principais conceitos aplicados:**

* Chave primária e estrangeira
* JOIN entre tabelas
* GROUP BY

**Exemplo de consulta SQL:**

```sql
SELECT c.nome, SUM(p.valor) AS total_gasto
FROM clientes c
JOIN pedidos p ON p.cliente_id = c.id
GROUP BY c.nome;
```

---

### 🔹 Projeto 2 – Controle Financeiro Simples

**Descrição:** Estrutura de banco para controle de entradas e saídas financeiras.

**Funcionalidades:**

* Lançamento de receitas e despesas
* Consulta de saldo mensal

**Conceitos utilizados:**

* Datas
* Funções de agregação
* Filtros com WHERE

**Exemplo de consulta:**

```sql
SELECT SUM(valor) AS saldo
FROM lancamentos
WHERE data BETWEEN '2025-01-01' AND '2025-01-31';
```

---

### 🔹 Projeto 3 – Versionamento com Git

**Descrição:** Projeto versionado no GitHub para demonstrar uso de controle de versão.

**Práticas utilizadas:**

* Commits organizados
* Criação de branches
* README documentado

**Comandos usados:**

```bash
git init
git add .
git commit -m "Projeto inicial"
git branch nova-funcionalidade
```



*(Links ajustáveis conforme seus perfis reais)*

