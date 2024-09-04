# Exemplo de Tabelas do Sistema de IMC

## Tabela de IMC

| Campo     | Tipo     | Descrição                                        |
|-----------|----------|--------------------------------------------------|
| id        | INT      | Chave primária, autoincremento                   |
| user_id   | INT      | Chave estrangeira para a tabela `users`          |
| valor_imc | NUMERAL  | Valor do IMC calculado                           |

## Tabela de Usuários

| Campo     | Tipo         | Descrição                                     |
|-----------|--------------|-----------------------------------------------|
| id        | INT          | Chave primária, autoincremento                |
| nome      | VARCHAR(100) | Nome do usuário                               |
| email     | VARCHAR(100) | Email do usuário                              |
| peso      | NUMERAL      | Peso do usuário em quilogramas                |
| altura    | NUMERAL      | Altura do usuário em metros                   |

## Tabela de Informativos

| Campo     | Tipo         | Descrição                                     |
|-----------|--------------|-----------------------------------------------|
| id        | INT          | Chave primária, autoincremento                |
| titulo    | VARCHAR(100) | Título do informativo                         |
| contento  | TEXT         | Conteúdo do informativo                       |
| link      | VARCHAR(255) | Link para mais informações, se necessário     |

