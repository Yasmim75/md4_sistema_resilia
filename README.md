## Projeto individual  desenvolvido para a Resilia e o Senac.

A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

Para nesse sistema tolerar a tarefa de realizar essa modelagem e responder algumas perguntas com nosso modelo:
➥ Existem outras entidades além dessas três?
➥ Quais são os principais campos e tipos?
➥ Como essas entidades estão relacionadas?

### Respostas
     ➥  Existem outras entidades além dessas três?
Sim, foi adicionada mais seis entidades.
     
       ➥  Quais são os principais campos e tipos?
Os principais  campos são os ID's, Nome, CPF e CNPJ e os principais tipo são Varchar e INT.

      ➥ Como essas entidades estão relacionadas?
 Uma Instituição para muitos Cursos (1:N)
Um Curso possue muitas Matrículas(1:N)
Um Curso possue muitas Diciplinas(1:N)
Uma Diciplina para muitas Turmas (1:N)
Muitos Alunos para muitas Turmas (N:N)
Muitos Professores para muitas Turmas (N:N)
Muitos Facilitadores para  muitas Turmas(N:N)
Uma Turma pertence a  uma Sala (1:1)
Um Aluno possue uma Matrícula(1:1)









![diagrama_relacionamento](https://raw.githubusercontent.com/Yasmim75/md4_sistema_resilia/main/02_01_SQLimagem.png)
