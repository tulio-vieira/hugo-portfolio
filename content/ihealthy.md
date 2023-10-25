---
head:
  title: IHealthy Case 
---

# IHealthy

<h2 style="font-weight: 300;">
Como utilizamos Design de Experiência para auxiliar os usuários do plano nutricional
</h2>

<br>

#### Entregáveis:
- Pesquisa Quantitativa
- Proposta de valor
- Arquitetura de informação
- Guia de estilos
- Protótipo
- Teste de usabilidade

#### Contexto
Não sei se você já tentou fazer a dieta que um nutricionista recomenda, mas às vezes a necessidade de preparar tudo com os itens bem definidos pode acabar tornando esse trabalho lento e muito artesanal. Parece muito mais prático pedir qualquer besteira nesses apps de delivery, não é verdade? Já pensou se pudéssemos tornar tão fácil seguir o planejamento nutricional quanto é fácil pedir um X-Morte-Lenta? Foi nesse contexto que começamos a pensar em como otimizar esses processos, *caso isso realmente fosse uma demanda do mercado*.

#### Hipótese e pesquisa
Pelas nossas vivências, acreditamos que a maioria das pessoas que se proponham a seguir uma dieta tenham uma dificuldade na hora de preparar as refeições, seja por qual for a razão. Para validar isso, enviamos um questionário semiestruturado utilizando o Typeform. Tínhamos o objetivo de entender se a maioria das pessoas fazem ou já fizeram dieta e por quê e se pessoas vão ou já foram em um nutricionista e por quê.

#### Resultados da pesquisa
<br>

![Resultados da pesquisa](img/ihealthy/resultados.png)

#### Canvas da proposta de valor
Agora sabemos que a hipótese inicial estava certa e que temos um público considerável que vê valor no plano nutricional (podemos perceber isso com a elevada porcentagem de pessoas que já seguiu e segue uma dieta), mas que necessita de um "empurrãozinho" a mais para conseguir cumprir o planejamento alimentar (isso fica evidente devido ao alto número de desistências). Para pensar em como conectar tudo da melhor forma, fizemos o Canvas da proposta de valor. Nele é possível visualizar como nossa solução aliviaria as dores dos usuários, levando em conta seus objetivos e tarefas.

![Resultados da pesquisa](img/ihealthy/proposta-valor.png)

#### Conceituando a solução
De maneira prática, na primeira etapa do aplicativo algumas perguntas seriam feitas para entender como estão as medidas da pessoa e qual seria seu objetivo pessoal principal em termos de saúde e estética (emagrecer, manter peso, ganhar massa). Posteriormente, seria utilizado uma calculadora que permita saber quais seriam as calorias aproximadas que ela deve consumir diariamente para alcançar esse objetivo, levando em conta suas medidas e nível de sedentarismo.

Na próxima etapa, Inteligência Artificial seria usada para selecionar pratos de restaurantes já cadastrados em outros aplicativos de entrega que se encaixem nessas calorias, ou seja, se no café da manhã está prescrito que a pessoa coma por exemplo 500 calorias, o aplicativo ofertaria opções de pratos saudáveis com, aproximadamente, 500 calorias. Pensamos em utilizar como banco de dados outros aplicativos de Delivery porque pesquisamos e descobrimos que a maioria já oferece a tabela nutricional na descrição das refeições, o que facilitaria o processo de seleção dos pratos pela IA. 

Já a ideia de manter certa similaridade com um Delivery comum, vem baseada em uma pesquisa secundária da Abrasel que diz que o hábito de pedir comida após a crise da Covid-19 está presente em cerca de 60% das casas brasileiras por conta da praticidade que esses aplicativos oferecem.
Logo, é intuitivo pensar que as pessoas se sentiriam mais propensas a seguir uma dieta dentro de um contexto em que já estão acostumadas -pedir comida - do que ter que pesar os alimentos e preparar as refeições por si só.

Além disso, pedir as refeições as poupariam de ter o trabalho de preparo, que é um das problemáticas apontadas na pesquisa. E os pratos seriam servidos quentes logo após a finalização no restaurante, o que também se mostrou algo relevante para os usuários.
Utilizar o sistema usual de Delivery de comida também ajuda na questão da rotatividade dos cardápios, já que constantemente estaremos buscando novos pratos para inserir no app.

#### Arquitetura de informação
A fim de que os conteúdos dispostos no aplicativo estejam da maneira mais compreensível possível, organizamos a Arquitetura de informação abaixo.

![Resultados da pesquisa](img/ihealthy/arquitetura.png)

#### Guia de estilo
O próximo passo realizado foi a definição do Guia de estilos. Ele servirá como base para os elementos da interface a fim de que as telas tenham um padrão de consistência.

![Resultados da pesquisa](img/ihealthy/guia.png)

#### Telas
Após finalizar os wireframes, realizamos o protótipo de alta fidelidade. As telas que você visualizará abaixo foram testadas na etapa seguinte.

<div class="img-grid">
{{< img src="images/ihealthy/screens/0.png" alt="0">}}
{{< img src="images/ihealthy/screens/1.png" alt="0">}}
{{< img src="images/ihealthy/screens/2.png" alt="0">}}
{{< img src="images/ihealthy/screens/3.png" alt="0">}}
{{< img src="images/ihealthy/screens/4.png" alt="0">}}
{{< img src="images/ihealthy/screens/5.png" alt="0">}}
{{< img src="images/ihealthy/screens/6.png" alt="0">}}
{{< img src="images/ihealthy/screens/7.png" alt="0">}}
{{< img src="images/ihealthy/screens/8.png" alt="0">}}
{{< img src="images/ihealthy/screens/9.png" alt="0">}}
{{< img src="images/ihealthy/screens/10.png" alt="0">}}
{{< img src="images/ihealthy/screens/11.png" alt="0">}}
</div>
<br>

#### Teste de Usabilidade
Nesta fase recrutamos 5 pessoas para realizar o teste de usabilidade e, assim, colher feedbacks para aprimorar o aplicativo da IHealthy.
A tarefa dada foi realizar a compra de alguma refeição. Os dados que obtivemos foram:
* 100% das pessoas chegaram ao final da tarefa
* 80% disseram que não sabiam o valor que estavam pagando
* 60% comentaram que não lembravam o prato que tinham selecionado
* 20% quiseram saber a previsão de chegada do prato, mas não acharam

#### Considerações após o teste de usabilidade
Dado os insights do teste de usabilidade, ficou claro que para a melhor experiência do usuário, algumas features deveriam ser adicionadas, sendo elas: 
1. Deixar mais evidente a mercadoria selecionada e o seu valor na hora da compra;
2. Adicionar a informação da previsão de chegada da refeição; 

Portanto, as telas relativas ao pagamento e de "compra efetuada" foram atualizadas da seguinte maneira:

![Tela](img/ihealthy/screens/pos-teste.png)

#### Conclusão
O objetivo inicial era auxiliar os usuários a cumprirem sua dieta de forma mais prática e, assim, promover bem estar físico e emocional.

As pesquisas indicaram que grande parte das pessoas já tentaram seguir um plano alimentar, mas que em algum momento foram desencorajadas por alguns fatores como falta de tempo e preguiça. Portanto, procurou-se desenvolver uma solução que tornasse esse processo algo mais fácil e natural. 

Foi então, que decidimos desenvolver a IHealthy, um aplicativo de Delivery aparentemente comum, mas que seleciona pratos condizentes com as calorias necessárias para cada indivíduo de forma personalizada. Essa modalidade de entrega de refeições garante uma variedade no cardápio e que as comidas sejam servidas quentes, conforme demostrado que era de extrema relevância para os usuários. 

Existem muitos próximos passos no contexto da IHealthy. Desejamos adicionar novas features conforme as necessidades que os usuários forem relatando. Para tanto, ficaremos atentos as avaliações nas lojas de aplicativo e nos comprometemos a enviar NP´s mensais a fim de que possamos proporcionar sempre as melhores experiências para nossos usuários.

<a href="../nubank" class="btn btn-primary">
Nu controle e Nu facilitação
<i class="icon-arrow-right"></i>
</a>
