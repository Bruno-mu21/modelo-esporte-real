# ⚽ Modelagem de Banco de Dados — Esporte Real

> Projeto de modelagem relacional de banco de dados desenvolvido e estruturado no **MySQL Workbench**[cite: 20].

---

## 📌 Sobre o Projeto

Este repositório contém a modelagem conceitual e lógica do banco de dados para o sistema **Esporte Real**[cite: 20]. 

O arquivo principal de modelo (`.mwb` do MySQL Workbench) reúne o Diagrama Entidade-Relacionamento (DER / EER), definição de tabelas, chaves primárias e estrangeiras, tipos de dados e regras de integridade relacional[cite: 20].

---

## 🗄️ Esquemas do Modelo

O arquivo do modelo inclui os seguintes esquemas estruturados[cite: 20]:
- **`esporte_real`**: Esquema principal da aplicação, estruturado com as tabelas de domínio do sistema[cite: 20].
- **`mydb`**: Esquema padrão de modelagem inicial do MySQL Workbench[cite: 20].

### Principais Características
- **Integridade Referencial:** Definição de chaves estrangeiras com restrições e relacionamentos entre entidades.
- **Normalização de Dados:** Estrutura organizada para evitar redundâncias e inconsistências em operações transacionais.
- **Forward Engineering:** Compatibilidade com a exportação automática de scripts DDL (`CREATE SCHEMA`, `CREATE TABLE`) diretamente para instâncias MySQL.

---

## 🛠️ Tecnologias e Ferramentas

- **Modelador:** [MySQL Workbench](https://www.mysql.com/products/workbench/) (Model Archive 1.0)[cite: 20]
- **SGBD Alvo:** [MySQL](https://www.mysql.com/) / [MariaDB](https://mariadb.org/)
- **Linguagem:** SQL (DDL / DML)

---

## 📁 Estrutura de Arquivos

```text
.
├── esporte_real.mwb (ou arquivo .mwb do projeto)   # Arquivo de modelo relacional EER do MySQL Workbench[cite: 20]
└── README.md                                       # Documentação e instruções de uso

🚀 Como Abrir e Utilizar o Modelo
Pré-requisitos
MySQL Workbench instalado (versão 8.0 recomendada).

Passo a Passo
Clone o repositório:

Bash


git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
cd NOME-DO-REPOSITORIO
Abrir o projeto no MySQL Workbench:

Dê dois cliques no arquivo .mwb do projeto; ou

Abra o MySQL Workbench, acesse File > Open Model... e selecione o arquivo.

Visualizar o Diagrama EER:

Na aba Model Overview, clique duas vezes sobre o diagrama em EER Diagrams para visualizar a modelagem gráfica completa das tabelas e seus relacionamentos.

Exportar o Script SQL (Forward Engineering):

No menu superior, vá em Database > Forward Engineer... (ou use o atalho Ctrl + G).

Siga as instruções do assistente para gerar o script SQL completo (.sql) ou aplicá-lo diretamente a uma base de dados local/remota.
