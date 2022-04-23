
![](/img/loja_rossmann.jpg)

**As demandas deste projetos são fictícias, porém criadas para simular uma demanda realizda pela direção da empresa. Para maior realismo foi desenvolvida com dados reais e abertos, disponibilizados pela empresa através da plataforma Kaggle**

## ****Contexto de negócio****

---

Rossmann é uma das maiores redes de drogarias da Europa. Com cerca de 56.200 funcionários e mais de 4.000 lojas. Em 2019, a Rossmann teve um faturamento de mais de € 10 bilhões na Alemanha, Polônia, Hungria, República Tcheca, Turquia, Albânia, Kosovo e Espanha. Com essa grande quantidade e variedade de lojas, é muito importante que a gestão da empresa tenha uma base de quanto irá vender no futuro, com isso surgiu uma questão de negócio que o CFO da empresa precisa resolver no momento.

O CFO da Rossmann precisa fazer reforma nas lojas,com isso ele solicitou para os gerentes de todas as lojas uma previsão de vendas para as próximas 6 semanas, com essa previsão ele vai saber quanto vai poder investir na reforma das lojas. Porém os gerentes com suas ferramentas atuais não conseguem fazer essa previsão, com isso foi solicitado a equipe de Data Scientists para criar uma solução para essa dor atual do time de negócio da empresa.

## ****Dados****

---

O conjunto de dados foi disponibilizado na plataforma Kaggle atravpes do seguinte link: [https://www.kaggle.com/c/rossmann-store-sales/data](https://www.kaggle.com/c/rossmann-store-sales/data) 

Abaixo um dicionário dos dados

- **Id** - um Id que representa (Store, Date) dentro do conjunto de teste
- **Store** - Id único para cada loja
- **Sales** - o volume de negócios em um determinado dia.
- **Customers** - o número de clientes em um determinado dia
- **Open** - um indicador para saber se a loja estava aberta: 0 = fechada, 1 = aberta
- **StateHoliday** - indica um feriado estadual. Normalmente todas as lojas, com poucas exceções, fecham nos feriados estaduais. Observe que todas as escolas fecham nos feriados e finais de semana. a = feriado, b = feriado da Páscoa, c = Natal, 0 = Nenhum
- **SchoolHoliday** - indica se (Loja, Data) foi afetado pelo fechamento de escolas públicas
- **StoreType** - diferença entre 4 modelos de loja diferentes: a, b, c, d
- **Assortment** - descreve um nível de sortimento: a = básico, b = extra, c = estendido
- **CompetitionDistance** - distância em metros até a loja concorrente mais próxima
- **CompetitionOpenSince[Month/Year]** - o ano e mês aproximados em que o concorrente mais próximo foi aberto
- **Promo** - indica se uma loja está fazendo uma promoção naquele dia
- **Promo2** - Promo2 é uma promoção contínua e consecutiva para algumas lojas: 0 = a loja não está participando, 1 = a loja está participando
- **Promo2Since[Year/Week]** - descreve o ano e a semana em que a loja começou a participar da Promo2
- **PromoInterval** - descreve os intervalos consecutivos de início da promoção 2, nomeando os meses em que a promoção é iniciada novamente. Por exemplo. "Fev, maio, agosto, novembro" significa que cada rodada começa em fevereiro, maio, agosto, novembro de qualquer ano para aquela loja

## ****Planejamento da solução****

---

A execução do planejamento segue a metodologia crispi, sendo desenvolvida de forma ciclica, desta forma é possível resolver o problema da empresa o mais rápido possível.

1. Entendimento do negócio e problemas e serem resolvidos - Entender do negócio e como funciona o segmento que a empresa atua faz toda diferença para avalir as hipóteses levantadas e confrontar com os dados. Isso vai ser o diferencial no andamento do desenvolvimento da solução e aplicação da estatística e algoritmos de machine learning.

2. Coleta dos dados -  Download do conjunto de dados que está disponibilizado na plataforma Kaggle;

3. Limpeza dos dados -

4. Análise Exploratória dos Dados - 

5. Preparação dos dados para os algoritmos de Machine Learning - 

6. Aplicação dos algoritmos de machine learning - 

7. Avaliação do algoritmo - 

8. Tradução do erro em métricas de negócio - 

9. Deploy do modelo em produção - 

## ****Insights Importantes****

---
... Em Desenvolvimento

## ****Machine Learning Models****

---
... Em Desenvolvimento

## Performance de Negócio

---
... Em Desenvolvimento

## ****Conclusão****