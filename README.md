# Projeto API Catalogo de Jogos

Entrega de projeto realizado em aula DIO, simulando um sistema de catálogo de jogos.



## Implementações

- Implementado novo método Get na aplicação. Agora é possível realizar buscas de jogos por Produtora pelo método ObterPorProdutora().
  Realizadas as adequações necessárias nas interfaces de suas respectivas camadas: controllers, repositories e services. Além de incluir o método em cada classe em que era necessário.
- No SQL Server, para criação de registros com padrão de código identificador igual ao utilizado em aula pelo professor, o atributo "Id" da tabela "jogos" foi reescrito para  UNIQUEIDENTIFIER DEFAULT NEWID(). 

