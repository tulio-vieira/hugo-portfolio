---
head:
  title: Nubank Case 
---

# Nu control and Nu facilitation

<h2 style="font-weight: 300;">
How we use Experience Design to help defaulting Nubank users
</h2>
<br>

#### Deliverables
- Quantitative research
- Persona
- User journey
- Prioritization matrix
- Mockups

#### The context
According to Serasa Experian, in 5 years, the number of Brazilian defaulters rose from 59 million in 2018 to 70 million in 2023, a record in the historical series. Furthermore, not only did default rates increase, but the value of debts also increased by 19% in the same period.

#### Problem definition and hypothesis
Many people do not have financial control.

The scenario of increased defaults seems to affect those who do not have financial control. Without financial control, the individual is more likely to incur debt and default. This is important to address because the more financial awareness people have, the more appropriate their purchases will be.

#### Quantitative research
The research method chosen to delve deeper into the subject and validate our hypothesis was the unmoderated structured questionnaire made by Typeform.

With it, we aimed to understand whether or not people have debts and what types, whether they write down their expenses regularly, what they think contributes to their default status (if they are) and what they believe is missing to be get rid of debts (if you have them).

#### Search results
- We received 105 responses. Of this total, 45% said they had debts and 36% of these same people did not monitor their expenses.
- The most cited types of debt were: credit cards, loans, car financing and medical debts.
- The reasons that contribute to default include: excessive interest, unemployment and health problems.
- There are reasons that would help to escape the default scenario that were mentioned: greater financial control, finding additional sources of income and the possibility of negotiating with creditors.

#### Search insights
After collecting the research data and analyzing it, it was possible to reach some conclusions. Among them we can highlight that the initial hypothesis was partially correct. Many people do not have financial control, but this does not mean that they are necessarily without financial awareness and spend even without the power, as we initially believed.

After research, we realized that the most accurate thing to say would be that people don't have *financial monitoring*. This change in perspective allows us to understand that people are not always out of control, but rather that they do not tend to monitor their finances and, therefore, lose track of how much they still have available in their account.

Furthermore, we also observed that when talking about debt, not only does personal control influence it, but external factors can also affect it. No matter how controlled a person is, if they are affected by a health problem and have to spend a lot on medical bills, they will possibly go into debt because the money coming in is less than the amount they have to spend on their health. And this is regardless of whether or not you have a spreadsheet with your expenses, for example.

#### Persona and User Journey
To start thinking about opportunities, it is first necessary to understand who our target audience is, then outline their pain points and finally outline a solution. To build this representation we use the Personas resource. For an even deeper understanding of the context in which this Persona is inserted, we use the User Journey Map.

![Persona](img/nubank/persona.png)

![Jornada do Usuário](img/nubank/jornada.png)

#### Impact VS Effort
Having understood the scenario that leads the user (represented by Jéssica) to take on debt, the next step was to use the Impact VS Effort matrix to define the best opportunities to be considered. The chosen solutions are in the upper left quadrant, which represent those with the greatest impact on Jéssica and the least effort to be used to develop them.

![Matriz de priorização](img/nubank/matriz.png)

#### Explanation of the matrix
##### Notify in advance the day that each expense will be deducted:
Knowing what Jessica's expenses are and the days on which they would be charged would not require much, but just knowing that a certain expense is about to be deducted from the invoice will not change the fact that Jessica will still have to pay the expense or much less cancel the expense. high amount of expenses.

##### Carry out price research for Jéssica:
Doing so would not necessarily imply less spending. Many times, the user ends up paying more due to the convenience of going to a closer location or even due to their impatience (as we saw on Jornada), which is why we classify it as low impact.

##### Present opportunities where Jéssica can have new sources of income:
It is an important point and would have a great impact. Jessica earning more will possibly make her pay her expenses more calmly because the money inflow will be greater. However, this can be a risk. No matter how much money a person has, if they don't know how to manage it and aren't in the habit of keeping track of their expenses, they may have problems. Furthermore, this solution is classified as high effort because we would have to think about how to architect all of this and our role as a digital bank does not cover something so complex.

##### Offer a spreadsheet with Jessica's expenses:
It would be of high value because with this information the user would be able to get an idea of when he can spend and when it is time to restrain himself more. Furthermore, it is classified as low effort because we would already have a large part (or all) of what Jéssica spent in the history.

##### Facilitate negotiation with creditors:
What we know at the moment is that Jéssica, at least currently, has more expenses than money coming in, so it is natural for her to get into debt. In this scenario, what we can do is make this debt payment process smoother and with fewer headaches. Such an opportunity is classified as low effort because most debt payments nowadays are already subject to negotiation, therefore, our job would only be to mediate and facilitate such requests.

#### Solutions
According to the information already presented, two new features were added to the Nubank application, Nu Controle and Nu Facilitação.

- *Nu Controle* would be a feature that needs to be enabled by the user. In the first configuration, the amount the person receives monthly would be requested. Once this is done, each time she uses her Nubank card, the expense spreadsheet will be updated automatically. Additionally, other analyzes will be offered in the same tab.

- *Nu Faciltação* is for more specific cases within the Nubank public. In this tab, we consider that the user is already in debt and wants to negotiate the payment of their debts. Therefore, he will have to make a request indicating how he plans to make the payment and within how long. Nubank will take care of the entire process, from sending the request to the creditor until sending the result to the user.

#### Screens
The next and final step was to design the screens that include the new features. It is important to highlight that before the entire ideation process, we carried out a thorough study of Nubank's brand guidelines and its Style Guide. This guided us throughout the production process, so that we have consistency and veracity in the interfaces. This material that we use as a reference source can be found in this [link](https://brand.nu.com.br/pt/).

##### Nu Controle
<style>
.img-flex {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 8px;
}
</style>
<div class="img-flex">
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
<div class="img-flex">
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

#### Final considerations
The main learning we learned from this case was the importance of carrying out research before conceptualizing any solution. In the beginning we believed that people spent more than they could voluntarily and thoughtlessly. In this sense, we could orient our solution towards a field that encompasses financial education.

However, after collecting the questionnaire data, we realized that many times, individuals do not know how much they have available in their account because they do not monitor their expenses, and if they knew, they would possibly not give in to certain shopping temptations. Furthermore, we were also aware that external factors are decisive for a person to incur debt (medical problems, job loss, etc.).
Therefore, understanding users more deeply was crucial to developing a valuable solution that met their real needs, even if this changed the direction we had initially thought for the project.

From now on, we are committed to remaining attentive to people's demands so that we can always provide the best experiences for our customers.

[//]: # (Comentários:)
[//]: # (Adicionar seta para o próximo estudo de caso)
[//]: # (Padronizar o tamanho das telas em alta fidelidade)
[//]: # (Verificar a quebra de linha a fim de que os parágrafos não fiquem muito longos)
[//]: # (Analisar se o tamanho das artes ficou bom ou se é necessário adicionar um link para o Figma)


Next case: [IHealthy App](../ihealthy)
