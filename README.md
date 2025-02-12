
# Aplicativo Planetas

O Planetas é um aplicativo desenvolvido com Flutter e Dart, o app permite adicionar, criar, modificar e excluir planetas.

Desafios Encontrados:

Durante o desenvolvimento, encontrei alguns desafios ao tentar integrar o banco de dados SQLite, que era essencial para armazenar as informações das plantas de forma persistente. Aqui estão os principais obstáculos:

Problemas com as dependências do SQLite: Tivemos dificuldades para integrar o pacote sqflite corretamente no Flutter, o que gerou alguns erros ao tentar armazenar e acessar dados no banco.

Conexão com o Banco de Dados: O app não estava conseguindo se conectar ao SQLite devido a configurações incorretas, principalmente em relação às permissões necessárias para o Android e iOS.

Dificuldades na migração de dados: Quando tento modificar a estrutura do banco de dados ou migrar dados existentes, o app apresentava falhas inesperadas, o que acabou atrasando a implementação da persistência de dados.

Apesar dos desafios encontrados com a integração do banco de dados SQLite, consegui avançar bastante no desenvolvimento do app.
