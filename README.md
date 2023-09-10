# Análise de Riscos em Dev de Software. 

### Olá! Vou apresentar nesse espaço um pouco das boas práticas que devemos seguir, segundo a [PMBOK](https://pt.wikipedia.org/wiki/Project_Management_Body_of_Knowledge), para analisar e tratar os possíveis risco no desenvolvimenbto de um software, com qualidade e máxima de eficiência. 

# 🤷‍♂️ O Que é Um Risco ? 

#### Primeiro, vamos imaginar uma situação, vamos usar como exemplo um planejamento para uma viagem, para entender quais são os possíveis riscos que venham acontecer e deixar a experirência dessa viagem um pouco frustrante.

#### Imagine você realizando um planejamento de uma viagem ao exterior nas próximas férias. Considerando que o roteiro está definido, bem como as reservas dos hotéis realizadas, as passagens reservadas e uma quantidade de dólares adquiridos, podemos, intuitivamente, aplicar uma abstração denominada risco, ou seja, o que pode ocorrer de errado na minha viagem?


  ![viagem](https://github.com/Jefsdatacode/Contribuindo-com-Analise-de-Projetos/assets/133138211/465fc04a-d220-449a-ad2c-d247816ce8b5)

  
### Vamos, então, gerar uma pequena lista de possíveis eventos negativos para entendermos os conceitos:

- Ocorrência de um problema de saúde, por causa de um acidente ou ter contraído alguma doença.
- Cancelamento da passagem pela companhia aérea.
- A quantidade de dólar adquirida não ser suficiente.

  Observe que a avaliação de risco gera uma preocupação que o conduz ao futuro, inserindo um grau de incerteza – ele pode ou não ocorrer. Ao mesmo tempo, espera-se que fique clara a importância de sua avaliação, pois, caso ocorra algum dos eventos listados durante a sua viagem, essa pode estar seriamente comprometida.

  *Se tratando de desenvolvimento de software, o risco permite planejar o futuro e evitar que empresas tenham “sustos” nos seus projetos em função de eventos inesperados e, a partir destes, iniciar as devidas tratativas. Em síntese, a área de Gerenciamento de Risco permite a sistematização dessas tratativas em forma de plano.*
  
  # 🕵️‍♀️Identificaçãos de Riscos
  Alinhado às descrições apresentadas, podemos determinar que um risco possui três componentes: um evento; a probabilidade de ocorrência do evento, associada ao grau de incerteza; e o impacto decorrente do evento, caso aconteça, associado ao grau de perda.

 Como parte do Plano de Gerenciamento de Riscos, a elaboração de uma Estrutura Analítica do Risco [(EAR)](https://pt.wikipedia.org/wiki/An%C3%A1lise_de_risco) auxilia na definição de potenciais fontes de riscos para o projeto, permitindo a identificação de riscos de forma categorizada.

O processo de Identificação de Riscos requer uma clara compreensão da missão, escopo e objetivos do projeto.

### Segundo Pressman (2016), uma proposta para identificação de categorias genéricas de risco relacionadas com o software inclui:
- #### TAMANHO DO PRODUTO
  - *Riscos associados ao tamanho do software.*
- #### IMPACTO NO NEGÓCIO
  - *Riscos oriundos de restrições impostas pelo cliente ou pelo mercado.*
- #### CARACTERÍSTICAS DO ENVOLVIDO
  - *Riscos relacionados com a comunicação oportuna, por exemplo, entre engenheiro de software e um determinado cliente.*
- #### DEFINIÇÃO DO PROCESSO.
    - *Riscos relacionados com a auditoria de processos por parte da equipe de qualidade.*
- #### AMBIENTE DE DESENVOLVIMENTO
  - *Riscos associados às ferramentas disponíveis para criar o software, tais como, ferramentas case disponíveis.*
- #### TECNOLOGIA A SER CRIADA.
  - *Risco relacionado com as inovações tecnológicas aplicadas no desenvolvimento do software, tal como, um novo framework de persistência de dados.*
- #### QUANTIDADE DE PESSOAS E EXPERIÊNCIA.
  - *Riscos que associados aos perfis dos engenheiros de software, administradores de banco de dados, web designers, enfim, da equipe que realizará o trabalho.*


### *O processo de identificação de riscos é iterativo, pois novos riscos podem aparecer durante o projeto. Uma técnica muito comum a ser utilizada na identificação de riscos é a técnica denominada de [Brainstorming](https://pt.wikipedia.org/wiki/Brainstorming). Esta inclui uma reunião com um conjunto multidisciplinar de especialistas com a finalidade de obter uma lista abrangente de cada risco de projeto e as fontes do risco geral do projeto, sendo as ideias geradas sob a orientação de um facilitador.*
![BRAINSTORM](https://github.com/Jefsdatacode/Contribuindo-com-Analise-de-Projetos/assets/133138211/b58cc1cd-86aa-4106-8342-64a2ec6750dd)

### *Uma segunda técnica é conhecida como Lista de Verificação ou Check List, ou seja, uma lista de riscos baseada em informações históricas e conhecimentos acumulados de projetos semelhantes e outras fontes de informações. Essas listas ajudam a identificar pontos fracos no projeto atual a partir de experiências passadas.*
!![CHECKLIST](https://github.com/Jefsdatacode/Contribuindo-com-Analise-de-Projetos/assets/133138211/5ddd3cee-6e4a-4666-902e-8c7cf5a4def2)

###  *Uma terceira técnica proposta pelo PMBOK é a entrevista.*
### *A seguir, vamos explorar um exemplo da aplicação dessa técnica com experientes gerentes de projeto de software, que levantaram as seguintes questões e foram apresentadas por Pressman (2016)*

![ENTREVISTA](https://github.com/Jefsdatacode/Contribuindo-com-Analise-de-Projetos/assets/133138211/c8e9a5a8-0881-48cb-9f4b-f65a938a08a1)


### Exemplo da Técnica de Entrevista

+ A alta gerência e o cliente estão formalmente comprometidos em apoiar o projeto?
+  Os usuários estão bastante comprometidos com o projeto e o sistema/produto a ser criado?
+ Os requisitos são amplamente entendidos pela equipe de engenharia de software e clientes?
+ Os clientes foram totalmente envolvidos na definição dos requisitos?
+ Os usuários têm expectativas realistas?
+ O escopo do projeto é estável?
+ A equipe de Engenharia de Software tem a combinação de aptidões adequadas?
+ Os requisitos de projetos são estáveis?
+ A equipe de projeto tem experiência com a tecnologia a ser implementada?
+ O número de pessoas na equipe de projeto é adequado para o trabalho?
+ Todos os clientes e usuários concordam com a importância do projeto e com os requisitos do sistema/produto a ser criado?

### *Caso alguma questão seja respondida negativamente, insira o risco, ou riscos, na sua lista de riscos.*



# 🤹‍♂️ ANÁLISE QUALITATIVA DOS RISCOS

### Até o momento, temos uma lista com os prováveis riscos do projeto.
### Vamos imaginar que tenhamos uma longa lista. Isso, intuitivamente, nos leva a considerar a necessidade de determinarmos a importância relativa entre os referidos riscos, a fim de que possamos saber quais os riscos prioritários.

### *É interessante destacar que a tratativa de riscos poderá gerar alocação de recursos financeiros, impactando o orçamento do projeto, ou seja, não é possível tratar os riscos listados com a mesma prioridade, devido às limitações de tempo e recursos.* 
![Time is money](https://github.com/Jefsdatacode/Contribuindo-com-Analise-de-Projetos/assets/133138211/79969e58-b6b0-4ff2-8c19-8c9327f4896e)

### O objetivo da Análise Qualitativa dos Riscos é priorizar os riscos, combinando a probabilidade de ocorrência e, caso o risco ocorra, o seu impacto. Essa combinação permite determinar o potencial de cada risco em influenciar os resultados do projeto. A probabilidade determina a dimensão da incerteza e o impacto, o efeito sobre os objetivos do projeto.


### No início deste módulo, definimos três eventos, a título de exemplo, no projeto de uma viagem ao exterior. Vamos agora aplicar a Análise Qualitativa de Riscos nesses eventos.




## PROBABILIDADES
Temos que definir as probabilidades que serão adotadas:

| Grande chance de ocorrer | 0,95 |
| ------------------ | ----------------- |
| Provavelmente ocorrerá| 0,75  |
| Igual chance de ocorrer ou não   | 0,50  |
| Baixa chance de ocorrer    | 0,25   |
| Pouca chance de ocorrer    | 0,10   |


## GRAUS DE IMPACTO

Definir os graus de impacto:

| GRAU DE IMPACTO | PESO |
| ------------------ | ----------------- |
| Muito Grande| 5  |
|Grande  |4  |
|Moderado    | 3  |
| Pequeno    | 2  
| Muito Pequeno   | 1


## APLICAÇÃO

Podemos, então, aplicar os valores a cada evento:


| EVENTO | PROBABILIDADE| IMPACTO| PROBABILIDADE x IMPACTO|
| ------------------ | ----------------- | --------| --------|
| 1) Ocorrência de um problema de saúde, por causa de um acidente ou ter contraído alguma doença| 0,75|5|3,75|
|3) Cancelamento da passagem pela companhia aérea |0,50  | 3| 1,5|
|2) A quantidade de dólar adquirida não ser suficiente    | 0,50  | 4| 2,0|

### Temos agora prioridades! De acordo com a tabela, o evento mais crítico está relacionado com a saúde, em seguida, com a quantidade de dólar e, finalmente, com a passagem.



|🧐 SAIBA MAIS: A Força Aérea Americana determina em seus projetos de software os seguintes componentes de risco: desempenho, custo, suporte e cronograma. As categorias de impacto incluem: catastrófico, crítico, marginal e negligenciável.|
| --------- |



# 👨‍💻 ANÁLISE QUANTITATIVA DOS RISCOS

### A Análise Quantitativa dos Riscos é um processo de analisar numericamente os efeitos dos riscos priorizados pela Análise Qualitativa de Riscos, pois estes podem gerar impacto potencial e substancial nos resultados do projeto.
### Vamos agora dar continuidade ao nosso pequeno exemplo. A tabela a seguir, considerando a simplicidade do cenário adotado, ilustra o resultado da análise quantitativa:

|PRIORIDADE | EVENTO| CUSTO R$|
|------------|-------|---------|
|1|Ocorrência de um problema de saúde, por causa de um acidente ou ter contraído alguma doença |R$ 10.000,00|
|2|A quantidade de dólar adquirida não ser suficiente|R$ 1.000,00|
|3|Cancelamento da passagem pela companhia aérea |R$ 3.000,00|

# 💸PLANEJAMENTO DE RESPOSTAS AOS RISCOS
### O processo Planejar Respostas aos Riscos inclui o planejamento de ações para o aumento das oportunidades e redução das ameaças aos objetivos do projeto, gerenciando os riscos de acordo com sua prioridade. As referidas ações são representadas pelas respostas adequadas a cada risco, podendo ser incluído o tratamento a ser aplicado, por exemplo, mitigação, quando se busca reduzir o impacto no resultado do projeto, ou eliminação, uma resposta que elimine o referido impacto.

### Retornando ao nosso pequeno exemplo, temos uma proposta de respostas aos riscos identificados na tabela a seguir:

| PRIORIDADE | EVENTO| TRATAMENTO| RESPOSTA|
| ------------------ | ----------------- | --------| --------|
| 1 | Ocorrência de um problema de saúde, por causa de um acidente ou ter contraído alguma doença |Eliminação| Contratar o seguro viagem|
| 2 | A quantidade de dólar adquirida não ser suficiente |Eliminação|Atualizar o cartão de crédito para uso internacional|
| 3 |Cancelamento da passagem pela companhia aérea|Mitigação|Confirmar a reserva em companhia aérea com boas alternativas de voos|


# 📜RESUMÃO

### Nesta pequena e humilde apresentação, podemos destacar a importância da área de conhecimento Gerenciamento dos Riscos do Projeto. Um risco é um evento ou condição incerta que, se ocorrer, provocará um efeito positivo ou negativo em um ou mais objetivos do projeto.

### A identificação dos riscos pode ser facilitada pela definição de uma Estrutura Analítica de Riscos (EAR), pois essa permite a categorização dos riscos.

### Definidos os riscos, surge a necessidade de priorização destes, pois a tratativa dos riscos poderá impactar o orçamento final do projeto. O processo de análise qualitativa permite a referida priorização definindo para cada risco a sua probabilidade de ocorrência e o grau de impacto, caso ocorra, nos resultados do projeto. Obtidos os dois valores numéricos, pode-se então priorizar os riscos.

### Priorizados os riscos, o próximo processo inclui a realização da análise quantitativa dos riscos, permitindo, de acordo com a priorização realizada anteriormente, quantificar os impactos sobre os custos do projeto em função dos riscos.

### O planejamento tem como último processo a elaboração do Planejamento de Respostas aos Riscos, incluindo as ações que irão realizar as tratativas que permitirão eliminar ou mitigar os impactos nos resultados do projeto. O referido plano é colocado em execução por meio do processo Implementar Respostas aos Riscos e devidamente monitorado pelo processo Monitorar os Riscos

