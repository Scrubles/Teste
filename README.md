# Venda Digital

## Carregar taxas do aplicativo

1. Fazer checkout do branch carga_taxas
    ```
    git checkout carga_taxas
    ```

2. Desinstalar a aplicação do dispositivo onde a carga será executada

3. Renomear o arquivo de taxas recebido para *product\_tax\_paiva.json* e o arquivo de grupo para *group\_profession.json*

4. Copiar o arquivo *product\_tax\_paiva.json* para o Android Studio, sobrescrevendo os que estão na pasta *assets/mocks*

    ![](./image1.png?raw=true)

5. Executar a aplicação e realizar o login com qualquer qualquer usuário

6. Aguardar o fim da carga e salvar o arquivo em um disco local usando o Android Studio

    6.1 Clicar em Device File Explorer

    ![](./image2.png?raw=true)

    6.2 Navegar até *data/data/com.mongeralaegon.vendadigital/files* clicar com o botão direito em *vendadigitaltaxes.realm*

    ![](./image3.png?raw=true)

    6.3 Salvar no disco local

7. Criar uma nova feature a partir de **develop**, copiar o arquivo *group_profession.json* para a pasta *assets/mocks* e o banco novo para a pasta *assets/database*

    ![](./image4.png?raw=true)

    ![](./image5.png?raw=true)

8. Criar o PR da nova feature
