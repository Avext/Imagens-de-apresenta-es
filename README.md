

# <font color="#DAA520">Resilia - Projeto do Módulo-3</font>

![](https://raw.githubusercontent.com/Avext/Imagens-de-apresenta-es/main/resiliam3s72.png)

## Objetivo do Projeto

Este projeto foi feito como parte integrante da avaliação do Módulo 3 do curso Data Analytics da Resilia Educação da turma 20. Este projeto foi desenvolvido pelo Squad 7, que é composto pelos estudantes:

- Ally;

- Camilo ;

- Carlos;

- Pedro;

- Thiago Vasconcelos.


## Descrição do Projeto

Este é um projeto de construção de um banco de dados para gerenciamento da estrutura de ensino da empresa Resilia Educação, com o objetivo de modernizar o processo de armazenamento de dados da empresa.

### Tema abordado

Atualmente são armazenadas diversas informações da empresa como dados sobre os alunos, facilitadores, departamentos, módulos e cursos em planilhas. Essas informações são colocadas em planilhas diferentes o que gera uma certa dificuldade na manipulação e consulta dos dados.

A partir deste projeto procuramos organizar de forma lógica o modelo de negócios da empresa a fim de melhorar, facilitar e modernizar e interação com os dados. Sendo esses objetivos viabilizados através de um banco de dados SQL.

Como resultados deste projeto pretende-se gerar informações estratégicas para a área de ensino da Resilia. As principais consultas que iremos realizar são:

◆ Selecionar a quantidade total de estudantes cadastrados no banco;

◆ Selecionar todos os estudantes com os respectivos cursos que eles estão cadastrados;

◆ Selecionar quais facilitadores atuam em mais de uma turma;

◆ Consulta 1;

◆ Consulta 2;

◆ Consulta 3.


## Estrutura do projeto


A ferramenta utilizada para a modelagem do banco foi o [  ](https://dbdiagram.io/home)dbdiagram.io - Database Relationship Diagrams Design Tool e como sistema gerenciador do banco de dados foi utilizado o PostgreSQL 14.5 juntamente com o pgAdmin 4 como plataforma de administração do banco de dados. Com essas ferramentas foi possível executar:

● Modelagem completa do banco de dados com entidades, atributos e relacionamentos;

● Scripts SQL de criação das tabelas com seus atributos e chaves;

● Resultado de das consultas propostas na realização do projeto.

### Estrutura do banco

O banco de dados está estruturado de acordo com o diagrama a seguir:
		
![](https://raw.githubusercontent.com/Avext/Imagens-de-apresenta-es/main/resiliam3s7.png)

### Entidades e relacionamentos

- Existem duas validações de entrada no código, que estão em funções: uma para o caso do input ser um inteiro ou uma string. No caso, se eu desejo que minha entrada seja um inteiro, meu código só aceita esse tipo de entradas, e em caso de outro tipo, ele entra em um loop, informando que a entrada está no formato incorreto e pedindo para o usuário inserir uma entrada válida. O mesmo se aplica a entrada de texto: se o usuário entrar com um número, entra no loop, até ser fornecido uma entrada do tipo string.

### Consultas
		

- Após informar a sua idade e gênero o usuário responderá as seguintes perguntas e opções de resposta:

		[1] Você concluiu o ensino médio? Sim (1), Não (2) e Não sei responder (3)
		
		[2] Sua média salarial ultrapassa 2 salários mínimos? Sim (1), Não (2) e Não sei responder (3)
		
		[3] Durante o período de pandemia, você ou alguém próximo, sofreu com alguma doença psicológica, agravada pelo isolamento social? Sim (1), Não (2) e Não sei responder (3)
		
		[4] Você consideraria procurar uma rede de apoio como forma de auxílio? Sim (1), Não (2) e Não sei responder (3)

