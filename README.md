
# Aplicativo Planetas


O Plantetas é um aplicativo criado com o objetivo de ajudar você a cuidar das suas plantas. Desenvolvido com Flutter e Dart, o app permite adicionar plantas, configurar lembretes para cuidados específicos e acompanhar o status das suas plantas, como quando regar ou fertilizar. A ideia é tornar o cuidado com as plantas mais fácil e organizado, para que nenhuma planta seja esquecida.

Desafios Encontrados:

Durante o desenvolvimento, encontramos alguns desafios ao tentar integrar o banco de dados SQLite, que era essencial para armazenar as informações das plantas de forma persistente. Aqui estão os principais obstáculos:

Problemas com as dependências do SQLite: Tivemos dificuldades para integrar o pacote sqflite corretamente no Flutter, o que gerou alguns erros ao tentar armazenar e acessar dados no banco.

Conexão com o Banco de Dados: O app não estava conseguindo se conectar ao SQLite devido a configurações incorretas, principalmente em relação às permissões necessárias para o Android e iOS.

Dificuldades na migração de dados: Quando tentamos modificar a estrutura do banco de dados ou migrar dados existentes, o app apresentava falhas inesperadas, o que acabou atrasando a implementação da persistência de dados.

Conclusão:

Apesar dos desafios encontrados com a integração do banco de dados SQLite, conseguimos avançar bastante no desenvolvimento do app. A persistência de dados ainda está sendo trabalhada, mas estamos comprometidos em corrigir os problemas e em breve teremos uma versão estável do Plantetas, com todas as funcionalidades planejadas, incluindo o armazenamento das informações das plantas.

