---
title: Ian Sommerville Exercicios
date: 23-05-2024
tags:
  - software_engineering
  - sommerville
  - pt
index: "[[software engineering]]"
---

# Ian Sommerville Exercicios
## Cap - 2 & 3

### 3.1 Explique por que, para as empresas, a entrega rápida e implantação de novos sistemas frequentemente é mais importante do que a funcionalidade detalhada desses sistemas.
Quando se trata de um sistema de pequeno/médio porte, acaba se perdendo muito tempo analisando seus requisitos e pouco tempo realmente produzindo algo. 

### 3.2 Explique como os princípios básicos dos métodos ágeis levam ao desenvolvimento e implantação de software acelerados.
1. **Pessoas e não processos**
	- As habilidades da equipe de software tem que ser exploradas e devem criar suas próprias maneiras de trabalhar, sem processos prescritivos.
2. **Envolvimento do cliente**
	- Ao invés de criar contratos durante longas negociações com o cliente, no desenvolvimento ágil os clientes participam diretamente do desenvolvimento do software. Assim podem dizer o que querem e o que não querem diretamente para o time de desenvolvimento.
3. **Aceitar as mudanças**
	- No desenvolvimento ágil o software vai sempre estar em constante mudança, ao invés de estar seguindo um contrato estrito. 
4. **Software ao invés de  documentação** 
	  - No desenvolvimento ágil é muito comum que a documentação seja deixada de lado, já que custa tempo dos desenvolvedores e por muitas vezes não é nem utilizada. 
### 3.3 Quando você não recomendaria o uso de um método ágil para o desenvolvimento de um sistema de software?
Quando se trata de times que estão geograficamente dispersas, já que fica mais difícil de coordenar os times desta maneira. 
Além disto métodos ágeis devem ser evitados para programas críticos, já que não seguem um plano e abrem margem para erros. Porem alguns princípios podem sim ser seguidos, como por exemplo o desenvolvimento test-first

### 3.4 Extreme Programming expressa os requisitos dos usuários como histórias, com cada história escrita em um cartão. Discuta as vantagens e desvantagens dessa abordagem para a descrição de requisitos.
1. **Vantagens**
	 - Eles representam situações reais, então o sistema irá dar suporte para as ações mais frequentes dos usuários. 
	 - É fácil para os usuários entenderem as historias. 
2. **Desvantagens**
	  - Podem ser incompletos, e por conta de sua natureza informal pode ser difícil detectar isto.
	  - Focam somente em requisitos funcionais
	  - A relação 

### 3.5 Explique por que o desenvolvimento test-first ajuda o programador a desenvolver um melhor entendimento dos requisitos do sistema. Quais são as potenciais dificuldades com o desenvolvimento test-first?
Como os testes são escritos antes da implementação, eles podem ser utilizando enquanto o software esta sendo desenvolvido e isto ajuda a mante-lo fiel aos requisitos. A principal dificuldade é conseguir com que os clientes trabalhem com a equipe pela maior quantidade de tempo possível. 

### 3.6 Sugira quatro razões pelas quais a taxa de produtividade de programadores que trabalham em pares pode ser mais que a metade da taxa de produtividade de dois programadores que trabalham individualmente.
1. Encoraja a refatoração do código já que ele tem que estar legível para a outra pessoa. 
2. Leva a fazer reviews mais frequentes do código, assim achando bugs mais facilmente.
3. Geralmente faz com que o foco seja totalmente no desenvolvimento das funcionalidades essenciais para o programa, e não em otimizações que não beneficiam a equipe. 

### 3.7 Compare e contraste a abordagem Scrum para o gerenciamento de projetos com abordagens convencionais dirigida a planos, como discutido no Capítulo 23. As comparações devem ser baseadas na eficácia de cada abordagem para o planejamento da alocação das pessoas nos projetos, estimativa de custos de projetos, manutenção da coesão da equipe e gerenciamento de mudanças no quadro da equipe do projeto.
#### Planejamento da Alocação das Pessoas nos Projetos
No Scrum, as pessoas são alocadas a sprints curtos (geralmente de duas a quatro semanas). A alocação é revisada a cada sprint, permitindo ajustes rápidos com base na carga de trabalho e nas necessidades do projeto.
As abordagens tradicionais geralmente envolvem um planejamento inicial detalhado, com a alocação de pessoas definida para a duração completa do projeto. Mudanças são menos frequentes e requerem processos formais de replanejamento.
#### Estimativa de Custos de Projetos
O Scrum usa estimativas incrementais e baseadas em histórias de usuário para cada sprint. Isso permite revisões e ajustes contínuos, proporcionando uma visão mais precisa e atualizada dos custos ao longo do projeto.
As abordagens tradicionais fazem estimativas detalhadas do custo do projeto logo no inicio, é menos adaptável a mudança. 
#### Manutenção da Coesão da Equipe
As reuniões diárias (Daily Scrum) e as revisões de sprint promovem a comunicação constante e a colaboração dentro da equipe, fortalecendo a coesão.As equipes Scrum são autônomas e empoderadas para tomar decisões, o que aumenta a motivação e o engajamento dos membros.
Nas abordagens mais tradicionais a coesão da equipe depende da eficácia da comunicação entre diferentes níveis hierárquicos. A colaboração pode ser menos intensa devido à separação clara de funções e responsabilidades. Além disto a comunicação tende a ser mais formal.
#### Gerenciamento de Mudanças no Quadro da Equipe do Projeto
Mudanças na equipe podem ser rapidamente acomodadas devido à natureza iterativa e ágil do Scrum. Novos membros podem ser integrados a cada sprint, e a equipe pode reconfigurar suas responsabilidades conforme necessário.As retrospectivas após cada sprint ajudam a resolver problemas.
Nos métodos mais tradicionais as mudanças requerem planejamento e realocação de recursos.Qualquer mudança significativa no quadro da equipe pode exigir aprovação formal e reestruturação do plano do projeto, o que pode afetar a agilidade na resposta a novas condições.

### 3.8 Você é um gerente de software em uma empresa que desenvolve softwares críticos de controles para aeronaves. Você é responsável pelo desenvolvimento de um sistema de apoio ao projeto de software que dá suporte para a tradução de requisitos de software em uma especificação formal de software (discutido no Capítulo 13). Comente sobre as vantagens e desvantagens das estratégias de desenvolvimento a seguir:
a) Coletar dos engenheiros de software e stakeholders externos (como a autoridade regulatória de certifica-
ção) os requisitos para um sistema desse tipo e desenvolver o sistema usando uma abordagem dirigida a
planos.
b) Desenvolver um protótipo usando uma linguagem de script, como Ruby ou Python, avaliar esse protóti-
po com os engenheiros de software e outros stakeholders e, em seguida, revisar os requisitos do sistema.
Desenvolver novamente o sistema final, usando Java.
c) Desenvolver o sistema em Java, usando uma abordagem ágil com um usuário envolvido na equipe de
desenvolvimento.

### 3.9 Tem-se sugerido que um dos problemas de se ter um usuário participando de uma equipe de desenvolvimento de software é que eles ‘se tornam nativos’, ou seja, adotam a perspectiva da equipe de desenvolvimento e perdem de vista as necessidades de seus colegas usuários. Sugira três maneiras de evitar esse problema e discuta as vantagens e desvantagens de cada abordagem.
1. Envolver múltiplos usuários no desenvolvimento. Isto pode ser bom pois a equipe de desenvolvimento teria diversos pontos de vista para analisar, a desvantagem é que podem haver conflitos entre os usuários. 
2. Estar constantemente mudando os usuários também pode ser uma boa abordagem, também provendo para  a equipe múltiplas perspectivas. Porem pode haver conflito entre usuários. 
3. Validar as sugestões também pode ser uma boa estrategia, porem desacelera o processo. 
### 3.10 Para reduzir os custos e o impacto ambiental das viagens, sua empresa decide fechar uma série de escritórios e dar suporte ao pessoal para trabalhar em casa. No entanto, a gerência sênior que introduz essa política não está ciente de que o software é desenvolvido por métodos ágeis, que contam com equipe trabalhando no mesmo local, e a programação em pares. Discuta as dificuldades que essa nova política pode causar e como você poderia contornar esses problemas.
A comunicação direta e informal é um ponto-chave para as metodologias ágeis, e a falta dessa comunicação pode comprometer a entrega do projeto. Além disso, é necessário que os programadores estejam sempre se comunicando entre si e saibam o que seus colegas estão fazendo. Para resolver esses problemas, ferramentas como Zoom ou Microsoft Teams podem ser utilizadas para manter a comunicação em tempo real. Ferramentas como Visual Studio Code Live Share facilitam o desenvolvimento cooperativo, enquanto ferramentas como Git são essenciais para o controle de versão do projeto, permitindo um desenvolvimento de software eficiente em equipe. 

## Cap - 4
### 4.1  Identifique e descreva brevemente os quatro tipos de requisitos que podem ser definidos para um sistema computacional.
- **Requisitos funcionais**: Declaração dos serviços que o sistema deve ter e como o sistema deve reagir em determinadas situações.
- **Requisitos não funcionais**: Restrições para os serviços que irão ser implementados pelo sistema. Normalmente requisitos não funcionais se aplicam ao sistema como um todo.
- **Requisitos de usuário**: Representação ,com linguagem natural, das funções que o sistema deve ter e suas restrições.
- **Requisitos de sistema**: Os requisitos de sistema são versões expandidas dos requisitos de usuário, usados por engenheiros de software como ponto de partida para o projeto do sistema. Eles acrescentam detalhes e explicam como os requisitos de usuário devem ser atendidos pelo sistema
### 4.2 Descubra ambiguidades ou omissões nas seguintes declarações de requisitos para parte de um sistema de emissão de bilhetes
**Um sistema automatizado para emitir bilhetes vende bilhetes de trem. Os usuários selecionam seu destino e inserem um cartão de crédito e um número de identificação pessoal. O bilhete é emitido, e sua conta de cartão de crédito, cobrada. Quando o usuário pressiona o botão de início, é ativado um display de menu de destinos possíveis, junto com uma mensagem ao usuário para selecionar um destino. Uma vez que o destino tenha sido selecionado, os usuários são convidados a inserir seu cartão de crédito. Sua validade é verificada e, em seguida, é solicitada ao usuário a entrada de um identificador pessoal. Quando a operação de crédito é validada, o
bilhete é emitido.**
- **Falta de clareza sobre a ordem de validação:** A etapa de validação do cartão de crédito ("Sua validade é verificada") e a etapa de entrada do PIN ("em seguida, é solicitada ao usuário a entrada de um identificador pessoal") não estão claramente definidas na ordem em que ocorrem. É crucial determinar se a validação do cartão de crédito acontece antes da entrada do PIN ou vice-versa.
- **Falta de informação sobre o tratamento de erros:** O que acontece se o cartão de crédito for inválido? Se o PIN estiver incorreto? O sistema deve exibir mensagens de erro claras e indicar ao usuário como proceder em cada caso.
- **Falta de requisitos não funcionais:** As declarações focam apenas nos requisitos funcionais do sistema, mas não abordam aspectos como desempenho, segurança, usabilidade, etc. É crucial definir esses requisitos para garantir que o sistema atenda às expectativas dos usuários.
### 4.3 Reescreva a descrição anterior usando a abordagem estruturada descrita neste capítulo. Resolva, de um modo apropriado, as ambiguidades identificadas.
**1. Introdução:**

* **Objetivo:** Descrever os requisitos funcionais e não funcionais para um sistema automatizado de emissão de bilhetes de trem.
* **Público-alvo:** Desenvolvedores de software, analistas de negócios e usuários finais.
* **Escopo:** Esta descrição abrange o processo de compra de bilhetes, desde a seleção do destino até a emissão do bilhete e a cobrança do cartão de crédito.

**2. Requisitos Funcionais:**

**2.1 Casos de Uso:**

* **Caso de Uso Principal:** Compra de bilhete de trem.
    * **Pré-condição:** O usuário está na interface inicial do sistema.
    * **Fluxo de atividades:**
        1. O usuário seleciona o destino desejado na tela de menu.
        2. O sistema valida a seleção do destino.
        3. O usuário insere seu cartão de crédito no leitor.
        4. O sistema verifica a validade do cartão de crédito.
        5. O usuário digita seu PIN no teclado.
        6. O sistema valida o PIN e a operação de crédito.
        7. O sistema emite o bilhete (físico ou digital).
        8. O sistema cobra o valor do bilhete no cartão de crédito.
        9. O sistema exibe uma mensagem de confirmação da compra.
    * **Pós-condição:** O usuário possui o bilhete de trem e a transação foi concluída com sucesso.
* **Casos de Uso Secundários:**
    * Consulta de saldo do cartão de crédito.
    * Cancelamento de compra de bilhete.
    * Impressão de segunda via do bilhete.

**2.2 Requisitos Detalhados:**

* **Seleção de Destino:**
    * O sistema deve apresentar um menu de destinos possíveis, com opções claras e fáceis de entender (texto, ícones, etc.).
    * O usuário deve poder selecionar o destino desejado por meio de toque na tela ou botões físicos.
    * O sistema deve validar a seleção do destino para garantir que seja um destino válido.
* **Validação do Cartão de Crédito:**
    * O sistema deve ler os dados do cartão de crédito inserido pelo usuário.
    * O sistema deve verificar a validade do cartão de crédito (data de validade, número do cartão, etc.).
    * O sistema deve exibir uma mensagem de erro clara caso o cartão de crédito seja inválido.
* **Validação do PIN:**
    * O sistema deve solicitar ao usuário que digite seu PIN no teclado.
    * O sistema deve verificar se o PIN digitado está correto.
    * O sistema deve exibir uma mensagem de erro clara caso o PIN esteja incorreto.
* **Emissão do Bilhete:**
    * O sistema deve emitir o bilhete de acordo com o tipo selecionado pelo usuário (físico ou digital).
    * O bilhete deve conter as informações relevantes da compra (destino, data, hora, valor, etc.).
    * O bilhete deve ser seguro e protegido contra falsificações.
* **Cobrança do Cartão de Crédito:**
    * O sistema deve debitar o valor do bilhete no cartão de crédito do usuário.
    * O sistema deve enviar uma notificação ao usuário sobre a transação realizada.
    * O sistema deve garantir a segurança da transação financeira.

**3. Requisitos Não Funcionais:**

* **Desempenho:**
    * O sistema deve estar disponível 24 horas por dia, 7 dias por semana.
    * O tempo de resposta do sistema deve ser inferior a 5 segundos para todas as operações.
    * O sistema deve ser capaz de lidar com um grande volume de usuários simultâneos.
* **Segurança:**
    * O sistema deve proteger os dados pessoais e financeiros dos usuários.
    * O sistema deve implementar medidas de segurança contra ataques cibernéticos.
    * O sistema deve garantir a confidencialidade, integridade e disponibilidade dos dados.
* **Usabilidade:**
    * A interface do usuário deve ser intuitiva e fácil de usar.
    * O sistema deve ser acessível a pessoas com deficiências.
    * O sistema deve oferecer instruções claras e concisas para cada operação.
* **Manutenabilidade:**
    * O código do sistema deve ser bem documentado e fácil de entender.
    * O sistema deve ser modular e fácil de modificar.
    * O sistema deve ser testado regularmente para garantir seu bom funcionamento.
* **Portabilidade:**
    * O sistema deve ser compatível com diferentes navegadores e sistemas operacionais
### 4.4 Escreva um conjunto de requisitos não funcionais para o sistema de emissão de bilhetes, definindo sua confiabilidade e tempo de resposta esperados.

**Desempenho:**

* O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com tempo de inatividade máximo de uma hora por semana.
* O tempo de resposta do sistema deve estar entre 1 e 5 segundos para operações gerais e entre 1 e 3 segundos para consultas.
* O sistema deve ser capaz de lidar com o "horário de pico" da estação.

**Segurança:**

* O sistema deve garantir a segurança dos dados sensíveis do usuário, como cartão de crédito.
* O sistema deve implementar proteções contra ataques cibernéticos, como DoS/DDoS, Phishing e etc.

**Tolerância a falhas:**

* O sistema deve continuar no ar mesmo se ocorrer falha em algum de seus componentes.

**Usabilidade:**

* A interface do usuário deve ser fácil de usar e intuitiva.
* O sistema deve ser acessível a pessoas com deficiência.

**Manutenabilidade:**

* O sistema deve ser fácil de manter e atualizar.
* O código deve ser bem documentado.

**Portabilidade:**

* O sistema deve ser compatível com diferentes navegadores e sistemas operacionais.

**Escalabilidade:**

* O sistema deve ser capaz de se adaptar a um aumento na demanda.
### 4.5 Usando a técnica sugerida neste capítulo, em que as descrições em linguagem natural são apresentadas em formato-padrão, escreva requisitos do usuário plausíveis para as seguintes funções:
1. **Um sistema de bomba de gasolina autônoma, que inclui um leitor de cartão de crédito. O cliente passa o cartão pelo leitor e, em seguida, especifica a quantidade de combustível requerida. O combustível é liberado, e a conta do cliente, debitada.**
	1. Função: Comprar combustível
	2. Descrição: O cliente deve ser capaz de comprar a quantidade de combustível desejada 
	3. Entradas: O cartão de credito e a quantidade de combustível 
	4. Saída: confirmação da compra
	5. Ação: O cliente entra com seu cartão e escolhe a quantidade de combustível, uma vez que o cliente confirma a compra seu cartão deve ser debitado
	6. Pre-condição: Os tanques de combustível tem a quantidade que o cliente está solicitando
	7. Pós-condição: O cartão do cliente deve ser debitado após a compra e o combustível só pode ser liberado caso a  compra for aprovada 
### 4.6 Sugira como um engenheiro responsável pela elaboração de um sistema de especificação de requisitos pode manter o acompanhamento dos relacionamentos entre requisitos funcionais e não funcionais.
- Utilize diagramas de casos de uso para representar o comportamento do sistema e identificar os requisitos funcionais e não funcionais associados a cada caso de uso.
- Crie protótipos do sistema para visualizar e testar a implementação dos requisitos funcionais e não funcionais.
- Mantenha comunicação constante com stakeholders, equipe de desenvolvimento e outros envolvidos no projeto para garantir o alinhamento e a compreensão dos requisitos.
### 4.7 Usando seu conhecimento de como um caixa eletrônico (ATM) funciona, desenvolva um conjunto de casos de uso que poderia servir de base para o entendimento dos requisitos para um sistema de ATM.

**Saque:**

**Condição:** Cartão de crédito e senha válida

**Eventos:**

1. Inserir cartão e senha
2. Selecionar a opção saque
3. Inserir a quantidade de dinheiro a ser retirada da conta
4. Confirmar a transação
5. Receber o dinheiro e o recibo
6. Atualizar o saldo na conta bancária do usuário

**Depósito:**

**Condição:** Cartão de crédito, senha válida e dinheiro em espécie

**Eventos:**

1. Inserir cartão e senha
2. Selecionar a opção depósito
3. Inserir o dinheiro na máquina
4. Confirmar a transação
5. Receber o recibo
6. Atualizar o saldo na conta bancária do usuário

**Transferência:**

**Condição:** Cartão de crédito, senha válida e outra conta bancária

**Eventos:**

1. Inserir cartão e senha
2. Selecionar a opção transferência
3. Inserir o número da conta de destino
4. Confirmar a transação
5. Receber o recibo
6. Atualizar o saldo em ambas as contas
### 4.8 Quem deve ser envolvido em uma revisão de requisitos?
**1. Clientes:**

- São os principais interessados no sistema e representam as necessidades dos usuários finais.
- Sua participação garante que os requisitos estejam alinhados com seus objetivos e expectativas.

**2. Desenvolvedores:**

- São responsáveis por construir o sistema e precisam entender completamente os requisitos para implementá-los corretamente.
- Sua participação ajuda a identificar ambiguidades, falhas e inconsistências nos requisitos.

**3. Testadores:**

- São responsáveis por testar o sistema e garantir que ele atenda aos requisitos.
- Sua participação ajuda a identificar requisitos ausentes ou mal definidos que podem levar a falhas de teste.

**4. Analistas de Requisitos:**

- São responsáveis por coletar, analisar e documentar os requisitos.
- Sua participação garante que os requisitos sejam claros, precisos e completos.

**5. Gerentes de Projeto:**

- São responsáveis por planejar, organizar e controlar o projeto.
- Sua participação garante que os requisitos sejam considerados no contexto geral do projeto e que os recursos sejam alocados de forma adequada.

**6. Outros Stakeholders:**

- Outros indivíduos ou grupos que podem ter interesse no sistema, como representantes de marketing, suporte técnico ou especialistas em domínio.
- Sua participação pode fornecer diferentes perspectivas e identificar requisitos adicionais que foram esquecidos.
### 4.9 Quando mudanças emergenciais precisam ser feitas em sistemas, o software do sistema pode precisar ser modificado antes de serem aprovadas as mudanças nos requisitos. Sugira um modelo de um processo para fazer essas modificações de modo a garantir que o documento de requisitos e implementação do sistema não se tornem inconsistentes.
![[ex_4.9_sommerville.canvas|ex_4.9_sommerville]]
## Cap - 5
### 7.1 Usando a notação estruturada do Quadro 7.1, especifique casos de uso da estação meteorológica para relatar status e reconfigurar. Você deve fazer suposições razoáveis sobre a funcionalidade necessária. 
1. Caso de uso: Relatar status
	-  Atores: Estação Meteorológica, Sistema de
	Monitoramento
	-  Dados: A estação meteorológica envia os dados das
	condições atuais da estação, estes dados podem conter
	tanto informações sobre o tempo quanto informações
	sobre o status da estação em si (como bateria,
	temperatura interna etc.)
	-  Estímulo: O sistema de monitoramento envia uma
	solicitação a estação para obter seu status
	- Resposta: A estação envia uma mensagem para o
	sistema de monitoramento com contendo seu status
2. Caso de uso: Reconfigurar
	- Estação Meteorológica, Técnico de Manutenção
	- Dados: Podem conter informações sobre a configuração
	da estação, como a frequência que ela deve relatar seu
	status, se os sensores devem ser ativados ou
	desativados e limites para alerta de temperatura, vento e
	pressão. Também pode conter comandos para alterar as
	configurações descritas acima.
	- Estímulo: Um Técnico de Manutenção envia um
	comando de reconfiguração para a Estação
	Meteorológica.
### 7.3 Usando a notação gráfica da UML para classes de objetos, projete as classes de objeto a seguir, identificando atributos e operações. Use sua experiência para decidir sobre os atributos e operações que devem ser associados a esses objetos.
	-Telefone: 
		- Atributos: marca,cor,preço
		- Métodos: fazer ligação, aceitar ligação, rejeitar ligação
### 7.4 Usando como ponto de partida os objetos da estação meteorológica identificados na Figura 7.5, identifique outros objetos que possam ser usados nesse sistema. Projete uma hierarquia de herança para os objetos que você identificou.
#### Objetos
- **Sensor de umidade:** Mede a umidade do solo e do ar.
- **Câmera:** Captura imagens e vídeos do ambiente ao redor da estação meteorológica.
#### Hierarquia
- Dispositivo -> Sensor -> sensor de umidade
- Dispositivo -> Atuador -> câmera
### 7.5 Desenvolva o projeto da estação meteorológica para mostrar a interação entre o subsistema de coleta de dados e os instrumentos que coletam dados meteorológicos. Use diagramas de sequência para mostrar essa interação.
**A estação meteorológica inicia o processo de coleta de dados:**
- A estação meteorológica envia uma mensagem para o sensor de temperatura solicitando a temperatura atual.
**O sensor de temperatura responde com a temperatura atual:**
- O sensor de temperatura mede a temperatura do ar e envia um valor de temperatura para a estação meteorológica.
**A estação meteorológica pode opcionalmente:**
- Enviar os dados coletados para um servidor remoto para armazenamento e análise.
- Exibir os dados coletados em um display local.
- Gerar alertas se os valores coletados excederem os limites predefinidos.

### 7.7 Desenhe um diagrama de sequência que mostre as interações dos objetos em um sistema de agenda de grupo quando um grupo de pessoas está organizando uma reunião.
![[5. Assets/ex_7.7_sommerville.png]]
### 7.8 Desenhe um diagrama de estado da UML mostrando as possíveis mudanças de estado na agenda de grupo ou no sistema do posto de gasolina.
![[ex_7.8_sommerville.png]]
### 7.9 Usando exemplos, explique porque o gerenciamento de configuração é importante quando uma equipe está desenvolvendo um produto de software.
Quando se trabalha em equipe é importante garantir que os
membros da equipe não interfiram no trabalho um do outro, para
garantir isto um gerenciamento de configuração é necessário. Pois
quando, por exemplo, duas pessoas trabalham no mesmo
componente/projeto caso não se tome cuidado existe a
possibilidade de um membro sobre escreva as alterações do outro,
para tentar evitar com que isto aconteça é possível utilizar
gerenciadores de versão como o Git.
### 7.10
**Uma pequena empresa desenvolveu um produto especializado
que se configura especialmente para cada cliente. Novos clientes
geralmente têm requisitos específicos para serem incorporados a
seu sistema, e eles pagam para que estes sejam desenvolvidos. A
empresa tem a oportunidade de concorrer a um novo contrato,
que deverá mais que dobrar sua base de clientes. O novo cliente
também deseja ter algum envolvimento com a configuração do
sistema. Explique por que, nessas circunstâncias, para a empresa
proprietária do software, pode ser uma boa ideia tornar o software
open source.**
Levando em conta que este produto não está sendo criado para
uma empresa específica e sim para diversas empresas, isso quer
dizer que o software não está ligado a nenhuma livraria/programa
incompatível com open source, isto por si só já abre a possibilidade
de abrir o código fonte.
Porém para realmente justificar esta abertura, podemos considerar
os seguintes pontos:
	• Abrir o código para a comunidade pode atrair mais
	clientes, já que passa mais confiabilidade tendo em vista
	que qualquer um pode analisar o código.
	• A personalização deste software para cada cliente se
	torna mais fácil, já que o cliente pode mais facilmente
	analisar o código e dizer quais alterações precisam
	feitas.
	• Também existe a possibilidade de contar com a ajuda da
	comunidade para aprimorar o código, embora deixar
	com que outros desenvolvedores alterem o código não é
	obrigatório. Muitos projetos open source não permitem
	com que desenvolvedores fora do projeto alteram o
	código fonte, tudo que pode ser feito é o analisar.
Para completar o open source abre a possibilidade para a empresa
não vender o software diretamente, mas sim o suporte. Assim
garantindo uma fonte de renda fixa, já que os clientes precisariam
pagar periodicamente para receber o suporte

# References