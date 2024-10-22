### Minhas anotações sobre Essencial Database.

---

Abordaremos os conceitos fundamentais para criação, desenvolvimento, implantação e manipulação de um banco de dados.

NOSSO OBJETIVO É CONSEGUIR MONTAR UM PROJETO DE BANCO DE DADOS COMPLETO, DESDE A ESPECIFICAÇÃO DOS REQUISITOS ATÉ SUA IMPLEMENTAÇÃO FÍSICA.

PARA SE FAZER UM PROJETO DE BANCO DE DADOS EXISTEM 3 NÍVEIS QUE PRECISAM SER ELABORADOS: O nível conceitual, lógico e físico.

E APÓS ISSO, USAREMOS A LINGUAGEM SQL PARA CRIAR TODAS AS ESTRUTURAS DENTRO DO BANCO DE DADOS E USAR ELA COM OS COMANDOS PARA FAZER AS QUERIES E VEREMOS QUE EXISTE VARIAS CLÁUSULAS DENTRO DE UMA QUERY.

CLÁUSULA WHERE / OPERADORES AND, OR e NOT / CLÁUSULA ORDER BY / FUNÇÕES DE LINHA / FUNÇÕES DE GRUPO / SUBCONSULTAS / CRIAÇÃO DE OUTROS OBJETOS COMO VIEWS / ÍNDICES / ...

LINGUAGEM SQL: É a linguagem que utilizamos para acessar e manipular todas as estruturas dentro de um banco de dados relacional.

TODAS AS CATEGORIAS DE COMANDOS QUE COMPÕEM A LINGUAGEM SQL: DDL, DML, DCL e DQL.

---

### PROJETO DE BANCO DE DADOS

DADO: É algo que precisa de processamento. Quando olhamos o dado sozinho, não faz sentido. É a menor unidade de processamento.

Pode ser uma data, uma temperatura, uma palavra, ...

INFORMAÇÃO: É o resultado da operação com o dado.

Para que obtenhamos a informação, precisamos do dado.

Com a ano atual e ano de nascimento da pessoa, conseguimos gerar a idade da pessoa.

A IMPORTÂNCIA DE SABERMOS A DIFERENÇA ENTRE DADOS E INFORMAÇÕES:

O BANCO DE DADOS ARMAZENA DADOS E O SISTEMA DE INFORMAÇÃO GERA INFORMAÇÕES.

O PROBLEMA DE ARMAZENAR INFORMAÇÃO AO INVÉS DO DADO, É QUE NO CASO DA IDADE, NOS PRÓXIMOS ANOS, A PESSOA ESTARÁ COM 48, 49, 50 ANOS... MAS NO SISTEMA DE INFORMAÇÃO PERMANECERÁ 47 ANOS.

---

ESSES DADOS FICAM ARMAZENADOS EM ARQUIVOS E OS ARQUIVOS FICAM ORGANIZADOS DENTRO DE UM SISTEMA.

O SISTEMA DE ARQUIVOS É UM SISTEMA RESPONSÁVEL POR ARMAZENAR ARQUIVOS CONTENDO DADOS.

O SISTEMA TEM UM CONJUNTO DE OPERAÇÕES QUE ACESSAM OS DADOS PARA GERAR AS INFORMAÇÕES.

### SISTEMAS DE ARQUIVOS:

É uma estrutura que indica como os arquivos devem ser gravados e guardados em mídias.

O Sistema de arquivos é quem determina como os arquivos podem ser gravados, copiados, alterados, nomeados e excluídos.


Toda e qualquer manipulação de dados numa mídia, necessita de um sistema de arquivos.

OBJETIVO DOS SISTEMAS DE ARQUIVOS:

Fornecer mecanismos para usuários manipularem arquivos e diretórios;

Garantir a validade e coerência dos dados;

Otimizar o acesso aos dados.

---

### BANCO DE DADOS X SGBD's

BANCO DE DADOS É QUALQUER LUGAR QUE TENHA DADOS ARMAZENADOS EM UMA DETERMINADA ORDEM.

EXEMPLO: Um livro é um local que tem dados armazenados na ordem de páginas.

EXEMPLO: Um arquivo de metal com pastas dentro desse arquivo, como em cartórios, aqueles armários de metal com várias fichinhas.

EXEMPLO: O fichário de madeira do dentista.

---

PODEMOS ENTENDER COMNO BANCO DE DADOS(DATA BASE):

COLEÇÃO DE DADOS RELACIONADOS;

COLEÇÃO LOGICAMENTE COERENTE DE DADOS COM ALGUM SIGNIFICADO INERENTE;

UM BANCO DE DADOS ESTÁ SEMPRE ASSOCIADO A APLICAÇÕES E A USUÁRIOS QUE TÊM INTERESSE NELE;

QUALQUER SISTEMA QUE REÚNA E MANTENHA ORGANIZADA UMA SÉRIE DE DADOS RELACIONADOS A UM DETERMIANDO ASSUNTO, EM UMA DETERMINADA ORDEM.

---

SGBD (Sistema Gerenciador de Banco de Dados) tem ferramentas, mecanismos, aplicações que permitem o acesso À 
























