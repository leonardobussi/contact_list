# Projeto de agenda telefonica

### Documentacao:
*  [Requisito para uso](#requisitos)
*  [Configuracao](#configuracoes)
*  [comando uteis](#uteis)

![Peek_16-12-2020_15-47](/uploads/0bbee24604881dc116d9d6665ef8c50e/Peek_16-12-2020_15-47.gif)

![Peek_16-12-2020_16-02](/uploads/40be2864110215fe9e6d67922ad6625f/Peek_16-12-2020_16-02.gif)


## Requisitos

#### Banco de dados:


Esse projeto está configurado para o postgresql(caso opte pelo postgresql 
verifique se o mesmo está instalado em sua maquina), mas é possivel usar outros
banco SQL.

#### Versão do ruby, rails, nodejs e yarn

versao usada no projeto `ruby 2.7.2`, `rails 6.0.3.2`, `nodejs 14.15.2` e `yarn 1.11.5`


#### Configuracoes:

* Postgresql:
    * vá até a pasta `config` e abra o arquivo database.yml, dentro de desse arquivo vai ter o bloco de configuração do banco de desenvolvimento, coloque suas credenciais, como no exemplo abaixo.


![Captura_de_tela_de_2020-12-16_16-35-00](/uploads/449e3fce1d74c89222ca91b6162e867f/Captura_de_tela_de_2020-12-16_16-35-00.png)


#### Uteis

* `bundle install` comando para instalar as depedencias
* `yarn install` comando para instalar dependencia javascript (nodejs)
* `rails db:create` comando para criar o banco de dados
* `rails db:migrate` comando para criar as tabelas no banco de dados
* `rais s` para rodar o servidor