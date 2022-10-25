## Métodos

Requisições para a API devem seguir os padrões:

| Endpoint                     | Método | Descrição                                                                                              |
| :----------------------------| :----- | :----------------------------------------------------------------------------------------------------- |
| `professores/`               | GET    | Rota usada para listar todos os professores cadastrados                                                |
| `professores/<int:id>/aulas` | POST   | Rota para cadastrar uma aula com o professor selecionado com base no id passado via parâmetro na url   |

