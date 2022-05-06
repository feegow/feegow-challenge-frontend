# Feegow Challenge

O objetivo é avaliar sua experiência em resolver problemas e escrever código de fácil manutenção. Por ser uma prova de front-end também desejamos que o layout seja agradável, por mais que isso seja relativo :)


## Apresentação do problema

A clínica _Exemplo_ precisa exibir a listagem de seus médicos separados por especialidade em seu site para que seus pacientes tenham acesso. Essa clínica utiliza o Feegow que possui toda a api necessária para isso,. 

  1- A tela inicial deve ser um SELECT contendo a listagem de todas as especialidades que a clínica trabalha. 
  
  ![Exemplo do SELECT](https://image.prntscr.com/image/krKCLaZGT1O3rf4h4ETLow.png)
  
  
  2- Quando o usuário escolhe uma especialidade, deverá ser listado apenas os profissionais que possuem a especialidade selecionada. 

  ![Exemplo do SELECT](https://image.prntscr.com/image/v4cm7l99TOuvcyhHuIgaJw.png)

  3- Quando o usuário clica em "AGENDAR", deverá ser exibido um formulário que o usuário irá preencher e clicar em "ENVIAR".
  Obs: A listagem do campo "Como conheceu" deve vir da api de lista de origens  

  ![Exemplo do SELECT](https://image.prntscr.com/image/w34r0YIUQsmlJcq7DcaIQA.png)
  
  4- Quando o usuário enviar, deverá salvar no localStorage o formulário com os valores **specialty_id, professional_id, name, cpf, source_id, birthdate e date_time**.
  
  5- Após salvar as informações, deverá ser exibido uma notificação ao usuário informando que os dados foram salvos com sucesso.

  6- **OPCIONAL** Deverá ser desenvolvido também uma tela com a listagem dos agendamentos, com "Nome do Paciente", "Nome do Profissional, "Nome da Especialidade", "Nome da Origem" ,"CPF" e "Data de Nascimento"


## Apis:

  Lista de especialidades: ``GET https://demo4450529.mockable.io/feegow-challenge/specialties/list``
  
  Lista de profissionais: ``GET https://demo4450529.mockable.io/feegow-challenge/professional/list``
  
  Lista de Origens: ``GET https://demo4450529.mockable.io/feegow-challenge/patient/list-sources``



## Tecnologias usadas

Os pré-requisitos para a aplicação:

- Utilize React JS ou Javascript Vanila.
- Documentação README.md sucinta e explicativa de como rodar seu código e levantar os ambientes.

## Avaliação

- Enviar o repositório git para welcome.tech@feegow.com.br.

## Dicas

- Aproveite os recursos das ferramentas que você está usando. Diversifique e mostre que você domina cada uma delas.
- Tente escrever seu codigo o mais claro e limpo possível. Código deve ser legível assim como qualquer texto dissertativo.
- Se destaque mostrando algo interessante e surpreendente. Isso sempre fará diferença.

Qualquer dúvida técnica, envie uma mensagem para welcome.tech@feegow.com.br.

Você terá 4 dias para fazer esse teste, a partir do recebimento deste desafio. Sucesso!
