#Medicinia-Test
Teste de desenvolvimento para ser um MED.

Requisitos
======
A aplicação deve ser desenvolvida preferencialmente com Angular (https://angular.io/) [mas sinta-se à vontade para utilizar a tecnologia que melhor lhe agradar] e deve possuir todas as funcionalidades exemplificadas no [mockup](https://xd.adobe.com/view/100570a7-37cb-488e-abde-d11535c9be9d/):

 0. Página com uma experiência agadável em qualquer dispositivo; 
 1. Três tipos de notificações (Consulta, Cirurgia e Exame);
 2. Listagem de notificações;
 3. Filtro por tipo de notificação (e por 'status' - favorita, arquivada);
 4. Criação de uma nova notificação com atualização da listagem de forma assíncrona;
   * A utilização de um serviço webhook ([Pusher](https://pusher.com/), [hook.io](https://hook.io/)) será vista com bons olhos.
 5. [Plus] Criação de *tags* no perfil de cada paciente
 6. [Plus] Criação/Edição de *dados genéricos* (notes na API) no perfil de cada paciente
 7. Os dados devem ser persistidos;
 8. Documentação de como rodar sua aplicação.

Desejável
======

 * Validação dos formulários.

API
======
Documentação da API para construção do Mockup

###### Base URL
https://medicinia-e04e.restdb.io/rest

###### Header padrão para requisições
**x-apikey:** 69d03052a08ad4496ce4758478c0aafd085ab

**content-type:** application/json

**Cache-Control:** no-cache

#### Swagger
[Link API](https://medicinia-e04e.restdb.io/apps/swagger/?url=https://medicinia-e04e.restdb.io/rest/_swagger.json)

https://medicinia-e04e.restdb.io/rest/_jsapi.doc
##### Notificações
https://medicinia-e04e.restdb.io/rest/_jsapi.doc#notification
##### Pacientes
https://medicinia-e04e.restdb.io/rest/_jsapi.doc#patients
##### Notas - Dados Genéricos
https://medicinia-e04e.restdb.io/rest/_jsapi.doc#notes
##### Tags
https://medicinia-e04e.restdb.io/rest/_jsapi.doc#tags

 
Mockup
======
Link para o [mockup](https://xd.adobe.com/view/100570a7-37cb-488e-abde-d11535c9be9d/)

<b>Ícones para desenvolvimento do layout</b><br>
Não é necessário utilizar os mesmos ícones do mock.<br>
Sugestão para substituição: [Flaticon](https://www.flaticon.com)

Avaliação
======
Nós avaliaremos o seu código seguindo os seguintes critérios:

**Legibilidade**

O código é de fácil manutenção? O código é legível e semântico?

**Organização**

Como foi pensada a arquitetura? Foi utilizado alguma metodologia de organizacao no CSS?

**Qualidade**

Foram criados testes? Os testes são de simples manutenção, caso seja necessário alterar alguma funcionalidade?

**Desempenho**

A performance foi considerada?

Bom Trabalho!
======

Você é livre para incrementar seu teste de modo a demonstrar como o resultado do seu esforço pode deixá-lo ainda melhor!
