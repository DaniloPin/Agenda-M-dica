Criei um sistema para agendamento de consultas em uma clínica. Toda consulta envolve o nome do paciente, o nome do médico e a data marcada. É comum que consultas sejam reagendadas — e o meu sistema precisa permitir isso.

Criei uma classe que represente uma consulta com os dados essenciais e um método para reagendar, mantendo o controle da data atualizada.

Criei uma classe chamada Consulta com:

- Propriedade pública NomePaciente.
- Propriedade pública NomeMedico.
- Propriedade pública DataConsulta (do tipo DateTime).
- Método Reagendar(DateTime novaData) para atualizar a data.
- Método ExibirResumo() que mostra as informações da consulta, usando "Data:" na primeira exibição e "Nova data:" se ela tiver sido reagendada.
