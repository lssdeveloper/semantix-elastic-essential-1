# Analyzer - Conceitos
### Principais analyzer
![image](https://user-images.githubusercontent.com/27785070/137135589-fc71d71b-6715-48ce-92a2-73869616eae4.png)
![image](https://user-images.githubusercontent.com/27785070/137135659-b0266c48-ebfb-4ecf-bb3d-134ffb84d300.png)
![image](https://user-images.githubusercontent.com/27785070/137135774-68f44683-b914-4f99-83cc-a6bc227beb42.png)
![image](https://user-images.githubusercontent.com/27785070/137135837-dc6d8222-1c76-40f8-b49c-4cea8fb6c3e9.png)
![image](https://user-images.githubusercontent.com/27785070/137135880-2c3b1872-0c90-45aa-9e26-a56ded9fea03.png)
![image](https://user-images.githubusercontent.com/27785070/137135927-b975bc30-b13b-4463-bfa3-537281c96971.png)
![image](https://user-images.githubusercontent.com/27785070/137135966-d1c7520c-90a5-484f-b3d3-5ae7a74cd401.png)
![image](https://user-images.githubusercontent.com/27785070/137136014-0a53fce8-318a-46dd-8608-f962dbee9a06.png)
![image](https://user-images.githubusercontent.com/27785070/137136047-f583c105-b771-4634-81a7-2a7a5a40ec09.png)
![image](https://user-images.githubusercontent.com/27785070/137136093-039c1454-435a-462d-afcb-c5e59d2cc5f3.png)
![image](https://user-images.githubusercontent.com/27785070/137136147-d29eb274-ce6e-49a3-82ca-31ae28e5dffa.png)
# Correção de Exercícios do Analyzer

**1. Criar os Analyzer simple, standard, brazilian e portuguese para a seguinte frase:**
![image](https://user-images.githubusercontent.com/27785070/137223277-f6da8c24-e356-47b6-938e-edc1ca937950.png)

_O elasticsearch surgiu em 2010_
**2. Realizar os passos no índice produto**

_a) Criar um analyzer brazilian para o atributo descricao_
![image](https://user-images.githubusercontent.com/27785070/137224524-e5db63cc-4b85-43af-8d34-a323546e68d1.png)
![image](https://user-images.githubusercontent.com/27785070/137224696-bcb94108-289f-45e8-b210-52a8c008a83a.png)

_b) Para o atributo descricao aplicar o analzyer brazilian para o tipo de campo text e criar o atributo descricao.original com o dado do tipo keyword_
![image](https://user-images.githubusercontent.com/27785070/137225773-4ac8071c-154e-45e5-8dd8-4546057a121f.png)
![image](https://user-images.githubusercontent.com/27785070/137225883-22e5dc78-4be9-4fad-bba2-2c5be2e5f240.png)
![image](https://user-images.githubusercontent.com/27785070/137225958-2de46e04-696f-4bcc-acad-332a6fd58d6b.png)

_c) Buscar a palavra “compativel” no campo descricao.original (hits = 0)_
![image](https://user-images.githubusercontent.com/27785070/137226221-bb41b37f-9d8f-42d0-a361-96526f7cb95e.png)
_d) Buscar a palavra “compativel” no campo descricao_
![image](https://user-images.githubusercontent.com/27785070/137226312-8ee53105-8b44-4b48-944e-b78b91526a15.png)
# Aggregations - Conceitos Tipos
![image](https://user-images.githubusercontent.com/27785070/137136280-18812866-118c-415e-8b08-b7074808af09.png)
![image](https://user-images.githubusercontent.com/27785070/137136315-63732503-d803-4bbf-b853-70a25cf47d8a.png)
![image](https://user-images.githubusercontent.com/27785070/137136380-bb31ec0f-c7a1-43a3-8180-deddf8038e7f.png)
# Agregações de Métricas
![image](https://user-images.githubusercontent.com/27785070/137136481-4d212a96-e2d2-4170-80fd-d966ea05f776.png)
![image](https://user-images.githubusercontent.com/27785070/137136540-09e92cfe-484b-4db8-9ffb-b8afd6c81860.png)
![image](https://user-images.githubusercontent.com/27785070/137136573-9e778680-dea2-49b1-b0ab-ae08b0ec0ca5.png)
![image](https://user-images.githubusercontent.com/27785070/137136605-4a52d8df-baa3-47fe-a997-80ec9409bd7a.png)
![image](https://user-images.githubusercontent.com/27785070/137136659-c93ac3b4-e744-4c68-b652-e1a69991725a.png)
![image](https://user-images.githubusercontent.com/27785070/137136737-6f041494-521d-40db-9955-b59197811753.png)
# Agregações de Buckets
![image](https://user-images.githubusercontent.com/27785070/137136839-277a4af2-f4dd-4864-bc04-a98798e4dd1d.png)
![image](https://user-images.githubusercontent.com/27785070/137136909-20c535b7-d23a-421f-a875-bb540bff2c4b.png)
![image](https://user-images.githubusercontent.com/27785070/137136963-70f94f68-2aed-4688-a11c-0063540ea7bd.png)
![image](https://user-images.githubusercontent.com/27785070/137137001-ad8aa972-726a-4a9e-8602-b90ac621a87d.png)
![image](https://user-images.githubusercontent.com/27785070/137137040-385814a4-8a22-4bc0-833f-663bf6c5d7d8.png)
![image](https://user-images.githubusercontent.com/27785070/137137226-473642a6-a3cf-4c0f-a43b-fe715cf79401.png)
![image](https://user-images.githubusercontent.com/27785070/137137264-f0a3e50d-7685-460f-8e73-adb0e5290d2a.png)
![image](https://user-images.githubusercontent.com/27785070/137137333-265ac4b2-e0a6-4efb-9f8c-cb5893dfdf8a.png)
 ### Correção Exercícios - Agregações

_**Realizar os exercícios no índice bolsa**_

**1. Calcular a média do campo volume**
![image](https://user-images.githubusercontent.com/27785070/137235943-9cf21c10-82ab-49d9-9bfe-61dc29476128.png)

**2. Calcular a estatística do campo close**
![image](https://user-images.githubusercontent.com/27785070/137237468-b451ac84-bd62-4a5f-ad6e-b665bc8f4d6a.png)

**3. Visualizar os documentos do dia 2019-04-01 até agora. (hits = 3)**
![image](https://user-images.githubusercontent.com/27785070/137241792-3bd51038-e367-4fa8-b92a-7321361f6fad.png)

**4. Calcular a estatística do campo open do período do dia 2019-04-01 até agora**
![image](https://user-images.githubusercontent.com/27785070/137242537-010a7b45-0879-4c37-b0ed-cd933daf32c1.png)

**5. Calcular a mediana do campo open**
![image](https://user-images.githubusercontent.com/27785070/137242884-beb49254-2473-4fe4-80e7-00ee78125b2b.png)

**6. Contar a quantidade de documentos agrupados por ano**
![image](https://user-images.githubusercontent.com/27785070/137243306-f4fb9101-4bff-4bcd-8f6e-fa550ac2f844.png)

**7. Contar a quantidade de documentos de 2 anos atrás até hoje**
![image](https://user-images.githubusercontent.com/27785070/137243774-7950df3e-62be-4db2-959f-7cd5a340f965.png)
