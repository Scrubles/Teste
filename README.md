# Venda Digital

## Carregar taxas do aplicativo

Fazer checkout do branch carga_taxas

```
git checkout carga_taxas
```

Desinstalar a aplicação do dispositivo onde a carga será executada

Renomear o arquivo de taxas recebido para *product\_tax\_paiva.json* e o arquivo de grupo para *group\_profession.json*

Copiar o arquivo *product\_tax\_paiva.json* para o Android Studio, sobrescrevendo os que estão na pasta *assets/mocks*

![](./image1.png?raw=true)

Executar a aplicação e realizar o login com qualquer qualquer usuário

Aguardar o fim da carga e salvar o arquivo em um disco local usando o Android Studio

* Clicar em Device File Explorer

![](./image2.png?raw=true)

* Navegar até *data/data/com.mongeralaegon.vendadigital/files* clicar com o botão direito em *vendadigitaltaxes.realm*

![](./image3.png?raw=true)

* Salvar no disco local

Criar uma nova feature a partir de **develop**, copiar o arquivo *group_profession.json* para a pasta *assets/mocks* e o banco novo para a pasta *assets/database*

![](./image4.png?raw=true)

![](image5.png?raw=true)

Criar o PR da nova feature
