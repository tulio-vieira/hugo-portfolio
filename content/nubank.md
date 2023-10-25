---
head:
  title: Nubank Case 
---

# Nu controle e Nu facilitação

<h2 style="font-weight: 300;">
Como usamos Design de Experiência para auxiliar os usuários inadimplentes da Nubank
</h2>
<br>

#### Entregáveis
- Pesquisa quantitativa
- Persona
- Jornada do usuário
- Matriz de priorização
- Mockups

#### O contexto
Segundo o Serasa Experian, em 5 anos, o número de brasileiros inadimplentes passou de 59 milhões em 2018 para 70 milhões em 2023, um recorde na série histórica. Para além disso, não só a inadimplência cresceu, mas também o valor das dívidas sofreu um aumento de 19% neste mesmo período.

#### Defnição do problema e hipótese
Muitas pessoas não têm controle financeiro.

O cenário de aumento de inadimplência parece acometer quem não têm controle financeiro. Sem um controle financeiro, o indivíduo fica mais propenso a contrair dívidas e entrar em inadimplência. Isso é importante ser tratado porque quanto mais consciência financeira as pessoas têm, mais adequadas serão suas compras.

#### Pesquisa quantitativa
O método de pesquisa escolhido para nos aprofundarmos no assunto e validar nossa hipótese foi o questionário estruturado não moderado feito pelo Typeform.

Com ele, tínhamos objetivo de entender se as pessoas têm ou não dívidas e quais os tipos, se elas anotam os gastos regularmente, o que elas pensam que contribuem para sua condição de inadimplente (caso sejam) e o que elas acreditam que falte para se livrar das dívidas (caso tenham).

#### Resultados da pesquisa
- Obtivemos 105 respostas. Desse total, 45% afirmaram ter dívidas sendo que 36% destas mesmas pessoas não acompanham seus gastos.
- Os tipos de dívidas mais citadas foram: cartão de crédito, empréstimos, financiamento de carros e dívidas médicas.
- Como motivos que contribuem para a inadimplência temos: juros excessivos, desemprego e problemas de saúde.
- Já motivos que contribuiriam para sair do cenário de inadimplência que foram mencionados: maior controle financeiro, encontrar fontes de renda adicionais e possibilidade de negociação com credores.

#### Insights da pesquisa
Após coletar os dados de pesquisa e analisá-los, foi possível chegar em algumas conclusões. Dentre elas podemos destacar que a hipótese inicial estava parcialmente certa. Muitas pessoas não têm controle financeiro, mas isso não implica dizer que elas sejam, necessariamente, sem consciência financeira e saiam gastando mesmo sem poder, como acreditávamos no início.

Pós pesquisa, percebemos que o mais correto a dizer seria que as pessoas não têm um *acompanhamento financeiro*. Essa mudança de perspectiva nos permite entender que as pessoas nem sempre são descontroladas, mas sim que elas não costumam acompanhar suas finanças e, portanto, perdem a noção de quanto ainda têm disponível na conta.

Para além disso, observamos também que quando se fala em dívidas não apenas o controle pessoal influencia, mas fatores externos também podem afetar. Por mais controlada que uma pessoa seja, se ela for acometida por um problema de saúde e tiver de gastar muito em contas médicas, ela possivelmente irá se endividar porque a entrada de dinheiro é menor do que quanto ela tem que gastar com a saúde. E isso independe dela ter ou não uma planilha com as despesas, por exemplo.

#### Persona e Jornada do usuário
Para começar a pensar em oportunidades, é necessário primeiro entender quem é nosso público alvo, para depois desenhar suas dores e finalmente esboçar uma solução. Para a construção dessa representação utilizamos o recurso de Personas. Já para um entendimento ainda mais aprofundado do contexto em que tal Persona está inserida, usamos o Mapa da jornada do usuário.

![Persona](img/nubank/persona.png)

![Jornada do Usuário](img/nubank/jornada.png)

#### Impacto VS Esforço
Entendido o cenário que leva o usuário (representado por Jéssica) a contrair dívidas, o próximo passo foi usar a matriz Impacto VS Esforço para definir as melhores oportunidades a serem contempladas. As soluções escolhidas estão no quadrante superior esquerdo que representam as de maior impacto à Jéssica e menor esforço a ser empregado para desenvolver.

![Matriz de priorização](img/nubank/matriz.png)

#### Explicação da matriz
##### Avisar previamente o dia que cada despesa vai ser descontada: 
Saber quais são as despesas de Jéssica e os dias em que seriam cobradas não exigiria muito, porém apenas saber que um determinado gasto está para ser descontado na fatura não mudará o fato de que Jéssica ainda vai ter que pagar a despesa ou muito menos anularia a quantidade elevada de despesas.

##### Realizar a pesquisa de preço para Jéssica: 
Fazer isso não, necessariamente, implicaria em menos gastos. Muita das vezes, o usuário acaba pagando mais pela conveniência de ir em um local mais perto ou até pela sua impaciência (como vimos na Jornada), por isso classificamos como baixo impacto.

##### Apresentar oportunidades em que Jéssica possa ter novas fontes de renda:
É um ponto importante e seria de grande impacto. Jéssica ganhando mais, possivelmente fará com que ela pague as despesas com mais tranquilidade porque a entrada de dinheiro vai ser maior. Porém, isso pode ser um risco. Por mais que a pessoa tenha caixa, se ela não souber administrar e não ter o hábito de acompanhar os gastos, possivelmente terá problemas. Além disso, esta solução é classificada como alto esforço porque teríamos que pensar em como arquitetar tudo isso e nosso papel de banco digital não abrange algo tão complexo.

##### Oferecer planilha com os gastos de Jéssica:
Seria de alto valor porque com essas informações o usuário conseguiria ter uma noção quando ele pode gastar e quando é hora de se conter mais. Ademais, é classificado como baixo esforço porque já teríamos no histórico grande parte (ou tudo) do que Jéssica gastou.

##### Facilitar negociação com credores:
O que sabemos no momento é que Jéssica, pelo menos atualmente, tem mais despesas do que dinheiro entrando, logo é natural que ela contraia dívidas. Neste cenário então, o que podemos fazer é tornar esse processo de pagamento de débitos algo mais tranquilo e com menos dores de cabeça. Tal oportunidade é classificada como baixo esforço porque grande parte dos pagamentos de dívidas hoje em dia já são passíveis de negociação, portanto, nosso trabalho seria apenas intermediar e facilitar tais solicitações.

#### Soluções
De acordo com as informações já apresentadas, chegou-se em duas novas features para o aplicativo da Nubank, a Nu Controle e a Nu Facilitação.

- *Nu Controle* seria um recurso que precisa ser habilitado pelo usuário. Na primeira configuração seria pedido o valor que a pessoa recebe mensalmente. Feito isso, cada vez que ela fizer uso do cartão da Nubank, a planilha de gastos será atualizada automaticamente. Além disso, outras análises serão oferecidas na mesma aba.

- *Nu Faciltação* é para casos mais específicos dentro do público Nubank. Nessa aba, consideramos que o usuário já está endividado e quer negociar o pagamento de suas dívidas. Portanto, ele terá de fazer uma solicitação indicando como planeja realizar o pagamento e em quanto tempo. A Nubank cuidará de todo o processo desde o envio da solicitação à entidade credora até o envio do resultado para o usuário.

#### Telas
O próximo e último passo foi desenhar as telas que contemplem as novas features. Importante ressaltar que antes de todo o processo de ideação, fizemos um denso estudo das diretrizes de marca da Nubank e seu Guia de estilos. Isso nos guiou durante todo o processo de produção, a fim de que tenhamos consistência e veracidade nas interfaces. Este material que utilizamos como fonte de consulta pode ser encontrado [neste link](https://brand.nu.com.br/pt/).

##### Nu Controle

<div class="img-grid">
{{< img src="images/nubank/telas-nu-controle/0.png" alt="telas-nu-controle/0" >}}
{{< img src="images/nubank/telas-nu-controle/1.png" alt="telas-nu-controle/1" >}}
{{< img src="images/nubank/telas-nu-controle/2.png" alt="telas-nu-controle/2" >}}
{{< img src="images/nubank/telas-nu-controle/3.png" alt="telas-nu-controle/3" >}}
{{< img src="images/nubank/telas-nu-controle/4.png" alt="telas-nu-controle/4" >}}
{{< img src="images/nubank/telas-nu-controle/5.png" alt="telas-nu-controle/5" >}}
{{< img src="images/nubank/telas-nu-controle/6.png" alt="telas-nu-controle/6" >}}
{{< img src="images/nubank/telas-nu-controle/7.png" alt="telas-nu-controle/7" >}}
</div>
<br>

##### Nu Facilitação
<div class="img-grid">
{{< img src="images/nubank/telas-nu-facilitacao/0.png" alt="telas-nu-facilitacao/0" >}}
{{< img src="images/nubank/telas-nu-facilitacao/1.png" alt="telas-nu-facilitacao/1" >}}
{{< img src="images/nubank/telas-nu-facilitacao/2.png" alt="telas-nu-facilitacao/2" >}}
{{< img src="images/nubank/telas-nu-facilitacao/3.png" alt="telas-nu-facilitacao/3" >}}
{{< img src="images/nubank/telas-nu-facilitacao/4.png" alt="telas-nu-facilitacao/4" >}}
{{< img src="images/nubank/telas-nu-facilitacao/5.png" alt="telas-nu-facilitacao/5" >}}
{{< img src="images/nubank/telas-nu-facilitacao/6.png" alt="telas-nu-facilitacao/6" >}}
{{< img src="images/nubank/telas-nu-facilitacao/7.png" alt="telas-nu-facilitacao/7" >}}
{{< img src="images/nubank/telas-nu-facilitacao/8.png" alt="telas-nu-facilitacao/8" >}}
{{< img src="images/nubank/telas-nu-facilitacao/9.png" alt="telas-nu-facilitacao/9" >}}
</div>
<br>

#### Considerações finais
O aprendizado principal que tiramos deste case foi a importância de realizar pesquisas antes de conceituar qualquer solução. No começo acreditávamos que as pessoas gastavam mais do que podiam de forma voluntária e impensada. Nesse sentido, poderíamos orientar nossa solução para um campo que abrangesse uma educação financeira.

Contudo, após coletar os dados do questionário, perecebemos que muita das vezes, os indivíduos não sabem quanto tem disponível na conta porque não acompanham seus gastos, e se soubessem, possivelmente não cederiam à certas tentações de compra. Para além disso, tivemos consciência também que fatores externos são decisivos para uma pessoa contrair dívidas (problemas médicos, perda de emprego,etc). 
Portanto, entender mais afundo os usuários foi crucial para desenvolver uma solução de valor que atendesse as reais necessidades, mesmo que isso tenha mudado o rumo que inicialmente tínhamos pensado para o projeto. 

Daqui para frente, nos comprometemos a continuar atentos as demandas das pessoas a fim de que possamos proporcionar sempre as melhores experiências para nossos clientes. 

[//]: # (Comentários:)
[//]: # (Adicionar seta para o próximo estudo de caso)
[//]: # (Padronizar o tamanho das telas em alta fidelidade)
[//]: # (Verificar a quebra de linha a fim de que os parágrafos não fiquem muito longos)
[//]: # (Analisar se o tamanho das artes ficou bom ou se é necessário adicionar um link para o Figma)


<a href="../ihealthy" class="btn btn-primary">
Aplicativo IHealthy
<i class="icon-arrow-right"></i>
</a>
