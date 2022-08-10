# Especificações do Projeto

Com base nos estudos e pesquisas desenvolvidas pelo grupo em parceria com potenciais usuários, levando em consideração suas necessidades e dificuldades do dia a dia na obtenção de créditos oriundos de empréstimos, podemos agora consolidar estas propostas de melhoria na forma de _personas_ e _histórias de usuário_.

## Personas

As personas inclusas durante o processo de pesquisa e desenvolvimento do problema são apresentadas nas imagens a seguir:

## `TAMIRES LETICIA DE MELLO`

| ![persona 1-edit](https://user-images.githubusercontent.com/93105125/163296843-f40d3ca4-f3cb-4659-ad5f-775d53c7b8c4.png) | Tamires Leticia de Mello, 32 anos                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------     |
| Ocupação                                    | Designer de bolsas e sapatos - Pessoa Física                                                                                           
| Credit Score                                |  900/1000                                                                   
| Motivações | Obter crédito via empréstimo de forma remota e sem a necessidade do deslocamento presencial voltado às pessoas físicas de modo à impulsionar as suas atividades como designer de bolsas e sapatos  
| Restrições anteriores de crédito em seu nome | Não                                                                                        
| Frustrações |  Ainda que possua um elevado Credit Score e não possua restrições anteriores de crédito em seu nome, encontra dificuldade em adquirir empréstimos nas empresas tradicionais, pois, por ser autônoma, estas empresas exigem a sua presença física para análise e eventual concessão da linha de crédito, o que gera grande dificuldade, dado que, por trabalhar sozinha, o deslocamento muitas vezes nos grandes centros urbanos 

## `Leonardo Jacques`

| ![persona 2-edit](https://user-images.githubusercontent.com/93105125/163297709-eadeb0bb-c882-4206-b2eb-fc9cc769bd57.png) | Leonardo Jacques, 36 anos                                                                                |
| ------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| Ocupação                    | Operador de máquinas CNC  
| Credit Score                |        850/1000            |
| Motivações                  |      Conseguir a liberação de linha de crédito para a quitação de seu financiamento imobiliário           |
| Frustações                  |      Até o momento não encontrou  junto às empresas tradicionais do segmento um aplicativo com a opção para financiamento imobiliário de maneira específica             |



## `Geneci dos Santos`

| ![persona 4-edit](https://user-images.githubusercontent.com/93105125/163298133-dc2a571d-5b3e-4c43-9ad8-7cd4df1b4f95.png) | Geneci dos Santos, 63 anos                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| Ocupação            | Recém-aposentada |                                                                                                 
| Credit Score        | 850/1000                                                                                                                
| Motivações          | Deseja obter um empréstimo via aplicativo para realizar um tratamento médico, pois, não possui plano de saúde 

| Frustrações?        |   Como não domina o uso de novas tecnologias, precisa de um aplicativo que ofereça praticidade e facilidade em seu uso                                                                                                                       

## `Rafael Luis`

| ![persona 3-edit](https://user-images.githubusercontent.com/93105125/163298476-3d2c9ee8-36b1-4f8a-bc09-eeaef548c772.png) | Rafael Luis, 35 anos                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| Ocupação                                                                                                                 | Técnico em informática                                                                                                         |
| Aplicativos preferidos                                                                                                   | Facebook, Watsapp, LinkedIn e aplicativos de bancos                                                                            |
| Motivações                                                                                                               | Já ativo no mercado digital, na posição de empresário, busca diversificar suas fontes de renda em investimentos mais dinâmicos |
| Seus Hobbies                                                                                                             | Futebol com os amigos, ir ao estádio do seu time e estar com sua esposa e filha                                                |
| Frustrações?                                                                                                             | Não conseguir acompanhar sua carteira de criptomoedas de forma rápida e consistente                                            |

## Histórias de Usuários

A partir do entendimento das necessidades expostas por cada persona, registramos então as seguintes histórias de usuários.

| Eu como...`PERSONA`      | ...quero/desejo...`FUNCIONALIDADE`                                                                                              | ... para...`MOTIVO/VALOR`                                                                                |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Tamires Leticia de Mello | Obter empréstimo de forma totalmente remota | Evitar o deslocamento físico e dedicar mais tempo ao seu trabalho                    |
| Leonardo Jacques         | Obter empréstimo para saldar o seu financiamento imobiliário | Necessita de agilidade e singularidade, pois, até o momento não encontrou um aplicativo que possua a opção de empréstimo voltado especificamente à quitação de financiamento imobiliário, o que por ser mais direcionado, poderia ensejar melhores condições de pagamento.
| Geneci dos Santos        | Uma ferramenta que permita a concessão de empréstimo de forma fácil e simples  | 
 A conclusão do empréstimo via aplicativo com menos etapas possíveis              

| Rafael Luis              | Uma ferramenta de fácil visualização da cotação das criptomoedas                                                                | Agilizar a tomada de decisão de qual moeda investir                                                      |
| Rafael Luis              | Realizar a pesquisa do valor de uma criptomoeda específica                                                                      | Localizar rapidamente uma moeda que já é de seu interesse ou de sua carteira                             |
| Rafael Luis              | Utilizar a ferramenta também pelo celular                                                                                       | Se manter informado em momentos que não tiver acesso ao desktop                                          |
| Rafael Luis              | Cadastrar sua carteira composta por criptoativos e moedas fiduciárias e comparar valores fazendo conversões de forma rápida     | cotar o valor de sua carteira em uma moeda ou criptoativo de sua escolha                                 |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID     | Descrição do Requisito                                                                                                                                                                                                | Prioridade |
| ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| RF-001 | O site apresentará na página principal as opções de serviço disponíveis. São elas: conversão de valores e monitoramento do mercado.                                                      | ALTA       |
| RF-002 | O site permitirá ao usuário informar a moeda fiduciária e/ou criptoativo "de entrada” e a moeda fiduciária e/ou criptoativo "alvo” para conversão.                                                                    | ALTA       |
| RF-003 | O site terá uma página em que será possível acompanhar a cotação das criptomoedas no mercado financeiro.                                                                                                              | BAIXA      |
| RF-004 | O site terá uma página em que será possível acessar um formulário de contato para que o usuário possa enviar dúvidas, sugestões ou críticas aos desenvolvedores do projeto.                                           | MÉDIA      |
| RF-005 | Os campos presentes no formulário de contato são de preenchimento obrigatório, salvo o referente ao número de telefone, o que traz mais credibilidade ao contato do usuário, bem como minimiza o recebimento de spam. | ALTA       |

### Requisitos não Funcionais

| ID      | Descrição do Requisito                                                                      | Prioridade |
| ------- | ------------------------------------------------------------------------------------------- | ---------- |
| RNF-001 | O site deverá ser publicado na internet.                                                    | MÉDIA      |
| RNF-002 | O site deverá ser responsivo e poderá ser acessado em diversos dispositivos e equipamentos. | MÉDIA      |
| RNF-003 | O site deverá ser compatível com diversos navegadores                                       | MÉDIA      |

## Restrições

As questões que limitam a execução desse projeto e que se configuram como obrigações claras para o desenvolvimento do projeto em questão são apresentadas na tabela a seguir.

| ID    | Descrição da Restrição                                       |
| ----- | ------------------------------------------------------------ |
| RE-01 | O projeto deverá ter seu código versionado utilizando Git.   |
| RE-02 | A equipe não deve terceirizar o desenvolvimento do trabalho. |
| RE-03 | Não haverá investimento financeiro no projeto.               |
