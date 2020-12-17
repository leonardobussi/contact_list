# Projeto de agenda telefonica

### Documentacao:
*  [Requisito para uso](#requisitos)
*  [Configuracao](#configuracoes)
*  [comando uteis](#uteis)

![Peek 16-12-2020 16-02](https://user-images.githubusercontent.com/54999837/102485623-a1b7d580-4046-11eb-9841-2ec0e1052427.gif)
![Peek 16-12-2020 15-47](https://user-images.githubusercontent.com/54999837/102485628-a3819900-4046-11eb-8282-edcb2b2645a7.gif)


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


![Captura de tela de 2020-12-16 16-35-00](https://user-images.githubusercontent.com/54999837/102485631-a41a2f80-4046-11eb-92ef-3d082f6c7756.png)


#### Uteis

* `bundle install` comando para instalar as depedencias
* `yarn install` comando para instalar dependencia javascript (nodejs)
* `rails db:create` comando para criar o banco de dados
* `rails db:migrate` comando para criar as tabelas no banco de dados
* `rais s` para rodar o servidor
