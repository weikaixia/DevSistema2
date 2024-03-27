
<div align="center">

### **Especificação de requisitos**

</div>



### Histórico de Revisões


| Versão | Data | Descrição |
|----------|----------|----------|
| Minuta da concepção   | 26/03/2024   | Primeira minuta. A ser refinada, principalmente durante a elaboração.   |







## Introdução
Este documento é o repositório de todos os requisitos do Sistema gerenciador financeiro não documentados nos casos de uso

## Requisitos funcionais
1. O sistema deve permitir que o usuário se cadastre
2. Exibir tipos de despesas.
3. Permitir que o usuário escolha as despesas.
4. Possibilitar ao usuário a alteração dessas despesas.
5. Permitir que o usuário cadastre cartões de crédito.
6. Exibir feedback.


<br>

## Requisitos não funcionais
1. Desempenho : 
    * O sistema deve ser responsivo, com tempos de carregamento rápidos para todas as funcionalidades, garantindo uma experiência de usuário ágil e sem interrupções.

    * As consultas de relatórios e análises devem ser processadas de forma eficiente, mesmo em conjuntos de dados volumosos, para proporcionar respostas rápidas aos usuários.

2. Segurança:
   * Todos os dados financeiros dos usuários devem ser protegidos por criptografia robusta em repouso e em trânsito, garantindo a confidencialidade e integridade das informações.
   * O sistema deve implementar medidas de segurança para prevenir acesso não autorizado, como autenticação multifatorial e controle de acesso baseado em funções.
   * Deve haver um sistema de monitoramento e detecção de intrusos para identificar e responder a qualquer atividade suspeita.

3. Disponibilidade:
   * O sistema deve garantir alta disponibilidade, com tempo de inatividade planejado mínimo para manutenções programadas.
    * Deve ser implementado um sistema de backup e recuperação para proteger os dados contra perdas acidentais e garantir a continuidade do serviço em caso de falha.

4. Conformidade:
   * O sistema deve cumprir com regulamentações financeiras relevantes, como PCI-DSS (Padrão de Segurança de Dados do Setor de Cartões de Pagamento), garantindo a segurança das transações com cartão de crédito.
    * Deve haver uma política clara de privacidade e conformidade com o GDPR (Regulamento Geral de Proteção de Dados) para proteger os direitos dos usuários em relação aos seus dados pessoais.


## Regras de negócio
1. *Benefício Empresarial*: Os clientes que utilizarem o aplicativo de controle de gastos regularmente e alcançarem metas específicas de economia serão elegíveis para benefícios exclusivos, como agilidade em serviços.
2. *Gestão de Patrimonio*: Os usuários que conseguirem economizar uma quantia pré-determinada de dinheiro ao longo de um período especificado receberão incentivos adicionais, como cashback ou acesso a recursos premium dentro do aplicativo.
3. *Singularidade do Usuário*: É permitido apenas o registro de um usuário vinculado a um único CPF, garantindo a individualidade e segurança das informações financeiras de cada usuário. Esta implementação evita duplicação de contas e garante a integridade dos dados.
