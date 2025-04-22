![Representação](imgs/ecommerce-regressao.jpg) 
# 🛒 Análise de Vendas em E-commerce com Modelos de Regressão
__Diferencial:__
Para diferenciar meu projeto em relação aos demais, optei por focar exclusivamente em modelos de regressão. A proposta é comparar o desempenho entre diferentes algoritmos desse tipo para identificar qual deles oferece os melhores resultados na resolução do meu problema de negócio.

__Cenário proposto:__
Uma empresa de e-commerce comercializa produtos através de seu web site e através de sua app para dispositivos móveis.Para efetuar uma compra,um cliente realiza um cadastro no portal (usando web site ou app). Cada vez que o cliente realiza o login, o sistema registra o tempo que fica logado, seja na app ou no web site. Para cada cliente a empresa mantém o registro de vendas com o total gasto por mês.  

A empresa gostaria de aumentar as vendas, mas o orçamento permite investir somente no web site ou na app neste momento. O objetivo é melhorar a experiência do cliente durante a navegação no sistema, aumentando o  tempo  logado,  aumentando o engajamento e, consequentemente, aumentando as vendas. Meu objetivo principal é ajudar a empresa (fictícia) a tomar essa decisão.

__Dataset utilizado: Dados gerados por IA - fictícios__  
Os dados usados neste projeto são fictícios, mas que representam dados reais para empresas  de  e-commerce. Os  dados  representam um  mês  de  operação  do portal  de  e-commerce. O título de cada coluna no conjunto de dados é auto-explicativo.  

Projeto desenvolvido para a disciplina de Machine Learning I, no 5º termo do Curso de Ciência de Dados da FATEC – Ourinhos.
 
__Professor:__ Vinicius Godoy  
__Aluno:__ Pedro Gabriel Pito Lopes  
__RA:__ 0211352313008 – Período Noturno  

---

## 🐍 Link do Jupyter Notebook: [Jupyter Notebook](https://github.com/gabrielpito92/projetos_fatec/blob/main/ML1_FATEC_Ecommerce/MLAnalise_Ecomerce/Vendas_Ecommerce.ipynb)  

## 💭 Hipóteses de Negócio

1. O tempo gasto no **site** influencia positivamente o valor gasto.
2. O tempo gasto no **aplicativo mobile** impacta diretamente no valor de compras.
3. O tempo médio de **atendimento ao cliente** pode estar relacionado ao valor gasto.
4. A plataforma de acesso (site vs. app) pode indicar **diferenças no perfil de consumo**.

---

## 🔍 Resumindo as Etapas Realizadas:

### 1. **Carregamento e inspeção do dataset**
- Leitura do arquivo de dados.
- Verificação de tipos de variáveis e dados faltantes.

### 2. **Análise Exploratória de Dados (EDA)**
- Histogramas para observar distribuições.
- Gráficos de dispersão para investigar correlações.
- Cálculo de coeficientes de correlação entre variáveis.

### 3. **Modelagem Preditiva**
- Construção de modelos de **Regressão**.
- Avaliação dos coeficientes e da significância estatística.
- Análise de resíduos e desempenho do modelo (R², erro médio).

---

## ❓ Perguntas de Negócio Respondidas:

- Existe relação entre o tempo no site e o valor gasto?
- O tempo de uso do app é um bom preditor de compras?
- Qual canal (site ou app) gera mais valor para o e-commerce?
- A atuação do atendimento ao cliente influencia nas compras?

---

## 📈 Principais Insights:

- O tempo gasto no **site** não mostrou correlação significativa com o valor gasto.
- Já o tempo gasto no **aplicativo mobile** demonstrou **forte correlação positiva** com o valor gasto.
- A variável relacionada ao **atendimento ao cliente** também mostrou impacto relevante.
- O modelo de regressão indica que o **app é o principal canal** para geração de receita.

---

## ✅ Conclusões:

- Investimentos em melhorias na **experiência do aplicativo mobile** podem trazer maior retorno financeiro.
- Estratégias voltadas exclusivamente ao site podem ter impacto limitado nas vendas.
- O modelo de regressão oferece uma boa capacidade de previsão com base nas variáveis disponíveis.

---

## 🔄 Próximos Passos:

- Testar outros algoritmos além das regressões, podem ser algoritmos mais robustos como **Random Forest** e **Gradient Boosting**.
- Incorporar variáveis de marketing e perfil de usuário para refinar a previsão.
- Segmentar clientes por grupo (novos vs. recorrentes) e realizar análises específicas.

---

## 📁 Estrutura do Projeto

```
.
├── README.md                      # Descrição do projeto (este arquivo)
├── imgs/                          # Imagens utilizadas no README
└── MLAnalise_Ecomerce/
    ├── Vendas_Ecommerce.ipynb     # Notebook principal com análise e modelo
    └── dados/
        └── dataset.csv            # Base de dados utilizada
```

---

> Projeto desenvolvido para prática de ciência de dados com foco em modelagem preditiva e análise de comportamento do consumidor em e-commerce.