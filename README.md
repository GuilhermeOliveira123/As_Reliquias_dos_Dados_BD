# As_Reliquias_dos_Dados_BD

Uma vez que o banco estiver bem estruturado e desenhado, é possível realizar testes, simulando relatórios ou telas que o sistema possa necessitar. A tarefa consiste em criar consultas que levem aos resultados esperados.
Crie um script e nele inclua consultas que retornem:

* Todos os dados e o valor médio das consultas do ano de 2020 e das que foram feitas sob convênio.
* select *, AVG(valor_consulta) from consulta group by year(data_consulta) = 2020 having convenio_id;
