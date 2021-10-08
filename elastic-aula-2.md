![image](https://user-images.githubusercontent.com/27785070/136402657-74baa7d6-ebba-44b1-9386-f1cb9fe49286.png)
![image](https://user-images.githubusercontent.com/27785070/136402812-6087f689-e1d3-4749-b723-e6828fb4d2c5.png)
![image](https://user-images.githubusercontent.com/27785070/136402912-732ce6fd-1414-47e8-a328-2496f7dd9583.png)
# Operações básicas - CRUD
![image](https://user-images.githubusercontent.com/27785070/136403063-a6c70444-2f75-4763-87de-a96afa5901b7.png)
![image](https://user-images.githubusercontent.com/27785070/136403107-125b7937-c826-49c6-b738-96a1e9c0b60b.png)
![image](https://user-images.githubusercontent.com/27785070/136403149-929c0bb2-f4ce-4a46-a83b-3d1bf46f12b2.png)
![image](https://user-images.githubusercontent.com/27785070/136403185-9def78f3-f9ba-42d8-a371-6b1845916208.png)
![image](https://user-images.githubusercontent.com/27785070/136403225-53d266fa-8afd-4649-a74f-5a3cdbea4758.png)
# Exercícios CRUD
![image](https://user-images.githubusercontent.com/27785070/136403296-e8536e06-ec7a-460a-b99d-7b5cd1864b9a.png)
# CRUD

#### 1. Criar o índice produto e inserir os seguintes documentos:
![image](https://user-images.githubusercontent.com/27785070/136598573-764431ac-d115-4e82-892e-12183334e15c.png)
![image](https://user-images.githubusercontent.com/27785070/136598614-eeaa4f50-f5bc-401b-9b86-80fbb490b655.png)
![image](https://user-images.githubusercontent.com/27785070/136598717-7ea45840-65bd-4de0-869d-04f66530a6bf.png)
![image](https://user-images.githubusercontent.com/27785070/136598798-b24551cc-d099-4469-be7c-b7f956d5c2b3.png)

#### 2. Verificar se existe o documento com  id 3
![image](https://user-images.githubusercontent.com/27785070/136596445-f3954405-e38b-40dd-b7dc-b26366c02a21.png)

#### 3. Alterar o valor do atributo qtd para 30 do documento com id 3
![image](https://user-images.githubusercontent.com/27785070/136597288-bf64fdcd-e70d-4594-aaf6-46335545d5c0.png)

#### 4. Buscar o documento com id 1
![image](https://user-images.githubusercontent.com/27785070/136597470-996a3add-4f42-4aec-9977-35527f686389.png)

#### 5. Deletar o documento com id 4
![image](https://user-images.githubusercontent.com/27785070/136597663-e17e5ec5-2310-47f6-afa1-48107514370f.png)
![image](https://user-images.githubusercontent.com/27785070/136597754-c4f780e4-d2f9-483d-a6d9-177602bc734b.png)

#### 6. Contar quantos documentos tem o índice produto
![image](https://user-images.githubusercontent.com/27785070/136598031-0e38ad9c-7230-43f8-b6af-7e500415bdd9.png)


# Múltiplas Operações Simultâneas - CRUD
![image](https://user-images.githubusercontent.com/27785070/136403436-a9749914-8b41-4af7-9c91-acbbf5c153c0.png)
![image](https://user-images.githubusercontent.com/27785070/136403484-168fea3f-7d05-4956-8209-2bb8ac94f2f1.png)
# Importação de dados - Kibana
![image](https://user-images.githubusercontent.com/27785070/136403643-1c5cbae3-bb24-4bd2-b345-585402421455.png)
# Exercícios Bulk API e Importação
![image](https://user-images.githubusercontent.com/27785070/136403781-87666a66-8aa9-465b-8a85-d4603423133f.png)
# Bulk API e Importação

#### 1. Importar os dados na Guia Arquivos para os índices

Índice: concessionaria2
dataset/cars.bulk

![image](https://user-images.githubusercontent.com/27785070/136600355-fdd3ac41-d2e7-4606-bc93-ec1086439824.png)
![image](https://user-images.githubusercontent.com/27785070/136600520-41a26db7-0d8f-4ddf-9906-70ab09288ba8.png)
#### Click em import
![image](https://user-images.githubusercontent.com/27785070/136600989-b285cbef-025d-4c27-8ede-9d497e339bc0.png)
![image](https://user-images.githubusercontent.com/27785070/136601092-0960e768-8fd4-455c-9fe7-c3de5d7258d5.png)

Índice: populacao
dataset/populacaoLA.csv
![image](https://user-images.githubusercontent.com/27785070/136601787-a85d21b3-f9f6-4ab7-8651-c6b83c4bce21.png)
![image](https://user-images.githubusercontent.com/27785070/136601956-b0ad10a2-1837-4d24-83bc-c0d20bde1cdc.png)
![image](https://user-images.githubusercontent.com/27785070/136602040-a8909bfc-bade-43b8-b438-74d82b8709ee.png)
![image](https://user-images.githubusercontent.com/27785070/136602111-b0a146a2-ce09-4a89-8c9d-9b59ffc84912.png)
![image](https://user-images.githubusercontent.com/27785070/136602179-826290c6-9b81-4a71-89c9-045c122ce269.png)

#### 2. Executar as consultas
![image](https://user-images.githubusercontent.com/27785070/136602490-f889778f-f586-4343-9db7-770f304c281f.png)

Contar o número de documentos de cada um dos novos índices
![image](https://user-images.githubusercontent.com/27785070/136602611-01026dfc-0224-44df-8905-d5b364cc2d94.png)
![image](https://user-images.githubusercontent.com/27785070/136602731-322efdf9-7d52-4064-a2b5-c42fe6a17279.png)

Mostrar todos os documentos de cada um dos novos índices
![image](https://user-images.githubusercontent.com/27785070/136603122-14635353-8fcb-44cb-b491-7ba70a217954.png)
![image](https://user-images.githubusercontent.com/27785070/136603198-fff475cb-4da4-48ef-b731-0efd4445a4b7.png)


