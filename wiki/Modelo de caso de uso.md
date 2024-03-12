# Modelo de caso de uso 
## 1. Casos de uso de negócio por ator
* Sistema de administracao de finança:
  * Gerar relatório financeiro
  * Alertar gastos excessivos
  * Exibir mensagem de êxito ao registrar despesa
  * Conferir dados inseridos pelo usuário
  * Sincronizar com as contas bancarias
* Usuário:
  * Fazer login
  * Registrar entradas e saídas
  * Categorizar despesas
  * Modificar valores e gastos (caso necessário)
  * Cadastrar contas bancárias
## 2. Casos de uso resumidamente
Gerar Relatório Financeiro: O sistema permite a geração de relatórios financeiros detalhados, apresentando informações sobre gastos, receitas e saldo atual. Esses relatórios são essenciais para fornecer uma visão 
abrangente da situação financeira do usuário ou da empresa.O usuário acessa a função de geração de relatório financeiro no sistema.O sistema processa os dados financeiros registrados e gera um relatório organizado por 
categorias, períodos de tempo ou outros critérios selecionados pelo usuário.O relatório é exibido para o usuário, apresentando informações detalhadas sobre gastos, receitas e saldo, fornecendo insights valiosos para 
análise financeira.

Alertar Gastos Excessivos: O sistema monitora os gastos do usuário e emite alertas quando são identificados gastos que excedem limites predefinidos, ajudando a evitar desperdícios e manter o controle financeiro.O sistema 
monitora continuamente os gastos registrados pelo usuário.Quando um gasto excede um limite definido para uma categoria específica ou globalmente, o sistema emite um alerta ao usuário.O usuário é notificado sobre o gasto 
excessivo, permitindo que tome medidas corretivas para evitar problemas financeiros.

Sincronizar com as Contas Bancárias: O sistema permite a sincronização com as contas bancárias do usuário, facilitando o registro automático de transações e garantindo que os dados financeiros estejam sempre atualizados.O 
usuário acessa a função de sincronização de contas bancárias no sistema.O sistema solicita as credenciais bancárias do usuário de forma segura.O sistema utiliza as credenciais fornecidas para acessar as contas bancárias 
do usuário.As transações bancárias são sincronizadas com o sistema, atualizando automaticamente o registro de gastos e receitas.O usuário pode revisar e categorizar as transações sincronizadas conforme necessário.

Registrar Entradas e Saídas: O usuário registra manualmente suas transações financeiras, incluindo despesas e receitas, para manter um registro completo e preciso de suas atividades financeiras.O usuário acessa a função 
de registro de entradas e saídas no sistema.O usuário insere os detalhes da transação, como descrição, tipo (entrada ou saída), valor e data.A transação é registrada no sistema, atualizando o saldo financeiro do usuário.

Categorizar Despesas: O usuário categoriza suas transações financeiras, facilitando a análise e o controle de gastos e receitas em diferentes áreas da vida financeira.O usuário acessa a função de categorização de despesas 
e ganhos no sistema.O usuário seleciona uma transação registrada e atribui uma categoria a ela, como alimentação, transporte, moradia, salário, entre outras.A transação é associada à categoria selecionada, organizando os 
dados financeiros do usuário para uma melhor compreensão e análise.

Cadastrar Contas Bancárias: O usuário adiciona suas contas bancárias ao sistema, permitindo a sincronização e o registro de transações bancárias para um gerenciamento financeiro mais eficiente.O usuário acessa a função de 
cadastro de contas bancárias no sistema.O usuário fornece os detalhes da conta bancária, como nome do banco, tipo de conta e informações de identificação.As informações da conta bancária são verificadas e validadas pelo 
sistema.A conta bancária é adicionada ao sistema para sincronização e registro de transações, facilitando o acompanhamento das atividades financeiras.

Exibir Mensagem de Êxito ao Registrar Despesa: Após o usuário registrar uma despesa com sucesso no sistema, uma mensagem de êxito é exibida para confirmar que a transação foi concluída com êxito. Essa mensagem proporciona 
uma confirmação visual ao usuário, garantindo que a despesa tenha sido registrada com precisão. Quando o usuário insere os detalhes da despesa e confirma o registro, o sistema processa as informações e verifica se a 
transação foi realizada corretamente. Após a validação dos dados inseridos, o sistema exibe uma mensagem de êxito na interface do usuário, informando que a despesa foi registrada com sucesso. Essa mensagem pode incluir 
informações adicionais, como a categoria em que a despesa foi registrada e o valor gasto, para fornecer ao usuário uma confirmação completa da transação. A mensagem de êxito é apresentada de forma clara e visível na tela 
do sistema, garantindo que o usuário seja informado imediatamente sobre o status positivo do registro da despesa.

Conferir Dados Inseridos pelo Usuário: Antes de confirmar o registro de uma despesa, o sistema verifica os dados inseridos pelo usuário para garantir precisão e consistência. Quando o usuário insere os detalhes da despesa 
e está prestes a confirmar o registro, o sistema inicia automaticamente o processo de verificação dos dados. O sistema analisa a categoria da despesa, o valor gasto e qualquer descrição adicional fornecida pelo usuário. 
Se o sistema detectar algum erro, inconsistência ou potencial problema nos dados inseridos, ele exibe uma mensagem de alerta ao usuário, indicando a natureza do problema e sugerindo correções. O usuário tem a oportunidade 
de revisar os dados e fazer as correções necessárias antes de prosseguir com o registro da despesa. Após a verificação bem-sucedida dos dados inseridos e qualquer correção realizada pelo 
usuário, o sistema permite que o registro da despesa seja confirmado. Ao incorporar a funcionalidade de verificação de dados, o sistema ajuda a garantir a precisão e a consistência dos registros financeiros do usuário, 
garantindo que tudo esteja corretamennte inserido e tudo no local certo.
## 3. Excel do caso de uso principal

![imagem1](https://github.com/weikaixia/DevSistema2/assets/137851402/e49490fa-36fc-4933-9878-6245fdddecd9)

## 4. Diagrama de caso de uso para visualizar os os casos de uso listados no item 1
    
 ![diag-caso-uso-UML](https://github.com/weikaixia/DevSistema2/assets/137851402/9cca8757-fd33-4e86-b886-6bf1854dd7fc)
