# Venda Digital

## Carregar taxas do aplicativo

1. Fazer checkout do branch carga_taxas

        git checkout carga_taxas

2. Desinstalar a aplicação do dispositivo onde a carga será executada

3. Renomear o arquivo de taxas recebido para *product\_tax\_paiva.json* e o arquivo de grupo para *group\_profession.json*

4. Copiar os arquivos *product\_tax\_paiva.json* e *group\_profession.json* para o Android Studio, sobrescrevendo os que estão na pasta *assets/mocks*

    ![Step 4](step4.png?raw=true)

5. Executar a aplicação e realizar o login com qualquer qualquer usuário

6. Aguardar o fim da carga e salvar o arquivo em um disco local usando o Android Studio

    6.1 Clicar em Device File Explorer

    ![Step 6.1](step6_1.png?raw=true)

    6.2 Navegar até *data/data/com.mongeralaegon.vendadigital/files* clicar com o botão direito em *vendadigitaltaxes.realm*

    ![Step 6.2](step6_2.png?raw=true)

    6.3 Salvar no disco local

7. Criar uma nova feature a partir de **develop**, copiar o arquivo*group_profession.json*para a pasta *assets/mocks* e o banco novo para a pasta *assets/database*

    ![Step 7(1)](step7(1).png?raw=true)

    ![Step 7(2)](step7(2).png?raw=true)

8. Criar o PR da nova feature
