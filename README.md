Passos:
- Ao executar docker-compose -d no **terminal do seu ms** e acessar a porta http://localhost:5050, a interface de login do pgadmin4 será aberta.
- insira seu **PGADMIN_DEFAULT_EMAIL** e **PGADMIN_DEFAULT_PASSWORD** do pgadmin4 que foram definidos no arquivo **docker-compose**
Com isso, seu banco de dados será aberto no pgadmin4.
- Clique em Add Dashboard ou Add Server
- Dê um nome a instância do seu banco.
- Na aba Server, cole o ID do container que foi executado quando o comando docker-compose -d foi acionado.
**Para pegar o ID, abra um novo terminal e digite: docker container ls** copie o id da imagem do postgresql
- cole no primeiro campo o ID copiado
- em name e password, insira root para ambos
- salve

Logo em seguida os database criados no arquivo **init.sql** serão exibidos na instância.
