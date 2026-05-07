# aws-cloud-lab
Laboratório prático AWS utilizando EC2, S3, RDS MySQL e conexão SSH.
# ☁️ AWS Cloud Lab

Laboratório prático utilizando serviços AWS para aprendizado de Cloud Computing, Linux e Banco de Dados.

## 🚀 Tecnologias utilizadas

* Amazon EC2
* Amazon RDS MySQL
* Amazon S3
* Linux Ubuntu
* SSH
* MySQL
* SQL

---

## 🎯 Objetivo do projeto

Criar uma infraestrutura cloud prática utilizando serviços da AWS para aprender:

* criação de servidores Linux
* conexão SSH
* banco de dados MySQL
* integração entre serviços cloud
* comandos Linux
* comandos SQL

---

## 🖥️ Serviços utilizados

### EC2

Instância Linux Ubuntu utilizada para acesso remoto e execução de comandos.

### RDS MySQL

Banco de dados relacional criado na AWS para armazenamento de dados.

### S3

Serviço de armazenamento utilizado para estudos de cloud storage.

---

## 🔐 Conexão SSH

Foi utilizada conexão SSH para acessar remotamente a instância Linux hospedada na AWS.

Exemplo:

```bash
ssh -i chave.pem ubuntu@ip-publico
```

---

## 🗄️ Comandos SQL utilizados

Criação de tabela:

```sql
CREATE TABLE clientes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(100),
    email VARCHAR(100)
);
```

Inserção de dados:

```sql
INSERT INTO clientes (nome, email)
VALUES ('Alysson', 'alyssonassis227@gmail.com');
```

Consulta:

```sql
SELECT * FROM clientes;
```

---

## 📚 Aprendizados

* utilização prática da AWS
* acesso remoto Linux
* banco de dados MySQL
* comandos SQL
* infraestrutura cloud
* integração entre serviços

---

## 👨‍💻 Autor

Alysson Assis
