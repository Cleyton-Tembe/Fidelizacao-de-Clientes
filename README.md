# Fidelizacao-de-Clientes
Aplicativo feito com a framework spring boot em contexto de controlar transacoes e recompensar os usuarios por tal feito. Quanto mais o usuario usa os nossos servicos ele acumula pontos para posteriomente usa-los para beneficio em nossos servicos.

Instrucoes para coloca-lo a funcionar:
1-Primeiro tera que ter um server mysql a correr em sua maquina
2-No directorio src/main.applicactionproperties tera que editar os campos:
        spring.datasource.url=jdbc:mysql://localhost:3306/fid_database
        spring.datasource.username=root
        spring.datasource.password=ERRON.sql.01
  Para as credencias do seu servidor mysql

3- Crie uma base dados com um nome a sua escolha depois passe no url do spring.datasource.url= ..../nome da sua base dados
  
4-Devido ao uso de Spring Security se por acaso apenas obtiver uma pagina sem link para registro entao tera que na pagina obtida inserir as seguintes credencias:
            username:admin
            password:admin
Feito isso caso nao esteja na pagina de login personalizada tera que colocar a url manualmente localhost:8080/Mylogin

5-Caso tenha logado com sucesso se a pagina principal nao processar tambem tera que colocar manualmente localhost:8080/index

6- Enjoy the Experience
