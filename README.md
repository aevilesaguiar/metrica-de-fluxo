# Métrica de Fluxo

## Quais são todas as métricas de fluxo possível que poder medir?  

Lead Time: do ponto de compromisso (commitment point) até ficar pronto. Começamos a contar quando nos comprometemos com a demanda (replenishment) até a entrega.  

 Cycle Time: é um tempo de ciclo entre quaisquer fases. Exemplo: Cycle Time de Desenvolvimento, Cycle Time de Homologação, Cycle Time de Revisão de Código. Cycle Time é avaliado entre dois pontos que escolhermos. 

 Customer Lead Time: o tempo transcorrido para suprirmos uma necessidade, normalmente do cliente, pensando desde quando minimamente sabemos o que queremos até quando entregamos. A contagem do Customer Lead Time começa em Upstream, em uma coluna onde existe alguma clareza (ou suspeita) do item que decidimos implementar. 
 
no Método Kanban, de David Anderson, costumamos considerar Lead Time, Cycle Time e Customer Lead Time conforme a figura abaixo: 

<img width="292" alt="image" src="https://github.com/user-attachments/assets/87bcb67d-7bbe-4d1f-877e-a5580ecce315">

<img width="422" alt="image" src="https://github.com/user-attachments/assets/b806c995-b4f5-4b58-b002-0d9eb8a36530">


Quem trabalha com o método kanban vai ouvir muito essas palavras: upstream e dowsntream

<img width="260" alt="image" src="https://github.com/user-attachments/assets/a35c3421-0f04-464b-8abd-e44660fd7d06">
Upstream visa mapear 

Exemplo de quadro Kanban de upstream:

<img width="262" alt="image" src="https://github.com/user-attachments/assets/2fd5cb4e-bf65-43c6-9162-5ef60a0a9285">



<img width="266" alt="image" src="https://github.com/user-attachments/assets/64579262-6927-465c-be6d-9f5406b33b43">

Exemplo de quadro Kanban de downstream:

<img width="263" alt="image" src="https://github.com/user-attachments/assets/aaad4cc3-05f2-492b-a237-2cc297002635">

A importancia de mapear tanto o dwnstream quanto o upstream é que você tem a visão completa  desde a concepção até a entrega:

<img width="226" alt="image" src="https://github.com/user-attachments/assets/e3ac70ee-6b68-4b71-a10e-32b902db0b00">

<img width="232" alt="image" src="https://github.com/user-attachments/assets/3f0b4660-482b-4434-b038-905d33e1cc31">

Tudo começa no upstream , onde temos várias ideias e faremos uma avaliação das ideias que foram definidas que irão para implentação e viram um produto , um desenvolvimento.

Para implentar melhorias no processo precisamos ter um quadro de downstream e upstream.

Committment Point: ponto de compromisso

- Cicle time : é o tempo que demoramos para entregar cada processo

- Throughtput(vazão): chamado de velocity. Conjunto de demandas entregues em um ciclo de tempo. Throughput. É a quantidade de vazão do sistema, ou seja, “quantas tarefas você faz por semana” ou “quantas tarefas foram entregues em um mês”. É uma métrica que mede a velocidade na qual uma certa quantidade de cards em um quadro kanban são entregues num determinado período de tempo.
- O que é Throughput? A métrica throughput é fundamental no desenvolvimento ágil, ele mede a quantidade de itens entregues por uma equipe em um período de tempo definido
O Throughput é uma métrica importante no desenvolvimento de software que mede a quantidade de trabalho concluído por uma equipe em um determinado período de tempo. Essa métrica é calculada contabilizando o número de user stories ou tarefas concluídas em um período específico, que pode ser semanal, quinzenal ou até mesmo uma iteração. Ela fornece uma visão clara da capacidade produtiva da equipe e ajuda a identificar se a equipe está entregando de acordo com as expectativas.
O Throughput é uma métrica que permite às equipes monitorar sua produtividade ao longo do tempo e identificar padrões ou tendências. Por exemplo, se uma equipe está apresentando um baixo throughput consistentemente, isso pode indicar a necessidade de ajustes nos processos ou na distribuição de tarefas.
O Throughput é aplicado de várias maneiras. Alguns exemplos de como essa métrica é utilizada:
Acompanhamento do número de user stories ou tarefas concluídas em cada iteração;
Análise da produtividade da equipe ao longo do tempo;
Identificação de gargalos ou áreas de melhoria na entrega de software;
Auxílio na definição de metas e estimativas realistas;
Comparação do throughput entre diferentes equipes ou projetos.
O benefício do Throughput é fornecer uma medida tangível da produtividade da equipe e permitir que a equipe e os stakeholders acompanhem o progresso do desenvolvimento de software. Ele ajuda a identificar possíveis atrasos, gargalos ou problemas de capacidade que podem afetar a entrega de software.

  
- O LeadTime: Tempo que uma demanda demora para percorrer todo o fluxo até chegar no estado de Done.
<img width="421" alt="image" src="https://github.com/user-attachments/assets/0e3f71eb-adfc-40e3-82de-75986839d234">

<img width="377" alt="image" src="https://github.com/user-attachments/assets/a4195b9f-5fcf-4329-801d-3c10c603a617">

- O que é velocity?
O velocity é uma métrica utilizada no desenvolvimento de software para medir a eficiência e a velocidade de uma equipe. Ele fornece uma estimativa da quantidade de trabalho que a equipe é capaz de realizar em um determinado período de tempo, geralmente medido em sprints ou iterações.

Ao contrário do throughput, que mede a quantidade de trabalho concluída, o velocity é uma medida relativa e específica da equipe. Ele é calculado com base em dados históricos, como a quantidade de story points concluídos em sprints anteriores. Com base nesses dados, a equipe pode estimar sua capacidade de trabalho futura e ajustar sua carga de trabalho de acordo.

Como o velocity é calculado?
O cálculo do velocity envolve a soma dos story points concluídos pela equipe em um determinado período de tempo. Os story points são uma técnica de estimativa relativa que mede o tamanho, a complexidade e o esforço necessário para concluir uma história de usuário ou tarefa.

Com base nas estimativas de story points e no histórico de conclusão, a equipe pode determinar sua velocidade média por sprint ou iteração. Isso proporciona uma visão clara da capacidade da equipe e ajuda a estabelecer expectativas realistas em relação ao trabalho que pode ser concluído em cada ciclo de desenvolvimento.

Aplicação do velocity no desenvolvimento de software
O velocity é uma métrica amplamente utilizada em metodologias ágeis, como o Scrum, para auxiliar no planejamento e gerenciamento do trabalho. Com base no velocity da equipe, é possível estabelecer metas de entrega e priorizar as tarefas de acordo com a capacidade da equipe.

Além disso, o velocity também é útil para monitorar o progresso do projeto e identificar possíveis gargalos ou áreas de melhoria. Se a equipe estiver consistentemente abaixo do velocity esperado, isso pode indicar que há obstáculos ou problemas que precisam ser resolvidos.

Diferenças entre throughput e velocity
Ao comparar as métricas de Throughput e Velocity, é importante entender suas diferenças e como elas são aplicadas no desenvolvimento de software.

Comparação dos cálculos e métodos de medição
O cálculo do throughput envolve a contagem do número de histórias de usuário ou tarefas que a equipe de desenvolvimento conclui durante um período de tempo específico, geralmente semanal ou por iteração. Já o velocity é calculado com base em dados históricos, normalmente levando em consideração as últimas iterações ou sprints. Essa diferença nos métodos de medição reflete abordagens distintas para avaliar o desempenho da equipe.

Foco e objetivo de cada métrica
O throughput tem como foco principal monitorar a produtividade da equipe de desenvolvimento, permitindo que ela acompanhe o progresso do trabalho e identifique gargalos ou áreas de melhoria. Por outro lado, o velocity é uma métrica relativa que ajuda as equipes a estimar seu desempenho futuro e ajustar sua carga de trabalho de acordo. Ele fornece insights sobre a capacidade da equipe de entregar valor de forma consistente ao longo do tempo.

Como as métricas refletem o desempenho da equipe de desenvolvimento
O throughput reflete a capacidade da equipe de concluir histórias de usuário ou tarefas dentro de um determinado período. Ele fornece uma visão direta da produtividade e eficiência da equipe. Já o velocity reflete o ritmo de entrega da equipe com base em dados históricos. Ele ajuda as equipes a entender sua capacidade de realizar entregas consistentes e aprimorar suas estimativas.

- CFD - Cumulative Flow Diagram: usado para entender o cenário do seu fluxo, se tem gargalo, onde não tem.
Se está melhorando ou piorando, se está ganhando performance.

Como podemos visualizar essas métricas no fluxo?

- Throughput: medido por tudo que foi entregue
<img width="404" alt="image" src="https://github.com/user-attachments/assets/e480c929-cfa1-41fc-add1-e8c165c8cc2b">

- System leadtime: vai ser medido entre o ponto de compromisso, onde de fato eu comecei a fazer , até que eu entreguei

<img width="373" alt="image" src="https://github.com/user-attachments/assets/6c7c21e4-622e-4e87-9e76-7a3bc1b1de20">

- wip: quantidade de trabalho em progresso
<img width="362" alt="image" src="https://github.com/user-attachments/assets/dbcc9a1e-10ff-41d9-bdec-c4b0c2899a81">
- Aging wip: idade dos itens, quanto tempo estão em execução. É muito importante avaliar o aging para entender o tempo e analisar os gasgalos, as vezes temos histórias grandes,
<img width="376" alt="image" src="https://github.com/user-attachments/assets/4c55f125-f200-43c7-8401-807b4c76fe93">


## Dados insigths miro

https://miro.com/app/board/o9J_lu_2CUM=/

<img width="794" alt="image" src="https://github.com/user-attachments/assets/e3a516b0-5d86-4c42-910f-024dbb74407d">


## Entendendo Métricas

Falando de métricas nós temos um delay, se avaliarmos lead time througthput nós estamos olhando o passado para projetar o futuro. 

<img width="365" alt="image" src="https://github.com/user-attachments/assets/172ffb3c-5519-4d31-a660-70234863495f">

Nós temos uma variável acionável, que são o que está ocorrendo no presente. E as métricas que podemos tomar mais decisões são: 
- wip
- Aging WIP

<img width="389" alt="image" src="https://github.com/user-attachments/assets/b79abead-7c87-4b07-a2d8-d64c45708056">

Quando está iniciando o trabalho não o limite, para ter mais visibilidade, depois disso podemos limitar.
A métrica mais acionável é o aging wip, pois olhando o tempo de cada item, podemos olhar de uma maneira diferente, para entender os gargalos. WIP Agind é fácil de aplicar mostramos um número e com base nisso geramos um gatilho de como agir e atuar.

<img width="367" alt="image" src="https://github.com/user-attachments/assets/a595a68b-95cb-4881-94a1-cb59338dd6a6">

<img width="382" alt="image" src="https://github.com/user-attachments/assets/f57f7e7b-482d-4101-a746-37ad53587ca7">

WIP AGING : É uma métrica do que está em progresso.  Quanto tempo esse item está em progresso
Customer leadtime: olha pela perspectiva da entrega. Quanto tempo algo que entreguei demorou para eu entregar desde uando o cliente fez o pedido.

## Analisando um cenário

<img width="362" alt="image" src="https://github.com/user-attachments/assets/b68b5a52-a80b-46c0-961d-f209ec929dbc">

Analisando na perspectiva das métricas que analisamos acima:

- Throughput vazão , geralmente recomenda que se analise o gráfico de 8 a 12 semanas, para que você não olhe um gráfico muito recente, mas que também não olhe um dado muito antigo. Senão sua avaliação não faz sentindo, pois as equipes mudam, os projetos mudam, a informação não é verdadeira.
  Podemos verificar que o time entregou mais com o passar do tempo, e a tendencia é subor. Ou seja aumentou a vazão, mas é necessário avaliar os motivos por esse aumento.Pode ser que no início do projeto o refinamento não era tão bem feito, as estórias não estavam tão quebradas. Não quer dizer dizer que estou mais ou menos produtivo. nas ultimas semanas houve uma consistencia. Mas é importante avaliar. Temos que ter uma performance estável, equilibrar a demanda
<img width="391" alt="image" src="https://github.com/user-attachments/assets/eaeb6063-c95e-490d-80b2-a064bfcaea6d">

- System Leadtime : cada bolinha é uma entrega. Se analisarmos as últimas 4 semanas, use a meta 85% e veja tudo que está acima. se olharmos o passado havia uma variação maior . Quando diminuimos essa variação percebemos que os itens foram melhor detalhado, que as definition of ready foram 

<img width="399" alt="image" src="https://github.com/user-attachments/assets/7f64df9e-118c-4315-ab47-a2c2a276d085">

Outlier : ponto fora da curva
“Um outlier é uma observação que se diferencia tanto das demais observações que levanta suspeitas de que aquela observação foi gerada por um mecanismo distinto” (Hawkins, 1980).

visualisando o gráfico através de um histograma:

<img width="385" alt="image" src="https://github.com/user-attachments/assets/281d46e1-0c03-4668-96aa-6fcc0d2cb7bd">

<img width="393" alt="image" src="https://github.com/user-attachments/assets/e8740e96-08e4-48c2-b3cc-80c135d40952">


Exemplo de uma retrospectiva usando o gráfico abaixo:

<img width="408" alt="image" src="https://github.com/user-attachments/assets/a3a6322d-844a-44a0-832f-82b5d76a5d85">

Vamos supor que levamos dois itens para discusão esses dois itens que levaram 14 e 41 dias. Não precisamos levar a narrativa de: pessoal está horrível o gráfico... E sim trazer uma narrativa sem julgamentos trazendo pessoal vamos discutir esse item que se destacou, e entender o que aconteceu, para tirar alguns aprendizados, geralmente podemos perguntar: O que aconteceu que levou a esse número? a gaera discuti, temos conciencia e clareza do que aconteceu, aí vem a pergunta que gera aprendizado: Se fossemos fazer esse time , como faríamos( essa pergunta é o que gera aprendizado), pode surgir as respostas-> o item não foi muito bem refinado, achamos que o item era menor e ele era bem maior do que o que planejamos,poderiamos ter parado no meio e revisto, e também nçao percebemos que estava demorando tudo isso. Podemos criar um gatinho de 85% de 13 dias, toda vez que tiver passando de 13 dias já deviamos estpa acabando. Olhar pelo o tempo de execução é a coisa mais fácil. Olhando a meta de 85% percentil podemos dizer que um item que passa pelo o fluxo pode ser entregue em até 13 dias.

<img width="49" alt="image" src="https://github.com/user-attachments/assets/35b35ecd-d2c7-42a6-80e0-809da64ceaa4">


## segunda parte

<img width="396" alt="image" src="https://github.com/user-attachments/assets/7c7ecad7-461b-45b2-ad7f-e8cafc28d3cf">

<img width="424" alt="image" src="https://github.com/user-attachments/assets/c092496a-9350-48a5-8e36-9f12737e192b">

Precisamos responder essas perguntas?

<img width="446" alt="image" src="https://github.com/user-attachments/assets/2f4ad423-7359-4e74-a4a4-cf25049fcdb6">

<img width="420" alt="image" src="https://github.com/user-attachments/assets/76ce55e0-32f4-4cf5-a350-68ce883f1d02">

Nós temos as métricas do passado, futuro e do presente:

- Aging wip, métrica do presente(tudo que está acontecendo, bloqueio , dependencias e tudo mais)
- 
  <img width="423" alt="image" src="https://github.com/user-attachments/assets/db9a2496-796f-412c-a46b-18aee3aaab63">

-  lead time, troughput e suas variações - metrica do passado(métrica do passado ajuda a prever o futuro)
- Métrica do futuro é tudo que vai acontencer, tudo que está no backlog, o que vai priorizar
  
<img width="443" alt="image" src="https://github.com/user-attachments/assets/f6284af0-b6f4-4b3e-8618-279bf0652d73">

<img width="359" alt="image" src="https://github.com/user-attachments/assets/f09316f9-084f-4b2b-b490-cef558710d25">

temos uma planilha do troy magness:

https://github.com/FocusedObjective/FocusedObjective.Resources/blob/master/Spreadsheets/Team%20Dashboard%20v5.xlsx

Podemos usar o actionable agile é uma ferramenta paga;

temos o getnave que ajuda a analisar os dashboards pré-configurados;

<img width="443" alt="image" src="https://github.com/user-attachments/assets/5025af7b-bc87-4e16-a865-02f120b16409">

<img width="428" alt="image" src="https://github.com/user-attachments/assets/e07d00c9-342d-433b-af98-df0b2f8756e5">

## Quando fica Pronto?

<img width="404" alt="image" src="https://github.com/user-attachments/assets/dc295930-4406-4ce5-ba4d-91e5779c22a0">

Qual a perspectiva criar um evento, perspectiva financeira, analise se o produto é viável ou não.

Entenda por que você está sendo pergunta quando ficará pronto, pois é necessário responder de forma madura, identificar riscos.

Um livro indicado para apoiar: User Storie map(descobrir a história por meio da narrativa)

Qual métricas de fluxo devo usar para responder quando ficar pronto?
- throughput
- velocity(olhando para uma pontuação)
- montecarlo


leadtime serve para olhar para um tipo de item, defeito que vem do cliente, ele pode dar uma resposta para você ter um prazo.


<img width="449" alt="image" src="https://github.com/user-attachments/assets/f2dc8969-2710-499f-990e-bb0711a3153b">

A previsão será feita com base no passado

<img width="443" alt="image" src="https://github.com/user-attachments/assets/a8de5b72-f861-4fc2-b29a-30a188a72f49">

<img width="466" alt="image" src="https://github.com/user-attachments/assets/5c2939e0-7194-4704-bd22-e5cb6a1719f7">

quando vamos planejar uma entrega pensar de forma probabilistica , não é certeza, previsão, pode acontecer diferente. Ou seja queremos saber o nível de risco que estamos correndo. 

<img width="471" alt="image" src="https://github.com/user-attachments/assets/1ec95eae-6dcc-4978-9e20-820740bb87c1">

<img width="468" alt="image" src="https://github.com/user-attachments/assets/6142ecf3-feca-47a0-907e-98741105b78a">

A equipe A ela tem uma menor consistencia, tem maior variação.
A equipe B é mais consistente .

Mas é importante analisar o througput por tipo de demanda(Equipe B)

<img width="403" alt="image" src="https://github.com/user-attachments/assets/80e155a7-e777-4cf8-9ee2-0d1a3cc3c868">


<img width="421" alt="image" src="https://github.com/user-attachments/assets/be2f550d-d1cf-4b6c-a5ad-24e937f34fdd">

<img width="458" alt="image" src="https://github.com/user-attachments/assets/8e194513-1c10-43fc-a07c-5ae729515c91">

média de 3/semana-> entrega em aproximadamente 1o semanas

melhor cenário: 4/semana -> 8 semanas

pior cenario: 2/semana -> 15 semanas


Usando o chat GPT:

<img width="419" alt="image" src="https://github.com/user-attachments/assets/2d10a11a-6469-447e-937a-dd540a041418">

<img width="383" alt="image" src="https://github.com/user-attachments/assets/08f0139d-f086-4e5a-9c15-24abb4f44db2">

<img width="364" alt="image" src="https://github.com/user-attachments/assets/02159f65-44af-4f11-bc62-4f1d6c62bed0">

<img width="371" alt="image" src="https://github.com/user-attachments/assets/6b16b05d-f313-4296-a4af-433ec5dcad25">

<img width="364" alt="image" src="https://github.com/user-attachments/assets/95eb4da8-80f1-47fa-af22-50b7d739edd1">

<img width="357" alt="image" src="https://github.com/user-attachments/assets/0d885612-8bc0-4172-943b-824b575acf7c">

<img width="334" alt="image" src="https://github.com/user-attachments/assets/ffb8bf88-c7c5-474f-bcf4-0605b175fc45">

<img width="359" alt="image" src="https://github.com/user-attachments/assets/49b43c42-a175-49f4-b408-14cd7166e192">

<img width="296" alt="image" src="https://github.com/user-attachments/assets/d58e4eb4-950e-485c-a456-36eb21102ad3">

<img width="326" alt="image" src="https://github.com/user-attachments/assets/d649d41b-bc91-4bd1-b60d-c995e4e89fab">

eLE ERROU A PREVISõ:
<img width="367" alt="image" src="https://github.com/user-attachments/assets/d3b33f74-2f5a-42ee-82cf-feefadc3bdf2">

<img width="388" alt="image" src="https://github.com/user-attachments/assets/af0de6f2-26c8-4b60-b03d-48d8c459ebd3">


<img width="347" alt="image" src="https://github.com/user-attachments/assets/2a326017-f153-476f-93a5-1bdfdfb927bb">


<img width="337" alt="image" src="https://github.com/user-attachments/assets/43ee4bcf-13c7-4f82-bcef-779ee4d530aa">


<img width="326" alt="image" src="https://github.com/user-attachments/assets/b71f8587-7875-41ff-bcdf-5c125a4d0f56">

<img width="357" alt="image" src="https://github.com/user-attachments/assets/27198423-7bb4-4de5-bf24-10044a990fcb">


<img width="346" alt="image" src="https://github.com/user-attachments/assets/2a5535be-357c-4bf1-a0a3-6b141e85968c">

<img width="340" alt="image" src="https://github.com/user-attachments/assets/c2aa9899-1dea-47c2-bb33-79566eb3d1b2">

<img width="435" alt="image" src="https://github.com/user-attachments/assets/8b341622-4aea-4c06-a1e2-cc8863287c8f">

<img width="428" alt="image" src="https://github.com/user-attachments/assets/95d41c81-c1bf-410f-bf20-d89c1f2f67c8">

<img width="435" alt="image" src="https://github.com/user-attachments/assets/0a8d5fad-5b52-4c35-87ff-3b01877d035c">
