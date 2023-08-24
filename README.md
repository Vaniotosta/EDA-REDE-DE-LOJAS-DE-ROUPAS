# PROJETO DE ANÁLISES DE DADOS DE UMA REDE DE LOJAS 

### Projeto realizado em : 09/08/2023
![](https://checkbits.com.br/wp-content/uploads/2020/08/Rede-de-Lojas-operacao-padronizada-e-otimizacao-da-gestao.png)
## INTRODUÇÃO
A gestão eficaz desempenha um papel crucial no sucesso de uma rede de lojas que vendem roupas. A indústria de varejo de moda é dinâmica e altamente competitiva, e uma gestão bem estruturada pode fazer a diferença entre o crescimento sustentável e a estagnação. 
A gestão adequada é essencial para entender e atender às demandas em constante mudança dos clientes. Ao analisar dados de vendas e tendências de moda, os gestores podem antecipar as preferências dos clientes e adaptar seu estoque e estratégias de marketing. Além disso, a gestão eficaz garante que as lojas estejam bem abastecidas com produtos populares, evitando rupturas de estoque que possam afetar negativamente a satisfação do cliente. 

Nesse contexto,uma empresa de consultoria em dados foi contratada por um rede de lojas de vendas de roupas masculinas e femininas, a rede reclamava da falta de organização na administração por não ter informações suficientes sobre seus clientes, sendo assim,decidiu tomar suas decisões baseadas nos dados. Ela também tem receio de perder clientes valiosos por falta de uma boa Gestão,sendo assim buscou auxílio na empresa de consultoria em dados.
## PROBLEMA DE NEGÓCIO
 O objetivo da empresa de consultoria contratada, é identificar os clientes mais valiosos para rede de lojas, além de trazer informações sobre o perfil dos clientes para que a rede possa tomar decisões  e organizar melhor sua administração dentro da base de clientes.
 ### Conhecendo as bases de dados
 Sobre a base de dados

Na planilha há quatro abas:

--> Dados de venda

ID: identificador único de uma venda

ProductID: identificador único de um produto

ClientID: identificador único de um cliente

Discount: desconto aplicado em uma venda

UnitPrice: preço unitário de um produto vendido

Quantity: quantidade de produto vendido em uma venda

StoreID: identificador único de uma loja

Date: data de uma venda

--> Dados de consumidores

ID: identificador único de um consumidor

City: cidade/localidade onde um consumidor fez a compra

State: Unidade Federativa onde um consumidor fez a compra

DateOfBirth: data de nascimento de um consumidor Sex: sexo de um consumidor

--> Dados de lojas

ID: identificador único de uma loja

Name: cidade/localidade de uma loja

State: Unidade Federativa de uma loja

--> Dados de produto

ID: identificador único de um produto

Name: nome de um produto

Size: tamanho de um produto
### Principais técnicas usadas nos dados
- Será usada análise estatísticas descritivas
- Análise de dados nulos e tipo de dados
- Distribuição e contagem dos dados
- Padronização dos dados
- Engenharia de variáveis
- Junção de dataframes
- Construção de novo dataframes
- Visualização dos dados em gráficos

  ### Algumas visualizações
  ![image](https://github.com/Vaniotosta/EDA-REDE-DE-LOJAS-DE-ROUPAS/assets/89017431/51c74a9e-f2f2-4142-a1c6-92a7661b35fe)
  ![image](https://github.com/Vaniotosta/EDA-REDE-DE-LOJAS-DE-ROUPAS/assets/89017431/216be725-cfe6-4ccc-844a-57f604f1f1fb)
  ![image](https://github.com/Vaniotosta/EDA-REDE-DE-LOJAS-DE-ROUPAS/assets/89017431/cf7ccd0d-b82a-411e-91ca-f7d0eddf8a68)

  # RESULTADOS DOS DADOS
  Vanio Tosta, foi o analista de dados escolhido pela empresa  de consultoria contratada para solucionar os problemas do cliente , ele foi escolhido com base em sua expertise com o negócio e sua experiência com os dados , pois o cliente quer informações gerais sobre seu perfil de clientes para assim tomar as melhores decisões do ponto de vista de gestão.
Sendo assim , Vanio chegou as seguintes insights, com base nas perguntas e respostas feitas durante as análises.

- Apesar da maioria dos clientes serem homens (87%), o gênero e as média de idade não interferem nas vendas, mas é importante definir esses públicos pois podem ser usados em campanhas de marketing segmentadas aos público alvo. Tão logo, a média de idade entre homens e mulheres é de 44 anos.

- Os clientes tem idade entre 22 e 72 anos, ou seja , não tem público infantil e nem adolescentes, o que define seu público como adulto. Sendo assim , seria interessante para a área de negócio segmentar públicos alvo entre faixas de idade para melhor gestão,campanhas de marketing e administração de estoques e compras de produtos.

- Como sugestão,seria interessante se trabalhar com público adulto jovem entre 22 e 39 anos, entre adultos de 40 e 59 anos, e público acima de 60 anos.

- Ao verificar clientes acima de 46 anos, verificou-se que 63% tem vendas acumuladas de 17.147 reais , e 98% tem acumulado em vendas um total 26.750. isso significa um público a ser observado com atenção especial no que tange a campanhas de marketing.

- Ao observar as marcas dos produtos, o produto BIXDream, representa 51% do toal das vendas, e seu valor real em vendas acumuladas varia entre 36 e 49 mil reais, o que requer uma atenção especial a essa marca em determimento aos outros produtos.

- Listamos os 10 maiores clientes por ID únicos, e verificamos que os clientes com maiores vendas variam entre 2100 e 2800 reais vistos individualmente, enquanto que, os 10 piores clientes em vendas estão com 114 reais.

- Verificamos as 10 cidades que mais vendem, e entre elas, se destacaram Florianópolis, Rio de janeiro e Porto alegre, com valores de 1.822 reais, 1.490 reais e 1.357 reais respectivamente.

- Ao analisar os 10 Estados que mais vendem, e observando a relação com as cidades, observou-se que Santa Catarina, Rio de janeiro e Rio Grande do Sul representam 62,7% das vendas, e que tem relação com as cidades que mais vendem.

- A média de preços vendidos por tamanho, as "GG" são as menores, 160 reais em comparação a outros tamanhos que chegam acima de 200 reais.

- Quanto as quantidades vendidas, o tamanho "G" são as que mais vendem , e as "GG" as que menos vendem, isso pode levar as informações futuras quanto ao peso, altura e tratar essas informações para definir uma melhor política de compras e de gestão de estoques.


Sendo assim, esses insights podem ser trabalhados pela empresa contratante buscando melhorar sua gestão, tanto do ponto de vista  do perfil dos seus clientes e da administração, seja para campanhas de marketing, segmentação de clientes, gestão logística de compras e estoques, e  melhorar canais de comunicação internas e externas com seus parceiros e clientes.

  


