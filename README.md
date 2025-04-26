
# Gelato Mágico - Previsão de Vendas de Sorvete com Machine Learning

---

### Cenário

Imagine que você é proprietário de uma sorveteria chamada **Gelato Mágico**, localizada em uma cidade litorânea. Você percebe que a quantidade de sorvetes vendidos diariamente tem uma forte correlação com a temperatura ambiente. Sem um planejamento adequado, há riscos de produzir mais sorvetes do que o necessário (gerando desperdício) ou produzir menos (perdendo vendas).

Para solucionar esse problema, decidimos usar **Machine Learning** para prever quantos sorvetes serão vendidos com base na temperatura. Com esse modelo, é possível antecipar a demanda e planejar a produção de maneira eficiente.

### Objetivo

O objetivo deste projeto é desenvolver um modelo de regressão preditiva que permita:

- 📅 Treinar um modelo de Machine Learning para prever as vendas de sorvete com base na temperatura do dia.
- 🔖 Registrar e gerenciar o modelo usando o **MLflow**.
- 📦 Implementar o modelo para previsões em tempo real em um ambiente de **cloud computing**.
- 🔄 Criar um pipeline estruturado para treinar e testar o modelo, garantindo **reprodutibilidade**.

### Como entregar esse projeto?

1. Criar um novo repositório no GitHub com um nome de sua preferência.
2. Criar uma pasta chamada **inputs** e adicionar um documento de texto com algumas sentenças.
3. Criar um arquivo chamado **README.md**, incluir prints, descrever o processo, insights e possibilidades aprendidas.
4. Compartilhar o link do repositório através do botão "entregar projeto".

---

## Desenvolvimento do Projeto

## Carregamento da Pasta com Dataset ao Notebook

- ### Dataset carregado com dados de vendas de sorvete e temperatura.

    ![Instância de Computação](./imagens/5.png)
 
  ![Instância de Computação](./imagens/1.png)

## Criação do Workspace

- ### Ambiente de trabalho configurado para experimentação.

    ![Instância de Computação](./imagens/2.png)

## Adição da Instância de Computação

- ### Criada a infraestrutura necessária para treinamento do modelo.

    ![Instância de Computação](./imagens/3.png)

## Criação de Cluster

- ### Cluster configurado para processamento em larga escala.

    ![Instância de Computação](./imagens/4.png)

## Criação do Job AutoML

- ### Início de experimentos automáticos de machine learning.

  ![Instância de Computação](./imagens/6.png)
  ![Instância de Computação](./imagens/7.png)
  
- ### Bloqueio de algoritmos indesejados.

![Instância de Computação](./imagens/8.png)
    
- ### Configuração de tempo limite para experiência e iteração.

![Instância de Computação](./imagens/9.png)
  
- ### Configuração de computação para execução do job.

  ![Instância de Computação](./imagens/10.png)

## Visualização do Job Criado

![Instância de Computação](./imagens/11.png)


## Criação do Pipeline no Designer

![Instância de Computação](./imagens/12.png)

- ### Configuração do tamanho do teste (test size).

![Instância de Computação](./imagens/13.png)
  
- ### Seleção das colunas relevantes.

![Instância de Computação](./imagens/14.png)
  
- ### Configuração do número de sementes.

![Instância de Computação](./imagens/15.png)
  
- ### Definição da coluna alvo para previsão.

  ![Instância de Computação](./imagens/16.png)


- ### Designer criado.
![Instância de Computação](./imagens/17.png)

  
## Criação do Job da Pipeline

![Instância de Computação](./imagens/18.png)
![Instância de Computação](./imagens/19.png)


- ### Job do Pipeline criado.
  ![Instância de Computação](./imagens/20.png)

 
## Execução e análise dos resultados.

- ### Terminou a execução do job criado a partir do automl, já me retornou o melhor modelo

  ![Instância de Computação](./imagens/21.png)


 - ### Detalhes do job filho, visão geral.

   ![Instância de Computação](./imagens/22.png)

   - ### Métrica geradas.
  
     ![Instância de Computação](./imagens/23.png)
  
     

   - ### Resultado do job criado pelo desinger
  
      ![Instância de Computação](./imagens/24.png)
     ![Instância de Computação](./imagens/25.png)
  
   - ### Dados gerados pelo train model.
  
      ![Instância de Computação](./imagens/26.png)
  
   - ### Dados do Evaluate Model

      ![Instância de Computação](./imagens/27.png)

 - ### Dados do Score Model
   
      ![Instância de Computação](./imagens/28.png)

## Conclusões e Possibilidades

- O modelo demonstrou boa capacidade preditiva.
- Insights de que temperaturas mais altas estão fortemente relacionadas a maiores vendas.
- Potencial expansão para incluir outras variáveis como umidade, dia da semana, feriados.

## Considerações Finais

Este projeto proporciona um aprendizado prático no Azure Machine Learning, utilizando ferramentas modernas para automação, gestão de modelos e implementação de pipelines. Ideal para fortalecer o portfólio e destacar suas habilidades técnicas!
