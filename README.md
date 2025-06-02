# 🚀 Tutorial para Iniciantes: Oracle Database XE + SQL Developer

> Um passo a passo simples para instalar e começar a praticar SQL com Oracle no Windows.

---

## 🧩 1. Instalar o Oracle Database XE (Express Edition)

💡 O Oracle XE é o banco de dados que você usará localmente.

### 🔗 Link de download:
👉 [oracle.com/xe-downloads](https://www.oracle.com/br/database/technologies/xe-downloads.html)

### ✅ Passos:
1. Clique em **"Windows x64"** para baixar.
2. Execute o instalador (`.exe`) baixado.
3. Siga o assistente → clique em **Next** até o final.
4. Quando pedir uma senha para o usuário `system`, **guarde bem essa senha!**
5. Finalize a instalação.

🔁 Após instalar, o Oracle inicia automaticamente no seu PC com os serviços:
- `OracleXETNSListener`
- `OracleServiceXE`

---

## 💻 2. Instalar o SQL Developer

💡 O SQL Developer é o programa onde você digita os comandos SQL.

### 🔗 Link de download:
👉 [oracle.com/sql-developer](https://www.oracle.com/database/sqldeveloper/technologies/download/)

### ✅ Passos:
1. Baixe a versão **Windows with JDK included**.
2. Extraia o `.zip`.
3. Abra o arquivo `sqldeveloper.exe`.

---

## 🔌 3. Criar sua primeira conexão

1. Clique no botão de **“+” Conexão** no SQL Developer.
2. Preencha os dados assim:

Nome da Conexão: minha_conexao
Usuário: system
Senha: [a senha que você escolheu]
Host: localhost
Porta: 1521
SID: xe


3. Clique em **Testar** → Se estiver “Status: Success”, clique em **Conectar**.

------------------------------------------------------------------------------------------------------------------------

# Diferenças entre Oracle Database XE e Oracle SQL Developer

Este README explica de forma simples as principais diferenças entre dois produtos essenciais da Oracle para trabalhar com banco de dados: o Oracle Database XE e o Oracle SQL Developer.

---

## O que são?

- **Oracle Database XE (Express Edition):**  
  É o banco de dados em si, onde seus dados são armazenados, organizados e gerenciados.

- **Oracle SQL Developer:**  
  É uma ferramenta gráfica (IDE) que permite você se conectar ao banco, escrever comandos SQL, criar tabelas, consultar dados e administrar o banco de forma mais simples.

---

## Diferenças principais

| Produto               | O que é?                                  | Função principal                              | Uso típico                                                      |
|-----------------------|-------------------------------------------|-----------------------------------------------|----------------------------------------------------------------|
| **Oracle Database XE** | Banco de dados completo e gratuito para aprendizado e projetos pequenos. | Armazenar dados, executar consultas e transações. | Servidor de banco de dados local, onde você cria tabelas, insere dados e executa queries. |
| **Oracle SQL Developer** | IDE cliente para Oracle Database.           | Interface gráfica para facilitar o trabalho com SQL. | Ferramenta para escrever SQL, modelar dados, executar comandos, gerar relatórios e administrar o banco. |

---

## Como começar a usar

1. **Instale o Oracle Database XE**  
   Baixe e instale o Oracle XE para ter o banco de dados local rodando no seu computador.  
   [Download Oracle Database XE](https://www.oracle.com/br/database/technologies/xe-downloads.html)

2. **Instale o Oracle SQL Developer**  
   Baixe e extraia o SQL Developer para ter uma interface gráfica para se conectar ao banco.  
   [Download SQL Developer](https://www.oracle.com/database/technologies/sql-developer.html)

3. **Crie uma conexão no SQL Developer**  
   Abra o SQL Developer, clique em "Nova Conexão" e preencha com os dados do Oracle XE (exemplo: usuário `system`, senha que você definiu, host `localhost`, porta padrão `1521`, serviço `XE`).

4. **Comece a criar tabelas e rodar consultas SQL!**

---

## Recursos úteis

- Documentação oficial Oracle XE:  
  https://docs.oracle.com/en/database/oracle/oracle-database/xe/index.html

- Guia rápido SQL Developer:  
  https://www.oracle.com/tools/downloads/sqldev-downloads.html

---
Boa jornada com Oracle! 🚀

