# BANCO_DADOS_RESILIA
# Proposta do projeto
- Realizar a tarefa de modelagem de Dados do novo sistema de acompanhamento da Resilia, recebi as seguintes instruções e perguntas:
Modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.

⇨ Existem outras entidades além dessas três? ⇨ Quais são os principais campos e tipos? ⇨ Como essas entidades estão relacionadas?.

# Respostas
## ⇨ Existem outras entidades além dessas três?
- Sim foi adicionado algumas entendidades que faz sentido ter em um sistema de Banco de Dados de uma instituiçao de ensino, sendo elas: Matricula, Disciplinas, Turma e Co-Facilitador.
## ⇨ Quais são os principais campos e tipos?.
- id_aluno, curso_id, turma_id sao do tipo Int PK.
- nome ( em geral) Varchar ( com varios tamanhos diferentes para cada caso).
## ⇨ Como essas entidades estão relacionadas?
- CURSO estao relacionados a DISCIPLINA no tipo (1:N).
- CURSO esta relacionado a ALUNO no tipo (N:N), Esta relacao faz nos termos uma nova entidade MATRICULA que esta ligada a CURSO e ALUNO.
- TURMA esta relacionado a professor no tipo (1:N).
- TURMA esta relacionado a DISCIPLINA do tipo (1:N) A disciplina pode haver apenas uma TURMA.

![SISTEMA_RESILIA](https://user-images.githubusercontent.com/113525442/213589952-7489dfc5-38b5-4fc3-ab23-a18b915cfdc5.png)
