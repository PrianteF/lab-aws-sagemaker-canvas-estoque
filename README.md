# 📊 Previsão de Estoque Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

Bem-vindo ao meu projeto de Previsão de Estoque Inteligente na AWS com SageMaker Canvas. Apresentando meu relatório sobre o uso do SageMaker Canvas para criar previsões de estoque e a análise do resultado apresentado baseadas em Machine Learning (ML).

## 📋 Relatos

- Em primeiro lugar, tive problemas com a abertura da conta e confirmação de pagamento. Não entendi o que ocorreu, mas levei mais tempo que o necessário para realizar este projeto.
- Toda análise foi baseada nos próprios dados fornecidos pela DIO (por ter levado mais tempo para abrir a conta, não houve tempo hábil para gerar outros dados base)

- Dataset: 1000 com Preço promocional e renovação de estoque
- Gerando dois modelos de coluna DATA_EVENTO e QUANTIDADE_ESTOQUE, para ambos, foi aplicado o modelo de Quick e Standard Build
  - DATA_EVENTO:
    - Facilidade de geração por parte do SageMaker;
    - Houve conflito ao gerar no modo Standard.
   
  - QUANTIDADE_ESTOQUE:
    - Leva um tempo a mais para gerar;
    - Apresentou melhores condições através do Standard;
    - Analises foram mais precisas.
