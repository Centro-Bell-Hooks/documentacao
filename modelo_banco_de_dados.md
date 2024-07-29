![][image1]

**GRUPO 03**

**INTEGRANTES**

Arthur Lopes de Moura Costa  
Danillo Oliveira  
Ezequiel Almeida  
Fernando Cássio  
Letícia Virgílio Oliveira  
Liara Cristina dos Santos  
Samira Grossi 

**PROJETO INTEGRADOR**  
**PROTOTIPANDO O BANCO DE DADOS**

**Tema: prototipando o banco de dados**

Relatório solicitado pela Generation Brasil para compor o projeto final. O relatório refere-se à descrição das tabelas que serão utilizadas no projeto integrador.

1) **DESCRIÇÃO DAS TABELAS E SEUS ATRIBUTOS**

| Nome do Banco de Dados: | bd\_projeto\_integrador |
| :---- | :---- |
| **SGBD:** | MySQL-8.0 |

**Tabela: USUÁRIO**

| Atributo | Descrição e motivo da escolha | Chave |
| ----- | ----- | ----- |
| Id BIGINT | ID do usuário | PK |
| Nome VARCHAR(255) | Nome do usuário |  |
| Email VARCHAR(255) | E-mail do usuário |  |
| Senha VARCHAR(255) | Senha do usuário |  |
| Tipo VARCHAR(255) | Se é empresa ou aluno |  |
| Foto VARCHAR(500) | Foto do usuário |  |

**Tabela: CATEGORIA**

| Atributo | Descrição e motivo da escolha | Chave |
| ----- | ----- | ----- |
| Id BIGINT | ID da Categoria | PK |
| Tipo VARCHAR(255) | Exibe Cursos ou vagas de emprego |  |
| Cargo VARCHAR(255) | Definir qual o tipo de cargo (estágio, trainee, junior, etc) |  |

**Tabela: SERVIÇO**

| Atributo | Descrição e motivo da escolha | Chave |
| ----- | ----- | ----- |
| id BIGINT | ID do serviço | PK |
| titulo VARCHAR(255) | Título do serviço |  |
| nome VARCHAR(255) | Nome da Empresa ou Instituição de Ensino. |  |
| descricao VARCHAR(500) | Descrições gerais sobre a vaga ou curso, se é remota, híbrido e presencial. |  |
| contador INT | Mostrará a quantidade de candidaturas |  |
| quantidade INT | Quantidade de serviços, filtro para páginas no frontend |  |
| data DATE | Para ter noção de há quanto tempo a vaga está aberta. |  |
| status BOOLEAN | Se a vaga está disponível ou não  |  |
| usuario\_id BIGINT | Foreign Key da tabela usuário | FK |
| categoria\_id BIGINT | Foreign Key da tabela categoria | FK |

**2\) DER do BD**

**![][image2]**  
			  
**3\) REPOSITÓRIO**

https://github.com/CentroBellHooks  
