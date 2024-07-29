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
**PROTOTIPAÇÃO DAS CLASSES**

**Tema: prototipação das classes**

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
**PROTOTIPAÇÃO DAS CLASSES**

**Tema: prototipação das classes**

Relatório solicitado pela Generation Brasil para compor o projeto final. O relatório refere-se à descrição dos atributos das classes que serão utilizadas no projeto integrador.

1) **DESCRIÇÃO DOS ATRIBUTOS**

**Nome da Classe: Servico**

| Atributo | Descrição e motivo da escolha |
| ----- | ----- |
| Id  (Long) | Identificador único do objeto.  |
| Título  (String) | Título da vaga. Ajuda a identificar a vaga, com um título resumido da função para vaga e o nome da empresa. |
| Nome  (String) | Nome da vaga. Este atributo é importante para identificar a vaga e diferenciar entre diversas vagas. |
| Descrição  (String) | Descrição da vaga. Fornece informações adicionais sobre o tema, ajudando a entender melhor seu contexto e aplicação. |
| Contador (Number) | Quantidade de inscrições na vaga. |
| Quantidade (Number) | Quantidade de vagas disponíveis.  |
| Data  (Date) | Data original da publicação da vaga. |
| Status  (Boolean) | Indica o status da vaga, se disponível ou não. |

**Nome da Classe: USUARIO**

| Atributo | Descrição e motivo da escolha |
| ----- | ----- |
| Id  (Long) | Identificador único do objeto.  |
| Nome  (String) | Nome do usuário. |
| Email  (String) | E-mail do usuário. |
| Senha Senha (String) | Senha do usuário. |
| Foto  (Boolean) | Foto do usuário. |

**Nome da Classe: Categoria**

| Atributo | Descrição e motivo da escolha |
| ----- | ----- |
| Id  (Long) | Identificador único do objeto.  |
| Tipo (String) | Exibe Cursos ou vagas de emprego. |
| Cargo (String) | Definir qual o tipo de cargo (estágio, trainee, junior, etc). |
|  |  |
|  |  |
|  |  |

**2\) REPOSITÓRIO DA ORGANIZAÇÃO** 

[**Centro-Bell-Hooks/backend (github.com)**](https://github.com/Centro-Bell-Hooks/backend)

[image1]: <data:image/png;base64,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>