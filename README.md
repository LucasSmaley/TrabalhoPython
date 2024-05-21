# TrabalhoPython
Trabalho Omar

Desenvolver um sistema de registro de notas de alunos para uma instituição de ensino de pequeno 
porte. 


    1. Elaborar o diagrama de Casos de Uso do modelo de negócios. 
    2. Elaborar o diagrama de Entidade-Relacionamento do modelo de dados (no mínimo três tabelas). 
    3. Criar as tabelas no banco de dados PostgreSQL. 
    4. Implementar as operações CRUD do banco de dados em Python com o framework psycopg2. 
    5. Implementar a interface gráfica com o framework tkinter. 


Entregas: 
    I. 
    Relatório com diagramas de Casos de Uso, diagrama de E-R e SQL de criação das tabelas no PostgreSQL (itens 1, 2 e 3 acima). 

    II. 
    Código fonte em Python com a implementação do sistema (itens 4 e 5 acima) conforme os 
    requisitos (itens a, b, c, d, e, f e g abaixo).


Requisitos do sistema: 
    a) O sistema deve permitir a inclusão de alunos, incluindo nome do aluno e número de matrícula.

    b) O sistema deve permitir a inclusão de disciplinas, incluindo nome da disciplina, ano e semestre em que está sendo oferecida. 

    c) O sistema deve permitir a inscrição de alunos em uma disciplina. 

    d) A cada prova do semestre, o sistema deve permitir a inclusão das notas: SM1, SM2, AV, AVS. 

    e) O sistema deve fazer o cálculo das notas finais (NF) de todos os alunos, conforme as regras i, ii, iii, iv e v abaixo, e gravar o resultado (NF) no banco de dados. 

    f) O sistema deve permitir a consulta de todas as notas e da situação (Aprovado ou Reprovado) de um dado aluno de uma dada disciplina. 

    g) O sistema deve emitir um relatório (na tela do computador) das notas das avaliações (SM1, SM2, AV, AVS) e da situação (Aprovado ou Reprovado) de todos os alunos de uma dada disciplina. 


Regras para cálculo da NF e da situação final: 
    i. O SM1 vale até um ponto adicional na NF. 

    ii. O SM2 vale até um ponto adicional na NF (mais um ponto, além do SM1). 

    iii. A AV vale até 10 pontos. 

    iv. A AVS vale até 10 pontos e substitui a nota da AV, caso seja maior. 
    
    v. Para aprovação, a NF tem que ser maior ou igual a 6.0 pontos. Caso contrário, isto é, NF menor que 6.0, implica em reprovação.


